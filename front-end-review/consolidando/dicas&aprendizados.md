### FrontEnd
###### Existem tipos de linguagens

1. linguagem de programação
2. linguagem de consulta
3. linguagem de estilização
4. linguagem de marcação

#### HTML
* é linguagem de marcação. 

###### A instrução DOCTYPE serve para indicar qual linguagem estamos usando 
no nosso documento e em qual versão.

###### A codificação UTF-8 abrange quase todos os sistemas de escritas do mundo. 

Além disso, todos os computadores vêm com suporte a essa codificação. 
Assim, se queremos que nossas páginas sejam acessíveis por todos, 
a codificação UTF-8 é a melhor opção.

###### Link relativo: href="portfolio.html". O navegador entende que isso é relativo
a página que você veio e só concatena. 
###### Link absoluto: href="http://meusite.com/portfolio.html". É exatamento o link inteiro.
* Todo link que não começa com o http, é um link relativo.

###### Tudo que for lista vai ser um <ul> e os filhos de um ul vão ser <li>

###### A tag <nav> é uma tag para agregar mais semântica no seu código/site. 
Tem a tag <main> também, que agrega semântica. Mais semântica, facilita a acessibilidade para leitores de tela. 
O <blockquote> também, agrega mais sentido quando você sabe que é uma citação. Todos são exemplos do HMLT5.

<main>: conteúdo principal da página
<header>: cabeçalho da página ou de uma região dela
<footer>: mesma ideia da tag <header> para o rodapé
<aside>: conteúdo auxiliar ao conteúdo principal, como links relacionados ao conteúdo
<article>: conteúdo que, por si só, já tem um sentido completo, como um post de um blog ou uma notícia
<section>: parte/seção de uma página ou texto

###### Uma coisa muito legal: a tag time. 
<time datetime="2014-07-13">13 de julho de 2014</time>

###### Entidades de HTML
* &copy;: ©
* &euro;: €
* &yen;: ¥
* &pound;: £
* &reg;: ®
* &hearts;: ♥

#### CSS
* é linguagem de estilização. 

###### O padding é o espaço interno do componente.
###### O margin controla os espaços externos do component. 

* Todas essas regras (width, height, margin, border, padding --> content) juntas formam o que chamamos **box model** ou, em português, "modelo de caixa", do CSS.

* Usar esse babado do reset do CSS: reseta todos os estilos de CSS que foram aplicados pelo browser.
```Devemos usar um reset nos nossos projetos para eliminar diferenças de layout entre navegadores e bugs específicos de alguns navegadores. Com isso, ganhamos uma base sólida para desenvolvermos nosso site. Ou seja, todas as alternativas listam benefícios de se usar um reset.```

-- No momento, estamos usando o reset do (Eric Meyer)[http://necolas.github.io/normalize.css/], mas existem várias alternativas. Uma também bastante famosa é o Normalize, criado por Nicolas Gallagher e Jonathan Neal.






