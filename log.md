# 100 Days Of Code - Log

<!--
### Día x: x de Mes, 20xx

**Progreso del día**:

**Pensamientos**:  

**Enlaces al trabajo hecho**: [localhost](http://localhost)
-->

### Día 1: 7 de Enero, 2018

**Progreso del día**: Retomé un curso de Reactjs que había abandonado hace meses. Subí el proyecto a Heroku. Empecé a buscar la manera de no usar [Express](https://github.com/expressjs/express/tree/master/) para la servir los archivos estáticos en heroku

**Pensamientos**: Se me ocurrió la brillante idea de actualizar una de las dependencias, [neutrino](https://github.com/mozilla-neutrino/neutrino-dev). En general no fue una mala idea pero sí me causó dolores de cabeza mientras buscaba la causa de los nuevos errores en las pruebas unitarias.

Resulta que el error estaba en las pruebas.

**Enlaces al trabajo hecho**: [Expensify-demo](https://github.com/VonHeikemen/expensify-demo/tree/e19196e23d83fd447a01adb54994baa227c66417) (último commit del día)

### Día 2: Enero 8, 2018

**Progreso del día**: Usé [Prettier](https://github.com/prettier/prettier) para darle formato al código de Expensify.

**Pensamientos**: Descubrí que mantener las líneas de código por debajo de 80 caracteres es útil. Ahora puedo tener la terminal de Visual Studio code como panel lateral y ver todo él código.

Después de leer mucho este [artículo](https://hackernoon.com/deploying-any-react-app-to-heroku-1ee6db9b97d3) me dí cuenta que sólo tenía que agregar el buildpack de create-react-app para que la aplicación funcionara sin express en Heroku

Fue un buen día

**Enlaces al trabajo hecho**: [Expensify-demo](https://github.com/VonHeikemen/expensify-demo/tree/0fb4495e521fd6ce0b768cc19219b8cc677df33f) (último commit del día)

### Día 3: 9 de Enero, 2018

**Progreso del día**: Eliminé Express como dependencia del proyecto y agregué funciones para formatear las fechas y cantidades dentro de la aplicación. Terminé una sección más del curso. Agregué un nuevo componente al proyecto.

**Pensamientos**: Ahora sé con certeza que el buildpack de create-react-app sí sirvió.

**Enlaces al trabajo hecho**: [Expensify-demo](https://github.com/VonHeikemen/expensify-demo/tree/d43d368a012db6e745714212e3a1a41e94078f8a) (último commit del día)

### Día 4: 10 de Enero, 2018

**Progreso del día**: Aprendí las funciones básicas de Firebase para almacenar datos. Refactoricé (olalá señor francés) el componente totalizador

**Pensamientos**: Firebase tiene una API muy diferente a otros soluciones NoSQL que he usado, parece simple, ya veré si sigue así.

**Enlaces al trabajo hecho**: [Expensify-demo](https://github.com/VonHeikemen/expensify-demo/tree/ffa206d8ef6606e5126d1c911be7944089a2c73a) (último commit del día)

### Día 5: 11 de Enero, 2018

**Progreso del día**: Cloné este repositorio. Escribí mi progreso hasta ahora. Empecé con un experimento para una aplicación con angular (versión 1) y neutrino.

**Pensamientos**:  Me asignaron un proyecto en el trabajo que está hecho con angular 1, pero quiero saber si puedo "modernizar" su estructura usando neutrino (que en realidad usa webpack para hacer el trabajo pesado). Hasta ahora ha sido algo incómodo pero definitivamente es posible.

**Enlaces al trabajo hecho**: [Log 100-days-of-code](https://github.com/VonHeikemen/100-days-of-code)

### Día 6: 12 de Enero, 2018

**Progreso del día**: Terminé la sección del curso que trata de los métodos básicos de Firebase.

**Pensamientos**: Firebase parece una solución genial para trabajar con aplicaciones que necesiten capacidad para responder en tiempo ante cambios en unos datos, pero trabajar con arreglos es incómodo.

**Enlaces al trabajo hecho**: N/A

### Día 7: 13 de Enero, 2018

**Progreso del día**: Comencé la integración de Firebase con Redux en el proyecto del curso.

**Pensamientos**: Hizo falta la instalación de otra librería para integrar completamente Redux y Firebase, pero muy natural la integración. Guardar persistir los cambios en la base de datos se convirtió sólo en un paso extra, sin tener que mover la lógica que ya estaba establecida.

**Enlaces al trabajo hecho**: N/A

### Día 8: 14 de Enero, 2018

**Progreso del día**: Heroku me dio problemas con las variables de entorno. Resulta que el buildpack que configuré para la aplicación sólo puede utilizar las variables de entorno con el prefijo "REACT_APP_". Al final la integración con Firebase resultó exisitosa.

**Pensamientos**:  Ahora, en la sección del curso hubo varios videos en los que se mezclaban pruebas unitarias y pruebas de integración, eso no me gustó. Debería haber una clara separación. El instructor intentaba evaluar con las pruebas cosas que estaban más allá de su control, como resultado cada prueba era complicada y tenía responsabilidades mezcladas.

**Enlaces al trabajo hecho**: [Expensify-demo](https://github.com/VonHeikemen/expensify-demo/commit/fa2ac8ff5678e0e9d25fa29e34ca8719452bce25) (último commit del día)

### Día 9: 15 de Enero, 2018

**Progreso del día**: Comencé con la autenticación mediante Firabase. Avancé con la autenticación de usuario en el inicio de sesión.

**Pensamientos**: El proceso de autenticación no me convenció del todo. Intenté encontrar una mejor manera, pero tristemente fallé. Aún así pienso que debe haber una mejor forma de manejar la sesión.

**Enlaces al trabajo hecho**: N/A

### Día 10: 16 de Enero, 2018

**Progreso del día**: Creé los componentes para integrar la funcionalidad de rutas privadas en la aplicación. Y con eso termino la integración completa con Firabase y la sección del curso.

**Pensamientos**: Aquí lo que no me convence de React es el hecho de que para todo la respuesta es un componente. ¿Quieres agregar alguna funcionalidad? Usa un componente de orden mayor. Es todo. Todo se reduce a eso. Incluso si no tiene sentido que algo sea un componente, debe ser un componente. No me gusta eso.

**Enlaces al trabajo hecho**: [Expensify-demo](https://github.com/VonHeikemen/expensify-demo/commit/fe5d630abd1b29f085d0396c4ac60ed1c1047489) (último commit del día)

### Día 11: 17 de Enero, 2018

**Progreso del día**: Empecé la sección del curso. Sólo pude ver dos videos. También me desvié un poco y vi unos videos de unas conferencias sobre Elm.

**Pensamientos**: Elm como herramienta parece genial. Voy a aprender Elm.

**Enlaces al trabajo hecho**: N/A

### Día 12: 18 de Enero, 2018

**Progreso del día**: Avancé con los estilos en la aplicación usando SASS.

**Pensamientos**: Descubrí los beneficios de usar una metodología como el BEM para manejar los estilos. Realmente útil.  

**Enlaces al trabajo hecho**: N/A

### Día 13: 19 de Enero, 2018

**Progreso del día**: Agregué el resto de los estilos a la aplicación.

**Pensamientos**: Ahora puedo decir que sé React (o por lo menos que puedo buscar en google cosas relacionadas a React).

**Enlaces al trabajo hecho**: N/A

### Día 14: 20 de Enero, 2018

**Progreso del día**: Decidí mi próximo objetivo. Terminaré los proyectos de FreeCodeCamp y reclamaré el certificado Frontend. Empecé con la página tributo. También terminé de ver el resto de los videos del curso. Publiqué la aplicación terminada en Heroku.

**Pensamientos**: Me tomó tiempo pero decidí qué tema y qué forma tendrá la página. Aunque no avancé mucho, al menos sé cómo proseguir.

**Enlaces al trabajo hecho**: [Expensify Live](https://desolate-savannah-67115.herokuapp.com)

### Día 15: 21 de Enero, 2018

**Progreso del día**: Terminé la página tributo. Algo así. Tiene todo el contenido, la forma. Faltan los media queries

**Pensamientos**: Empecé a usar el metodo BEM para los estilos, debo decir que es mi trabajo avanza más rápido cuando tengo una estructura sobre la cual basarme.

**Enlaces al trabajo hecho**: N/A

### Día 16: 22 de Enero, 2018

**Progreso del día**: Publiqué la página tributo en codepen. Comencé con el segundo proyecto, el portafolio

**Pensamientos**: Me cuesta pensar en un diseño, así que en lugar de pensarlo desde cero, recrearé una [plantilla](https://github.com/RyanFitzgerald/devportfolio) que encontré en un repositorio de github.

**Enlaces al trabajo hecho**: [Tribute Page](https://codepen.io/VonHeikemen/pen/WdmVPm)

### Día 17: 23 de Enero, 2018

**Progreso del día**: Intenté usar [Picnic.css](https://picnicss.com/) para emular algunas características de la plantilla que intento recrear.

**Pensamientos**: Aunque sí pude avanzar un poco con el header, no está quedando como me gustaría. Además el framework está haciendo algo de magia que me gustaría hacer por mi cuenta.

**Enlaces al trabajo hecho**: N/A

### Día 18: 24 de Enero, 2018

**Progreso del día**: Empecé de cero la página. Esta vez no usaré un Picnic.css. Aunque sí utilizaré [Normalice.css](https://necolas.github.io/normalize.css/) para tener una mejor base. Logré recrear con cierta fidelidad la primera sección del header sin usar un framework.

**Pensamientos**: Aún lucho con el CSS, pero ahora estoy empezando a memorizar algunos trucos. También estoy agarrando práctica con la estructura de las clases.  

**Enlaces al trabajo hecho**: N/A

### Día 19: 25 de Enero, 2018

**Progreso del día**: Agregué el media query a la sección del header para manejar los estilos a partir de un solo punto de quiebre.

**Pensamientos**: Esta vez mantendré simple los media queries. Sólo uno por ahora. Con eso bastará para manejar las pantallas pequeñas y medianas.

**Enlaces al trabajo hecho**: N/A

### Día 20: 26 de Enero, 2018

**Progreso del día**: Empecé a hacer el menú responsive para el portafolio. No pude terminarlo, estaba demasiado cansado para pensar bien. Decidí descansar y ver un [video](https://www.youtube.com/watch?v=bm7RlNEcQM0) de una charla sobre webpack.

**Pensamientos**: De repente webpack me parece más interesante ahora que sé lo que hace. Si no estuviera tan cansado, empezaría a hacer algún plugin inútil sólo para ver si lo que estaba en el video es cierto.

**Enlaces al trabajo hecho**: N/A

### Día 21: 27 de Enero, 2018

**Progreso del día**: Empecé de cero la página del portafolio. Esta vez con el enfoque mobile first. Logré darle forma a las secciones del encabezado, acerca de y proyectos; con sus respectivos media queries para adaptarlo a pantallas grandes y medianas.

**Pensamientos**: Al enfocarme primero en el estilo para dispositivo móviles fue más concentrarme en cómo deberían lucir los elementos. Ya entiendo porque la gente lo hace.

**Enlaces al trabajo hecho**: N/A

### Día 22: 28 de Enero, 2018

**Progreso del día**: Ya por fin pude hacer el menú responsive para el portafolio. Dividí la etiqueta style en componentes.

**Pensamientos**: Una emergencia del trabajo me impidió avanzar más, pero el menú ya está hecho. Puedo decir que he descubierto lo valioso y útil que es tener una estructura cuando avanzas en un proyecto.

**Enlaces al trabajo hecho**: N/A

### Día 23: 29 de Enero, 2018

**Progreso del día**: Terminé el proyecto del portafolio. Agregué los últimos detalles a los estilos y lo subí a github.

**Pensamientos**: Fue más difícil de lo que pensé, pero pude recrear la página sin usar bootstrap. Lamentablemente usé javascript para completar la funcionalidad del menú responsive, pero bueno, tendré que vivir con eso.

**Enlaces al trabajo hecho**: [Portafolio](https://vonheikemen.github.io/)

### Día 24: 30 de Enero, 2018

**Progreso del día**: Avancé hacia el siguiente proyecto de FreeCodeCamp, el generador de frases aleatorias. Tomé un pequeño descanso y en su lugar vi [este video](https://youtu.be/AINnOyUVEyI) acerca de un ejemplo práctico del uso de Ramda.js

**Pensamientos**: Aunque el código final en el video se ve complicado, espero algún día poder obtener suficiente práctica para hacer cosas similares usando el paradigma de la programación funcional. Al principio no lo parece pero creo que este paradigma es más flexible que la programación imperativa que me han enseñado.

**Enlaces al trabajo hecho**: N/A

### Día 25: 31 de Enero, 2018

**Progreso del día**: Empecé usando Vuejs en el proyecto del actual. Encontré una API que pudiera usar en codepen. Hice la mayor parte de la funcionalidad. También, empecé a ver este [playlist](https://www.youtube.com/playlist?list=PLrhzvIcii6GNjpARdnO4ueTUAVR9eMBpc) que trata de patrones de diseño (vi los primeros dos).

**Pensamientos**: Aunque en un momento quise usar React, no pude, no me parecía natural para resolver este tipo de problema. Para ser honesto pude haberlo hecho sin usar algún framework pero Vue se siente bien en esta situación (completamente innecesario pero se siente bien usarlo).

**Enlaces al trabajo hecho**: N/A

### Día 26: 01 de Febrero, 2018

**Progreso del día**: Fue el turno de los estilos. Eso es todo. Empecé a agregarle el CSS al proyecto.

**Pensamientos**: Está casi terminado, es prácticamente la forma final que tendrá. Faltan unos detalles (los botones) y la funcionalidad del Tweet, después de eso estará terminado. Aún me averguenza el hecho de que me cueste más incorporar los estilos que la misma lógica, pero bueno, para eso están estos proyectos, para practicar.

**Enlaces al trabajo hecho**: N/A
