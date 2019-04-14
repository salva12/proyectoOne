# proyectoOne
repositorio para el TP FINAL

Informacion,propuestas,reflexiones para nuestro grupo y para informar/coordinar con el grupo que tiene el mismo tema que nosotros.

Informacion del lenguaje, estamos pensando segun "veamos/aprendamos"
mas acerca de arquitectura de microservicios y ventajas que cada 
lenguaje aporta a estos areas/temas/etapas.


lenguage para tratar con FrontEnd(framework) elegimos.........esto

lenguaje para tratar con  web servicies elegimos..............esto

lenguaje para tratar con  regla de negocio elegimos...........esto

lenguaje para tratar con  ORM /acceso a datos elegimos .......esto

Base de datos elegida hasta ahora mySql.

Sistema operativo para trabajar Ubuntu.

Modelar por medio de arquitectura de microservicios <----> (ademas aprender de docker/kubernetes)


De aca en mas me parece que tenemos 2 objetivos PRINCIPALES: 

1-Ponernos de accuerdo en las herramientas a usar, si bien pueden variar, mejoran la comunicacion y coordinacion,
les dejo una propuesta de herramientas a usar, despues lo hablamos en detalle.

2-Lo Principal es terminar la estructura de la base de datos logica/fisica, cargarla con datos, 
 seguir con trigger/StoreProcedure para mantener integridad/consistencia etc. Esto es algo que todos en ambos grupos
 sabemos hacer  y es la base "creo" para cuando eligamos y luego hagamos pruebas sobre el ORM/acceso a datos(mapeo).

3-Ir aprendiendo sobre ORM/acceso a datos (mapeo-relacional-->objetos) 
---> Vi  "muy" de pasada esto y bueno  saltan dos opciones...  salen al toque dos frameworks ORM:
--> node (sequelize) o java(hibernate) investigen otras opciones (pro/contras--cual se adapta mejor a microservicios etc) 
pero tambien en el corto plazo hay que ir eligiendo, asi nos ponemos a leer/probar sobre lo que tenemos hecho al terminar BD.


Propuestas de herramientas.

Editor de texto microsoft visual studio code...es bastante completito y tiene muchos plugins "muy" utiles (git por ejemplo)
para hacer un cambio rapido o documentar algo (sin usar consola de git). Ademas es multiplataforma.

Sistema operativo - ubuntu = Principalmente porque Docker es compatible con gnu/linux   y queremos trabajar con una IDE
que nos permita integracion con git/github/docker/Kubernetes/Base de Datos y que nos permita tener a todos una "misma mesa de trabajo" (digamos) y que los cambios que hagamos sean vistos/manipulados por los demas desde la IDE; teniedo un respaldo por si tenemos que volver atras. Facilitando tener que juntarnos un "poco" menos y seguir avanzando.


IDE de desarrollo elegida....probablemente "Eclipse" o "netbeans" (visual estudio no es compatible en ubuntu) salvo que trabajemos con esa IDE en windows y luego cuando este todo listo de alguna forma exportamos el resultado a docker/Kubernetes. 

*Eclipse/Netbeans son medios pesados al arrancar (eclipse en particular sino tenes ssd) pero no esta tan "roto" como visual studio
 por lo menos no se me cerro la ventana al jugar con git por ejemplo o no se me quedo la ventana en NO RESPONDE.

El diseño de la base de datos pensamos realizarlo con ErStudio cosa de ir detallando el diseño
logico y luego el Fisico.

***La instalacion de ErStudio funciona en ubuntu !!! :) tienen que instalar wine 4.0 y con
eso quedan "hasta ahora todas las herramientas de desarrollo en linux". No es necesario cambiar de
SO. 

***De ultima en windows anda tmb, una ves terminado el diseño logico/fisico vuelven a Ubuntu. Era para no andar cambiando de SO cada rato. Por un cambio rapido que se deba hacer del diseño Fisico o del codigo, lo cargamos en
contenedor   con docker y github-->  lo suben a la nube para corregir tener algo y que la IDE tome esa info rapidamente.

***el ErStudio 8.0  luego de instalar wine va a instalar un par de paquetes de internet luego
les dice que falta algo denle ok saltar nomas. Termina instalacion sale tmb un pequeño faltante
de algo. Pero den siguiente. Peguen los archivos faltantes y denles permisio de lectura/escritura. El ejecutable esta en .wine ...
bue creo que ya saben el resto. Si quieren ejecutarlo mas facil haganse un launcher. 

Todo esto va a estar respaldado por git de forma local y cuando terminen de hacer cambios pueden
hacer sus propias ramas y seguir sus desarrollos de determinadas versiones o tareas o hacer un push (cuando todo funcione y funcione bien...) a mi github   (documenten sus cambios o va a ver " :) GARROTE :) " tanto del codigo como de docker , BD etc) ... O sea que el codigo fuente, contenedor de docker con la BD y codigo, va a estar en github, con la IDE alimentada de esos repositorios. La parte de Kubernetes lei algo pero me falta mas para darme una idea y utilidad ... Pero por lo que vi de docker los contenedores con mysql/SO (una ves que tengamos el diseño fisico y aprendamos a cargar/manipular tablas/datos desde la IDE) "creo" que la idea es usarlos durante el desarrollo para hacer cambios/comit/subimos sino descartes y atras --> si nada se rompio seguimos --> y asi sucesivamente hasta que funcione, eso nos beneficia al no tener que tocar, levantar/rediseñar base de datos  o con los cambios/errores del codigo en un nivel superior. 

Bue... me falta "MUCHA" mas lectura/teoria para entender esta metodologia de trabajo y las tecnologias usadas, microsevicios etc...
pero bue por algo se comienza....APORTES Y OPINIONES RECIBIDAS 

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