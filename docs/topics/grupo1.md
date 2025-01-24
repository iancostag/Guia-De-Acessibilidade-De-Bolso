## Alto contraste 
Ofereça opções de alto contraste (*dark-mode*).

<style>
  button:not(#aumentar):not(#diminuir) {
    border: 1px solid black;
    padding: 5px 10px;
    border-radius: 10px; /* Adiciona cantos arredondados */
    background-color: #4051B5; /* Cor de fundo */
    color: white; /* Cor do texto */
    font-size: 16px; /* Tamanho da fonte */
    cursor: pointer; /* Cursor de ponteiro */
    box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3); /* Sombra */
    transition: background-color 0.3s, transform 0.3s;
  }
  button:not(#aumentar):not(#diminuir):hover {
    background-color: #0056b3; /* Cor de fundo ao passar o mouse */
    transform: scale(1.05); /* Aumenta ligeiramente o botão */
  }
</style>

<button title="alo" class="botao-conceito" onclick="let el = document.getElementById('altocontraste'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="altocontraste" style="display: none;">
O alto contraste facilita a leitura e a compreensão do conteúdo para pessoas com dificuldades visuais, como daltonismo ou visão embaçada. Quando as cores de fundo e texto têm um contraste forte, é mais fácil para essas pessoas distinguir as informações, tornando o site mais inclusivo e acessível para todos. Isso ajuda a garantir que mais pessoas possam navegar de forma eficiente e sem barreiras.
</div>

## Ampliação da tela

O conteúdo permaneça claro e organizado, ao aumentar a tela com zoom em até 200%.

<button onclick="let el = document.getElementById('ZOOM'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖 
</button>
<div id="ZOOM" style="display: none;">
Ao aumentar a tela com o zoom do navegador em até 200%, o conteúdo precisa continuar claro e organizado, sem que nenhuma informação desapareça ou fique sobreposta.
</div>

## Áreas de clique

Áreas clicáveis com no mínimo 44px (pixels) de altura e 44px de largura.

<button onclick="let el = document.getElementById('clique'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="clique" style="display: none;">
Os botões e áreas de clique de uma página devem ter um tamanho suficiente para que qualquer pessoa consiga usar com facilidade e segurança. Em computadores, o tamanho mínimo recomendado é de 24x24px, e em celulares é 48x48px. Mesmo que o ícone ou botão em si seja menor, como por exemplo 40px ou 20px de largura. Porém, não tão grandes a ponto de invadirem o espaço de outros botões ou elementos próximos. Ainda mais em telas menores para não ocorrer cliques acidentais.
</div>

## Design responsivo

Certifique-se que o design seja responsivo.

<button onclick="let el = document.getElementById('responsivo'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="responsivo" style="display: none;">
O design responsivo é muito importante para a acessibilidade, pois permite que a interface se adapte às necessidades de quem está navegando.

Uma dica é começar a criar o design para celular e, depois, ajustar para computadores. Isso facilita o desenvolvimento e garante que o conteúdo fique bem organizado em telas de todos os tamanhos.
</div>

## Foco visível

Tenha algum tipo de **destaque** ao redor do elemento, como borda, moldura ou brilho.

<button onclick="let el = document.getElementById('focov'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="focov" style="display: none;">
Garantir que o foco esteja visível na tela é essencial. O foco é como um destaque ao redor do elemento em que o usuário está interagindo, como uma borda ou moldura. Quando o foco não aparece ou simplesmente não existe, fica muito difícil navegar usando apenas o teclado.

Para resolver isso, use recursos visuais para mostrar claramente onde está o foco. 
</div>

## Navegação 100% por teclado

Permite/visa a navegação por meio de Atalhos de teclado como o ```TAB```.

<button onclick="let el = document.getElementById('teclado'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="teclado" style="display: none;">
Todas as funções de uma página web precisam funcionar usando apenas o teclado. Por isso, é importante evitar efeitos visuais que dependem somente do movimento do mouse, como quando passamos o cursor sobre algo (<i>mouseover</i>) para revelar informações. Uma boa alternativa é fazer com que as ações também sejam ativadas com um clique, permitindo que pessoas que usam leitores de tela consigam acessar tudo usando o teclado.
</div>

## Navegação em celular e computador

A navegação deve permanecer acessível para celular e computador.

<button onclick="let el = document.getElementById('navcel'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="navcel" style="display: none;">
No Brasil, há mais celulares do que computadores, e muitas pessoas navegam por *notebooks* ou desktops sem encontrar problemas. Porém, ao acessar o mesmo conteúdo pelo celular, é possível que surjam barreiras, algo que não deveria ocorrer. A experiência de navegação acessível pode variar bastante dependendo do fabricante do celular ou do navegador utilizado.
</div>

## Pausar, parar ou ocultar conteúdo

Conteúdos que se movem, permita opções para pausar, reduzir movimento e avançar e voltar.

<button onclick="let el = document.getElementById('carrosel'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="carrosel" style="display: none;">
Para conteúdos que se movem, como carrosseis, é essencial permitir que o usuário possa pausar, esconder ou parar. Movimentos automáticos sem controle podem prejudicar a experiência de pessoas com condições neurodiversas ou que usam leitores de tela. Isso acontece porque esses conteúdos podem gerar sobrecarga mental, distrair do restante da página ou dificultar a navegação.
Por isso, evite usar movimentos automáticos sempre que possível. Se for realmente necessário mantê-los, ofereça opções de pausar, reduzir o movimento, além de botões para avançar e voltar.
</div>

## Tamanho da fonte

Tenha ferramentas que aumentem ou diminuiam a fonte para o leitor.

<button onclick="let el = document.getElementById('tamanho'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="tamanho" style="display: none;">
Botões para ajuste do tamanho das letras, embora não sejam obrigatórios para garantir a acessibilidade, podem ser úteis para os usuários. Isso ocorre porque muitas pessoas com deficiência já utilizam essas funções diretamente em seus navegadores ou por meio de atalhos no teclado. No entanto, é fundamental que o site seja bem elaborado e compatível com essas ferramentas. Assim, esses botões podem oferecer mais conforto durante a navegação.
<div class="container">
  <button id="aumentar" onclick="aumentarFonte()">A+</button>
  <button id="diminuir" onclick="diminuirFonte()">A-</button>
</div>
<script>
  function aumentarFonte() {
    var texto = document.getElementById('tamanho');
    var style = window.getComputedStyle(texto, null).getPropertyValue('font-size');
    var fontSize = parseFloat(style);
    texto.style.fontSize = (fontSize + 2) + 'px';
  }
  function diminuirFonte() {
    var texto = document.getElementById('tamanho');
    var style = window.getComputedStyle(texto, null).getPropertyValue('font-size');
    var fontSize = parseFloat(style);
    texto.style.fontSize = (fontSize - 2) + 'px';
  }
</script><style>
  .text-parag{
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .container {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
  }
  #aumentar, #diminuir {
    font-size: 400%;
    margin: 10px;
  }
  #aumentar:hover, #diminuir:hover {
    color: #4051B5;
    font-size: 425%;
  }
</style>
</div>

## Uso da cor

Verificar a escolha das cores de maneira mais adequada.

<button onclick="let el = document.getElementById('cor'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="cor" style="display: none;">
A escolha das cores de um site deve ser feita com cuidado, pois as pessoas enxergam as cores de formas diferentes. Algumas têm dificuldade em distinguir certas cores, como nos casos de daltonismo, em que a pessoa pode não enxergar vermelho, verde, azul ou, em alguns casos, nenhuma cor. Por isso, as cores podem ter um impacto muito grande na forma como essas pessoas entendem o conteúdo.
</div>

## Referências Bibliográficas

> <a id="RP1" href="https://www.w3.org/WAI/WCAG22/Understanding/use-of-color.html](https://www.w3.org/WAI/WCAG22/Understanding/use-of-color.html"></a> WCAG 2.2 Understanding Docs. SC 1.4.1 Use of Color (Level A). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/use-of-color.html](https://www.w3.org/WAI/WCAG22/Understanding/use-of-color.html). Acesso em: 9 Mai. 2024. 