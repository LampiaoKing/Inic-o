/* # Shorthand

* junção de propiedades
* Resumido
* Legível */



  /* background properties*/
  
h1{
  background-color: #000 ;
  background-image: url(imagens/bg.gf);
  background-repeat: no-repeat;
  background-position: left top;

  /* background shorthand*/
  background: #000 url(imagens/bg.gif) no-repeat left top;

  /* font shorthand */
  font-style: italic;
  font-weight: bold;
  font-size: 8em;
  line-height: 1.2;
  font-family: Arial, Helvetica, sans-serif;

  /* font shorthand*/
  font: italic bold .8em/1.2 arial, sans-serif;
}

## Detalhes
* Não irá considerar propiedades anteriores
* Valores não especificados irão assumir o valor padrão
* Geralmente, a ordem descrita não importa, mas, se houver muitas propiedades com valores semelhantes, poderemos encontar problemas.

##Pesquisar: Propiedades que aceitam shorthand