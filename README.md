# Cartão Virtual
> Projeto para trabalhar com HTML e CSS de forma inicial. O objetivo é criar um cartão virtual com informações de contato. Referencia: https://linktr.ee/

## Criando HTML
Todo arquivo html deve ter o nome com .html, exemplo: 
index.html


### HTML - Hyper Text Markup Language
```html
<destacado>TEXTO</destacado>
<comando></comando>
<comando> --> <tag>
<p></p> --> Parágrafo
<br> --> quebrar linha
<h1></h1> ..... <h6></h6> --> Títulos
<img src="foto.jpg"> --> Imagem
<a href="https://github.com/marcelodanelon">GitHub</a> --> Link
```
- **Table** - Indentação para frente
- **Shift + Tab** - Indentação para traz
- **Alt + Shift + F** - Indentação automatica

## Criando o CSS
Cascading Style Sheet (Folha de estilo em cascata). O CSS é modo pelo qual iremos formatar (estilizar) o nosso conteúdo(HTML).

Existem 3 formas de estilizar o conteúdo:
1. inline - formatação diretamente no elemento HTML.
2. na página - formatação é feita dentro de uma sessão `<style>`
3. **arquivo externo** - criamos um arquivo especifico para a formatação (.css).

A escolha do elemento HTML que será formatado se dá atraves de Seletores. Seletores são criados a partir de 3 possibilidades: tag, classe(.) e identificação (ID) (#).

Por exemplo: imagine que queremos modificar o fundo do site para a cor laranja e a cor da letra para amarelo, podemos montar um seletor da seguinte forma:
```css
body{
    background-color: orange;
    color: yellow;
}
```
Explicação:
- body --> seletor (onde será formatado)
- background-color --> propriedade (o que será formatado)
- orange --> valor (como será formatado)

Design
- Tipografia
- Cores
- Grid
- Espaçamento
- Gestalt
- Contraste
(https://www.youtube.com/c/Chiefofdesign)
(https://www.instagram.com/onebitcode/)
(https://www.instagram.com/rocketseat_oficial/)
