# Ghost Media — pacote HTML estático

Este pacote contém a landing page institucional da Ghost Media e todas as páginas vinculadas, em HTML, CSS e JavaScript locais. Não há necessidade de Node.js, React, banco de dados ou backend.

## Estrutura

A página inicial está em `index.html`. As páginas adicionais são `contato.html`, `politica-de-reembolso.html`, `termos-de-uso.html` e `politica-de-privacidade.html`. Os arquivos compartilhados ficam em `assets/styles.css` e `assets/script.js`.

## Hospedagem

Envie todos os arquivos e a pasta `assets` para a pasta pública do seu hosting, normalmente chamada `public_html`, `www` ou `htdocs`. Preserve os nomes dos arquivos e a estrutura de diretórios. Abra o domínio apontando para `index.html` como documento inicial.

A única dependência externa é o carregamento opcional das fontes Google Fonts pelo CSS. O restante da página, incluindo os gráficos, foi feito com HTML e SVG inline. O contato usa o WhatsApp oficial `https://wa.me/5511944355660`.

## Slugs e páginas

| Página | Arquivo | URL relativa |
|---|---|---|
| Página inicial | `index.html` | `/` ou `/index.html` |
| Contato | `contato.html` | `/contato.html` |
| Política de reembolso | `politica-de-reembolso.html` | `/politica-de-reembolso.html` |
| Termos de uso | `termos-de-uso.html` | `/termos-de-uso.html` |
| Política de privacidade | `politica-de-privacidade.html` | `/politica-de-privacidade.html` |

Se o servidor utilizar Apache e você desejar URLs sem `.html`, será necessário configurar regras de rewrite no `.htaccess`. A versão entregue funciona diretamente com os nomes `.html` em praticamente qualquer hospedagem estática.

Os textos legais são uma minuta de trabalho e devem ser revisados por um profissional qualificado antes do uso oficial.
