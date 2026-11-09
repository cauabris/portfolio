# Portfólio — Cauã Bris

Site pessoal de portfólio, publicado como página estática pelo GitHub Pages. O projeto preserva o template original de animações por rolagem e mantém os estilos e scripts junto ao HTML.

## Arquivos publicados

- `index.html` — página completa, com HTML, CSS e JavaScript inline. É o ponto de entrada do GitHub Pages.
- `CREDITS.md` — créditos das imagens e recursos usados no template.
- `LICENSE` — licença MIT do template original.
- `.nojekyll` — instrui o GitHub Pages a servir o projeto como arquivos estáticos, sem processamento Jekyll.
- `CNAME` — domínio personalizado preparado: `cauabris.com.br`. O domínio ainda precisa ser configurado nas definições do Pages e no DNS do Registro.br.
- `README.md` — este guia.

Arquivos de trabalho, versões anteriores, documentos de conteúdo e metadados locais não fazem parte da publicação.

## Dependências e recursos externos

Não há etapa de build, `package.json` ou biblioteca JavaScript externa. O CSS e as animações ficam no `index.html`.

As imagens são carregadas do Unsplash e as fontes Gabarito/Onest do Google Fonts (`fonts.gstatic.com`). A página precisa de conexão à internet para exibir esses recursos. O HTML não depende de caminhos para imagens ou scripts locais.

## Publicação

O site pode ser servido a partir da raiz da branch `main` em **Settings → Pages → Deploy from a branch → main → /(root)**. Cada push para `main` atualiza o GitHub Pages automaticamente.

## Atualizações futuras

1. Edite `index.html` sem remover os IDs e atributos `data-8b-*` usados pelas animações.
2. Faça commit das alterações na branch `main` e envie (`push`) ao GitHub.
3. Aguarde a publicação automática do Pages.

O formulário de contato e o campo de newsletter ainda não estão conectados a um serviço de envio. O preview social e o favicon continuam com valores de demonstração enquanto o site está em desenvolvimento.
