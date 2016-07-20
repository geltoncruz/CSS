# Flexbox
caixas flexíveis, ou flexbox, é um novo modo de layout no CSS3.  

Uso de flexbox garante que os elementos se comportam de maneira previsível
quando o layout da página deve acomodar diferentes tamanhos de tela e
diferentes dispositivos de exibição.  

Para muitas aplicações, o modelo de caixa flexível fornece uma melhoria sobre
o modelo de blocos em que ele não usa carros alegóricos, nem margens de colapso
do recipiente flexível com as margens de seu conteúdo.  

## Básico:

* flex container
* flex items  
[img 001]

## Suporte de navegadores

* Chrome 29+
* Firefox 28+
* Internet Explorer 11+
* Opera 17+
* Safari 6.1+ (prefixed with -webkit-)
* Android 4.4+
iOS 7.1+ (prefixed with -webkit-)

## Uso
Para usar o flexbox informamos a propriedade do HTML
<pre>
  <code>
  .flex-container {
display: -webkit-flex; /* Safari */
display: flex;
}
  </code>
</pre>

## Propriedades Flexbox container
### flex-direction

propriedade que define a direção dos itens dos containers.  
Temos basicamente duas direções:   
* Row (Linha)
* column (Coluna)

<pre>
  <code>
  .flex-container {
  -webkit-flex-direction: row; /* Safari */
  flex-direction:         row;
  }
  </code>
</pre>

![row](../slides/imagens/flexbox/003-view.jpg)

* Usando Row-reverse
<pre>
  <code>
  .flex-container {
-webkit-flex-direction: row-reverse; /* Safari */
flex-direction:         row-reverse;
}
  </code>
</pre>

![row](../slides/imagens/flexbox/004-view.jpg)

*Usando column

<pre>
  <code>
  .flex-container {
-webkit-flex-direction: column; /* Safari */
flex-direction:         column;
}
  </code>
</pre>

![row](../slides/imagens/flexbox/004-view.jpg)
