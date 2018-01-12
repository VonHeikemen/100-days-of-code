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
