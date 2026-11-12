# Instalação do Lumen Screen 1.0.0

## Requisitos

- macOS 15 ou posterior.
- Mac Intel (x86_64) ou Apple Silicon (arm64). O DMG contém um aplicativo Universal.
- Permissão de gravação de tela do macOS para os recursos de captura e gravação.

## Baixar e instalar

1. Baixe `Lumen-Screen-1.0.0-Universal.dmg` e `Lumen-Screen-1.0.0-Universal.dmg.sha256` na [Release 1.0.0](https://github.com/valentesolucoes/lumenscreen-releases/releases/tag/v1.0.0).
2. Na pasta de download, confira o checksum com:

   ```bash
   shasum -a 256 -c Lumen-Screen-1.0.0-Universal.dmg.sha256
   ```

   O resultado deve indicar `OK`. Se não corresponder, não abra o pacote.

3. Abra o DMG e arraste **Lumen Screen.app** para **Aplicativos**.
4. Ejete a imagem e abra o aplicativo pela pasta **Aplicativos**.

Para atualizar, encerre o Lumen Screen antes de substituir o aplicativo. Guarde uma cópia da versão anterior se precisar de rollback. As preferências existentes são mantidas; o macOS pode solicitar novamente permissões de captura.

## Segurança do macOS

Este aplicativo está assinado com **Apple Development** e **não foi notarizado pela Apple**. A assinatura não significa aprovação da Apple; o macOS pode alertar ou impedir a primeira abertura.

Se o aviso disser somente que a Apple não pode verificar o aplicativo ou identificar o desenvolvedor, confirme a origem oficial e o SHA-256. Se decidir confiar no aplicativo, siga os controles por aplicativo nas [orientações oficiais da Apple](https://support.apple.com/pt-br/102445): após tentar abrir, acesse **Ajustes do Sistema > Privacidade e Segurança** e, se disponível, use **Abrir Mesmo Assim**. Leia o alerta antes de confirmar; a aparência e disponibilidade dependem da versão e das políticas do macOS.

Se o sistema indicar que o aplicativo está danificado, contém malware ou que a assinatura foi revogada, interrompa a instalação e informe os mantenedores. Não desative o Gatekeeper globalmente nem remova a quarentena por comando.

## Permissões

Autorize **Gravação de Tela e Áudio do Sistema** somente se quiser usar os recursos correspondentes. Revise permissões em **Ajustes do Sistema > Privacidade e Segurança**. O som de obturador é reproduzido pelo próprio app; ele não grava áudio nem solicita acesso ao microfone.

## Informar um problema

Informe a versão 1.0.0, o modelo e a arquitetura do Mac, a versão do macOS, os passos para reproduzir e o resultado observado. Remova nomes de documentos, conteúdo de tela e outros dados privados antes de compartilhar registros ou capturas.
