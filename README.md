# OmniSearch Games & Apps

Versão focada apenas em **jogos, mods, Minecraft e aplicativos**.

## Resultados diretos dentro do site

- GitHub Releases — tenta mostrar os arquivos reais de releases; se não houver, usa ZIP do repositório.
- Modrinth — arquivos de mods/modpacks/projetos.
- F-Droid — APK da versão sugerida.

## Pesquisas especializadas abertas no próprio site

- MCPEDL
- CurseForge
- GameBanana
- itch.io
- APKMirror
- Uptodown
- APKPure
- Aptoide

Esses sites são abertos em uma nova aba porque um site estático no GitHub Pages não consegue copiar de forma confiável os resultados de todos eles para dentro da página sem API/CORS ou autenticação.

## MediaFire Finder

A seção MediaFire Finder cria pesquisas como:

`site:mediafire.com/file/ "sua pesquisa" "apk"`

Ela oferece Google, Bing e DuckDuckGo, além de uma opção para pesquisar pastas públicas.

O site não rastreia nem indexa o MediaFire diretamente.

## Publicar no GitHub Pages

Substitua na raiz do seu repositório:

- `index.html`
- `sw.js`
- `manifest.webmanifest`
- `README.md`

Faça o commit. O GitHub Pages atualiza automaticamente.
