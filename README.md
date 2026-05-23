# Fenix Log
Relatório de Integridade e Custódia de Evidências

🍏 Como Instalar no iOS (iPhone e iPad)
WARNING

Nota do iOS: O sistema da Apple permite a instalação de PWAs apenas através do navegador nativo Safari. Navegadores de terceiros (como Chrome ou Firefox no iOS) não têm permissão do sistema para adicionar apps à tela inicial.

Abra o Safari no seu iPhone ou iPad.
Acesse a URL onde o seu Fênix Log está publicado (ex: https://fenix-log.vercel.app/).
Toque no botão Compartilhar na barra inferior (o ícone de um quadrado com uma seta apontando para cima).
Role a lista de opções para baixo e selecione "Adicionar à Tela de Início" (Add to Home Screen).
O sistema carregará o ícone da Fênix (icon.svg) e o nome do app automaticamente. Toque em "Adicionar" no canto superior direito.
Pronto! O ícone do Fênix Log estará na sua tela inicial como se fosse um aplicativo nativo.

🤖 Como Instalar no Android

No Android, a instalação é muito flexível e pode ser feita pelo Google Chrome ou por navegadores compatíveis (como Samsung Internet, Brave, Edge).

Abra o Google Chrome no seu celular Android.
Acesse a URL do seu Fênix Log.
Banner automático: Frequentemente, o próprio navegador exibirá um aviso flutuante na parte inferior com o texto "Adicionar Fênix Log à tela inicial" ou "Instalar aplicativo". Basta tocar nele.
Instalação manual (Alternativa): Caso o banner não apareça:
Toque nos três pontinhos no canto superior direito do Chrome.
Selecione a opção "Instalar aplicativo" (ou "Adicionar à tela inicial").
Confirme tocando em "Instalar" na janela pop-up.
O app será adicionado à sua gaveta de aplicativos e à tela inicial.

💻 Como Instalar no Computador (Windows, macOS e Linux)

Você também pode instalar o Fênix Log como um aplicativo de desktop super leve através de navegadores baseados no Chromium (Google Chrome, Microsoft Edge, Brave, Opera).

Abra o Google Chrome ou Microsoft Edge no seu computador.
Acesse a URL do aplicativo.
Olhe para a barra de endereços do navegador (no topo, à direita, ao lado da estrela de favoritos):
No Chrome, aparecerá um ícone redondo de monitor com uma seta para baixo (ou o aviso "Instalar Fênix Log").
No Edge, aparecerá um ícone de três quadrados com um símbolo de mais.
Clique no ícone de instalação e confirme clicando em "Instalar".
O aplicativo se abrirá em uma janela própria, sem as barras de navegação do browser, e um atalho será criado na sua Área de Trabalho / Launchpad.
🔄 Como Atualizar o App após Modificações no Código
O Service Worker do PWA utiliza a estratégia Stale-While-Revalidate. Ao abrir o app:

Ele carrega instantaneamente a versão cacheada (velocidade máxima).
Paralelamente, ele verifica no servidor se há uma versão mais nova.
Se houver, ele baixa a atualização em segundo plano.
Para aplicar a nova atualização:

Feche completamente o aplicativo (remova-o da aba de apps abertos/multitarefa do celular) e abra-o novamente.
No computador, basta fechar a janela do app e abrir de novo (ou clicar com o botão direito na barra superior e selecionar Recarregar App).
