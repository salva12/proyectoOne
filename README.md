# proyectoOne
repositorio para el TP FINAL

Informacion del codigo, estamos pensando segun veamos/aprendamos
mas acerca de arquitectura de microservicios y ventajas que cada 
lenguaje aporta a estos temas.


lenguage para tratar con FrontEnd(framework) elegimos.........
lenguaje para tratar con  web servicies elegimos..............
lenguaje para tratar con  regla de negocio elegimos...........
lenguaje para tratar con  ORM /acceso a datos elegimos .......
Base de datos elegida hasta ahora mySql.
Sistema operativo para trabajar Ubuntu.

Principalmente porque Docker es compatible con gnu/linux   y queremos trabajar con una IDE
que nos permita integracion con git/github/docker/Kubernetes/Base de Datos y que nos permita tener a todos una "misma mesa de trabajo" (digamos) y que los cambios que hagamos sean vistos/manipulados por los demas; teniedo un respaldo por si tenemos que volver atras. Facilitando tener que juntarnos un "poco" menos y seguir avanzando.


IDE de desarrollo elegida....probablemente "Eclipse" o netbeans (visual estudio no es compatible en ubuntu) salvo que trabajemos con esa IDE en windows y luego cuando este todo listo de alguna forma exportamos el resultado a docker/Kubernetes. 

El diseño de la base de datos pensamos realizarlo con ErStudio cosa de ir detallando el diseño
logico y luego el Fisico.

*La instalacion de ErStudio funciona en ubuntu !!! :) tienen que instalar wine 4.0 y con
eso quedan "hasta ahora todas las herramientas de desarrollo en linux". No es necesario cambiar de
SO. 

*De ultima en windows anda tmb, una ves terminado el diseño logico/fisico vuelven a Ubuntu. Era para no andar cambiando de SO cada rato. O por un cambio rapido del diseño Fisico, lo cargan en
docker rapidamente y lo suben a la nube para corregir tener algo.

el ErStudio 8.0 luego de instalar wine va a instalar un par de paquetes de internet luego
les dice que falta algo denle ok saltar nomas. Termina instalacion sale tmb un pequeño faltante
de algo. Pero den siguiente. Peguen los 2 archivos faltantes y denles permisio de lectura/escritura. El ejecutable esta en .wine ...bue creo que ya saben el resto. Si quieren ejecutarlo mas facil haganse un launcher. 

Todo esto va a estar respaldado por git de forma local y cuando terminen de hacer cambios pueden
hacer sus ramas o hacer un push (cuando todo funcione y funcione bien...) a github ya sea a mi
master (documenten sus cambios o va a ver "GARROTE" tanto del codigo como de docker , BD etc) ... O sea que el codigo fuente, imagenes de docker , diseño logico/Fisico va a estar en github con la IDE alimentada de esos repositorios. La parte de Kubernetes lei algo pero me falta mas para darme una idea ... Pero por lo que vi de docker los contenedores con mysql (una ves que tengamos el diseño fisico y aprendamos a cargar/manipular tablas/datos desde la IDE) "creo" que la idea es usarlos durante el desarrollo para hacer cambios/comit/descartes o nada se rompio seguimos --> y asi sucesivamente hasta que funcione, eso nos beneficia al no tener que tocar, levantar/rediseñar base de datos  o con los cambios/errores del codigo en un nivel superior. 

Bue me falta MUCHA mas lectura/teoria para entender la metodologia de trabajo...

y bue algo para tener en cuenta :)

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


