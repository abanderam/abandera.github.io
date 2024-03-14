---
title: "Informática Aplicada a la Biología"
collection: teaching
type: "Grado en Biología"
permalink: /teaching/IABio
date: 2023-01-01
venue: "Universidad de Sevilla"
location: "Sevilla, España"
---

Asignatura del primer cuatrimestre del primer curso del Grado en Biología.

Parte 1: Introducción a las hojas de cálculo y bases de datos
======

<b>Sesión 1: Clase del 15/9/2023.</b>

<em>Contenidos:</em> Introducción a la asignatura. Introducción a la enseñanza virtual. Introducción a Open Office Calc (Estructura, Ayuda, Series de datos, Fórmulas Simples, Referencias Relativas, mixtas y Absolutas).

<em>Problema propuesto:</em> Creación de un documento con las asignaturas del grado en Biología. Debe aparecer los créditos de cada asignatura, la calificación y una columna en la que se multiplique el número de créditos por la nota obtenida. Debe hacerse la suma del total de créditos y otra suma con los resultados de la multiplicación anterior. Finalmente, debe hallarse la nota media dividiendo el último resultado por el total de créditos.

<b>Sesión 2: Clase del 22/9/2023.</b>

<em>Contenidos:</em> Fórmulas lógicas, Condicionales, Gráficas.

<em>Problema propuesto:</em> En el documento de la sesión anterior, añadir una columna en el que nos diga automáticamente la calificación en palabras (Suspenso, Aprobado, Notable, Sobresaliente) con uso de condicionales. Crear una gráfica de columnas con las calificaciones de las asignaturas en la que aparezca en el eje horizontal los nombres de las asignaturas, además deben representarse las etiquetas de datos. Fuera de la tabla, calcularemos el número de asignaturas suspensas, aprobadas, con notable y con sobresaliente, calcularemos los porcentajes respectivos con respecto al total de asignaturas y representaremos los resultados mediante una gráfica circular, deben añadirse también las etiquetas de datos.

<b>Sesión 3: Clase del 29/9/2023.</b>

<em>Contenidos:</em> Repaso de Gráficas, Listas de datos y Filtros, Formateo Condicional.

<em>Problema propuesto:</em> Ejercicio Final de OpenOffice Calc.

<b>Consejos para el examen:</b>

* El examen de Calc tiene dos partes, una de datos y otra de filtros, contesta cada pregunta en la pestaña correspondiente.
* Cuando hacemos formato porcentaje NO hay que multiplicar por 100.
* En el ejercicio condicional, tenemos que utilizar un comando Si menos del numero de condiciones. Haz el diagrama para visualizarlo mejor.
* Para aplicar una fórmula con una condición, el comando suele ser la acción seguida de .SI, por ejemplo, CONTAR.SI(), SUMA.SI().
* En la parte de filtros, primero hacer el SUBTOTALES y después aplicar los filtros.

Parte 2: Introducción a la programación
======

<b>Sesión 1: Clase del 6/10/2023.</b>

<em>Contenidos:</em> Introducción a Matlab en la ventana de comandos: Calculadora, Funciones elementales, Variables y Funciones comunes. Matlab en la venta del editor: m-ficheros (scripts), input y display, la función anónima.

<em>Problema propuesto:</em> En un script de Matlab, crear un archivo que pida dos números por pantalla. Después evalúe la función f(x) = (x<sup>5/3</sup>-x<sup>2</sup>)/(x<sup>log(x<sup>2</sup>)/x</sup>+cos(x)), en los puntos anteriores. Por útlimo, debes sumar los resultados anteriores y mostrar el valor de la suma por pantalla.

<b>Sesión 2: Clase del 9/10/2023.</b>

<em>Contenido:</em> Vectores, vectores equiespaciados (comando a:h:b y linspace(a,b,h)), componentes de vectores, operaciones con vectores. Introducción a la programación, condicionales (if, if-else, if-elseif-else).

<em>Problema propuesto:</em> En un m-fichero:

* Pide un número por pantalla, n.
* Si n es par, crea un vector de n componentes entre 0 y 1, y muestra la segunda componente. En caso contrario, crea un vector que empiece en 1 y termine en 100 con paso n, muestra la última componente.
* Calcula la suma del vector correspondiente y muestra el resultado por pantalla.
* Evalúa ﻿f(x) = sin(x tan(x<sup>2</sup>)), en el valor anterior.
* Muestra el resultado por pantalla.

<b>Sesión 3: Clase del 20/10/2023.</b>

<em>Contenido:</em> Condicionales y bucles (FOR y WHILE).

<em>Problema propuesto:</em> En un m-fichero: 

* Pedir un número que sea múltiplo de 3 y compruébalo.
  * Si es par, entonces calcula la siguiente suma: log(4)/2 +  log(9)/4 + log(16)/6 + ··· +  log(100)/18

  * Si es impar, entonces calcula el siguiente vector recursivo hasta k=10, donde a(1) = 7: a<sub>k+1</sub> = a<sub>k</sub> e<sup>a<sub>k</sub> - 8</sup>

* Muestra el resultado correspondiente por pantalla.

<b>Sesión 4: Clase del 27/10/2023. </b>

<em>Contenido:</em> Bucle FOR para definir vectores recursivos. Cadena de caracteres, gráficas de funciones, gráficas de vectores.

<em>Problema Propuesto:</em> Ver ejercicio final primera parte de matlab.

Parte 3: Modelos poblacionales
======

<b>Sesión 2. Clase del 3/11/2023.</b>

<em>Contenido:</em> Modelos discretos y paquete de cálculo simbólico.

<em>Problema propuesto:</em> Modelo logístico completo:

* Pedir un número R por pantalla. Debe comprobarse que cumple 1<R<4.
* El modelo discreto sigue la función x<sub>k+1</sub> = R x<sub>k</sub> (1 - x<sub>k</sub>)﻿, donde la k indica el número de días. 
* Calcular la evolución con condición inicial 0.3 durante 50 días y representarlo.
* Estudiar la estabilidad de los puntos de equilibrio para R=2 y R=3.5.
* EXTRA: Calcular los puntos de equilibrio y estudiar su estabilidad en función de R.

<b>Sesión 3. Clase del 24/11/2023.</b>

<em>Contenidos:</em> Modelos continuos unidimensionales. Cálculo de puntos de equilibrio y estudio de la estabilidad.

<em>Problema propuesto:</em> Ver secuencia de actividades: <a href="https://github.com/abanderam/abanderam.github.io/blob/master/files/paper1.pdf">SecuenciaActividades1D.pptx</a>.

<b>Sesión 4. Clase del 1/12/2023.</b>

<em>Contenidos:</em> Modelos Lotka-Volterra: Competición, simbiosis y presa-depredador. Cálculo de puntos de equilibrio y estudio de la estabilidad.

<em>Problema propuesto:</em> Ver secuencia de actividades: SecuenciaActividades2D.pptx.
