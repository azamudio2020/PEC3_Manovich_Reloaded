# PEC3: Visionando el futuro con las gafas de Manovich

Autor: Angello Paolo Zamudio Penko

En este ensayo analizaré dos ejemplos de hibridación moderna poniéndome las gafas de Manovich. Los casos que he seleccionado son: Selfiecity, un proyecto que investiga el estilo de los selfies en cinco ciudades del mundo, y Timeline, una serie interactiva de la plataforma Eko. 

## 1- Selfiecity 

Selfiecity es un proyecto de investigación a partir de selfies de Instagram correspondientes a cinco distintas ciudades: Bangkok, Berlín, Moscú, New York y Sao Paulo. Con un total de 640 fotos por ciudad y utilizando una combinación de métodos teóricos, artísticos y cuantitativos nos revela patrones interesantes y distintivos de los selfies según la ciudad a la que pertenecen, así por ejemplo podemos concluir: 

<img src="/src/selfiecity-data-02.jpg" width=600>

> ↑ Que en Moscú existe la diferencia más pronunciada entre selfies que se publican por género, siendo las mujeres las que más fotos suben. 

<img src="/src/selfiecity-data-01.jpg" width=600>

> ↑ Que en Berlín las mujeres en los selfies se muestran más sonrientes que en las demás ciudades analizadas.


El proceso para la recopilación de las fotos empieza con una selección random de 20 mil a 30 a mil fotos de Instagram por ciudad. Estas fotos pasan inicialmente por un proceso de intervención humana con la participación de trabajadores de Mechanical Turk de Amazon, plataforma para tareas simples que requieren cierto nivel de inteligencia que una máquina no puede hacer ("¿Qué es Amazon Mechanical Turk?", 2021), estos trabajadores tras descartar las fotos que no sean selfies individuales, pasan el lote a otros más calificados quienes estiman el género y edad de los fotografiados.
Finalmente los selfies se someten a un análisis facial automático, que proporciona estimaciones algorítmicas de la posición de los ojos, la nariz y la boca, el grado de las distintas expresiones emocionales, etc (http://selfiecity.net).

<img src="/src/selfiecity-process.jpg" width=600>

Si bien este proceso de recolección y análisis de datos es curioso por comprender de fases diferenciadas donde son necesarias inicialmente la inteligencia humana para los datos de género, edad y después la fase de inteligencia artificial para los datos faciales y expresivos. El caso de hibridación lo encontramos en la manera en que son representados estos datos resultantes, inicialmente nos presenta cada país como una transición de sus fotos alineadas de manera que coinciden en posición los rostros de selfies que la conforman, consiguen esta composición ajustada mediante su software de reconocimiento facial. 

Se trata de un medio híbrido que combina y reconfigura formatos de medios conocidos e interfaces de medios para ofrecer un nuevo tipo de representación híbrida (Manovich, 2014). En este caso está combinando la fotografía y los datos extraídos de ellas (ubicación, género, edad, posicionamiento facial) para ofrecernos una nueva experiencia donde no sólo nos muestra un transición de fotos en formato vídeo, nos está transmitiendo más: nos invita a encontrar el patrón que siguen los selfies, en este patrón se encuentra la información relevante. Por ello apenas da tiempo para visualizar cada rostro por separado, este nuevo medio no intenta representar gente fotografiada, sino que busca representar los datos derivados del conjunto de sus elementos.

<a href="http://www.selfiecity.net" target="_blank">
<img src="/src/selfiecity-saopaulo.gif" width=600>
</a>

> ↑ Representación de los selfies de Sao Paulo

El apartado “Selfieexploratory” incluye una herramienta la cual nos permite interactuar con este medio híbrido entre datos y fotografías. Podemos manipular los parámetros para filtrar y recibir las imágenes correspondientes a nuestra selección: por ejemplo podemos pedir las selfies de rostros sonrientes inclinados hacia arriba de mujeres de Nueva York. Esta función reafirma el caracter de este nuevo medio por incluir en las estructuras de datos de las selfies sus valores correspondientes para posteriormente tratarlas desde estos valores.  

<a href="http://selfiecity.net/selfiexploratory/t" target="_blank">
<img src="/src/selfiecity-ui.gif" width=600>
</a>

> ↑ Selfieexploratory


## 2- Timeline

Eko es una productora que ofrece un abanico variado de series interactivas e inventa una forma completamente nueva de entretenimiento. Es considerada la primera plataforma de vídeo interactivo del mundo. Sus programas permiten a los espectadores convertirse en participantes, brindándoles una capacidad sin precedentes para controlar e influir en las historias a medida que se desarrollan (http://eko.com).

La serie Timeline nos adentra en la historia de Dee, una estudiante de secundaria cuyo teléfono misteriosamente adquiere la capacidad de predecir el futuro otorgándole el poder de visualizar publicaciones que le informan de sucesos antes de que ocurran. 

<img src="/src/timeline-01.gif" width=600>

> ↑ Dee leyendo las futuras publicaciones de compañeros de secundaria.

Durante las secuencias nos muestra sus conflictos internos, como su indecisión para acercarse al chico que le atrae o que se siente intrigada por el rechazo que le demuestra una antigua amiga, dándonos de esta manera la libertad para intervenir ayudándola en su toma de decisiones. 

<img src="/src/timeline-02.gif" width=600>

> ↑ Interfaz de la interacción para elegir opciones.

Por lo tanto, consideraremos este nuevo medio como híbrido entre cine e interacción a través de las elecciones del usuario. Por tanto ofrece una experiencia más amplia que la de visualizar un vídeo convencional, nos atrapa por hacernos responsables del desarrollo de la historia, es interesante observar cómo con este nuevo medio surgido de la hibridez adoptamos más implicación como usuarios, al volvernos protagonistas es más probable que nos adentremos más a fondo en la trama y por tanto nos focalizamos con mayor nivel de recepción hacia sus contenidos.

Este medio híbrido se centra en ofrecernos un nueva manera de navegar e interaccionar con un formato de medios ya existentes. En este caso el tipo de medio en sí ni se modifica ni se combina con otros, sino que la hibridación se produce en la interfaz de usuario y las herramientas que facilita el proyecto, servicio o aplicación para trabajar con ese tipo de medios (Manovich, 2014).

Para controlar esta nueva especie de medio la interfaz para la reproducción del vídeo adquiere una nueva estética, en lugar de avanzar o retroceder por medidas de tiempo, lo hacemos entre los puntos de la historia en que se tomaron las decisiones. De esta manera si no nos gustan las consescuencias de alguna opción elegida, podemos retroceder para alternar de opción y cambiar así el curso de la historia. 

A diferencia de una obra cinematográfica, este nuevo tipo de medio híbrido no sigue un orden estático de representación, sino que nos presenta un contenido variable. Es la principal propiedad que gana al haberse hibridado con otro medio como es la interacción.
Debido a esta estructura común, ahora podemos emplear conjuntamente diversas técnicas que en el pasado eran exclusivas de un medio específico (Manovich, 2014). Gracias a manejar el vídeo como estructura de datos es posible su manipulación a través de algoritmos de programación. En este caso, los datos de este medio almacenan escenas cuya reproducción está condicionada por las opciones que elijamos. Por tanto nos brinda una experiencia de cine cuya trama no está definida, la compondremos nosotros según nuestro criterio. Lo que a su vez significa una experiencia con mayor implicación del usuario, abandonando su rol de espectador para covertirse en jugador.


<img src="/src/timeline-03.gif" width=600>

> ↑ Interacción para retroceder y explorar otras alternativas.



### Referencias

* **Eko. (2021)**. Recuperado de: https://eko.com/
* Manovich, L. (2013). **El software toma el mando** (Primera edición digital: diciembre 2013). Editorial UOC.
* **¿Qué es Amazon Mechanical Turk?**. (2021). Recuperado de AWS website: https://aws.amazon.com/es/premiumsupport/knowledge-center/mechanical-turk-use-cases/ 

* **Selfiecity. (2021)**. Recuperado de: http://selfiecity.net/

* **Timeline. (2021)**. Recuperado de: https://video.eko.com/timeline-/
