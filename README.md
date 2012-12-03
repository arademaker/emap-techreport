
# LaTeX style for EMAp Techreport

LaTeX style file for EMAp techreport and an example.

## How to use it?

No diretório do seu artigo, coloque os arquivos ```emap.sty``` e
```emap-logo.pdf```. Modifique seu LaTeX como indicado acima e
pronto!

- It is not necessary but I recommend in the first line the following
  declaration:

```
\documentclass[a4paper,twocolumn]{article}
```

- Include the package ```emap.sty``` in the preambule of your LaTeX
  file.

```
\usepackage{emap}
```

- Right after the ```\begin{document}```, include the following
  commands:

```
\headerauthor{Val\'eria de Paiva,Alexandre Rademaker,Gerard de Melo}
\headertitle{OpenWordNet-PT: an open Brazilian Wordnet for reasoning}
\headeryear{2012}
\cover
```

## How to publish it in the FGV Digital Library? 

The EMAP Techreports is available at:

http://bibliotecadigital.fgv.br/dspace/handle/10438/7823

Instructions:

http://www.youtube.com/watch?v=l9U-U_-jqRM

## TODO

- Fazer o logo em tikz/pgf

- Talvez um rodapé padrão também ajudasse a divulgar o nome da
  EMAp... Dado que muitas pessoas acabam fazendo o download,
  imprimindo e certamente a capa será a primeira página a ser jogada
  fora.

- Algumas outras melhorias e otimizações no código LaTeX são possíveis
  também.


## Author

Alexandre Rademaker
http://arademaker.github.com
