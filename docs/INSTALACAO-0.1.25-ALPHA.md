# Instalação do Lumen Screen 0.1.25 Alpha

## Requisitos

- macOS 15 ou posterior.
- Mac Intel (x86_64) ou Apple Silicon (arm64). O aplicativo é Universal; esta versão ainda não foi testada funcionalmente em Apple Silicon.
- Permissão de gravação de tela do macOS para captura e gravação.

## Baixar e instalar

1. Baixe `Lumen-Screen-0.1.25-Alpha-Universal.dmg` e o arquivo `.dmg.sha256` da publicação oficial do Lumen Screen, quando disponível.
2. Confira o SHA-256 como indicado abaixo e abra o DMG no Finder.
3. Arraste **Lumen Screen.app** para o atalho **Applications** (Aplicativos).
4. Ejete a imagem e abra o aplicativo pela pasta **Aplicativos**.

Para atualizar uma versão anterior, encerre o Lumen Screen pelo menu na barra superior antes de copiar. Considere guardar uma cópia da versão anterior e das preferências; confirme a substituição no Finder. As preferências existentes são mantidas pelo aplicativo, mas o macOS poderá solicitar novamente a autorização de gravação de tela.

## Segurança do macOS

Esta versão experimental é assinada com **Apple Development** e **não foi notarizada pela Apple**. A assinatura não significa que o aplicativo foi aprovado pela Apple. O macOS pode alertar ou impedir a primeira abertura.

Se o aviso disser apenas que a Apple não pode verificar o aplicativo ou identificar o desenvolvedor, confirme primeiro a origem oficial e o SHA-256. Se você decidir confiar no aplicativo, siga os controles por aplicativo descritos nas [orientações oficiais da Apple](https://support.apple.com/pt-br/102445): depois de tentar abrir, acesse **Ajustes do Sistema > Privacidade e Segurança** e, se disponível, escolha **Abrir Mesmo Assim**. Isso cria uma exceção para o aplicativo; leia o alerta antes de confirmar. A aparência e a disponibilidade desses controles dependem da versão e das políticas do macOS.

Se o macOS indicar que o aplicativo está danificado, contém malware ou que a autorização foi revogada, interrompa a instalação e informe os mantenedores. Não desative o Gatekeeper globalmente nem remova a quarentena por comando.

## Permissões

Para captura ou gravação, autorize **Gravação de Tela e Áudio do Sistema** quando solicitado. A permissão pode ser revisada em **Ajustes do Sistema > Privacidade e Segurança**. A interface pode variar entre versões do macOS. Não conceda permissões que você não deseja usar.

## Verificar o SHA-256

No Terminal, na pasta onde os arquivos foram baixados, execute:

```bash
shasum -a 256 -c Lumen-Screen-0.1.25-Alpha-Universal.dmg.sha256
```

O resultado deve indicar `OK`. Se não corresponder, não instale o pacote e informe os mantenedores. O checksum deve ser comparado com a informação publicada por um canal oficial confiável.

## Informar um problema

Informe a versão 0.1.25 (25), modelo e arquitetura do Mac, versão do macOS, passos para reproduzir e resultado observado. Antes de compartilhar registros ou capturas, remova nomes de documentos, imagens, conteúdo de tela e outros dados privados. Use a página de issues do repositório de distribuição ou o canal de suporte indicado na publicação oficial.
