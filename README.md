# aplica-es-para-internet
1- troquei o <div id="header/content/footer"> por tags como (<header>, <nav>, <main>, <section>, <footer>) pra melhorar a acessibilidade, SEO e legibilidade do DOM

2- Removi o CSS interno do HTML e passei para styles.css para garantir separação de responsabilidades e facilitar a manutenção

3- Refatorei o menu para <nav><ul><li><a>> e removi os separadores “|” do HTML, deixando a apresentação por conta do CSS.

4- Ajustei títulos para <h1>/<h2> seguindo hierarquia semântica correta, substituindo “título/subtítulo” em <div>.

5- Melhorei a imagem usando <figure> + <figcaption> e adicionei alt, aumentando acessibilidade (leitores de tela) e qualidade do markup.

6- Adicionei <meta name="viewport"> para melhorar responsividade no celular.

7- Usei <address> no rodapé e link tel: para dar semântica e usabilidade ao contato.