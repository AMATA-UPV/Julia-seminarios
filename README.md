# Seminarios de iniciación al lenguaje de programación Julia

Seminarios de introducción al lenguaje [Julia](https://julialang.org/) para el grupo de investigación AMATA de la UPV.

## Primeros pasos

En primer lugar instalaremos el compilador Julia en nuestro ordenador. Dependiendo de nuestro sistema operativo tendremos diferentes formas de hacerlo.
- Instalación de Julia:
  - Descargar la [última versión](https://julialang.org/downloads/) para nuestro sistema operativo.
  - (opcional) Si se quiere tener acceso a Julia desde el terminal de Windows seguir los pasos hay que modificar la variable de entorno _PATH_ siguiendo los pasos que se indican [aquí](https://julialang.org/downloads/platform/#windows).
  - (opcional) Para los usuarios de Windows es interesante trabajar con el nuevo [Windows Terminal](https://www.microsoft.com/es-es/p/windows-terminal/9n0dx20hk701?rtc=1&activetab=pivot:overviewtab), una versión mejorada del terminal que viene por defecto en Windows.
  
Para el desarrollo de software tenemos varias opciones.

- La opción más básica es utilizar nuestro editor de textos favorito (vim, notepad++, emacs) para escribir el código, y ejecutarlo en un terminal o bien en la consola de Julia REPL. 
- Instalación de un entorno integrado de desarrollo o IDE (opcional):
  - [Juno](https://junolab.org/). Opcionalmente, se puede descargar [Juliapro](https://juliacomputing.com/products/juliapro/) que incluye Julia con el entorno de desarrollo Juno (requiere creación de una cuenta).
  - [VS Code](https://code.visualstudio.com/).
- Instalación de un entorno interactivo (opcional):
  - Instalación de [IJulia](https://github.com/JuliaLang/IJulia.jl) notebook. Permite utilizar el entorno gráfico Jupyter para python (IPython) con el lenguaje Julia.
  - Instalación de [Pluto](https://github.com/fonsp/Pluto.jl/blob/master/README.md) notebook. Parecido a IJulia pero con la característica de que es reactivo, cualquier cambio en el notebook se refleja inmediatamene en todo el documento (espectacular !!). Hay un tutorial de [instalación de Julia + Pluto](https://computationalthinking.mit.edu/Fall20/installation/) del curso del MIT [Introduction to Computational Thinking](https://computationalthinking.mit.edu/Fall20/)

Finalmente, tenemos la posibilidad de editar y ejecutar nuestro código utilizando servicios en la nube, sin necesidad de instalación local. Puede ser una buena opción para una primera toma de contacto con Julia. Similar a la solución Matlab Online para MATLAB.
- Ejecución de Julia en servicios en la nube:
  - [Binder](https://mybinder.org/) Permite ejecutar una colección de notebooks IJulia alojados en un repositorio interactivamente en nuestro navegador (por ejemplo alojados en [Github](https://github.com) del que hablaremos en otra ocasión). [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AMATA-UPV/Julia-seminarios.git/main)
  - [Colab](https://colab.research.google.com). Un notebook interactivo de Google. Inicialmente pensado para ejectuar Jupyter notebook en la nube, es posible utilizarlo para ejecutar Julia siguiendo estas [instrucciones](https://github.com/Dsantra92/Julia-on-Colab).
  - [Replit](https://replit.com/). Es un entorno IDE en la nube. Permite el desarrollo de software y ejecución en diversos lenguajes.

## Recursos
Los siguientes enlaces recogen y resumen mucha información que nos puede er útil:
- [Fast track to Julia](https://juliadocs.github.io/Julia-Cheat-Sheet/)
- [Cheatsheet](https://cheatsheets.quantecon.org/) Matlab vs Julia
- [Tutorial](https://syl1.gitbook.io/julia-language-a-concise-tutorial/)
- [Canal YouTube](https://www.youtube.com/channel/UC9IuUwwE2xdjQUT_LMLONoA/playlists)

## Seminarios
El curso se organiza en diferentes sesiones prácticas.
- Seminario 1. Instalación y sintáxis básica de Julia.

## Bonus
- Documentación de [notebooks con LaTeX](./latex/latex.ipynb).
