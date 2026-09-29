CANAL BORA DE DORAMAS — PWA V2

ESTRUTURA
- index.html: aparência e funcionamento do app. Normalmente não precisa editar.
- catalogo.js: artistas, dramas, temas e links do Telegram. ESTE É O ARQUIVO DAS ATUALIZAÇÕES.
- imagens.js: imagens incorporadas do catálogo. Só troque quando adicionar/alterar fotos ou pôsteres.
- manifest.webmanifest: dados de instalação do PWA.
- sw.js: atualização/cache do aplicativo.
- icons/: ícones do aplicativo.

COMO ATUALIZAR LISTAS
1. Edite/substitua catalogo.js.
2. No GitHub, faça upload do novo catalogo.js na raiz do repositório e confirme a substituição.
3. Aguarde o GitHub Pages publicar a alteração.
4. Abra/recarregue o app. O V2 busca uma versão nova do catálogo na internet antes de usar a cópia em cache.

IMPORTANTE
Na primeira migração para a V2, substitua index.html e sw.js e adicione catalogo.js e imagens.js. Os demais arquivos podem permanecer.
