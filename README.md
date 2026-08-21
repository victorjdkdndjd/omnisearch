# OmniSearch — GitHub Pages Edition

Versão feita para ser publicada somente no GitHub Pages.

## Arquivos

Todos ficam na raiz do repositório:

- `index.html`
- `sw.js`
- `manifest.webmanifest`
- `README.md`

Não precisa de Cloudflare, Node.js, servidor, `functions/` nem `site/`.

## Publicar

1. Abra seu repositório no GitHub.
2. Envie os 4 arquivos para a tela principal do repositório.
3. Abra `Settings` → `Pages`.
4. Em `Build and deployment`, selecione `Deploy from a branch`.
5. Em Branch, escolha `main` e `/(root)`.
6. Toque em `Save`.
7. Aguarde a publicação.

A URL normalmente será:

`https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`

## Pesquisa

O navegador consulta diretamente APIs públicas de:

- Wikipédia
- GitHub
- Stack Overflow
- Hacker News
- Open Library

Também há índice local e atalhos para abrir a consulta no Google, Bing e DuckDuckGo.

## Limitação

O GitHub Pages não executa backend. Portanto, mecanismos de busca que não permitem acesso direto pelo navegador não podem ter seus resultados copiados para dentro do OmniSearch sem API/backend adicional.

## Offline

Após abrir o site uma vez, o Service Worker tenta manter a interface em cache. A busca local continua funcionando offline; fontes online precisam de conexão.
