# Plantilla_Tesis_UASD

Plantilla para tesis de licenciatura en biología de la UASD

## Como utilizar la plantilla

Para las personas que recién son introducidas al mundo de LaTeX una de las opciones más fáciles sería utilizar un editor de LaTex en línea como son [Overleaf](https://www.overleaf.com/) y [ShareLaTeX](https://www.sharelatex.com/).
Luego de crear una cuenta gratuita en una de estas páginas pueden incluir todos los archivos de esta plantilla e introducir su texto en el archivo debido.
El programa se encargará automáticamente de compilar el documento.

Para utilizar LaTeX localmente en su computadora puede instalar una de las distribuciones de LaTeX dependiendo su sistema operativo.
[MiKTeX](https://miktex.org/) (Windows), [TeXLive](https://www.tug.org/texlive/) (Linux,Windows), [MacTex](https://www.tug.org/mactex/) (Mac).

Los archivos TeX son archivos de texto sin formato de manera que pueden editarse en el editor de texto de su preferencia.
Aunque existen editores especializados para facilitar la escritura en LaTeX.
Algunos de ellos son [TeXstudio](http://www.texstudio.org/) y [Texmaker](http://www.xm1math.net/texmaker/)

## Bugs conocidos (Resueltos)

* Al parecer el la versión 2.10.1 del paquete titlesec tiene un bug.
Esta es la versión incluida en Texlive 2016.
Por lo que se incluye entre los archivos las versión 2.10.2 de [titlesec](https://www.ctan.org/pkg/titlesec).
* La versión 3.3 y 3.4 de [biblatex](https://www.ctan.org/pkg/biblatex) presenta un bug que no permite la separación adecuada de las citas de tipo autor (año).
Esto es corregido a partir de la versión 3.5.
En la plantilla incluyo un código que arregla este problema para la versión 3.4.
Esta línea puede ser comentada si tienen accesso a la versión 3.5+ de [biblatex](https://www.ctan.org/pkg/biblatex).
NOTA: No he podido arreglarlo para la versión 3.3. Si usan [Overleaf](https://www.overleaf.com/) no tienen que preocuparse con este bug ya que tiene la versión necesaria de biblatex.
## Paquetes utilizados

1. [titlesec](https://www.ctan.org/pkg/titlesec)
2. [geometry](https://www.ctan.org/pkg/geometry)
3. [color](https://www.ctan.org/pkg/color)
4. [inputenc](https://www.ctan.org/pkg/inputenc)
5. [fontenc](https://www.ctan.org/pkg/fontenc)
6. [babel](https://www.ctan.org/pkg/babel)
7. [mathptmx](https://www.ctan.org/pkg/mathptmx)
8. [microtype](https://www.ctan.org/pkg/microtype)
9. [csquotes](https://www.ctan.org/pkg/csquotes)
10. [enumitem](https://www.ctan.org/pkg/enumitem)
11. [booktabs](https://www.ctan.org/pkg/booktabs)
12. [array](https://www.ctan.org/pkg/array)
13. [graphicx](https://www.ctan.org/pkg/graphicx)
14. [biblatex](https://www.ctan.org/pkg/biblatex)
15. [setspace](https://www.ctan.org/pkg/setspace)
16. [lipsum](https://www.ctan.org/pkg/lipsum)
17. [pdflscape](https://www.ctan.org/pkg/pdflscape)
18. [hyperref](https://www.ctan.org/pkg/hyperref)

## Guías, Tutoriales y Manuales de LaTeX

### Español

1. [Introducción a LaTeX](http://pcmap.unizar.es/~pilar/latex.pdf)
2. [Curso de LaTeX](http://matematicas.uclm.es/earanda/wp-content/uploads/downloads/2013/10/latex.pdf)
3. [Tutorial de LaTeX](http://www2.dis.ulpgc.es/~lalvarez/teaching/pi/latex/TutorialLatex.pdf)
4. [Manual de LaTeX](https://es.wikibooks.org/wiki/Manual_de_LaTeX)
5. [Edición de textos científicos: LaTeX 2014](http://tecdigital.tec.ac.cr/revistamatematica/Libros/LATEX/LaTeX_2014.pdf)

### Inglés

1. [ShareLaTeX Documentation](https://www.sharelatex.com/learn)
2. [LaTeX Wiki Book](https://en.wikibooks.org/wiki/LaTeX)

## Reconocimientos

El archivo .gitignore de este repositorio fué tomado del repositorio en github [gitignore](https://github.com/github/gitignore).

El reglamento de tesis que se añade en este repositorio es de la autoría de la Prof. Ruth Bastardo de la Universidad Autónoma de Santo Domingo (UASD).
Se incluye aquí para referencia del formato necesario que tiene que lograr esta plantilla para cumplir con los requisitos de la tesis de Biología de la UASD.

## Limitaciones del reglamento de tesis

1. El reglamento de tesis solo incluye como debe citarse cuando hay un autor o más de dos autores, pero no especifíca en el caso de dos autores como deben separarse estos, ya sea con la letra "y" o el símbolo "&". En este caso estoy dejando la separación con  "y" ya aparece de esta manera en la bibliografía para separar el último autor.

2. De igual manera el reglamento de tesis solo se enfoca en la cita de artículos y libros pero no da indicaciones para páginas web, conferencias, tesis, reportes, mapas y demás. Si tienen sugerencias o hay algún consenso no oficial de como citar otras fuentes en la tesis de biología de la UASD pueden crear [Issues](https://github.com/fpichardom/Plantilla_Tesis_UASD/issues) indicando el formato sugerido, de manera que pueda ser incorporado a la plantilla.
3. No existe un estilo definitivo de la portada de la tesis, pero si de la información que debe incluir.
## Falta por hacer

2. Configurar el estilo de la portada (estilo preliminar con los datos obligatorios).
4. ...Cualquier sugerencia de cosas que falten por dar formato o cualquier inquietud o problema es bienvenida.

Para Reportar problemas o inquietudes o hacer sugerencias pueden usar la pestaña [Issues](https://github.com/fpichardom/Plantilla_Tesis_UASD/issues).
