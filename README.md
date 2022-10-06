# ITAMates-Repo

<!-- Tabla de contenidos -->
# :notebook_with_decorative_cover: Tabla de contenidos

- [Sobre el proyecto](#star2-sobre-el-proyecto)
  * Integrantes del proyecto
  * Resumen del producto
  * Requisitos
  
- [Roadmap](#compass-roadmap)
- [Plan de calidad](#plan-de-calidad)


<!-- Sobre el proyecto -->
## :star2: Sobre el proyecto

## :wave:Integrantes del Proyecto 

  * Luis Fernando Ramirez

  * Isabela Valls 
  
  * Raul Resendiz

  * Victoria Ordorica 
  
  * Gustavo Escobar
 
  * Santiago Hernández
  
## 	:toolbox:Resumen del producto: 

Conforme las plataformas de peer-to-peer se vuelven más populares y abarcan más áreas de la vida diaria, la necesidad de conectar alumnos que se interesan por los mismos temas se vuelve más importante. Es con este propósito que surge ITAMates, un proyecto impulsado por el Instituto Tecnológico Autónomo de México que permitirá a los estudiantes sobresalientes ofrecer asesorías a cambio de compensación económica. Esta aplicación, que será exclusiva para alumnos del ITAM, será gestionada por las autoridades escolares, por lo que se brindará especial atención a detectar casos de fraude académico. Busca competir con otras plataformas similares bajo la premisa de que los oferentes son avalados por la institución. Se buscará digitalizar las actuales labores de facultad menor y los laboratorios; de esta manera, los estudiantes podrán sacar máximo provecho a las herramientas que tienen a su disposición. 


<!-- Requisitos -->
## :grey_question: Requisitos
### Objetivos del sistema
| ID         | Nombre     |Descripción |
| ----------------- | --------------------------------- |-----------------|
|OBJ01| Reservar asesorías | El sistema deberá gestionar todo lo relacionado con la coordinación de clases entre alumnos asesores y alumnos del ITAM |
|OBJ02| Ofrecer asesorías |El sistema deberá permitir que alumnos del ITAM puedan ofrecer clases con beneficios económicos |
|OBJ3|Gestionar asesorías| El sistema permitira que el administrador tenga control de todas las clases impartidas |

### Requisitos funcionales de información

| ID         | Nombre     |Descripción |
| ----------------- | --------------------------------- |-----------------|
|RI1| Alumnos | El sistema deberá guardar información sobre los alumnos registrados en el sistema. (Clave única, Nombre y Contraseña)|
|RI2|Asesores|El sistema deberá guardar información sobre los asesores asignados por los administradores. (Clave única, Nombre, contraseña, materias impartidas)|
|RI3|Materias | El sistema guarda las materias que se imparten en las asesorías. (Nombre, Clave de materia, asesores)|
|RI4| Asesorías agendadas| El sistema guarda las asesorías agendadas con Fecha, Clave única (fk), Clave única asesor (fk), clave materia (fk) y costo|
|RI5|Historial asesorías| El sistema guarda todas las asesorías que se realizaron. (Fecha, clave única alumno, clave única asesor)|

### Requisitos funcionales del sistema

| ID         | Nombre     |Descripción |
| ----------------- | --------------------------------- |-----------------|
|RF1| | |
|RF2| | |
|RF3| | |


<!-- Roadmap -->
## :compass: Roadmap
https://isabelavlls.atlassian.net/jira/software/projects/IT/boards/1/roadmap?shared=&atlOrigin=eyJpIjoiODZlNTcxNjM5MTM3NDU1YWExMjQ1OWIwYTA1NGM1MTIiLCJwIjoiaiJ9

## Plan de calidad

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

