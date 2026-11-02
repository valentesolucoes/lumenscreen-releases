# Lumen Screen 0.1.25 Alpha — build 25

Versão experimental Universal do aplicativo de captura e gravação para macOS.

## Alterações

- A captura de área congela a tela antes de abrir a interface de seleção, preservando menus e outros elementos temporários.
- As reações do Facebook permanecem na captura ao acionar o atalho de captura de área enquanto estão visíveis.
- O processo de compilação e empacotamento valida as duas arquiteturas, os metadados e a assinatura do aplicativo Universal.

## Validação

- 297 testes automatizados aprovados.
- 13 testes funcionais manuais aprovados em Mac Intel, conforme informado na validação do projeto.
- Binário Universal com x86_64 e arm64. A versão 0.1.25 ainda não foi testada funcionalmente em Apple Silicon.

## Requisitos e limitações

- macOS 15 ou superior e permissão de gravação de tela para capturar ou gravar.
- Versão Alpha experimental: podem ocorrer falhas, perda de gravação ou diferenças em outras configurações de monitores e sistemas.
- Assinada com Apple Development e **não notarizada pela Apple**. O Gatekeeper pode avisar ou impedir a abertura; a assinatura não representa aprovação da Apple.
- Consulte o [guia de instalação](INSTALACAO-0.1.25-ALPHA.md) e as [orientações oficiais da Apple](https://support.apple.com/pt-br/102445).
