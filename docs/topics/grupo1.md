# Guia de Acessibilidade 

## 1. Alto contraste 
- [ ] Ofereça opções de alto contraste (*dark-mode*).

<style>
  .botao-conceito {
    border: 1px solid black;
    padding: 5px 10px;
    border-radius: 10px;
    background-color: #4051B5;
    color: white;
    font-size: 16px;
    cursor: pointer;
    box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
    transition: background-color 0.3s, transform 0.3s;
  }
  .botao-conceito:hover {
    background-color: #0056b3;
    transform: scale(1.05);
  }
</style>

<button title="Conceito alto contraste" class="botao-conceito" onclick="let el = document.getElementById('altocontraste'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="altocontraste" style="display: none;">
O alto contraste facilita a leitura e a compreensão do conteúdo para pessoas com dificuldades visuais, como daltonismo ou visão embaçada. Quando as cores de fundo e texto têm um contraste forte, é mais fácil para essas pessoas distinguir as informações, tornando o site mais inclusivo e acessível para todos. Isso ajuda a garantir que mais pessoas possam navegar de forma eficiente e sem barreiras. <a href="#referencia-1">[1]</a>
</div>

---

## 2. Ampliação da tela

- [ ] O conteúdo permaneça claro e organizado, ao aumentar a tela com zoom em até 200%.

<button title="Conceito ampliação de tela" class="botao-conceito" onclick="let el = document.getElementById('ZOOM'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖 
</button>
<div id="ZOOM" style="display: none;">
Ao aumentar a tela com o zoom do navegador em até 200%, o conteúdo precisa continuar claro e organizado, sem que nenhuma informação desapareça ou fique sobreposta. <a href="#referencia-2">[2]</a>
</div>

---

## 3. Áreas de clique

- [ ] Áreas clicáveis com no mínimo 44px (pixels) de altura e 44px de largura.

<button title="Conceito área de clique" class="botao-conceito" onclick="let el = document.getElementById('clique'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="clique" style="display: none;">
Os botões e áreas de clique de uma página devem ter um tamanho suficiente para que qualquer pessoa consiga usar com facilidade e segurança. Em computadores, o tamanho mínimo recomendado é de 24x24px, e em celulares é 48x48px. Mesmo que o ícone ou botão em si seja menor, como por exemplo 40px ou 20px de largura. Porém, não tão grandes a ponto de invadirem o espaço de outros botões ou elementos próximos. Ainda mais em telas menores para não ocorrer cliques acidentais. <a href="#referencia-3">[3]</a>
</div>

---

## 4. Design responsivo

- [ ] Certifique-se que o design seja responsivo.

<button title="Conceito responsividade" class="botao-conceito" onclick="let el = document.getElementById('responsivo'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="responsivo" style="display: none;">
O design responsivo é muito importante para a acessibilidade, pois permite que a interface se adapte às necessidades de quem está navegando.

Uma dica é começar a criar o design para celular e, depois, ajustar para computadores. Isso facilita o desenvolvimento e garante que o conteúdo fique bem organizado em telas de todos os tamanhos. <a href="#referencia-4">[4]</a>
</div>

---

## 5. Foco visível

- [ ] Tenha algum tipo de **destaque** ao redor do elemento, como borda, moldura ou brilho.

<button title="Conceito foco visível" class="botao-conceito" onclick="let el = document.getElementById('focov'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="focov" style="display: none;">
Garantir que o foco esteja visível na tela é essencial. O foco é como um destaque ao redor do elemento em que o usuário está interagindo, como uma borda ou moldura. Quando o foco não aparece ou simplesmente não existe, fica muito difícil navegar usando apenas o teclado.

Para resolver isso, use recursos visuais para mostrar claramente onde está o foco. <a href="#referencia-5">[5]</a>
</div> 

---

## 6. Navegação 100% por teclado

- [ ] Permite/visa a navegação por meio de Atalhos de teclado como o ```TAB```.

<button title="Conceito navegação por teclado" class="botao-conceito" onclick="let el = document.getElementById('teclado'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="teclado" style="display: none;">
Todas as funções de uma página web precisam funcionar usando apenas o teclado. Por isso, é importante evitar efeitos visuais que dependem somente do movimento do mouse, como quando passamos o cursor sobre algo (<i>mouseover</i>) para revelar informações. Uma boa alternativa é fazer com que as ações também sejam ativadas com um clique, permitindo que pessoas que usam leitores de tela consigam acessar tudo usando o teclado. <a href="#referencia-6">[6]</a>
</div>

---

## 7. Pausar, parar ou ocultar conteúdo

- [ ] Conteúdos que se movem, permita opções para pausar, reduzir movimento e avançar e voltar.

<button title="Conceito carrossel" class="botao-conceito" onclick="let el = document.getElementById('carrosel'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="carrosel" style="display: none;">
Para conteúdos que se movem, como carrosseis, é essencial permitir que o usuário possa pausar, esconder ou parar. Movimentos automáticos sem controle podem prejudicar a experiência de pessoas com condições neurodiversas ou que usam leitores de tela. Isso acontece porque esses conteúdos podem gerar sobrecarga mental, distrair do restante da página ou dificultar a navegação.
Por isso, evite usar movimentos automáticos sempre que possível. Se for realmente necessário mantê-los, ofereça opções de pausar, reduzir o movimento, além de botões para avançar e voltar. <a href="#referencia-7">[7]</a>
</div>

---

## 8. Tamanho da fonte

- [ ] Tenha ferramentas que aumentem ou diminuiam a fonte para o leitor.

<button title="Conceito tamanho da fonte" class="botao-conceito" onclick="let el = document.getElementById('tamanho'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="tamanho" style="display: none;">
Botões para ajuste do tamanho das letras, embora não sejam obrigatórios para garantir a acessibilidade, podem ser úteis para os usuários. Isso ocorre porque muitas pessoas com deficiência já utilizam essas funções diretamente em seus navegadores ou por meio de atalhos no teclado. No entanto, é fundamental que o site seja bem elaborado e compatível com essas ferramentas. Assim, esses botões podem oferecer mais conforto durante a navegação. <a href="#referencia-8">[8]</a>
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

---

## 9. Uso da cor

- [ ] Use informações além da cor, como forma ou texto, para transmitir significado.

<button title="Conceito do uso da cor" class="botao-conceito" onclick="let el = document.getElementById('cor'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="cor" style="display: none;">
A cor não é utilizada como o único meio visual de transmitir informações, indicar uma ação, pedir uma resposta ou distinguir um elemento visual. <a href="#referencia-9">[9]</a>
</div>

## Referências 

<a id="referencia-1" href="https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#contrast-minimum" target="_blank" aria-label="WCAG 2.1 - Constraste (Seção 1.4.3). Abre em uma nova aba">
  1. WCAG 2.1 - Constraste (Seção 1.4.3)
</a>. Disponível em: <a href="https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#contrast-minimum" target="_blank" aria-label="Link para WCAG 2.1 - Constraste (Seção 1.4.3). Abre em uma nova aba">
  https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#contrast-minimum
</a>. Acesso em 24 Jan. 2025.

<a id="referencia-2" href="https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#resize-text" target="_blank" aria-label="WCAG 2.1 - Redimensionamento de Texto (Seção 1.4.4). Abre em uma nova aba">
  2. WCAG 2.1 - Redimensionamento de Texto (Seção 1.4.4)
</a>. Disponível em: <a href="https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#resize-text" target="_blank" aria-label="Link para WCAG 2.1 - Redimensionamento de Texto (Seção 1.4.4). Abre em uma nova aba">
  https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#resize-text
</a>. Acesso em 24 Jan. 2025.

<a id="referencia-3" href="https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#target-size" target="_blank" aria-label="WCAG 2.1 - Tamanho do Alvo (Seção 2.5.5). Abre em uma nova aba">
  3. WCAG 2.1 - Tamanho do Alvo (Seção 2.5.5)
</a>. Disponível em: <a href="https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#target-size" target="_blank" aria-label="Link para WCAG 2.1 - Tamanho do Alvo (Seção 2.5.5). Abre em uma nova aba">
  https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#target-size
</a>. Acesso em 24 Jan. 2025.

<a id="referencia-4" href="https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#cc2" target="_blank" aria-label="WCAG 2.1 - Responsividade (Seção 2.1). Abre em uma nova aba">
  4. WCAG 2.1 - Responsividade (Seção 2.1)
</a>. Disponível em: <a href="https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#cc2" target="_blank" aria-label="Link para WCAG 2.1 - Responsividade (Seção 2.1). Abre em uma nova aba">
  https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#cc2
</a>. Acesso em 24 Jan. 2025.

<a id="referencia-5" href="https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#focus-visible" target="_blank" aria-label="WCAG 2.1 - Foco Visível (Seção 2.4.7). Abre em uma nova aba">
  5. WCAG 2.1 - Foco Visível (Seção 2.4.7)
</a>. Disponível em: <a href="https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#focus-visible" target="_blank" aria-label="Link para WCAG 2.1 - Foco Visível (Seção 2.4.7). Abre em uma nova aba">
  https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#focus-visible
</a>. Acesso em 24 Jan. 2025.

<a id="referencia-6" href="https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#keyboard-accessible" target="_blank" aria-label="WCAG 2.1 - Acessibilidade por Teclado (Seção 2.1). Abre em uma nova aba">
  6. WCAG 2.1 - Acessibilidade por Teclado (Seção 2.1)
</a>. Disponível em: <a href="https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#keyboard-accessible" target="_blank" aria-label="Link para WCAG 2.1 - Acessibilidade por Teclado (Seção 2.1). Abre em uma nova aba">
  https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#keyboard-accessible
</a>. Acesso em 24 Jan. 2025.

<a id="referencia-7" href="https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#pause-stop-hide" target="_blank" aria-label="WCAG 2.1 - Pausar, Parar ou Ocultar Conteúdo (Seção 2.2.2). Abre em uma nova aba">
  7. WCAG 2.1 - Pausar, Parar ou Ocultar Conteúdo (Seção 2.2.2)
</a>. Disponível em: <a href="https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#pause-stop-hide" target="_blank" aria-label="Link para WCAG 2.1 - Pausar, Parar ou Ocultar Conteúdo (Seção 2.2.2). Abre em uma nova aba">
  https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#pause-stop-hide
</a>. Acesso em 24 Jan. 2025.

<a id="referencia-8" href="https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#text-alternatives" target="_blank" aria-label="WCAG 2.1 - Tamanho da fonte (Seção 1.1.1). Abre em uma nova aba">
  8. WCAG 2.1 - Tamanho da fonte (Seção 1.1.1)
</a>. Disponível em: <a href="https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#text-alternatives" target="_blank" aria-label="Link para WCAG 2.1 - Tamanho da fonte (Seção 1.1.1). Abre em uma nova aba">
  https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#text-alternatives
</a>. Acesso em 24 Jan. 2025.

<a id="referencia-9" href="https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#use-of-color" target="_blank" aria-label="WCAG 2.1 - Uso de Cor (Seção 1.4.1). Abre em uma nova aba">
  9. WCAG 2.1 - Uso de Cor (Seção 1.4.1)
</a>. Disponível em: <a href="https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#use-of-color" target="_blank" aria-label="Link para WCAG 2.1 - Uso de Cor (Seção 1.4.1). Abre em uma nova aba">
  https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/#use-of-color
</a>. Acesso em 24 Jan. 2025.