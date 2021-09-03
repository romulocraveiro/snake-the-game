# Recriação do "jogo da cobrinha" com JavaScript

## Objetivos / Aims

* Construir o jogo da cobrinha e personalizar o jogo usando criatividade. O projeto é avaliação parcial do Bootcamp HTML Web Developer da Digital Innovation One. Professora: Gabriela Spruce
* <i> Build the snake game and customize it by using creativity. The project is part of the assessment system of Digital Innovation One's Bootcamp HTML Web Developer. Teacher: Gabriela Spruce</i>

## Algumas lições que aprendi / Some lessons I learned

* Usamos Math.random para que a cobrinha se mova; / _We use Math.random for the snake to move_;

* A cobrinha é criada como lista, ou seja, tem coordenadas que são "pintadas" para criar os quadradinhos; / _The snake is created as a list, meaning it has coordinates that will be "painted" to create the little squares_;

* As teclas das setinhas são referenciadas com os números 37, 38, 39 e 40, esquerda, para cima, direita, para baixo, respectivamente; _The little arrows in the keyboard are referenced with the numbers 37, 38, 39 and 40, respectively left, up, right, down_.

* O teste do WAVE (web accessibility evaluation tool) sinalizou erro de contraste nas palavras, mas tal sinalização parecia incoerente. Felizmente, a própria ferramenta mostra num código o suposto erro nas cores em questão. Percebi que a ferramenta não considera uma imagem de fundo como contrastante, levando em consideração o que está por trás dela, ou seja, uma página em branco padrão. Então resolvi incluir mais uma linha de código no CSS referente à cor de fundo. Faz sentido, pois se a imagem de fundo não carregar por algum motivo, então não haverá perda de visibilidade. / _The WAVE (web accessibilite evaluation tool) showed contrast errors on the title and subtitle of the page, but it didn't make sense. Fortunately, the tool also shows the supposed error in the colors. I noticed, though, that it does not consider the background image as a constrasting element, taking into consideration the color behind the image, which is the standard html page. Then I decided to include a line of code on CSS that styled the page's background color (behind the image). It makes sense, though, because if for any reason the background image is not loaded, it will not get in the way of accessibility._


  

## Tecnologias / Technologies

* CSS
* HTML
* JavaScript

  

## Links 

* [Digital Innovation One](https://digitalinnovation.one/);
* [Link para a página web (GitHub) deste projeto / Link to this project's webpage](https://romulocraveiro.github.io/snake-the-game/);
* [Free SVG images, onde encontrei a imagem da cobrinha / where I found the snake image](https://freesvg.org/)
* [Remova fundos de imagens / Remove images background](https://www.remove.bg/pt-br)

## Autor / Author

| Foto                                                   | Nome                               | GitHub                                               | Likedin                                                 | E-mail                   |
| ------------------------------------------------------ | ---------------------------------- | ---------------------------------------------------- | ------------------------------------------------------- | ------------------------ |
| <img src="./img/fotogit.jpeg" width="100px"> | Romulo Craveiro de Sousa Tartaruga | [Romulo Craveiro](https://github.com/romulocraveiro) | [Linkedin](https://www.linkedin.com/in/romulocraveiro/) | romulocraveiro@gmail.com |

