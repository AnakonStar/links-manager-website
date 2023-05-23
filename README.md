# Projeto de site gerenciador de links

## Todos os links em um canto só

Notas para o código: 
```css
Pai:

.links ul li {
    width: 100%;
    list-style-type: none;
    position: relative;
}

Filho:

.links ul li img {
    height: 40px;
    left: 10px;
    position: absolute;
```
Caso eu queira adicionar algum item e que ele fique fixado, absoluto em algum canto da sua div e não da tela, você deve adicionar ```position: relative``` como propriedade no CSS do pai daquele item.

Para fixar: 

```css
:root {
    --font: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    --fullscreen: 100%;
    --halfscreen: 50%;
    --blue: rgb(96, 96, 214);
    --bluegradient1: rgb(81, 137, 211);
    --bluegradient2: rgb(127, 163, 209);
}
```
É possível adicionar variáveis dentro do ambiente de CSS (pesquisar sobre possibilidades no HTML), o que te possibilita mudar um valor de algum item, como background-color ou font-family, diretamente na variável, assim alterando para todos que tiverem aquele valor como algo padrão.
