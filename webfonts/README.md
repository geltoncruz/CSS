# WEB FONTS

![WebFonts](../slides/imagens/webfonts/001.jpg)

* Permite usar fonts não instaladas;
* Download Automático se necessário.


## Formatos de fontes permitidos:

* TrueType Fonts (TTF)
* OpenType Fonts (OTF)
* The Web Open Font Format (WOFF)
* The Web Open Font Format (WOFF 2.0)
* SVG Fonts/Shapes
* Embedded OpenType Fonts (EOT)


## USO:
<pre>
  <code>
  @font-face {
   font-family: helveticaneue;
   src: url('HelveticaNeueLTStd-UltLt.otf');
}
  </code>
</pre>

<pre>
  <code>
  p {
  font:36px helveticaneue, Arial, Tahoma, Sans-serif;
}
  </code>
</pre>

![Helvetica Neue](../slides/imagens/webfonts/004.jpg)

### Download Automático se necessário:

* Download automático se necessário:
![Helvetica Neue](../slides/imagens/webfonts/005.jpg)

  <pre>
    <code>
    @font-face {
     font-family: helveticaneue;
     src: local(HelveticaNeueLTStd-UltLt.otf), url(HelveticaNeueLTStd-UltLt.otf);
  }
    </code>
  </pre>

*  Palavra reservada __local__ prioriza a busca no computador do cliente.


## Diretório de fonts na web
* http://www.cssfontstack.com/Web-Fonts
* https://www.google.com/fonts

![Google Fonts Api](../slides/imagens/webfonts/007.png)
![CSS FONT STACKS](../slides/imagens/webfonts/009.jpg)
![CSS FONT STACKS](../slides/imagens/webfonts/010.png)
<pre>
<code>

body {
  font-family: 'Tangerine', serif;
  font-size: 48px;
  text-shadow: 4px 4px 4px #aaa;
}
</code>
</pre>

![Efeitos em texto google Api Fonts
](../slides/imagens/webfonts/011.png)
![Efeitos em texto google Api Fonts
](../slides/imagens/webfonts/011-2.png)
