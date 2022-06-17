# Cosas para hacer.

<img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/5ea5339a-7a33-486a-8e47-2cdf3b21336f/dbwripy-a5f13ad2-1079-4328-a4fc-79650aba9913.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcLzVlYTUzMzlhLTdhMzMtNDg2YS04ZTQ3LTJjZGYzYjIxMzM2ZlwvZGJ3cmlweS1hNWYxM2FkMi0xMDc5LTQzMjgtYTRmYy03OTY1MGFiYTk5MTMuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.xbKwOlRfAdqaoNoKrpVMlfu0wwMxyaMG8r9GNso4kcI" alt="Peon Warcraft 1 Work Work Gif by jpmoses333 on DeviantArt" style="zoom:67%;" />

* ~~Hacer las demos de conos y profundizar un poco en esa parte de teoría de lenguajes. Podría agregar todo lo de lenguajes regulares y ya definir lo de poly context free. Cuando entienda esto mejor comentarselo a Iván. También podría hablarlo con Verónica ya que le quería hablar por el doctorado y esto es lo más computacional.~~
* Masticar mejor el algoritmo para obtener el automáta de pila a partir del grupo virtualmente libre. Iván me sugirió verlo a partir de la presentación dada a partir del grafo de Bass Serre. Estaría bueno entender como encontrar el libre en un caso en general. ¿Es el mismo algoritmo que el de la forma normal para Bass Serre?
  * ~~Ver si es necesario usar sistemas de reescritura para este algoritmo. Así tal como lo tengo lo uso para saber que podemos llevar toda palabra en los generadores a una de una pinta en particular. Creo que en el paper original de Schupp no usaban estas herramientas. Sino ya fue y lo uso porque es bastante útil y poco sofisticadas las definiciones iniciales.~~
* Ver lo que me sugirió Iván de su tesis. El (2.5) tiene una equivalencia de virt libre con Out($F_n$) sobre conjugación. Quizá pueda servirme para algo.
* Rehacerme todo lo de Bass Serre que nunca lo entendí. Consultarle bien a Iván cuando lo tenga más digerido. Consultarle la construcción topólogica del árbol de Bass Serre.
* ~~Ver si dado un grupo virtualmente libre puedo tomar el libre tal que sea normal. En qué casos podría hacer esto? Quizá ver en $SL_2(\Z)$ para empezar. Iván también me dijo que podría pensar lo de la intersección de Hannah (algo así...) para este caso aunque parece muy difícil.~~

---

### Grafos de Cayley.

* ~~Escribir bien la definición de grafo de Cayley para que las aristas no sean una cosa rara como está ahora.~~
* ~~Escribir bien la parte de subdivisión baricéntrica. Quizá Iván pueda decirme como la escribiría él.~~ 
* Reescribir la tercera condición de treewidth finito. Chequear el argumento para ver que es acíclico que está escrito bastante bastante rari.
* Agregar que los vecinos de un bolsón para cada bolsón nos termina dando otra desc en un árbol.
* ~~Terminar de pasar la demo de gramática independiente de contexto implica treewidth finito.~~ 
* ~~Dar bien la definición de grafo de Cayley. Que quede claro que tomo un grafo con generadores como monoide.~~
  * ~~Dar un ejemplo. Quizá pueda poner el de $F_2$ que es lindo :)~~
* ~~Escribir bien el ejemplo del treewidth de un árbol.~~
  * ~~Puedo hacerlo a partir de un vértice como pensaba yo~~ 
  * ~~O haciendo la subdivisión baricentrica como decía Iván :)~~
* ~~Explicar rapidamente que los grafos de Cayley son espacios métricos geodésicos. Después uso ambas cosas así que tengo que mencionarlo.~~
* Quizá agregar el ejemplo de $SL_2(\Z)$ o el de un grafo cíclico. Eso depende cuando esté rehaciendo la siguiente sección. 

### Gramáticas.

* ~~Reescribir todo como sugirió Iván.~~
* ~~Escribir un ejemplo de gramática así se entiende tal como me sugirió el otro día o mejor, un ejemplo de derivación.~~
* ~~Explicar las notaciones usuales para las gramáticas.~~
* ~~Poner las definiciones de lenguajes que vamos a usar y explayarlas mejor.~~ 
  * ~~Lenguajes regulares y un ejemplo.~~
  * ~~Lenguajes independientes de contexto y un ejemplo (ya está hecho pero en otra sección).~~

## Lenguajes regulares.

* ~~Definición.~~
* ~~Ejemplo.~~
* ~~Automáta finito no determinístico.~~
  * Reescribirlo igual y que quede super claro porque no lo está.
* Mismo ejemplo pero aceptado por un automáta finito no determinístico.
* Teorema: Regulares aceptados por AFNDs.

## Lenguajes independientes de contexto.

* ~~Definición.~~
* ~~Ejemplo.~~
* ~~Forma normal de Chomsky.~~
* Comentar utilidad de tenerla en esta forma.
* ~~Automatas de pila.~~
* Si bien está me gustaría reordenar todo porque está escrito con muchos párrafos y mejor sería tirar el ejemplo de una, creo yo.
* ~~Ejemplos de automatas de pila.~~
* Teorema: equivalencia automatas de pila con gramáticas ind de contexto.
* Propiedades de estos lenguajes:

  * Cerrados por morfismos.

  * Cerrados por inversos de morfismos.

  * Intersección con lenguajes regulares.

## Cuasisometrías.

* ~~Agregar la otra definición equivalente de cuasisometría. Yo estoy usando que es un embedding y que es bilipschitz cuando a veces la definición original es con una inversa.~~
* ~~Agregar la definición particular para grafos definida sobre vértices para facilitar argumentos.~~
* ~~Agregar que los grafos de Cayley para distintos generadores son cuasisométricos.~~
* ~~Agregar lo del subgrupo de índice finito es cuasisométrico con el grupo.~~
* Terminar de pensar la implicación que quería hacer para ver que cuasisométrico con un árbol es equivalente a tener treewidth finito. Puedo pensarlo en el contexto de grafos de Cayley en vez de grafos en general. Charlarlo con Iván.
  * ~~Pensaba ver que todo ciclo geodésico está acotado en tamaño. Pensé que quizá esto valía porque tenemos las reglas de la gramática que nos permiten acortar los ciclos.~~ 
    * ~~La idea de hacer esto es para que los bolsones nos queden conexos siguiendo el paper de Diestel.~~ 


---

## Latex.

* Solucionar lo de las referencias para que ande el backref.

* Agregar un \halmos a los enviroments de teoremas y demás?

  