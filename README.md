# aplica-es-para-internet
 troquei o div id="header/content/footer"> por tags como (<header>, <nav>, <main>, <section>, <footer>) pra melhorar a acessibilidade, SEO e legibilidade do DOM
 
 Removi o CSS interno do HTML e passei para styles.css para garantir separação de responsabilidades e facilitar a manutenção

 Refatorei o menu para <nav><ul><li><a>> e removi os separadores “|” do HTML, deixando a apresentação por conta do CSS.

 Ajustei títulos para <h1>/<h2> seguindo hierarquia semântica correta, substituindo “título/subtítulo” em <div>.

 Melhorei a imagem usando <figure> + <figcaption> e adicionei alt, aumentando acessibilidade (leitores de tela) e qualidade do markup.

 Adicionei meta name="viewport"> para melhorar responsividade no celular.

 Usei <address> no rodapé e link tel: para dar semântica e usabilidade ao contato.
