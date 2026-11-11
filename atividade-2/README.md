# Atividade 2 — Página pessoal e formulário de contato

Página pessoal de Isabeli Azevedo, desenvolvida na disciplina Programação Web I.

A seção **Entre em contato** contém campos de nome, e-mail, assunto e mensagem, com campos obrigatórios, rótulos associados, agrupamento com `fieldset` e `legend` e botões **Enviar** e **Limpar**.

## Captura da página

Página aberta no navegador, mostrando o formulário implementado:

![Página pessoal com a seção Entre em contato e o formulário implementado](img/captura-formulario.png)

# Atividade - Aplicando CSS à Página Pessoal

A página recebeu uma folha externa `style.css`, compartilhada por `index.html` e `sobre.html`. Os estilos incluem cores, fontes, seletores de elementos, classes e identificador, bordas, dimensões da imagem, espaçamentos, formulário personalizado e links com `:hover`. A estrutura semântica e os campos obrigatórios foram preservados.

### Resultado com CSS

![Página pessoal aberta no navegador com os estilos CSS aplicados](img/captura-css.png)

## Página pessoal com Flexbox e Grid

A seção **Tecnologias e Interesses** apresenta quatro cartões: HTML, CSS, Geografia e Educação. Cada cartão contém título, conteúdo e tags.

- **Grid nos cartões:** `.grade-cartoes` usa `display: grid`, `grid-template-columns` e `gap` para formar duas colunas no computador e uma no celular.
- **Flexbox interno:** `.cartao` usa `display: flex`, `flex-direction`, `justify-content`, `align-items` e `gap`. As tags usam Flexbox com quebra de linha.
- **Estrutura da página:** `body`, `header`, `nav`, `main` e `footer` são organizados com Grid. `grid-column: 1 / -1` permite que as áreas e seções ocupem todas as colunas da grade.
- **Preservação:** identificação pessoal, foto, hobbies, formulário, página Sobre e estilos anteriores foram mantidos. O CSS permanece externo.

### Captura do resultado final

![Página pessoal com cartões organizados por Grid e Flexbox](img/captura-flexbox-grid.png)