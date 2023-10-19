# Jogo da memória com Emojis - DIO
--------

### Projeto guidado ministrado no bootcamp Potência Tech iFood - Desenvolvimento de Jogos.

#### 💻Tecnologia utilizada:
HTML, CSS e JavaScript.

* 📑 HTML
 Utilizado na criação do botão e do container aonde o jogo vai ser inserido pela manipulação do DOM. E criado o botão e usado a função de reload para atualizar pagina e o jogo ser reiniciado.

* 🖌 CSS
main.css: Utilizado para posicionar os elementos na tela, esconder os conteudos (emoji) dos cards e também gerar o efeito de rotate no elemento e fazer a card do jogo virar assim que for executada a função de click... 

reset.css: Zerado o margin, padding do navegador e definido o box-sizing.


* 👨‍💻 JavaScript
Criado um array para armazenar os emojis usados nos cards, metodo Math.random para embaralhar as cards. Cria um laço for para que seja posicionado na tela os cards com os seus respectivos emojis percorrendo o tamanho do array de emojis. Colocado a função de click nos cards e assim dar o efeito de rotação, no mesmo click, o innerHtml do card é armazenado em um array na posição[0] e o segundo card clicado é armazenado na posição[1], depois disso é comparado os seus valores e assim verificar se é o seu par.
