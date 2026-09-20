# Kodi 22 "Piers" Beta 2

Pré-lançamento 

Equipe Kodi

05 de setembro de 2026



Anunciamos o segundo lançamento Beta do Kodi 22 "Piers"!

Muitas melhorias foram implementadas nos recursos adicionados na versão Beta 1. O suporte a HDR foi drasticamente aprimorado, incluindo capturas de tela em HDR. O suporte a idiomas internacionais também foi melhorado, especialmente para usuários de JSON-RPC. E se você tiver um adaptador Pulse-Eight CEC, encontrará um gerenciamento expandido de dispositivos de central de mídia.

Se você quer o que há de mais recente e melhor, esta versão é para você. A Beta 2 incorpora mais de 100 correções cumulativas, além das melhorias da Beta 1. No entanto, por se tratar de uma versão Beta, ainda existe a possibilidade de alguns bugs precisarem ser corrigidos antes do lançamento da versão final v22. Por favor, abra um chamado no GitHub com os logs de depuração completos para nos ajudar a resolver quaisquer problemas.

Certo, quais são as novidades desta versão?

# Registro de alterações

#  Vídeo
* FFmpeg atualizado para a versão 9.0.1
* Detecção de formato de pixel fixo para conteúdo AV1
* Dimensões fixas de reprodução em tela cheia em TVs de 50 Hz.
* Correção na detecção de FPS em fluxos de transporte MPEG (.ts / .m2ts)
* Corrigido o problema de perda do sinal de vídeo HDMI ao reproduzir determinados conteúdos.
* Correção na precisão de pular quando pausado
* Problema de reprodução corrigido ao mover o Kodi entre telas no Windows.
* Correção do problema de retomada de fluxos de transporte MPEG com vídeo H.264 no Android.
* Corrigida a regressão do VC-1 que causava travamentos significativos no Android TV.
* Corrigida a configuração "sincronizar reprodução com a tela" para algumas plataformas embarcadas (GBM).
* Corrigido o problema que causava o fechamento inesperado do sistema ao usar codecs de vídeo adicionais com algumas plataformas integradas (DRMPRIME).
* Corrigido possível vazamento de memória com complementos binários de codec de vídeo.

# Blu-ray
* Libbluray atualizado para a versão 1.5.0
* Melhoria no processamento de episódios em Blu-ray
* Seleção de listas de reprodução de filmes Blu-ray aprimorada
* Velocidade aprimorada na detecção de discos Blu-ray.
* Corrigido possível travamento ao selecionar "Menu Blu-ray" durante a escolha de uma lista de reprodução Blu-ray.
* Corrigidos metadados desatualizados na transição de itens da lista de reprodução.
  
# HDR
* Capturas de tela ativadas para conteúdo HDR
* Colorimetria com mapeamento de tons fixo (HDR->SDR)
* Corrigido o problema com metadados HDR desatualizados exibidos para informações de vídeo.
* Correção na reprodução de Dolby Vision no Android com legendas PGS
* Lógica PQ de transferência HDR corrigida no webOS
* Correção na reprodução de conteúdo HDR10 HEVC Main 10 no macOS
* Correção na reprodução de fontes com metadados de luz HDR incorretos.
  
# Marcadores / Capítulos
* O marcador corrigido não era apagado ao término da reprodução.
* Correção do problema de pular capítulos durante a reprodução de DVDs.
* Corrigido o tempo e o capítulo exibidos após a mudança de capítulo.
* Corrigido o problema que fazia com que dois capítulos fossem criados no primeiro segundo.

# 3D
* Correção do atraso na troca ao mudar para o modo 3D
Áudio
Altere as configurações do pré-amplificador ReplayGain para que fiquem centradas em 0 dB em vez de 89 dB.
Correção de erros no analisador M2TS para conteúdo DTS/TrueHD e LPCM.
Correção na quebra de metadados de áudio DTS/DTS-HD pela sonda rápida MPEG-TS.
Corrigida possível perda de áudio ao reproduzir HDR com áudio passthrough.
Corrigido o problema de distorção de som no webOS.
Corrigido o problema que fazia com que a primeira faixa fosse pulada após a reprodução da última faixa com a opção "repetir tudo" ativada.
Legendas
Seleção automática aprimorada de diferentes idiomas.
Corrigido possível problema de dessincronização de legendas externas ao realizar a busca.
Problema resolvido com a busca de legendas externas e caminhos HTTP://
Corrigido o problema das legendas não aparecerem após retroceder para o capítulo anterior ou realizar uma busca extensa.
Corrigido o problema que causava o fechamento inesperado do sistema no LG webOS ao exibir legendas.
Correção na remoção de legendas com caminhos codificados em URL.
PVR
Correção da "seleção inteligente" na janela Guia.
Corrigida possível perda de vídeo ao trocar de canal no PVR em plataformas integradas.
Corrigido o tipo de lembrete exibido incorretamente na caixa de diálogo de configurações do temporizador.
Resolução corrigida para itens que contêm apenas o caminho do item, sem tag.
Jogos
Adicionado suporte completo ao RetroAchievements
Adicionada a capacidade de memorizar quais emuladores são usados ​​por jogo e por pasta.
Adicionada mensagem de erro quando os estados de salvamento compactados da versão 23 são carregados na versão 22.
Adicionada emulação do canal F da Fairchild
Suporte aprimorado para RetroAchievements
Corrigido problema de áudio em alguns emuladores.
Corrigido o descarte de quadros de áudio no início de uma transmissão.
Corrigido o problema com a vibração no jogo.
Correção de problemas com quadros corrompidos em algumas plataformas baseadas em Linux.
Emuladores corrigidos usando os diretórios system/save do emulador anterior.
Corrigido possível problema de travamento ao conectar/desconectar controladores.
Gatilhos analógicos corrigidos em emuladores de Dreamcast
Biblioteca
Adicionada configuração avançada para ignorar nomes de pastas dentro de arquivos compactados.
Funcionalidade aprimorada da versão em vídeo
Melhoria na transição gradual de imagens
Corrigido o problema na exibição da arte da série de filmes
Corrigido o problema que causava o fechamento inesperado do programa ao sair enquanto um diretório ainda estava carregando.
Corrigido o status desatualizado de filmes/séries assistidos/em andamento.
Corrigido o problema em que os detalhes dos programas de TV eram perdidos após uma atualização de metadados.
Correção na ordenação de itens da biblioteca com acentos nórdicos (æ/ø/å/ä/ö)
Exibição fixa de programas de TV vazios
Corrigida a remoção incompleta de filmes ao definir o conteúdo de origem como "Nenhum".
Corrigido o problema de extração de dados de itens com uma {tvdb}tag no nome do arquivo.
Corrigidos diversos erros no manuseio de arquivos .rar
Ordem de classificação dos filmes com versões corrigida.
Corrigido o problema de lentidão na digitalização de miniaturas de atores e artes de séries de TV para importação/exportação.
Corrigido o nome e as informações incorretas exibidas para os arquivos BDMV.
Corrigido o problema que impedia a reprodução de trailers quando uma imagem ISO de Blu-ray já havia sido reproduzida pelo menos uma vez.
interface do usuário
Adicionado suporte para imagens SVG
Corrigido o problema de rolagem vertical instável em textos longos.
Correção na detecção de swizzle em algumas plataformas OpenGL.
Corrigido o impasse no encerramento quando a caixa de diálogo PlayerProcess está aberta.
Resolução fixa em algumas plataformas embarcadas.
A seleção fixa de monitor fica oculta em alguns sistemas com vários monitores.
Correção na exibição da temperatura da CPU/GPU em sistemas M5.
Esfolamento
Adicionada $MAP[]sintaxe XML para tabelas de pesquisa de chave/valor.
Adicionado Control.ResetGrouplist()para redefinir o último item selecionado em uma lista agrupada.
[TABS]Manuseio incompatível corrigido
Corrigido o problema de itens que ultrapassavam o limite em listas fixas, reduzindo-o para um item.
Corrigido possível erro ao carregar fontes TTF
Corrigido o problema com o uso de fontes personalizadas sem o campo "family_name".
Corrigimos diversas falhas na renderização de fontes no Windows.
Corrigido um bug no protetor de tela ao atualizar o tema ativo.
Corrigido o registro de erros ao carregar uma skin.
Imagens desatualizadas corrigidas após atualização meteorológica.
Periféricos
Suporte aprimorado para CEC, especialmente para adaptadores CEC da Pulse-Eight.
libcec atualizado para a versão 8.1.6
Alteramos o gerenciamento do controlador da API de Joystick do Linux para o Udev.
Correção de vazamento de memória ao desconectar dispositivos
Correção na ordenação dos layouts de teclado
Correção no funcionamento do botão "guia" em alguns controles remotos.
Corrigido o problema de alteração não confirmada das configurações periféricas.
Rede
Atualizei o Samba para a versão 4.24.4.
Melhoria na estabilidade de PMEs em conexões instáveis.
Corrigido o problema que causava o fechamento inesperado do programa ao analisar pastas NFS com # ou ; no nome do diretório.
Corrigida a perda de serviços de rede/banco de dados ao sair do perfil principal.
Correção na navegação de arquivos via HTTP, HTTPS e WebDAV quando o servidor exige autorização.
Correção no tratamento de espaços em caminhos WebDAV.
Correção na ordenação de itens UPnP por data.
Corrigido o problema de escape do MySQL para strings com %.
JSON-RPC
Database.GetDatabaseNameMétodo e Database.Typeenumeração adicionados .
VideoLibrary.SetSourceContentMétodo adicionado
PVR.GetPlayableBroadcastsMétodo adicionado
Adicionado GUI.OnSkinUnloadinge notificaçõesGUI.OnSkinLoaded​GUI.OnSkinLoadFailed
Adicionada a capacidade de definir o trailer de uma série de TV.
Adicionada a capacidade de obter fontes de jogos viaFiles.GetSources
Suporte completo e estendido para o idioma BCP 47 via JSON-RPC.
Relatórios de erros JSON-RPC aprimorados
Corrigido o campo "status" que estava faltando emVideo.Fields.TVShow
Corrigido bug de consistência para versões retornadas porFiles.GetDirectory
Correção dos metadados de transmissão ao vivo ao reproduzir um canal de rádio PVR.
Python
Atualizei o Python para a versão 3.14.7.
Pillow atualizado para a versão 12.3.0
Adicionadoxbmc.getDevicePowerStatus()
Adicionadoxbmc.getCecAdapterNames()
Adicionadoxbmc.getDatabaseName()
Adicionadoxbmcgui.ControlVideoWindow
Corrigido xbmcgui.ControlButton.setLabel()o problema que impedia a alteração da fonte do item.
Perfis
Estabilidade do banco de dados corrigida e ativação/desativação de complementos após a troca de perfil.
Corrigido o problema que impedia a exclusão do perfil atualmente ativo.
Android
Corrigido possível travamento ao sair
Corrigido o problema que solicitava permissão de acesso à rede local.
Corrigido o problema ao iniciar listas de reprodução com intents do Android.
Desenvolvedores
Dependência da plataforma p8 removida.
Aumentamos a versão mínima do macOS a ser implementada para 10.15.
Melhoria na execução do Kodi em simuladores de iOS e tvOS.
Edifício fixo com GCC 15
Edifício fixo com geradores diferentes do Visual Studio
Corrigidos problemas na documentação e no modo escuro.
Problemas conhecidos
Se o Kodi for fornecido sem a nossa TagLib 2.3.1 corrigida, a marcação Matroska será revertida para a versão 21.
Link para download
Se você curte softwares de ponta, pode baixar a versão Beta 2 aqui . Selecione a plataforma de sua preferência e procure na seção "Pré-lançamento". Compartilhe sua experiência conosco para que possamos corrigir os bugs. E faça um backup antes!
