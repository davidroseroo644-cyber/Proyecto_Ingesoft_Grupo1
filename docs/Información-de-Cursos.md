# Historias de Usuario

PETICIONES DE PABLO
## HU-01: Presentacion de cursos por videos  

*Titulo:* Presentacion de cursos por videos  
*Como:* Estudiante interesado en lo academico  
*Quiero:* Ver los videos que suben los profesores explicando de que trata su materia  
*Para:* Entender sus enfoques de manera clara  

### Criterios de aceptacion:

*Scenario: Acceso al material del curso*  
Given: El estudiante esta explorando la información de una electiva  
When: Hace clic en una seccion llamada "Presentación del docente o curso"  
Then: El sistema reproduce un video donde el profesor explica su materia y que van a hacer  

*Scenario: Interfaz para informacion*  
Given: El estudiante busca una alternativa al sistema actual (Banner)  
When: Navega por el nuevo sitio de información de cursos  
Then: El sistema presenta la informacion de manera intuitiva y visualmente atractiva  


## HU-02: Visualizacion de ofertas de electivas internacionales   

*Titulo:* Visualizacion de ofertas de electivas internacionales  
*Como:* Estudiante en porceso de intercambio  
*Quiero:* ver la lista de las electivas ofertadas por otras universidades en convenio  
*Para:* agilizar la busqueda entre los cursos extranjeros y los de ICESI  

### Criterios de aceptacion:

*Scenario: Consulta de materias en universidades en convenio*   
Given: Que el estudiante entra al modulo de movilidad internacional  
When: Selecciona una universidad extranjera de la lista  
Then: El sistema despliega los cursos disponibles en esa institucion que pueden ser tomados como electivas  

*Scenario: Identificacion de similitudes*   
Given: El estudiante visualiza la lista de cursos internacionales  
When: Compara la informacion de un curso extranjero con una electiva de ICESI  
Then: El sistema permite visualizar los objetivos de ambos para facilitar el tramite  



## HU-03: Busqueda de electivas disponibles
*Titulo:* Busqueda de electivas disponibles
*Como:* estudiante de ICESI
*Quiero:* buscar electivas que se encuentren disponibles en la universidad
*Para:* encontrar mas facilmente los cursos que se ajusten a mis intereses academicos

### Criterios de aceptacion:


*Scenario:Busqueda exitosa de una electiva*
Given: El estudiante esta en el sitio de electivas
When: Escribe el nombre o una palabra clave relacionada con el curso
Then: El sistema muestra las electivas que coinciden con la busqueda

*Scenario: Busqueda de una electiva sin resultados*
Given: El estudiante esta en el sitio de electivas
When: Escribe una palabra para buscar un curso
Then: El sistema muestra un mensaje indicando que no se encontraron resultados


## HU-04: Consulta de informacion general de una electiva
*Titulo:* Consulta de informacion general de una electiva
*Como:* Estudiante de ICESI
*Quiero:* Consultar la informacion principal de una electiva
*Para:* Conocer de manera rápida de que trata el curso antes de inscribirlo

### Criterios de aceptacion:


*Scenario: Visualizacion exitosa de la información del curso*
Given: Que el estudiante ingresa al sitio de electivas
When: Selecciona una electiva de la lista
Then: el sistema muestra la descripcion, objetivos, contenidos, departamento responsable y el profesor encargado

*Scenario: Información incompleta del curso*
Given: El estudiante selecciona una electiva
When: La informacion del curso no está completa
Then: El sistema muestra los datos disponibles
And: Informa que falta información por actualizar


------------------------------------------------------------------------------

PETICIONES DE ROBIN
## HU-01: Filtros de busqueda de electivas  

*Titulo:* Filtros de busqueda de electivas  
*Como:* Estudiante de la universidad  
*Quiero:* Contar con una base de datos que permita realizar busquedas por contenido y horario  
*Para:* Encontrar electivas que se ajusten a mi disponibilidad academica  

### Criterios de aceptacion:

*Scenario: Busqueda efectiva por criterios especificos*  
Given: El estudiante esta en el buscador de cursos  
When: Ingresa un criterio de busqueda como "contenido" o un "horario"  
Then: el sistema muestra una lista de cursos filtrados que coinciden exactamente con los parametros que puso el usuario  

*Scenario: Visualizacion de una estructura organizada*  
Given: El estudiante tiene duda sobre la procedencia de un curso  
When: Selecciona una electiva del listado  
Then: El sistema muestra a que departamento pertenece el curso para futuras consultas  


## HU-02: Gestion y validacion de Syllabus  

*Titulo:* Gestion y validacion de Syllabus  
*Como:* Jefe de departamento  
*Quiero:* Un sistema que permita organizar, consultar y validar la informacion de los syllabus creados por los profesores  
*Para:* Que la informacion académica sea oficial y sea accesible para los estudiantes  

### Criterios de aceptacion:

*Scenario: Validacion exitosa de un nuevo syllabus*  
Given: Un profesor ha cargado el syllabus de su curso en el sistema  
When: El jefe de departamento revisa y le da en "Aprobar"  
Then: El sistema publica la informacion automaticamente para que sea visible para los estudiantes  

*Scenario: Agente inteligente para consultas*   
Given: El sistema cuenta con un agente inteligente integrado  
When: Un usuario realiza una pregunta compleja sobre el contenido de los syllabus  
Then: El agente inteligente procesa la base de datos y entrega una respuesta  

## HU-03: Visualizar departamento al que pertenece una electiva

*Titulo:* Visualizar departamento al que pertenece una electiva  
*Como:* Estudiante de la universidad  
*Quiero:* Identificar a que departamento pertenece cada electiva
*Para:* Saber a donde dirigir las consultas o solicitudes relacionadas con el curso

### Criterios de aceptacion:

*Scenario: Visualizacion del departamento de una electiva*  
Given: El estudiante esta consultando la lista de las electivas
When: Selecciona una electiva
Then: el sistema muestra al departamento académico que pertenece el curso 

*Scenario: Electiva sin departamento asignado*  
Given: El estudiante esta consultando la lista de las electivas
When: Selecciona un curso de electiva que no tiene departamento
Then: El sistema informa en un mensaje indicando que la informacion del departamento esta pendiente por actualizar


## HU-04: Consultar syllabus de una electiva

*Titulo:* Consultar syllabus de una electiva
*Como:* Estudiante de la universidad 
*Quiero:* Acceder de manera sencilla al syllabus de una electiva
*Para:* Conocer la información detallada de los contenidos, objetivos, metodología y evaluación del curso

### Criterios de aceptacion:

*Scenario: Consulta exitosa del syllabus*  
Given: El estudiante está visualizando la información de una electiva
When: Selecciona la opcion de “Consultar syllabus”
Then: El sistema muestra el syllabus del curso de forma clara y accesible

*Scenario: Syllabus no disponible*   
Given: El estudiante intenta consultar el syllabus de una electiva
When: El Syllabus no ha sido cargado o aprobado 
Then: El sistema informa que el syllabus aun no se encuentra disponible 





## Información de Cursos
