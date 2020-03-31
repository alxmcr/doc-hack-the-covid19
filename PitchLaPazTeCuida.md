# Pitch

## Problema elegido
El problema que elegimos es: Sistema o Aplicacion para generar información sobre el movimiento de usuarios para la prevención del COVID-19

## Solución desarrollada
La solucion desarrolla se divide en dos: una plataforma web (Front-End) y servicios API (Back-End) REST. La plataforma web, es la parte de la solucion que el usuario puede ver, como ser: formularios, tabla de datos e imagenes, con el objetivo de permite el registro de Usuarios, Buses, Rutas que recorren los buses, viajes y personas confirmadas con COVID-19. Ahora, por parte de los servicios Web, se construyo en un API REST, con el objetivo de facilitar la comunicacion entre el Front-End y el Back-End mediante peticiones HTTP, ademas nos da una libertad de escoger el gestor de Base de Datos sin afectar la plataforma web o viceversa podemos cambiar las herramientas usadas en la plataforma sin afectar los servicios y ademas nos permite la posibilidad que una aplicacion movil, consuma facilmente los datos e incluso otra plataforma u otra institucion, finalmente, se consideraron dos metodologias de desarrollo: metodologia orientada a servicios y la otra diseño de interfaces por componentes.

## Herramientas utilizadas
Medio de comunicacion: WhatsApp
Para la gestion de tareas: Trello y WhatsApp
Para el analisis de requerimientos, se utilizo los casos de uso.
Para la base de datos: PostgreSQL
Para el API REST, se uso el lenguaje de programacion: JavaScript, como servidor web: Node.js, para la gestion de paquetes Node.js: NPM, ExpressJS como manejador de rutas y proporcionar la publicacion de servicios, Sequelize para lograr un mapeo Objeto Relacional (ORM) entre los modelos y las tablas de las base de datos, Paquete de Node.js body-parse para la transformacion de Objetos a elementos JSON.
Para la plataforma Web, se uso el lenguaje de programacion: JavaScript y para el maquetado y los estilos: HTML y CSS, librerias como Bootstrap para los estilos y Axios comunicacion con el API REST desarrollada, Frameworks Javascript: Vue para el diseño de componentes, Vue-Router para el manejo de Rutas, Vuex para la gestion de la fuente de datos, Vuetify para el uso de componentes desarrollados en Vue y como servidor web: Node.js


## Obstáculos que afrontaron durante los días del hackathon
- Distancia entre los integrantes del equipo para definir objetivos, coordinar tareas a realizar, compartir avances, etc.
- Disponibilidad de tiempo, algunos integrantes, debian trabajar durante la competencia e ir combinando trabajo y el hackaton.
- Acceso a la informacion facilmente
- Recursos economicos, para comprar herramientas, dominios, imagenes, etc.

## Que proponen desarrollar para continuar con el proyecto
- Poner a produccion, la primera version de la plataforma y el API REST, con dominio y datos reales.
- Permitir que la plataforma no solo se oriente al COVID-19, sino a otro tipo de enfermedades o pandemias
- Adaptar la plataforma para otras ciudades y otros tipos de transporte publico o privado
- Permitir conocer el recorrido completo del bus y el pasajero.
- Plataforma web, mas inclusiva: multiidioma, iconografia, lectura de voz.
- Fusionar la Base de datos de La Paz te Cuida con la del Pumakatari (Buses, rutas, viajes, etc)
- Plataforma web, mas informativa y preventiva: brindar mayor informacion sobre los cuidados a tener ante una determinada enfermedad, que centros de salud o farmacias existen en el recorrido del bus, numeros de emergencia, que acciones a tomar si se encuentra en el bus y existen personas con algun problema de salud.
- Compartir informacion valiosa con otras instituciones como ser: Policia, Fuerza Especial de Lucha Contra el Crimen, División de Trata y Tráfico de Personas
- Aplicacion movil, para el uso del pasajero u operador de transporte, reducir los pasos y mejorar el uso del servicio proporcionado por la plataforma como ser: uso de codigo de QR, uso del GPS para conocer el recorrido realizado.


## Que recursos necesitarian para completar el proyecto

- Expertos en poner en ambientes de produccion, servidores fisicos o en la nube, administradores de base de datos para una posible migracion de datos y documentacion de la base de datos.
- Acceso a la informacion real y completa del pumakatari y del ministerio de salud.
- Expertos en el uso y aplicacion en codigo del GPS
- Expertos en el uso de mapas como ser Google Maps u Openstreetmap conjunto el GPS
- Expertos en el desarrollo movil Android y iOS
- Expertos en Salud y Movilidad Urbana
- Convenios entre instituciones publico - privado