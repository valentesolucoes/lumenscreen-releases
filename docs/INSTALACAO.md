# Instalação do Lumen Screen 0.1.0-beta.1

Este guia acompanha a primeira Beta experimental do Lumen Screen. Ela é gratuita, requer macOS 15 ou superior e foi compilada para Macs Intel (x86_64). O aplicativo não foi notarizado pela Apple e pode exibir avisos de segurança na primeira abertura.

## 1. Baixar a Beta

1. Abra [Releases do Lumen Screen](https://github.com/valentesolucoes/lumenscreen-releases/releases).
2. Na versão **v0.1.0-beta.1**, baixe `LumenScreen-0.1.0-beta.1-macOS-Intel.dmg`.
3. Se um arquivo `.sha256` for publicado junto ao DMG, baixe-o também. Para conferir o arquivo, siga as instruções de verificação publicadas com a versão. Instale somente um pacote obtido na página oficial do projeto.

## 2. Instalar na pasta Aplicativos

1. No Finder, abra o arquivo `.dmg` baixado.
2. Na janela do instalador, arraste **Lumen Screen.app** para o atalho **Applications (Aplicativos)**.
3. Aguarde a cópia terminar.
4. Ejete o DMG no Finder.
5. Abra **Finder > Aplicativos** e localize **Lumen Screen**.

## 3. Abrir pela primeira vez

A Beta não foi notarizada pela Apple, então o Gatekeeper pode impedir a abertura inicial.

1. Em **Aplicativos**, clique com o botão direito (ou Control-clique) em **Lumen Screen** e selecione **Abrir**.
2. Leia o aviso do macOS. Se ele informar que o desenvolvedor não pode ser verificado, confirme **Abrir** somente se obteve o DMG na página oficial e deseja testar esta versão.
3. Se o macOS bloquear a abertura, faça uma tentativa de abertura pelo Finder. Em seguida, abra **Ajustes do Sistema > Privacidade e Segurança**.
4. Role até a seção **Segurança** e, se estiver disponível, selecione **Abrir Mesmo Assim** para o Lumen Screen. Confirme a abertura no alerta seguinte.

Os nomes e a posição dos controles podem variar conforme a versão e o idioma do macOS. Esse fluxo autoriza a abertura deste aplicativo pelos controles do sistema. **Não desative o Gatekeeper nem a Proteção da Integridade do Sistema (SIP).** Se o macOS disser que o app está danificado ou contém malware, interrompa a instalação e avise os mantenedores; não tente contornar o alerta. Consulte as [orientações oficiais da Apple para abrir apps com segurança](https://support.apple.com/pt-br/102445).

## 4. Autorizar captura e gravação de tela

1. Abra o Lumen Screen. Quando o macOS perguntar se o app pode gravar a tela, permita o acesso se desejar usar captura ou gravação.
2. Se não aparecer uma solicitação ou se a captura não funcionar, abra **Ajustes do Sistema > Privacidade e Segurança > Gravação de Tela e Áudio do Sistema** e habilite o Lumen Screen. O nome desta seção pode variar conforme a versão do macOS.
3. O macOS pode pedir que você encerre e reabra o aplicativo para aplicar a permissão. Para encerrar completamente, use **Sair** no menu do Lumen Screen na barra de menus; fechar a janela pode deixar o app ativo.

O Lumen Screen não grava áudio nesta Beta e não precisa de permissão para microfone.

## 5. Encontrar o app e fazer a primeira captura

1. Depois de abrir o aplicativo, procure o ícone do Lumen Screen na barra de menus, no alto da tela. Clique nele para abrir as opções do app.
2. Pressione **⌘1**.
3. Clique e arraste sobre a tela para selecionar a área que deseja capturar.
4. Use as ferramentas de anotação se desejar; depois, copie ou salve a captura pela interface.

## Problemas comuns

- **Não encontro o Lumen Screen na barra de menus:** confirme que o app foi aberto. Se usar um organizador de ícones da barra de menus, verifique também a área de itens ocultos.
- **Não aparece “Abrir Mesmo Assim”:** tente abrir o app pelo Finder uma vez e volte a **Ajustes do Sistema > Privacidade e Segurança**. A opção só aparece quando oferecida pelo macOS para aquele app.
- **A captura está preta, vazia ou não começa:** confirme que o Lumen Screen está habilitado em **Gravação de Tela e Áudio do Sistema** e encerre e abra o app novamente.
- **O aviso diz que o app está danificado ou contém malware:** não autorize nem tente remover o aviso por comandos ou alterações nas proteções do sistema. Interrompa a instalação e informe os mantenedores.
- **Esperava ouvir som no vídeo:** gravação de áudio não está disponível nesta Beta.

Se o problema continuar, informe aos mantenedores o modelo do Mac, a versão do macOS e as etapas realizadas.
