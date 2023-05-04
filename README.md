# F#: your first functional programming language

## Index 

En español, próximamente en otros idiomas...

- [¿Qué es F#?  ](blob/main/es/Intro.ipynb)
- [Fundamentos  ](blob/main/es/Fundamentals_new.ipynb)
- [¿Qué es una función?  ](blob/main/es/Functions_new.ipynb)
<!-- - [Ejercicios sobre funciones   ](blob/main/es/Exercises.ipynb) -->
- [Más sobre funciones   ](blob/main/es/MasSobreFunciones.ipynb)    
- [Pensar con tipos   ](blob/main/es/IntroToTypes_es.ipynb)        
- [Discriminated Unions  ](blob/main/es/DiscriminatedUnions_es.ipynb) 
- [Records  ](blob/main/es/Records_es.ipynb)
<!-- - [Ejercicios de tipos   ](blob/main/es/Exercises.ipynb) -->
- [Manejando por las ramas   ](blob/main/es/ControlFlow.ipynb)      
<!-- - [Ejercicios  ](blob/main/es/Exercises.ipynb)  -->
- [Tuplas   ](blob/main/es/Tuples.ipynb)
- [Colecciones   ](blob/main/es/OnCollections.ipynb) 
<!-- - [Ejercicios  ](blob/main/es/Exercises.ipynb) -->
- [Más sobre Colecciones   ](blob/main/es/MoreOnCollections.ipynb)
- [Diccionarios   ](blob/main/es/Maps.ipynb)
- [Excepciones   ](blob/main/es/Exceptions.ipynb)
<!-- - [Ejercicios  ](blob/main/es/Exercises.ipynb) -->
- [El tipo Result   ](blob/main/es/Results.ipynb)
- [Unidades de medida   ](blob/main/es/Units.ipynb) 
<!-- - [Un kata clásico  ](blob/main/es/Exercises.ipynb) -->
- [Secuencias    ](blob/main/es/YetAnotherTakeOnCollections.ipynb)
- [Leyendo y escribiendo archivos   ](blob/main/es/IO.ipynb)
<!-- - [Ejercicios  ](blob/main/es/Exercises.ipynb)  -->
- [Resources   ](blob/main/es/_resources.ipynb) 

## Introduction

These guides are oriented to those programmers interested in learning some concepts on functional programming, 
from a practical perspective. F\# is an excelent _first_ functional programming language: it is functional (of course), it has a clean and readable syntax (not a lot of fancy symbols and stuff), it is flexible (in case you need to grasp some other paradigm in the middle of your code) and it is concise enough to express your ideas with clarity. 

Learning a new language _and_ a new programming paradigm is a wonderful adventure. You do not need any special preparation, although I assume that the reader has some background in at least one popular language (let us say C, Python, Java or JavaScript, for example). 

This guides are entirely written as Jupyter Notebooks. Yes, it is possible to run F\# in a Jupyter notebook interactive environment, which is fantastic for learning.

[This repository](https://github.com/fcolavecchia/fp-course/tree/binder) contains the Jupyter Notebooks edition of the course. The content is in english in the `en` folder, mientras que el contenido en español está 
en el directorio `es`. Para los lectores en español, la traducción está hecha en forma automática, con 
la edición correspondiente en los casos en que el traductor no trabaja adecuadamente. 

> Sin embargo, hasta tanto no se consolide el contenido, dejaré la traducción automática como sale del traductor. Sepan disculpar mis lectores hispano hablantes este detalle por el momento.

The course can also be accesed as a read only content [in my blog](https://flavio.colavecchia.net/blog/).

### Working with the notebooks

#### Using binder

I managed to develop the connection to [Binder](mybinder.org), so you can open the course directly there, just 
click this button

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fcolavecchia/fp-course.git/binder?labpath=en%2F)

You will land in a page that shows you all the magic that is behind running binder. After a while, you will land into this page:

<img src="img/mybinder-config.png" alt="Binder landing page" width="400"/>

Click on the folder icon on the left, and you will see all the available notebooks. Open the one of your
choice, check that the `Kernel` on the right is properly selected. 

It automatically detects .NET C\#, 

<img src="img/i-do-not-want-csharp.png" alt="I do not want C#" width="400"/>

but that is not the language you are looking for:

<img src="img/i-want-fsharp.png" alt="This is it" width="400"/>

and you are good to go.

> I have found instructions on how to build .NET in Binder [here](https://www.macivortech.com/blog/how-to-run-dotnet-on-binder/) and copied config files from [here](https://github.com/oddrationale/AdventOfCode2021FSharp/tree/main/.binder), updated to .NET 7.

### Installing polyglot notebooks

To install the .NET interactive with Jupyer Notebooks, follow the instructions [here](https://github.com/dotnet/interactive/blob/main/docs/NotebookswithJupyter.md). 




### Resources

- [The Jupyter notebook edu book](https://jupyter4edu.github.io/jupyter-edu-book/).


Coming soon:
- What `if` say `for` goodbye?
- To be or not to be, that is the option 

