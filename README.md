# CSS Cheatsheet 

## Common CSS Media Queries Breakpoints Cheatsheet 🔥
```css
@media only screen and (min-width: 1800px) {}
@media only screen and (min-width: 1200px) and (max-width: 1799px) {}
@media only screen and (min-width: 992px) and (max-width: 1199px) {}
@media only screen and (min-width: 768px) and (max-width: 991px) {}
@media only screen and (min-width: 481px) and (max-width: 767px) {}
@media only screen and (max-width: 480px) {}
@media only screen and (orientation: landscape) {}
@media only screen and (orientation: portrait) {
```

## Smooth scrolling Cheatsheet 🔥
```css
html{
    scroll-behavior: smooth;
}
```

## 7 Amazing CSS properties 🔥

### word-spacing
###### Similar to letter-spacing, but defines the value of spacing between indivual words.
```css
.text {
    word-spacing: 1rem;
}
```

### text-align-last
###### Alings the last line alone of a paragraph.
```css
.text {
    text-align-last: right;
}
```

### text-emphasis
###### Adds emphasis marks to text.
```css
.text {
    text-emphasis: '🔥';
}
```

### text-wrap
###### Adds emphasis marks to text.
```css
.text {
    text-wrap: balance;
}
.text {
    text-wrap: nowrap;
}
```

### pointer-events
###### Determines whether or not an element should react to pointer events.
```css
.content{
    pointer-events: auto;
}
.content{
    pointer-events: none;
}
```

### tab-size
###### Sets the size of the tab character in terms of either number of space or absolute lenght value.
```css
.content {
    tab-size: 4;
}
```

### user-select
###### Determines whether or not the user can select test from the element.
```css
p {
    user-select: none;
}
p {
    user-select: auto;
}
```

##  Cheatsheet for HTML 
### Texto 🔥
###### Tags de formatação de texto em HTML são usadas para formatar texto de diferentes maneiras, como colocar o texto em negrito, itálico ou monoespaçado. A semântica de texto embutido HTML é usada para definir o significado, estrutura ou estilo de uma palavra, linha ou qualquer parte arbitrária de texto.
```html
<em>…</em> //Usado para enfatizar algum texto ou mostrar algum grau de ênfase.
<strong>…</strong> //Indica que o conteúdo tem grande importância.
<sub>…</sub> //Escreve o texto como subscrito.
<sup>…</sup> //Escreve o texto como sobrescrito.
<abbr>… </abbr> //Representa uma abreviatura ou sigla.
<mark>…</mark> //Destaca textos importantes para fins de referência ou notação.
<cite>…</cite> //Descreve o título de um trabalho criativo.
<time>…</time> //Usado para representar um período específico de tempo.
```
```html
<!-- emphasis -->
<div><em>Emphasized text</em></div>
<!-- strong -->
<div><strong>Important text!</strong></div>
<!-- subscript -->
<div>GFG<sub>subscript text</sub></div>
<!-- superscript -->
<div>GFG<sup>Superscript text</sup></div>
<!-- abbreviation -->
<div><abbr>Abbreviation</abbr></div>
<!-- mark -->
<div><mark>Highlighted text</mark></div>
<!-- cite -->
<div><cite>Title of creative work</cite></div>
<!-- time -->
<div>Time<time>9:00 am</time>
    to <time>7:00 pm</time>
</div>
```
### Listas 🔥
###### Tags de lista em HTML, incluindo <ul>, <ol> e <li>, são usadas para criar diferentes tipos de listas. Podem ser símbolos numéricos, alfabéticos, marcadores ou outros símbolos. Existem três tipos de lista em HTML:
```html
<em>…</em> //Usado para enfatizar algum texto ou mostrar algum grau de ênfase.
<strong>…</strong> //Indica que o conteúdo tem grande importância.
<sub>…</sub> //Escreve o texto como subscrito.
<sup>…</sup> //Escreve o texto como sobrescrito.
<abbr>… </abbr> //Representa uma abreviatura ou sigla.
<mark>…</mark> //Destaca textos importantes para fins de referência ou notação.
<cite>…</cite> //Descreve o título de um trabalho criativo.
<time>…</time> //Usado para representar um período específico de tempo.
<pre>…</pre> //Representa texto pré-formatado para ser apresentado exatamente como está escrito no arquivo HTML.
<code>…</code> //Usado para representar códigos-fonte
<address>..</address> //Fornece informações de contato de uma pessoa, pessoas ou organização.
```
```html
    <h5>Unordered List</h5>
    <!-- Unordered List -->
    <ul>
        <li>Data Structures & Algorithm</li>
        <li>Web Technology</li>
        <li>Aptitude & Logical Reasoning</li>
    </ul>
    <h5>Ordered List</h5>
    <!-- Ordered List -->
    <ol>
        <li>Array</li>
        <li>Linked List</li>
        <li>Stacks</li>
    </ol>
    <h5>Description List</h5>
    <!-- Description List -->
    <dl>
        <dt>Courses:</dt>
        <dd>100 </dd>
        <dt> Quizes:</dt>
        <dd> 500 </dd>
        <dt> Interview Experiences:</dt>
        <dd>1000 </dd>
    </dl>
```
