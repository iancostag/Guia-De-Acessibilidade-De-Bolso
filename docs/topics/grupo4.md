# Guia de Acessibilidade 

## 1. Conteúdos em Diversos Formatos

- [ ] Oferecer texto alternativos para imagens
- [ ] Disponibilizar transcrições de áudios e legendas em vídeos.

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

<button title="Conceito conteúdos em diversos formatos" class="botao-conceito" onclick="let el = document.getElementById('diversosFormatos'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="diversosFormatos" style="display: none;">
É importante diversificar os formatos de conteúdo para garantir que pessoas com diferentes habilidades possam acessar informações. Quando possível, utilize diversos para que atenda um demanda maior de público. <a href="#referencia-1">[1]</a> <a href="#referencia-2">[2]</a>

</div>

---

## 2. Blocos de Texto e Parágrafos

- [ ] Os blocos de textos foram divididos em parágrafos curtos.

- [ ] Foi utilizado subtítulos para estruturar o conteúdo.

- [ ] Foi utilizado listas quando possível, para facilitar a leitura.

<button title="Conceito blocos de texto e parágrafos" class="botao-conceito" onclick="let el = document.getElementById('paragrafos'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="paragrafos" style="display: none;">
Textos longos frequentemente apresentam uma estrutura complexa, com múltiplos parágrafos, subtópicos e argumentos interligados. Pessoas com dificuldades de leitura ou organização cognitiva podem ter dificuldade em identificar a estrutura principal, seguir o fluxo do texto e entender a relação entre as diferentes partes. <a href="#referencia-2">[2]</a>
</div>

---

## 3. Fontes

- [ ] Foi usando tamanhos de fonte adequados, geralmente a partir de 16px para textos principais.

- [ ] Foi utilizado fontes sem serifa, como Arial ou Verdana.

- [ ] Foi Garantido espaçamento adequado entre linhas e caracteres.

<button title="Conceito Fontes" class="botao-conceito" onclick="let el = document.getElementById('fonte'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="fonte" style="display: none;">
Uma fonte legível e agradável melhora a experiência do usuário, tornando a leitura mais confortável e eficiente. Isso resulta em maior engajamento, satisfação e tempo de permanência na página. Também torna a leitura mais rápida e fácil que permite que os usuários processem informações de forma mais eficiente, aumentando sua produtividade. <a href="#referencia-6">[6]</a>
</div>

---

## 4. Animações

- [ ] As animações não-essencias podem ser desativadas

<button title="Conceito animações" class="botao-conceito" onclick="let el = document.getElementById('animacoes'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="animacoes" style="display: none;">
Animações podem ser distrativas ou prejudiciais para pessoas com epilepsia ou problemas de atenção. Para mitigar problemas, é recomendado permitir que o usuário pause ou desative animações. <a href="#referencia-3">[3]</a>
</div>

---

## 5. Orientação

- [ ] Usuários não dependem de uma determinação orientação de tela para acessar uma determinada função

<button title="Conceito Orientação" class="botao-conceito" onclick="let el = document.getElementById('rediTexto'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="rediTexto" style="display: none;">
 Em resumo, não depender da orientação da tela é fundamental para criar interfaces inclusivas, usáveis e que proporcionam uma boa experiência de usuário em uma variedade de dispositivos e contextos. Ao seguir as práticas de design responsivo e priorizar a flexibilidade da interface, os desenvolvedores podem garantir que seus aplicativos e sites sejam acessíveis e agradáveis de usar para todos. <a href="#referencia-4">[4]</a>
</div>

---

## 6. Idioma da página

- [ ] Idioma da página deve ser definido para que os tradutores consiga identificar corretamente o idioma.

<button title="Idioma da página" class="botao-conceito" onclick="let el = document.getElementById('idioma'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="idioma" style="display: none;">
 Declarar o idioma da tela é fundamental para a acessibilidade, especialmente para usuários que dependem de leitores de tela. Isso garante que o conteúdo seja lido com a pronúncia e entonação corretas, proporcionando uma experiência mais natural e compreensível. <a href="#referencia-5">[5]</a>
</div>


## Referências 

<a id="referencia-1" href="https://www.w3.org/WAI/WCAG22/Understanding/non-text-content.html" target="_blank" aria-label="WCAG 2.2 - Non-text Content">
  1. WCAG 2.2 - Texto-visual
</a>. Disponível em: <a href="https://www.w3.org/WAI/WCAG22/Understanding/non-text-content.html" target="_blank" aria-label="Link para WCAG 2.2 - Texto-visual">
  https://www.w3.org/WAI/WCAG22/Understanding/non-text-content.html
</a>. Acesso em 24 Jan. 2025.

<a id="referencia-2" href="https://www.w3.org/WAI/WCAG22/Understanding/captions-prerecorded" target="_blank" aria-label="WCAG 2.2 - Non-text Content">
  2. WCAG 2.2 - Legendas
</a>. Disponível em: <a href="https://www.w3.org/WAI/WCAG22/Understanding/captions-prerecorded" target="_blank" aria-label="Link para WCAG 2.2 - Legendas">
  https://www.w3.org/WAI/WCAG22/Understanding/captions-prerecorded
</a>. Acesso em 24 Jan. 2025.

<a id="referencia-3" href="https://www.w3.org/WAI/WCAG22/Understanding/animation-from-interactions" target="_blank" aria-label="WCAG 2.2 - Animações">
  3. WCAG 2.2 - Animações
</a>. Disponível em: <a href="https://www.w3.org/WAI/WCAG22/Understanding/animation-from-interactions" target="_blank" aria-label="Link para WCAG 2.2 - Animações">
  https://www.w3.org/WAI/WCAG22/Understanding/animation-from-interactions
</a>. Acesso em 24 Jan. 2025.

<a id="referencia-4" href="https://www.w3.org/WAI/WCAG22/Understanding/orientation" target="_blank" aria-label="WCAG 2.2 - Orientação">
  4. WCAG 2.2 - Orientação
</a>. Disponível em: <a href="https://www.w3.org/WAI/WCAG22/Understanding/orientation" target="_blank" aria-label="Link para WCAG 2.2 - Orientação">
  https://www.w3.org/WAI/WCAG22/Understanding/orientation
</a>. Acesso em 24 Jan. 2025.

<a id="referencia-5" href="https://www.w3.org/WAI/WCAG22/Understanding/language-of-page" target="_blank" aria-label="WCAG 2.2 - Idioma">
  5. WCAG 2.2 - Idioma
</a>. Disponível em: <a href="https://www.w3.org/WAI/WCAG22/Understanding/language-of-page" target="_blank" aria-label="Link para WCAG 2.2 - Idioma">
  https://www.w3.org/WAI/WCAG22/Understanding/language-of-page
</a>. Acesso em 24 Jan. 2025.

<a id="referencia-6" href="https://www.w3.org/WAI/WCAG22/Understanding/contrast-enhanced" target="_blank" aria-label="WCAG 2.2 - Fontes">
  6. WCAG 2.2 - Fontes
</a>. Disponível em: <a href="https://www.w3.org/WAI/WCAG22/Understanding/contrast-enhanced" target="_blank" aria-label="Link para WCAG 2.2 - Fontes">
  https://www.w3.org/WAI/WCAG22/Understanding/contrast-enhanced
</a>. Acesso em 24 Jan. 2025.