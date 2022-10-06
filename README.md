# ITAMates-Repo

<!-- Tabla de contenidos -->
# :notebook_with_decorative_cover: Tabla de contenidos

- [Sobre el proyecto](#star2-sobre-el-proyecto)
  * [Integrantes del proyecto](#wave-integrantes-del-proyecto)
  * [Resumen del producto](#toolbox-resumen-del-producto)
  * [Requerimientos](#grey_question-requerimientos)
  
- [Roadmap](#compass-roadmap)
- [Plan de calidad](#warning-plan-de-calidad)


<!-- Sobre el proyecto -->
## :star2: Sobre el proyecto

## :wave: Integrantes del Proyecto 

  * Luis Fernando Ramirez

  * Isabela Valls 
  
  * Raul Resendiz

  * Victoria Ordorica 
  
  * Gustavo Escobar
 
  * Santiago Hernández
  
## 	:toolbox: Resumen del producto: 

Conforme las plataformas de peer-to-peer se vuelven más populares y abarcan más áreas de la vida diaria, la necesidad de conectar alumnos que se interesan por los mismos temas se vuelve más importante. Es con este propósito que surge ITAMates, un proyecto impulsado por el Instituto Tecnológico Autónomo de México que permitirá a los estudiantes sobresalientes ofrecer asesorías a cambio de compensación económica. Esta aplicación, que será exclusiva para alumnos del ITAM, será gestionada por las autoridades escolares, por lo que se brindará especial atención a detectar casos de fraude académico. Busca competir con otras plataformas similares bajo la premisa de que los oferentes son avalados por la institución. Se buscará digitalizar las actuales labores de facultad menor y los laboratorios; de esta manera, los estudiantes podrán sacar máximo provecho a las herramientas que tienen a su disposición. 


<!-- Requerimientos -->
## :grey_question: Requerimientos
### Objetivos del sistema
| ID         | Nombre     |Descripción |
| ----------------- | --------------------------------- |-----------------|
|OBJ01| Reservar asesorías | El sistema deberá gestionar todo lo relacionado con la coordinación de clases entre alumnos asesores y alumnos del ITAM |
|OBJ02| Ofrecer asesorías |El sistema deberá permitir que alumnos del ITAM puedan ofrecer clases con beneficios económicos |
|OBJ3|Gestionar asesorías| El sistema permitira que el administrador tenga control de todas las clases impartidas |

### Requerimientos funcionales de información

| ID         | Nombre     |Descripción |
| ----------------- | --------------------------------- |-----------------|
|RI1| Alumnos | El sistema deberá guardar información sobre los alumnos registrados en el sistema. (Clave única, Nombre y Contraseña)|
|RI2|Asesores|El sistema deberá guardar información sobre los asesores asignados por los administradores. (Clave única, Nombre, contraseña, materias impartidas)|
|RI3|Materias | El sistema guarda las materias que se imparten en las asesorías. (Nombre, Clave de materia, asesores)|
|RI4| Asesorías agendadas| El sistema guarda las asesorías agendadas con Fecha, Clave única (fk), Clave única asesor (fk), clave materia (fk) y costo|
|RI5|Historial asesorías| El sistema guarda todas las asesorías que se realizaron. (Fecha, clave única alumno, clave única asesor)|

### Requerimientos funcionales del sistema

| ID         | Nombre     |Descripción |
| ----------------- | --------------------------------- |-----------------|
|RF1|Registrar usuario | El sistema permite que los alumnos del ITAM se den de alta en la base de datos del sistema y puedan solicitar asesorías|
|RF2|Selección de rol |El sistema presenta una pantalla sencilla que desplegará tres botones, cada uno correspondiente a asesor, alumno y administrador. |
|RF3|Interfaz de Alumno |El sistema presenta una interfaz que muestra el menú de todas las funcionalidades del sistema. Los alumnos y asesores visualizan las diferentes materías impartidas, los asesores y noticias del sistema.|
|RF4|Visualizar perfil asesores|El sistema deberá permitir que todos los usuarios puedan visualizar todos los asesores y sus descripciones actualizadaS|
|RF5|Visualizar horarios de asesorías|El sistema deberá permitir que los alumnos puedan visualizar los horarios de asesorías mostrando la matería, nombre del asesor y precio |
|RF6|Visualizar noticias |El sistema deberá permitir que todos los usuarios puedan consultar las diferentes noticias que se publican en el sistema|
|RF7|Publicar noticias|El sistema permite que asesores y administrativos puedan publicar nuevas noticias |
|RF8|Ingreso al sistema de alumno y asesor|El sistema permite que se ingrese clave única y contraseña que será validada en la base de datos para permitir acceso o negarlo|
|RF9|Ingreso al sistema de administrador|El sistema debe aceptar un correo electrónico y una contraseña para permitir el acceso al sistema. El sistema valida la información en la base de datos de administrador que tienen acceso a gestionar información comprometedora |
|RF10|Perfil de asesor|El sistema presenta una interfaz donde se despliega la información básica del asesor con foto y reviews. Formato similar al perfil personal Likedin|
|RF11|Actualizar descripción|El sistema permite que el asesor pueda actualizar sus datos|
|RF12|Registrar review|El sistema permite que al finalizar clase el alumno deje un comentario sobre su experiencia con la asesoría|
|RF13|Compartir contenido|El sistema permite que el asesor pueda publicar documentos relevantes para su materia|
|RF14|actualizar base de datos de asesor|El sistema debe actualizar los datos y validar que la información tenga coherencia|
|RF15|Registrar horarios de disponibilidad|El sistema permite que el asesor registre sus horarios de disponibilidad|
|RF16|Interfaz de horario alumno|El sistema muestra una página que muestra los horarios disponibilidad de horarios. Muestra nombre de materia y asesor por cada horario|
|RF17|Interfaz de horario asesor|El sistema muestra las citas agendadas y el historial de clases impartidas|
|RF18|Interfaz de horario administrador|El sistema permite que el administrador actualice información de exámenes y puede agendar o cancelar asesorías|
|RF19|Interfaz de citas alumno|El sistema muestra la vista para agendar cita|
|RF20|Solicitar asesoría|El sistema debe de permitir solicitar asesoría a un alumno|
|RF21|Registrar cita|El sistema despues de la validación de un administrador, registra los datos de la asesoría en la base de datos de asesoría|
|RF22|Interfaz de citas asesor|El sistema muestra la vista para confirmar o rechazar citas|
|RF23|Confirmar cita|El sistema deberá permitir al asesor registrar una cita y confirmar|
|RF24|Cancelar cita|El sistema deberá permitir al asesor cancelar cita y registrar la razón de la cancelación|
|RF25|Envío de confirmación|El sistema debe de notificar al alumno de la aceptación de su cita vía correo registrado|
|RF26|Interfaz de pago|El sistema muestra la vista para realizar el pago despues de que la cita fue confirmada|
|RF27|Pagar monto Paypal|El sistema debe de permitir pagar el monto de la asesoría por medio de cuenta paypal
|RF28|Listar todos los alumnos registrados|El sistema muestra la lista de todos los alumnos si un administrador lo requiere|
|RF29|Lanzar mensaje de recuperación contraseña|El sistema debe de arrojar mensaje y permitir recuperación de contraseña en caso de olvidar contraseña|
|RF30|Ajustar imagen para inserción|El sistema debe de poder mostrar las imagenes en el formato requerido|
|RF31|Formulario para consultas|El sistema muestra una ventana para consultas con asesores y/o administradores|
|RF32|Contacto con asesores|El sistema despliega formas de contacto con los asesores|
|RF33|Eliminar alumno|El sistema permite eliminar alumno en la base de datos con permiso de los administradores|
|RF34|Modificar registro de alumno|El sistema permite que se actualice la base de datos por alumno o administrador|
|RF35|Visualizar materias impartidas por cada asesor|EL sistema deberá desplegar la relación de materias co asesores|
|RF36|Descargar guías de materias| El sistema permite la descarga de material relacionado con la materia de la asesoría|
|RF37|Descarga ejercicios prácticos por materia|El sistema deberá permitir descargar documentos pdf previamente registrados por los asesores|
|RF38|Visualizar precios de clase|El sistema deberá permitir desplegar los precios de las diferentes asesorías|
|RF39|Monto acumulado|El sistema deberá permitir que los asesores vean el monto acumulado por las asesorías impartidas|
|RF40|Aclaración saldo|El sistema deberá permitir que el asesor tenga contacto con administradores para aclarar situación económica|





<!-- Roadmap -->
## :compass: Roadmap

<img width="1062" alt="Captura de Pantalla 2022-10-06 a la(s) 15 27 34" src="https://user-images.githubusercontent.com/35547664/194412144-c83c3001-f40a-4098-8e38-ea4d50d5398e.png">
<a href="https://isabelavlls.atlassian.net/jira/software/projects/IT/boards/1/roadmap?shared=&atlOrigin=eyJpIjoiODZlNTcxNjM5MTM3NDU1YWExMjQ1OWIwYTA1NGM1MTIiLCJwIjoiaiJ9">LinkRoadMap</a>


## :warning: Plan de calidad

| Práctica          | Desarollo      |Objetivos y Fundamentos |
| ----------------- | ------------------------------------------------------- |-----------------|
| Planificación | Planificar el trabajo del proyecto en iteraciones de 1 semana de duración con comunicación constante por medio de Daily Standup |Aplicar un proceso de desarrollo flexible que se adapte a las necesidades del cliente. Obtener retroalimentación del usuario |
| Arquitectura | Documentar la arquitectura seleccionada básica en un diagrama|Se busca lograr una estructura del sistema en una forma que todos los integrantes del equipo comprendan el funcionamiento del sistema |
| Diseño simple | Realizar el código lo más simple posible y comentado correctamente |Se busca que el código sea simple para que cada uno de los desarrolladores entiendan los pasos que se están realizando y no se pierda tiempo en entender los procesos |
| Pruebas unitarias | Realizar pruebas a medida que se desarrolla el sistema |Se busca qué durante el desarrollo se realicen pruebas unitarias para encontrar errores lo más temprano posible y así no perder tiempo en escribirlo |
| Refactoreo | Mientras se desarrolla el sistema, los programadores mejoran el código y documentación continuamente | Se busca que el diseño se mantenga simple, que el número de errores sea menor y los programadores puedan desarrollarlo más fácil |
|Integración continua |Integrar las distintas partes desarrolladas del sistema |Disminuir el número de errores presentes en la etapa de integración por falta de congruencia |
|Propiedad colectiva | Se desarrolla en paralelo para que todos conozcan el código y lógica de solución | Se busca que los programadores conozcan todo el código para que sea más ágil y más flexible el proceso de desarollo |
|12 horas semanales |Cantidad de horas semanales que pueden trabajar los programadores. Cada desarrollador cuenta con 2 horas de trabajo semanal | Se busca mejorar el ánimo del equipo y evitar errores por cansancio y aumentar productividad |




### Planes de calidad concretos


| |**Plan de calidad  1**|
| ----------------- | ---------------------- |
|**Qué** | Visualización correcta del asesor |
|**Quién** |Victoria Ordorica Pardo|
|**Cuándo**| Iniciar el 10 de Octubre |
|**Cómo**|  Curriculum en su perfil con opción de descarga; Apartado con las calificaciones del asesor; Foto del asesor; Datos personales del Asesor|
|**Para qué**| El alumno podrá ver la información completa del asesor para decidir si se acomoda a sus necesidades|
|**Documentación** | Visto bueno por todos los integrantes del equipo | <br>




| |**Plan de calidad  2**|
| ----------------- | ---------------------- |
|**Qué**| Cobro correcto de una clase|
|**Quién**| Luis Fernando Ramírez|
|**Cuándo**|  Iniciar el 30 de Octubre |
|**Cómo**|  Pago mediante Paypal, envío de correo de confirmación de pago al alumno, visibilidad de los datos de la clase en la cuenta del alumno| 
|**Para qué**| Mayor seguridad del usuario para realizar el pago en línea; Cuenta de PayPal vigente con datos fiscales correctos|
|**Documentación**| Visto bueno por todos los integrantes del equipo; Registro de las facturas |




| |**Plan de calidad  3**|
| ----------------- | ---------------------- |
|**Qué**| Correcto inicio de sesión de roles |
|**Quién**|  Gustavo Alejandro Escobar Rea|
|**Cuándo**|  Iniciar el 10 de Octubre|
|**Cómo**|  La Clave Única del alumno existe y está vigente; Se omiten los ceros al inicio de la clave única; El correo institucional sirve como respaldo por si el alumno necesita recuperar su contraseña; El correo registrado del asesor sirve como respaldo para recuperar su contraseña|
|**Para qué**| Se tiene mayor control sobre el acceso de los alumnos, asesores y administradores; Facilita la creación de usuarios así como su identificación y su asignación de rol|
|**Documentación**| Visto bueno por todos los integrantes del equipo|




| |**Plan de calidad  4**|
| ----------------- | ---------------------- |
|**Qué**| Correcta visualización de las clases disponibles |
|**Quién**|   Raúl Isaac Reséndiz Zayas|
|**Cuándo**| Iniciar el 20 de Octubre |
|**Cómo**| En un apartado de la página, se visualizan las materias que cuentan con clases disponibles; las clases disponibles están ordenadas acorde a su fecha y su hora de impartición; Dentro de la información de la clase aparece el nombre del asesor que la impartirá; El alumno puede dar click a un enlace para ver el perfil del asesor|
|**Para qué**| Al alumno se le facilita buscar la materia para la cual requiere una asesoría; Se evita mostrar la información desordena|
|**Documentación**| Visto bueno por todos los integrantes del equipo|




| |**Plan de calidad  5**|
| ----------------- | ---------------------- |
|**Qué**|Correcta implementación de base de datos|
|**Quién**| Santiago Hernández Gutiérrez y Isabela Valls Chávez|
|**Cuándo**|  Iniciar el 8 de Octubre|
|**Cómo**| Uso de PosgreSQL para hostear la base de datos y DBeaver para la gestión|
|**Para qué**|Asegurar una BD segura y robusta que pueda manejar las solicitudes y estar siempre activa|
|**Documentación**| Visto bueno por todos los integrantes del equipo|

