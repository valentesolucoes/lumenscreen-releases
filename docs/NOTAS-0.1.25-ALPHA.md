# Lumen Screen 0.1.25 Alpha — build 25

Versão experimental Universal do aplicativo de captura e gravação para macOS, desenvolvida pela Valente Soluções.

## Novidades

- A captura de área congela a tela antes de abrir a interface de seleção, preservando menus e outros elementos temporários.
- As reações do Facebook permanecem na captura ao pressionar ⌘1 enquanto estão visíveis.
- A compilação Universal, o versionamento e o empacotamento foram aprimorados, com validações de arquitetura, metadados e assinatura.

## Validação

- 297 testes automatizados aprovados.
- 13 testes funcionais manuais aprovados em Mac Intel.
- DMG transferido para um MacBook, com SHA-256 confirmado e funcionalidades aprovadas. A arquitetura desse MacBook ainda não foi confirmada.
- O executável inclui x86_64 e arm64; a execução funcional desta versão em Apple Silicon ainda não foi confirmada.

## Requisitos e instalação

- macOS 15 ou superior e Mac Intel ou Apple Silicon.
- Permissão de gravação de tela para capturar ou gravar.
- Baixe o DMG e seu arquivo `.sha256`, confira o checksum, abra o DMG e arraste **Lumen Screen.app** para **Aplicativos**. Consulte o [guia de instalação](https://github.com/valentesolucoes/lumenscreen-releases/blob/v0.1.25-alpha/docs/INSTALACAO-0.1.25-ALPHA.md) para atualização, permissões e segurança.

## Limitações

Esta é uma versão Alpha experimental; podem ocorrer falhas, perda de gravação ou diferenças entre configurações de monitores e sistemas. O aplicativo é assinado com **Apple Development** e **não foi notarizado pela Apple**. O Gatekeeper pode alertar ou impedir a abertura; a assinatura não representa aprovação da Apple. Consulte as [orientações oficiais da Apple](https://support.apple.com/pt-br/102445).

## SHA-256 do DMG

```text
707e6b0c5ed13290112c0b7bae2695f623fa45f9dac684dd89377ce424709e1b
```
