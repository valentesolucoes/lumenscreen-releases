# Instalação do Lumen Screen 0.1.24 Alpha

## Requisitos

- macOS 15 ou posterior.
- Mac Intel ou Apple Silicon. O aplicativo inclui as arquiteturas x86_64 e arm64.
- Permissão de gravação de tela do macOS para usar captura e gravação.

## Baixar e instalar

1. Abra a [publicação Lumen Screen 0.1.24 Alpha](https://github.com/valentesolucoes/lumenscreen-releases/releases/tag/v0.1.24-alpha).
2. Baixe `Lumen-Screen-0.1.24-Alpha-Universal.dmg` e, se desejar, o arquivo `.dmg.sha256` para conferir o checksum.
3. Abra o DMG no Finder.
4. Arraste **Lumen Screen.app** para **Aplicativos**.
5. Ejete a imagem e abra o aplicativo pela pasta **Aplicativos**.

## Segurança do macOS

O aplicativo possui assinatura Apple Development, mas ainda não foi notarizado pela Apple. Dependendo das políticas de segurança do Mac, o sistema pode apresentar um aviso ou impedir a primeira abertura. Confira que o pacote veio da publicação oficial e siga somente os controles apresentados pelo Finder e por **Ajustes do Sistema > Privacidade e Segurança**. Se o macOS indicar que o aplicativo contém malware ou está danificado, interrompa a instalação e informe os mantenedores. Não desative globalmente o Gatekeeper, não remova a quarentena por comando e não ignore alertas de segurança.

Consulte as [orientações oficiais da Apple para abrir apps com segurança](https://support.apple.com/pt-br/102445).

## Permissões

Ao usar captura ou gravação, autorize **Gravação de Tela e Áudio do Sistema** quando solicitado pelo macOS. Se necessário, revise a permissão em **Ajustes do Sistema > Privacidade e Segurança**. A interface pode variar entre versões do macOS. Conceda somente as permissões necessárias.

## Verificar o SHA-256 do DMG

Compare o SHA-256 calculado para o arquivo baixado com o valor publicado no arquivo `Lumen-Screen-0.1.24-Alpha-Universal.dmg.sha256` e nas notas da versão. Se os valores forem diferentes, não instale o pacote e informe os mantenedores.

## Informar um problema

Inclua a versão 0.1.24, o modelo e a arquitetura do Mac, a versão do macOS, os passos para reproduzir e o resultado observado. Revise e remova nomes de documentos, imagens, conteúdo de tela ou outros dados privados antes de compartilhar registros ou capturas.

A Beta 1 possui um [guia histórico separado](INSTALACAO.md).
