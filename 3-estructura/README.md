# Plano de estructura

## Introducción

En este plano se va a tratar el diseño de interacción, bajando de manera práctica y concreta la forma en que el usuario podrá moverse dentro del sitio web, las cosas que podrá realizar y las que no. 
A su vez, se va abordar la arquitectura de la información, es decir el enfoque del contenido, su jerarquía y los principios para su organización.
También se va a elaborar un Card Sorting como método abierto de consulta a los usuarios para encontrar la manera más apropiada de ponerle nombre a las pestañas y la organización del contenido dentro de cada una.
Finalmente, se va a volcar en un diagrama el diseño del sitio web y la interacción de todas las partes como paso previo al armado de los wireframes que se van a encontrar en el plano siguiente -esqueleto-.


## Diseño de le interacción

### Elementos del diseño de la interacción 
Desde el diseño de la interacción se busca mejorar el funcionamiento del sitio web Aupa, de este modo es importante tener en cuenta que no todos los parámetros son necesarios para el sitio, pero si deben estudiarse todos para saber cual o cuales son los más pertinentes o adecuados para el éxito de la plataforma. De este modo sabemos que los elementos del diseño interactivo son: la comunicación persona maquina, acción/reacción, flujo de trabajo, estado y los errores o mal funcionamiento. 

Las principales funciones interactivas que nos encontramos en “Aupa” son “Foro”, “Contáctenos” y “Buscar”, los cuales se ejecutarán de la siguiente manera: 

**Foro:** dentro de la pestaña foro se tendrá en cuenta la comunicación de persona maquina, acción/reacción y flujo de trabajo, todo ello mediante los siguientes pasos: 

1. La barra de menú permite acceder a la pestaña de foro. 
2. Estando allí, cada usuario podrá seleccionar la región donde quieren instalarse, es decir, San Sebastián, Bilbao, Vitoria o Irún. 
3. Las opciones serán “añadir un tema nuevo” o elegir uno ya existen con un título X ejemplo: “tramites de documentos para marruecos”.
4. Cuando el usuario esté dentro del foro elegido, tendrá la opción de leer los comentarios de los demás usuarios y así mismo responder a cada uno de ellos. Ejemplo: El personaje 1 ha dicho que para los marroquíes que llevan aproximadamente 2 años se le harán la tramitación de documentos el próximo 15 de noviembre. Por ende el personaje número 2 responde que quiere saber a dónde debe dirigirse. Pero a la hora de pulsar enter para comentar su texto la plataforma no le deja comentar. Entonces le aparecerá una nota que dice “Su mensaje no se ha enviado, vuelva a intentarlo”
5. Después de que el personaje 2 pueda responder el comentario del personaje 1 los demás personajes del foro podrán comentar el comentario del personaje 2. Así se podrá seguir la misma secuencia respondiendo los comentarios de cualquier personaje. 

**Contacto:** Desde Contacto se pretende cumplir con los siguientes elementos del diseño de la  interacción, persona-máquina y acción-reacción. 

El usuario se podrá comunicar por medio del número telefónico de las entidades o el whatsapp de las mismas. Además, cuenta con la facilidad de enviar emails a las entidades o en este caso a la plataforma de Aupa, desde el apartado contacto se le pedirá al usuario un email y en un espacio apartado podrá escribir las preguntas o inquietudes que tenga, de este modo se le enviará la respuesta al correo que asignó. 

1. Desde la barra de menú, se permite el acceso a “Contactos”
2. Una vez dentro, el usuario podrá ponerse en contacto con la página a través de la mensajería de la página.
3. Se solicitará rellenar los siguientes campos:
- Mail de contacto.
- Nombre completo (si lo desea)
- Asunto:  Motivo de contacto.
- Texto: En donde la persona podrá detallar el motivo de contacto.

4. Respecto a la acción/reacción, si el usuario busca salir sin haber antes enviado el mensaje, aparecerá una  alerta que dice “esta seguro que desea abandonar esta página”. Permitiendo al usuario decidir si seguir o no en la página actual.
5. Una vez el mensaje se envía correctamente, el sistema le dará confirmación al usuario por medio del email y otra en la pantalla de la plataforma donde dirá “Su mensaje ha sido enviado, confirme la verificación en su correo”. 

**Buscador:**
En la barra de búsqueda el usuario cuenta con la oportunidad de escribir lo que quiere consultar o la información que requiere. Ejemplo: 
1. Desplegar la barra de busqueda
2. Escribir el enunciado como “trámites para migrantes colombianos” o palabras como “migración”.
3. Clic en enter o en el icono de la lupa
4. Los resultados que le aparecerán en la pantalla a los usuarios serán conforme a las palabras que pongan en el enunciado, en este caso hablamos de resultados relacionados con las palabras “trámites” “migrantes” y “colombianos”. 

Sin embargo si nos anteponemos a posibles fallos los pasos serían los siguientes: 

1. Desplegar la barra de busqueda
2. Escribir el enunciado como “Anuncios para Italianos” 
3. Clic en enter o en el icono de la lupa
4. En caso de no haber resultados la pagina tendra un enunciado que dice “No se ha encontrado ningún resultado para “anuncios para Italianos” por favor cambie las palabras de búsqueda  para el enunciado o intentelo mas tarde”

## Arquitectura de la información
En esta parte, se va adentrar en la arquitectura de la información del la página web Aupa y de la organización de su contenido. 

### Estructura del contenido

Desde el primer momento, el contenido en Aupa, debe persuadir al usuario acerca de la forma en que debe moverse por el sitio web para sacar el máximo provecho del mismo.

Debido a que Aupa es un sitio con una audiencia particular, -inmigrantes forzados-, para cumplir su misión y visión es importante que los usuarios alcancen a través de la oferta de contenidos el marco y el camino a seguir para cubrir sus necesidades, abordando cada tema de forma integral, para ello, el contenido tiene que presentarse de modo que permita una navegación intuitiva, eficiente y eficaz.

El plano de estrategia, evidenció que ser un medio ó puente entre los inmigrantes forzados y la comunidad del País Vasco representa un gran desafío ya que requiere una atención politemática, por ello y casi de forma natural se encontró que para estructurar el contenido, la mejor solución es aplicar una estructura “de Arriba a Abajo”, en la que se espera atender correctamente la necesidad de información de los usuarios y a posteriori del contenido que se pueda incorporar o complementar con el vigente. Bajo esta lógica, el sitio web va a tener unas categorías principales y de éstas, se desprenderán unas subcategorías de las cuales se podrá continuar ramificando en una relación de nodos (páginas) como padre-hijo.

Entonces, en el sitio web, se va a utilizar esquemas exactos y ambiguos.
En efecto, vamos a utilizar un esquema geográfico, por ejemplo, a la hora de desagregar las entidades de manera que el usuario pueda considerar la información pertinente más cercana a donde se encuentra. 
Y por otra parte, esquemas ambiguos, organizados por tema. Esto es apropiado para el sitio web ya que la información que se genera para las pestañas, más precisamente, la de “Trámites” y dentro de la misma, según las secciones de modo tal que el usuario pueda sacar el máximo provecho de la información para ayudarle a cumplir sus objetivos. 

Finalmente, incluiremos esquemas ambiguos organizados por metáfora, la razón es importante destacar, las personas navegan por diferentes sitios buscando información relevante o que simplemente capten su atención e interés, todo eso ocurre en los primeros 10-20 segundos de navegación en el sitio web, entonces, una manera de captar su atención es a través del diseño sugerente de algunas funciones, por ejemplo, en lugar de poner la palabra ‘Buscador’, se va a utilizar una “Lupa”, en lugar de escribir la palabra inicio se va a poner el Logo del sitio al nivel de la barra de menú para volver a empezar la navegación. También se utilizarán los logos de las redes sociales en que el sitio web está presente en lugar de definir el acceso escribiendo la palabra de cada una.

### Enfoques de arquitectura

De los distintos enfoques, el que va en sintonía con la estructura de contenido es elde tipo jerárquica. 
Este enfoque muestra la apariencia del árbol, mientras los nodos principales (que en verdad son las mismas páginas) sirven de base para los nodos menores en una relación “padre/hijo”, toma importancia definir y comprender bien los niveles superiores y que éstos guarden una estrecha relación con las necesidades que el usuario intentará satisfacer.

Se va a utilizar como forma de jerarquía las denominadas "anchas y superficiales", que es cuando los usuarios pueden acceder a cada contenido pasando por una categoría. Ejemplo, cada categoría tiene un contenido, si hay 5 contenidos, habrá 5 categorías.

![Ejemplo para Aupa](https://github.com/DeustoPWEB2018/proyectoweb-migraciones/blob/5345076350097ecea54e1abb462c109a77a82b31/3-estructura/estructura_ejemplo_aupa.png)
*Fuente: elaboración propia*

En este ejemplo, podemos ver que en la pestaña “Documentos”, hay cinco temas distintos y que se necesita solo un clic para ir dentro de cada uno. El contenido va a estar directamente enlazado a cada tema. En caso de que más adelante, de uno de estos se desprendan dos o más subtemas, se va a desplegar un columna a la derecha con la lista de subtemas y así sucesivamente.

### Card Sorting 

Para implementar la técnica del card sorting hemos decidido de hacer un Open Card Sorting (clasificación abierta de tarjeta) porque nuestro sitio web es nuevo y tenemos como objetivo de descubrir qué tipo de clasificación de categorías sería más correcto utilizar. En efecto, con este método los participantes obtienen tarjetas mostrando el contenido del sitio y deben clasificar las tarjetas en grupos que ellos elijan para luego describir cada grupo.

Por eso, hemos elegido distintos contenidos relevantes para hacer la prueba: 

* Datos personales sobre el ayuntamiento de San Sebastián 
* Datos personales sobre la delegación de ACNUR en Pais Vasco 
* Obtener un permiso de residencia en País Vasco
* Datos personales sobre el ayuntamiento de Bilbao 
* Empadronarse en Vitoria Gasteiz 
* Conseguir la residencia permanente 
* Busco un piso en Bilbao - Maria 
* Conocéis hospitales en la ciudad de San Sebastián? - Enrique 
* Datos personales sobre nuestra empresa
* Se ofrece empleo de tecnico de mantenimiento en Vitoria Gasteiz
* Obtener la nacionalidad española 
* Hacer la solicitud de Tarjeta Individual Sanitaria 
* Encontrar un banco de alimentos
* Contactar el servicio de información de viviendas municipales 
* Estudiar en un centro de educación en San Sebastián 

El contenido elegido corresponde a contenidos de nivel 2 en nuestra página web que están dentro el contenido de nivel 1. Queríamos hacer asi porque permite evaluar contenidos de mismo nivel y evitar los errores o resultados equivocados al final. Hemos también numerado cada carta para que el ejercicio sea más sencillo. 

Hicimos la prueba con un grupo de 5 personas que han reflexionado juntos sobre las categorías y han clasificado las tarjetas en ellas: 

![Tabla grupo](grupo1.png)

Las cinco personas han creado las categorías siguientes: 
 
* Enlaces de interés
  * General 
  * San Sebastián 
  * Bilbao 
  * Vitoria 
* Quiénes somos? 
* Foro

Hicimos también una segunda prueba individual con una persona que no estaba en el grupo anterior. Así, ha trabajado sola:

![Tabla Marina](marina1.png)

Marina ha creado las categorías siguientes: 

* Tramités
  * Tarjeta Individual Sanitaria 
  * Nacionalidad
  * Empadronamiento
  * Permiso de residencia...
* Quiénes somos? 
* Foro 
  * San Sebastián 
  * Bilbao
  * Vitoria 

Ademas, podemos comparar estos resultados a las categorías que habíamos elegido antes de hacer la prueba:

![Tabla recap](resumen.png)

Aparecen similitudes y diferencias entre nosotros, el grupo y Marina que van a ayudarnos sobre la repartición de los contenidos en categorías. Despues observación, ya podemos decir que la categoría “Quiénes somos?” aparece más clara para los usuarios que “Contactos”. Además, vamos a guardar la categoría “Foro” con las subcategorías. 

Para concluir, las categorías que definitivamente elegimos son las siguientes:

* Tramités
  * Tarjeta Individual Sanitaria 
  * Nacionalidad
  * Empadronamiento
  * Permiso de residencia...
* Quiénes somos? 
* Foro 
  * San Sebastián 
  * Bilbao
  * Vitoria 

## Diagramación 
Mediante la diagramación se quiere mostrar el diseño del sitio web y para ello la estructura que se usará será la conocida como “el árbol”, además, se visualizarán las etiquetas pensadas para cada una de las pestañas por el grupo de trabajo. 

![Diagrama uno](uno.png)
![Diagrama dos](dos.png)
