Trivia (Laboratoria)
=============
- Este proyecto se realizó siguiendo estas consideraciones [El Proyecto](https://laboratoria1.gitbook.io/preadmision/a-trabajar/proyecto) , lo desarrollamos dentro de la semana de Pre - admisión de [Laboratoria - Sede Lima](https://www.laboratoria.la/) y lo mejoré posteriormente

- **Periodo :** 26 - 29 Abril, 2021
> Proyecto para postulación de Laboratoria, se usó HTML, CSS y JS

## Índice

* [1. Preámbulo](#1-preámbulo)
* [2. Resumen del proyecto](#2-resumen-del-proyecto)
* [3. Objetivos de aprendizaje](#3-objetivos-de-aprendizaje)
* [4. Criterios que cumple el proyecto](#4-criterios-que-cumple-el-proyecto)
* [5. Consideraciones técnicas](#5-consideraciones-técnicas)

***

## 1. Preámbulo

La trivia es un tipo de juego, generalmente en el marco de un concurso, en el
que se plantea una serie de preguntas cuyas respuestas deben ser escogidas entre
diferentes opciones.

En la actualidad, con lo extendido del uso de smartphones, sus aplicaciones, y
el acceso a Internet, existen muchas posibilidades de participar de una trivia
online. Con una rápida búsqueda en internet, te podrás dar cuenta que existen
trivias de muchas temáticas (ciencia, series, televisión, etc.), Hay varias que,
incluso, ofrecen dinero como recompensa.

![TRIVIA](https://phandroid.s3.amazonaws.com/wp-content/uploads/2018/01/hq-trivia-android-screenshot.jpg)

## 2. Resumen del proyecto

Esta es una aplicación web que le permita a un usuario responder distintas preguntas
escogiendo sus respuestas de una lista de alternativas.

## 3. Objetivos de aprendizaje

Los objetivos en general son los siguientes, de los cuáles utilicé los que están con ✓:

### HTML y CSS

* [ ] Uso de HTML semántico.
* [x] Uso de selectores de CSS.
* [x] Construye tu aplicación respetando el diseño realizado (maquetación).

### JavaScript

* [x] Uso de condicionales (if-else | switch | operador ternario)
* [x] Uso de funciones (parámetros | argumentos | valor de retorno)
* [x] Declaración correcta de variables (const & let)

### Estructura del código y guía de estilo

* [x] Utilizo identificadores descriptivos (Nomenclatura | Semántica).


## 4. Criterios que cumple el proyecto

* [x] Mostrar una pantalla de bienvenida, pida tu nombre para comenzar a jugar.
* [x] Mostrar un mensaje de Hola [tu nombre] y dos botones para comenzar a jugar.
   - Jugar con preguntas de tipo A (Por ejemplo: sobre comida)
   - Jugar con preguntas de tipo B (Por ejemplo: sobre cervezas)
* [x] Lanzar la pregunta 1 con alternativas, el usuario responde, luego se muestra
   la pregunta 2 y luego la 3.
* [x] Mostrar una pantalla de resultados (respuestas correctas) y dos botones de
   volver a jugar:
   - Jugar con preguntas de tipo A (Por ejemplo: sobre comida)
   - Jugar con preguntas de tipo B (Por ejemplo: sobre cervezas)
* [x] Agregar una cuenta regresiva con un tiempo límite para responder cada pregunta.
* [x] Subir tu código a GitHub (commit/push) y desplegar la interfaz usando GitHub pages.

### Definición del producto

#### ¿Cómo el producto soluciona los problemas/necesidades de dichos usuarios?

Esta aplicación les permite a los usuarios relajarse un momento, ya que es muy intuitiva para usarlo, no demorará en reponder las preguntas y saber su puntaje final.

### Diseño de la Interfaz de Usuario

#### Prototipo de baja fidelidad

En estos mockups, se planteo el esquema del juego:

![](https://raw.githubusercontent.com/sgcm14/LIM015-trivia/master/img/doc/plantilla1.jpg)
> Plantilla de **Bienvenida**

![](https://raw.githubusercontent.com/sgcm14/LIM015-trivia/master/img/doc/plantilla2.jpg)
> Plantilla de **Categoria**

![](https://raw.githubusercontent.com/sgcm14/LIM015-trivia/master/img/doc/plantilla3.jpg)
> Plantilla de **Preguntas**

![](https://raw.githubusercontent.com/sgcm14/LIM015-trivia/master/img/doc/plantilla4.jpg)
> Plantilla de **Resultados**

### Implementación de la Interfaz de Usuario (HTML/CSS/JS)

A continuación muestro como quedó el Juego de Trivia :

En la pantalla de **BIENVENIDA**, se solicita al usuario su nombre para empezar a jugar.

![](https://raw.githubusercontent.com/sgcm14/LIM015-trivia/master/img/doc/1.jpg)
> Pantalla de **INICIO**

Una vez escriba su nombre debe darle click en **ENTRAR**

![](https://raw.githubusercontent.com/sgcm14/LIM015-trivia/master/img/doc/2.jpg)
> Pantalla de **INICIO**

En la pantalla **CATEGORIA**, se muestra el nombre del usuario a su vez, se solicita al usuario que seleccione una de las categorías. Una vez selecciona una de ellas, lo redireccionara a la sección de preguntas, de acuerdo a la categoría seleccionada.

![](https://raw.githubusercontent.com/sgcm14/LIM015-trivia/master/img/doc/3.jpg)
> Pantalla de **CATEGORIA**

En la pantalla **PREGUNTAS** , si el usuario no selecciona nada, se agota su tiempo de 10 segundos.
![](https://raw.githubusercontent.com/sgcm14/LIM015-trivia/master/img/doc/4.jpg)
> Pantalla de **PREGUNTAS** (Aparece un timer que contabiliza un tiempo para pasar a la siguiente pregunta)

En la pantalla **PREGUNTAS** , al agotarse el tiempo pasa a la siguiente pregunta automaticamente.

![](https://raw.githubusercontent.com/sgcm14/LIM015-trivia/master/img/doc/5.jpg)
> Pantalla de **PREGUNTAS** (Aparece un timer que contabiliza un tiempo para pasar a la siguiente pregunta)

En la pantalla **PREGUNTAS** , el usuario selecciona una opción de respuesta, si esta es correcta el juego le avisará y a su vez se desactivaran todas las respuestas, debe darle click a **NEXT**.

![](https://raw.githubusercontent.com/sgcm14/LIM015-trivia/master/img/doc/6.jpg)
> Pantalla de **PREGUNTAS** (Aparece un timer que contabiliza un tiempo para pasar a la siguiente pregunta)

En la pantalla **PREGUNTAS** , el usuario selecciona una opción de respuesta, si esta es incorrecta el juego le avisará y a su vez se desactivaran todas las respuestas, debe darle click a **NEXT**.

![](https://raw.githubusercontent.com/sgcm14/LIM015-trivia/master/img/doc/7.jpg)
> Pantalla de **PREGUNTAS** (Aparece un timer que contabiliza un tiempo para pasar a la siguiente pregunta)

En la pantalla **RESULTADOS** se muestra las respuestas, e indica cuáles fueron correctas y cuáles fueron incorrectas. Asimismo, el usuario tiene la opción de volver a jugar, o finalizar el juego.

![](https://raw.githubusercontent.com/sgcm14/LIM015-trivia/master/img/doc/8.jpg)
> Pantalla de **RESULTADOS** (Al cerrar sesión, se inicia el juego nuevamente)

## 5. Consideraciones técnicas

La lógica del proyecto esta implementada completamente en JS, HTML y CSS
En este proyecto NO se uso librerías o frameworks,
solo [vanilla JavaScript](https://medium.com/laboratoria-how-to/vanillajs-vs-jquery-31e623bbd46e).

### `index.html`

Acá va la página que se muestra al usuario, también nos sirve para indicar
qué script se usa y une todo lo que hemos hecho.

### `style.css`

Este archivo contiene las reglas de estilo. 

### `main.js`

Acá está todo el código que tiene que ver con la interacción del DOM
(seleccionar, actualizar y manipular elementos del DOM y eventos), entre otras
funciones que son necesarias para actualizar el resultado en la pantalla (UI).


**Realizado por :** 

Sammy Gigi Cantoral Montejo (sgcm14)

<img src ="https://raw.githubusercontent.com/sgcm14/sgcm14/main/sammy.jpg" width="200">
