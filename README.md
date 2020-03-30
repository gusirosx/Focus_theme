# Tema Focus para apresentações minimalistas

Esse tema é uma versão adaptada do tema [Focus](https://github.com/elauksap/focus-beamertheme) que visa disponibilizar um tema de apresentações para o LaTeX Beamer com design limpo e minimalista, para minimizar as distrações e colocar o foco diretamente no conteúdo.

Demontração
----

Uma demonstração completa está disponível. busque por `presentation.tex` and `presentation.pdf`.

![](https://github.com/elauksap/focustheme/blob/master/demo-screenshots/demo-titlepage.jpg)
![](https://github.com/elauksap/focustheme/blob/master/demo-screenshots/demo-subsectionpage.jpg)
![](https://github.com/elauksap/focustheme/blob/master/demo-screenshots/demo-typeset.jpg)
![](https://github.com/elauksap/focustheme/blob/master/demo-screenshots/demo-focus.jpg)
![](https://github.com/elauksap/focustheme/blob/master/demo-screenshots/demo-references.jpg)
![](https://github.com/elauksap/focustheme/blob/master/demo-screenshots/demo-appendix.jpg)

Download
========
Faça o download da versão mais recente através [deste link](https://github.com/gusirosx/Focus_theme/releases).

Instruções
============

Após o download, copie os arquivos chamados beamer*themefocus.sty para a mesma pasta que o arquivo de origem do LaTeX.
Em seguida, inclua o tema escrevendo:
```latex
\documentclass{beamer}

\usetheme{focus}
```
no preâmbulo do seu documento.

Personalizar cores
----------------
A presente versão do tema focus é baseada em três cores, denominadas `main`,`mainb` e `background`, que podem ser personalizadas após a inclusão do tema. Onde por padrão `main` refere-se a cor de destaque do tema,`mainb` refere-se a cor das fonte e `background` refere-se a de fundo do tema.

Por exemplo, as seguintes configurações:
```latex
\usetheme{focus}

\definecolor{mainb}{RGB}{64, 64, 64} % Black Font
\definecolor{main}{RGB}{64, 64, 64}  % Dark
\definecolor{main}{RGB}{78, 0, 142}  % Pur
\definecolor{main}{RGB}{175, 51, 51} % Red
\definecolor{main}{RGB}{16, 6, 159}  % blue
\definecolor{background}{RGB}{240, 247, 255}
```
produzem as seguintes possibilidades de cores.

![](https://github.com/elauksap/focustheme/blob/master/demo-screenshots/demo-titlepage-color.jpg)

Personalizar o Rodapé
----------------------
A numeração do rodapé pode ser personalizada através da opção de tema _numbering_. O valor padrão é:

```latex
\usetheme[numbering=progressbar]{focus}
```
que mostra uma barra de progresso de comprimento crescente no footline.

Como alternativa, uma barra de rodapé completa com a numeração de quadros pode ser mostrada com:

```latex
\usetheme[numbering=fullbar]{focus}
```

O rodapé também pode ser desativado digitando:
```latex
\usetheme[numbering=none]{focus}
```

Personalizar fontes
---------------
O foco está usando o [Fira fonts](https://bboxtype.com/typefaces/FiraSans/) por padrão.

Isso pode ser alterado usando a opção _nofirafonts_:
```latex
\usetheme[nofirafonts]{focus}
```
Licença
=======
seu software é lançado sob a licença [GNU GPL v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).

Contribuidores
============
Esse tema foi criado e projetado inicialmente por [Pasquale Africa](https://github.com/elauksap).
A presente versão, foi adaptada para o português por [Gustavo Rodrigues](https://github.com/gusirosx).
