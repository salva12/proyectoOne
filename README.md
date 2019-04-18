# proyectoOne
repositorio para el TP FINAL

Informacion,propuestas,reflexiones para nuestro grupo y para informar/coordinar con el grupo que tiene el mismo tema que nosotros.

Informacion del lenguaje, estamos pensando segun "veamos/aprendamos"
mas acerca de arquitectura de microservicios y ventajas que cada 
lenguaje aporta a estos areas/temas/etapas.


lenguage para tratar con FrontEnd(framework) elegimos.........esto

lenguaje para tratar con  web servicies elegimos..............esto

lenguaje para tratar con  regla de negocio elegimos...........esto

lenguaje para tratar con  ORM /acceso a datos elegimos ...JPA(POR TEORIA HASTA AHORA ESTUDIAR)....

Base de datos elegida hasta ahora mySql. 
(deje algunos registro de ingreso sobre que surguen de: 
 Registro de Pre-ingreso (prehospitalario) del paciente al hospital desde una ambulanncia
 registro de un nuevo paciente al hospital 
 Registro de internacion(normal/intesiva) dentro del hospital/sanatorio)
 Cualquiera sea el nivel de detalle elegio para modelar la BD sirver de "INSPIRACION"

Sistema operativo para trabajar Ubuntu.

Modelar por medio de arquitectura de microservicios <----> (ademas aprender de docker/kubernetes)


De aca en mas me parece que tenemos 2 objetivos PRINCIPALES: 

1-Ponernos de acuerdo en las herramientas a usar, si bien pueden variar, mejoran la comunicacion y coordinacion,
les dejo una propuesta de herramientas a usar, despues lo hablamos en detalle. 
Ejemplo herramienta para diseñar BD -> Erstudio o alguna online y colaborativa etc.


2-Lo Principal es terminar la estructura de la base de datos logica/fisica, cargarla con datos, 
 seguir con trigger/StoreProcedure para mantener integridad/consistencia etc. Esto es algo que todos en ambos grupos
 sabemos hacer.

3-Ir aprendiendo sobre ORM/acceso a datos (mapeo-relacional-->objetos) --> HASTA AHORA JPA
---> Vi  "muy" de pasada esto y bueno  saltan dos opciones...  salen al toque dos frameworks ORM:
--> node (sequelize) o JPA -> implementacion-> (hibernate)   investigen otras opciones (pro/contras--cual se adapta mejor a microservicios etc) 
pero tambien en el corto plazo hay que ir eligiendo, asi nos ponemos a leer/probar sobre lo que tenemos hecho al terminar BD.

4- Deberian poder crear un contenerdor con docker que contenga un BD de mysql y poder verla/modificarla desde la IDE. 
(todo esto a modo de ejercicio, seguramente mas adelante lo vamos a usar + otras cosas--> pero para ir aprendiendo esta.)



Propuestas de herramientas.

Editor de texto microsoft visual studio code...es bastante completito y tiene muchos plugins "muy" utiles (git por ejemplo)
para hacer un cambio rapido o documentar algo (sin usar consola de git). Ademas es multiplataforma.

Sistema operativo - ubuntu = Principalmente porque Docker es compatible con gnu/linux  
Puede ser otro, simplemente es mas facil usar docker sin instalar windows 10.

IDE de desarrollo elegida....probablemente "Eclipse" o "netbeans" o "visual estudio" -->no es compatible en ubuntu (ESTA ULTIMA)
TODAS SIRVEN VEAN CON CUAL SE SIENTEN MAS COMODOS.

Propongo que -->El diseño de la base de datos  usemos ErStudio cosa de ir detallando el diseño
logico y luego el Fisico.
(ya la conocemos la herramienta de BDA es flexible y potente...
faltaria que sea un poco mas colaborativa pero github+saves+script.sql deberiamos andar)

***La instalacion de ErStudio funciona en ubuntu !!! :) tienen que instalar wine 4.0 y con
eso quedan "hasta ahora todas las herramientas de desarrollo en linux". No es necesario cambiar de
SO. 

SI TIENE ALGUNA OTRA BUENA HERRAMIENTA COLABORATIVA PARA DISEÑO DE BD que ademas permita el paso de diseño logico a fisico --> avisen!!!

 
APORTES Y OPINIONES RECIBIDAS 

y bue... algo para tener en cuenta :)

III. Mantendrás la sencillez.

Keep It Simple, Stupid (KISS principle). Este principio te alejará de construir barriles para conservar el valor de la  botella de vino. No confundas la sobre-ingeniería con calidad. La calidad es concisa y escalable

IV. Esperarás siempre una catástrofe.

Espera la peor de las sorpresas. Haz tus recursos redundantes, respalda tus datos, testea tus respaldos, y respaldalos. The shit will hit the fan someday. Preparate.

V. Planificarás objetivamente.

Un buen trabajo, sigue de un buen plan. Mantén el objetivo, identificándolo primero. Planea tu trabajo cuidadosamente, y las sorpresas serán más sencillas de manejar.

VI. Te mantendrás informado.

Reúne todas las noticias, información, logs y estadísticas que puedas. Sin los datos crudos para analizar, no puedes estar seguro, no puedes debuggear y no puedes pronosticar. Sin nueva información, no puedes aprender.

VII. Compartirás tu conocimiento.

Nadie está solo en este mundo. Pasa tu conocimiento a otros. Da a los demás, contribuye con tu comunidad y cosecharás muchas recompensas. No es prudente embotellar conocimiento. Don’t be an asshole.

VIII. Automatizarás tus tareas.

Haz más y velozmente, automatizando tareas. Tu manejas los hilos, no pierdas tu tiempo con tareas simples. Trabaja inteligentemente, no de más.

IX. Documentarás tu trabajo.

Siempre documenta tu trabajo, tu código (scripts) y tus planes. Luego documenta su ejecución y mantenimiento. Documenta para otros y para tí mismo. La documentación debe ser una extensión de tu mente y un recurso para los demás.

X. Respetarás tu organización.

Sin organización, no hay sistema, no hay usuarios y no hay trabajo. Comprende a la organización y su negocio. Respétalos y ayudales a prosperar.

XI. Confía, pero verifica.

Confía en tus compañeros y en tus usuarios, pero verifica sus acciones.


pd:Perdonen horrores ortográficos. 