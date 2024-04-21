![Badge Concluido](http://img.shields.io/static/v1?label=STATUS&message=%20CONCLUIDO&color=GREEN&style=for-the-badge)
# 📁 Projeto Landing Page

  O desafio foi criar a Landing Page baseada no desing. 
  
  Usando tags mais semânticas para criação de um código mais limpo, para facilitar na manutenção e ser mais fácil na adição de mais informações.

  A melhor forma de deixar o código mais organizado e fácil de dar manutenção é separar as marcações e as estilizações no **HTML** e no **CSS**.

  A melhor forma é dar bons nomes, deixar os nomes descritivos e fáceis de entender.

  Ao criar uma **class** para mater o nível de especificidade nos elementos e evitar que de problema.

````html
<header class=”header”>
	<div class=”header-container”>
````
  O conceito de media queries é super importante quando falamos de responsividade, estilizando os elementos a partir de determinadas resoluções.

````CSS
  @media (max-width: 425px) {
    .hero {
        height: 60vh;
    }
    .hero h2 {
        font-size: 2.5rem;
    }
}
````

### :movie_camera: Landing Page

<img src=".\Animação1.gif" alt="Landing Page" width="600px" heidth="400px">

#### Gostei muito desse padrão de **reset.css** e vou usá-lo daqui para frente.

````CSS
*{
    margin: 0;
    padding: 0;
    border: none;
    outline: none;
    font-weight: 300;
    box-sizing: border-box;
}

a{
    text-decoration: none;
    color: black;
}

ul{
    list-style: none;
}

img{
    max-width: 100%;
}
````


#### Achei muito legal esse efeito no menu e como fica no responsivo.

````CSS
.header input:checked ~ label .hamburguer {
    transform: rotate(45deg);
}

.header input:checked ~ label .hamburguer:before {
    transform: rotate(90deg);
    top: 0;
}

.header input:checked ~ label .hamburguer:after {
    transform: rotate(90deg);
    bottom: 0;
}
````



## :arrows_counterclockwise: Como trocar a fonte:

  Entrando no site do **[google fontes](https://fonts.google.com/)**, digite a fonte que procura. Ex. Public Sans.
  
  Selecione a fonte, clique no botão **Get font**, botão **Get embeb code**, escolha o tamanho da fonte botão **One value**, copie o link  do código **Copy code** e cole no código html.

````html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Public+Sans:ital,wght@0,500;1,500&display=swap" rel="stylesheet">
````

  Em seguida copie o código para a regra do **CSS**, copie o link  do código **Copy code** e cole no código **style.css**.

### :dart: Use um nome de **classe** único e descritivo.

````CSS
.pintura {
  font-family: "Public Sans", sans-serif;
  font-optical-sizing: auto;
  font-weight: 500;
  font-style: normal;
}
````

### :film_strip: Como trocar a fonte:

<img src=".\Animação2.gif" alt="Google fontes" width="600px" heidth="400px">


## :computer: Técnicas e Tecnologias utilizadas:

- Flexbox
- Grid
- Técnicas de código limpo
- Mudar fontes
- Marcação HTML5 semântica
- Propriedades personalizadas CSS
- Fluxo de trabalho voltado para dispositivos móveis

