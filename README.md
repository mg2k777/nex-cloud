# NEX CLOUD

Projeto Android do NEX CLOUD.

Inclui:
- Biblioteca de jogos
- FiveM como primeiro jogo da interface
- NEX PC (Windows 10 Cloud PC) como item especial
- Área de trabalho do NEX PC
- Configurações e personalização de papel de parede
- Explorador de arquivos / navegador / jogos (interface)
- Modo Gamepad
- Modo Teclado + Mouse
- Controles de streaming
- Workflow do GitHub Actions para gerar APK

## Gerar APK pelo GitHub no celular

1. Crie um repositório no GitHub.
2. Envie todos os arquivos deste projeto para o repositório.
3. Abra a aba **Actions**.
4. Escolha **Build NEX CLOUD APK**.
5. Toque em **Run workflow**.
6. Quando terminar, abra a execução e baixe o artefato **nex-cloud-debug-apk**.
7. Dentro dele estará `app-debug.apk`.

## Importante

A interface de NEX PC é a camada visual/preparação. Para existir um Windows 10 remoto de verdade, é necessário conectar um servidor/VM Windows 10 ao backend/cloud provider. O app não finge uma conexão real quando essa infraestrutura não está configurada.
