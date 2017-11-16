# Generador de Textos con RNN y Pytorch

En este proyecto trataremos de crear textos nuevos a partir de algunos documentos ya escritos, es decir,
textos ya elaborados en donde la Red Neuronal Recurrente (RNN), tratara de imitar la forma en como
escribe cierto autor, en otras palabras predicira cual es el caracter mas probable en base a su entrenamiento
con los textos.

## ¿Qué es una RNN?

Básicamente es una red neuronal que se puede utilizar cuando tus datos se tratan como una secuencia, 
donde el orden de los datos es importante y esta secuencia de datos puede ser de una longitud arbitraria.


Tenemos una serie temporal de números, donde el objetivo principal es predecir el siguiente valor 
conociendo los valores previos. La entrada al RNN en cada paso de tiempo es el valor actual, así como 
un vector de estado que representa lo que la red ha "visto" en pasos de tiempo anteriores.
Este vector de estado es la memoria codificada del RNN, inicialmente configurada a cero.

![](img/RNN_img.png)

## PyTorch 
Utilizaremos este framework de aprendizaje profundo.

Para la instalacion ve a este su [sitio web](http://pytorch.org/) para instalarlo.
Cabe mencionar que solo esta disponible en Linux y OS.

## Resultados Generador de Municipios

Algunos nombres de municipios que me ha generado son:

* Teezaltepec
* Tecotlan
* Matepec
* Tepaltepec
* Chimentelis
* Santiago Sotutla
* San Juan Tuxtitlan
* Reyes de Reforma
* La Magdalena Cardenas
* San Juan Cuautitan
---

## Resultados con el libro de la Biblia
Al usar toda la biblia nos ha generado parrafos como:
> Jehova a tu padre. 
2 Esta para que habia enfermos de los hijos de Catras, y la grande son salido en ellos de los hijos de Ahora, y la tierra que habia hijo de los hijos de Cada habia trabanas partes, y te aqui el entranieron que se habia habia le sino que habia con mano de los hijos de la profeta, y con tambien la tierra de tomaron con muerte sola para que hablado con todo lo sepultado anos de los que acerca y a la tierra de aqui la casa de Zabaras que estaba para solio en todos los que el perdones de la nacion con todos los entrescion de las angalos; y de los encenderan no trabajo trabocaste a ellos al trair de los habia pan de la saldad de ello; y su que te habia de camino de sus reyes que el hombre a la tierra en rey habia hecho a tu padre. 
El dijo a sus hermanos, y tambien no habia hijo de Asa el partigo, de la tambien en Aseras, y se ha de la salid a los hijos de los que habia habia padre. 
Los que habian en la bada por mi mensan sus siervos traberas de Jehova a Mananias, y Adais


> Cristos, Jehova que dia trazo su ciudad con sus levitas. 24 Pero su malde a Raus que hablamiento a fin de los hijos de verdades por por todos los padres, y se peste las casas in suberta manania que mandamientos hoy a vuestra frera de Dios. 53 Porque los serviteis de los ejidos y Jacobaron, y habia te aqui, y te hubiera quebran en el camino es habeis antresenza, con los que destruir sea que su sereis son sus mil ejido. 4 Penor hasta se ha de la grancinte hablaron que en sus senor por la mano al pueblo; por todo lo siervo: Pero no habitadero a el me se contra te alto; y no ma el camino de saparia. 
2 Y agua Faraon habitando ayos hasta decir toda la sierdaron se ereto por cago, las cuales creedad a todo mi santo santa de esta y de tanternado todad Abalec. 
5 Cuando todo el respondio: Asin de la fe mi pecado para me siguieron, y para que enviemente en el arban todo el le habia sido contra veceses tramente, de las arrombres quemaran todas las tribuo de los de los padres y con el padre. 

> Dios volvio por lleguidor votos te has compasion a ellos, del efeladro y que envian para fueron; y no con las sangres de la piedra a Cristo. 
La efel, consutalo nado testigo, y de la tierra lo que habitaraamente boce a los hijos y hijo mil medio que ha que se lanta con estas tambien el called de ella por sus sitomos. 8 De los ha se dijo: Jehova: De ellos mientes bebera en cacho han estovo de la tierra de Sion, para quedara Juda, nados habia habia hermano, sino que el anigar en vuestro Dios, al tiempo en el sabeis, y a para que te tambien a ti dara envio que la tierra temor, y al tendra, y cuales te entre los ganozoras y su padre. 3 Y al ribaria y ser vendra que este bien, sino que el Dios, al malor a Ahora de sus hijos de los reyes, y de abrio y los libanzas, y las lados, en todas las entres de verdotes, ni fuego traereis sera todas las libando al ganado. 5 No te diciendo la tierra a el Senor, el que estan traidonia de ellos a mi hiervo, y con el tomado a la castad que para el camino dijo: 