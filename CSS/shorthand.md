# shorthand

*junção de propriedades
*resumido
*legível

```css
{
    /*background properties*/
    background-color: #000;
    background-image: url(image/bg.gif);
    background-repeat: no-repeat;
    background-position: left top;

    /* background shorthand*/
    background: #000 url(images/bg.gif) no-repeat left top;

    /*font properties*/
    font-style: italic;
    font-weight: bold;
    font-size: .em;
    line-height: 1.2;
    font-family: Arial, sans-serif;

    /*font shorthand*/ 
    font: italic bold .em/1.2 Arial, sans-serif

}

#detalhes

-não irá considerar propriedades anteriores
-valores não especificados irão assumir o valor padrão
-geralmente, a ordem descrita não importa, mas se houver muitas propriedades com valores semelhantes, poderemos encontrar problemas
