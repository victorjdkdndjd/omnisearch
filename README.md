# OmniSearch Files+ — GitHub Pages

Nova versão com **ícones/prévias de arquivos** e mais fontes.

## Ícones e miniaturas

A opção **Mostrar ícones/prévias** fica na barra lateral.

Quando disponível, o OmniSearch usa:
- miniatura real de imagens do Wikimedia Commons;
- ícone do projeto no Modrinth;
- avatar do repositório/autor no GitHub;
- ícone de projeto do GitLab;
- capa/miniatura do Internet Archive;
- prévia de imagens locais importadas.

Quando a fonte não fornece uma imagem, aparece um ícone baseado na extensão do arquivo.

## Fontes

### Já existentes
- Internet Archive
- Wikimedia Commons
- GitHub
- Modrinth
- Hugging Face
- npm
- Zenodo
- OpenAlex

### Novas
- GitLab
- Maven Central
- crates.io
- RubyGems
- Packagist

Todas podem ser ligadas ou desligadas separadamente.

## Atualizar o GitHub Pages

Substitua na raiz do repositório:
- `index.html`
- `sw.js`
- `manifest.webmanifest`
- `README.md`

Depois faça o commit. O GitHub Pages republica automaticamente.

## Observação

O site continua sendo 100% estático no GitHub Pages. As fontes usam APIs públicas diretamente do navegador. Se uma API mudar, aplicar limite de requisições ou bloquear CORS, apenas aquela fonte pode deixar de responder temporariamente.
