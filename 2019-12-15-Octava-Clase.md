---
layout: "post"
title:  "Octava Clase"
date:   2019-12-15 20:34:47 -0500
categories: jekyll update
---

# Ámbito general del ciclo de vida del SW

* Desde un punto de vista general puede considerarse que el ciclo de vida de un software tiene tres etapas claramente diferenciadas:

* Planificacio´n: idearemos un planeamiento detallado que gui´e la gestio´n del proyecto, temporal y econo´micamente.
* Implementacio´n: acordaremos el conjunto de actividades que componen la realizacio´n del producto.
* Puesta en produccio´n: nuestro proyecto entra en la etapa de definicio´n, alli´ donde se lo presentamos al cliente o usuario final, sabiendo que funciona correctamente y responde a los requerimientos solicitados en su momento. Esta etapa es muy importante no so´lo por representar la aceptacio´n o no del proyecto por parte del cliente o usuario final sino por las mu´ltiples dificultades que suele presentar en la pra´ctica, alarga´ndose excesivamente y provocando costos no previstos.
* En cada una de las etapas de un modelo de ciclo de vida, se pueden establecer una serie de objetivos, tareas y actividades que lo caracterizan.
* Expresio´n de necesidades: esta etapa tiene como objetivo el armado de un documento en el cual se reflejan los requerimientos y funcionalidades que ofrecera´ al usuario el sistema a implementar (que´, y no co´mo, se va a implementar).
* Especificaciones: formalizamos los requerimientos; el documento obtenido en la etapa anterior se tomara´ como punto de partida para esta etapa.
* Ana´lisis: determinamos los elementos que intervienen en el sistema a desarrollar, su estructura, relaciones, evolucio´n temporal, funcionalidades, tendremos una descripcio´n clara de que´ producto vamos a construir, que´ funcionalidades aportara´ y que´ comportamiento tendra´.
* Disen~o: ya sabemos que´ hacer, ahora tenemos que determinar co´mo debemos hacerlo (¿co´mo debe ser construido el sistema en cuestion?; definimos en detalle entidades y relaciones de las bases de datos, seleccionamos el lenguaje que vamos a utilizar, el Sistema Gestor de Bases de Datos, etc.).
* Implementacio´n: empezamos a codificar algoritmos y estructuras de datos, de- finidos en las etapas anteriores, en el correspondiente lenguaje de programacio´n o para un determinado sistema gestor de bases de datos. En muchos proyectos se pasa directamente a esta etapa; son proyectos muy arriesgados que adoptan un modelo de ciclo de vida de code & fix (codificar y corregir) donde se eliminan las etapas de especificaciones, ana´lisis y disen~o con la consiguiente pe´rdida de control sobre la gestio´n del proyecto.
* Debugging: el objetivo de esta etapa es garantizar que nuestro programa no contiene errores de disen~o o codificacio´n. En esta etapa no deseamos saber si nuestro programa realiza lo que solicito´ el usuario, esa tarea le corresponde a la etapa de implementacio´n. En e´sta deseamos encontrar la mayor cantidad de errores. Todas los programas contienen errores: encontrarlos es cuestio´n de tiempo. Lo ideal es encontrar la mayori´a, si no todos, en esta etapa. Tambie´n se pueden agregar testeos de performance.
* Validacio´n: esta etapa tiene como objetivo la verificacio´n de que el sistema desarrollado cumple con los requerimientos expresados inicialmente por el cliente y que han dado lugar al presente proyecto. En muchos proyectos las etapas de validacio´n y debugging se realizan en paralelo por la estrecha relacio´n que llevan. Sin embargo, tenemos que evitar la confusio´n: podemos realizarlos en paralelo, pero no como una u´nica etapa.
* Evolucio´n: en la mayori´a de los proyectos se considera esta etapa como Mantenimiento y evolucio´n, y se le asigna, no so´lo el agregado de nuevas funcionalidades (evolucio´n); sino la correccio´n de errores que surgen (mantenimiento). En la pra´ctica esta denominacio´n no es del todo erro´nea, ya que es posible que aun luego de una etapa de debugging y validacio´n exhaustiva, se filtren errores.

