STUG Guarda — PWA

Conteúdo:
- index.html: aplicação original preparada para PWA
- manifest.webmanifest: manifesto de instalação
- sw.js: service worker/offline app shell
- icon-192.png / icon-512.png: ícones PWA
- apple-touch-icon.png: ícone iOS
- README.txt: instruções

Instalação:
1. Publique esta pasta num alojamento HTTPS (ou use localhost para testes).
2. Abra a aplicação no navegador.
3. No Android/Chrome: escolha "Instalar aplicação".
4. No iPhone/iPad/Safari: Partilhar -> Adicionar ao ecrã principal.

Nota:
- O service worker só é ativado em HTTPS ou localhost.
- Mapas/serviços externos continuam a depender da Internet.
