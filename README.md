# Cobrinha para Android

Projeto Android mínimo que empacota o jogo offline em um WebView.

## Gerar o APK na nuvem (GitHub Actions)
1. Crie um repositório no GitHub.
2. Envie todos os arquivos desta pasta para a branch `main`.
3. Abra a aba **Actions** do repositório.
4. Se solicitado, habilite GitHub Actions.
5. Execute **Build Cobrinha APK** (Run workflow), ou aguarde o build automático após o push.
6. Quando terminar, abra a execução e baixe o artefato **cobrinha-apk**.
7. Extraia o ZIP e instale `app-debug.apk` no Android.

O APK de depuração é assinado automaticamente com chave de debug e serve para instalação/teste.
