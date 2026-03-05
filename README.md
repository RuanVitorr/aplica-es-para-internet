# Aplicações para Internet

- Troquei as `div` com `id="header/content/footer"` por tags semânticas (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`) para melhorar a acessibilidade, SEO e legibilidade da estrutura do DOM.

- Removi o CSS interno do HTML e passei para `styles.css`, garantindo separação de responsabilidades e facilitando a manutenção do código.

- Refatorei o menu para a estrutura `nav > ul > li > a` e removi os separadores `|` do HTML, deixando a apresentação por conta do CSS.

- Ajustei os títulos para `<h1>` e `<h2>`, seguindo uma hierarquia semântica correta, substituindo elementos usados apenas para estilização.

- Melhorei a imagem utilizando `<figure>` e `<figcaption>`, além de adicionar o atributo `alt`, aumentando a acessibilidade e a qualidade do markup.

- Adicionei a meta tag `viewport` (`<meta name="viewport">`) para melhorar a responsividade em dispositivos móveis.

- Usei `<address>` no rodapé e o link `tel:` para dar mais semântica e usabilidade às informações de contato.
