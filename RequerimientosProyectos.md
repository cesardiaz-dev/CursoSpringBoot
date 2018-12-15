# Proyectos de Prueba Tecnica

Integrar y utilizar SWAGGER para la publicación de API RESTful
Todos deberan tener un Dashboard para el administrador para porder revisar que ha pasado en el sistema

## 1 - Servicio de CHAT
* Cada usuario va a pertenecer a una dependencia.
* Se listaran todos los usuarios que se encuentran registrados en el sistema agrupados por dependencia.
* Los usuarios que no hayan iniciado, no apareceran en la lista de usuarios.
* Chat grupal
* Chat privado
* Usando WebSockets
* Base de Datos NoSQL
  	
## 2 - Servicio documental
* Usuario puede crear un documento
* A un documento se le pueden agregar varios archivos
* A un documento se le agregará un titulo, una descripcion y varias etiquetas para catalogar este documento en el sistema
* Un documento puede estar en borrador (aun sin terminar) o público (para consulta de otros usuarios). Estos estados los puede asignar el propietario en cualquier momento.
* Los documentos solo pueden ser editados por el usuario que lo creó o por el administrador.
* Para buscar un documento agregado, se puede consultar por nombre, usuario que lo agregó o segun las etiquetas que le haya etiquetado.
* El sistema permitirá visualizar (ojalá en linea) los archivos que han sido cargados al documento (como lo hace GMAIL)
* Base de Datos NoSQL

## 3 - Servicio de evaluación (examenes)
* Profesor puede entrar y crear una nueva prueba (examen) donde se dará una descricion (introduccion) a la prueba y cuanta es la nota maxima que se puede obtener.
* Cada prueba está compuesta por varias preguntas que tienen una descripción, una imagen (opcional) y una valoración (peso) dentro de la prueba.
* Las preguntas tendran diferentes tipo de respuesta:
  * Seleccion multiple con unica respuesta
  * Seleccion multiple con multiple respuesta
  * Respuesta abierta
* Si la respuesta es de seleccion unica o multiple, se debe seleccionar cual(es) respuesta(s) es la válida.
* Al momento de realizar la prueba, se debe publicar un enlace donde los estudiantes podrán tomar la prueba. 
* Si todas las preguntas son de seleccion multiple, al terminar todas las preguntas y confirmar la terminación de la prueba por parte del estudiante, se le puede dar la nota según las respuestas correctas y el peso de cada pregunta.
* Base de Datos NoSQL

## 4 - Sistema de control de tiempos
* En un sistema de gestion de proyectos, cada proyecto tiene una serie de tareas que deben ser ejecutadas por los miembros del equipo que trabajan en él.
* El miembro del equipo entra por el celular (o web) y selecciona el proyecto y tarea en la que va a empezar a trabajar. Ahi empieza a contar el tiempo que está invirtiendo en la ejecución de esta tarea.
* Cuando ha terminado de ejecutar la tarea, podrá parar el contador y registrar el estado (Pendiente, Cerrado) de la tarea y una descripción explicando que realizó durante ese tiempo.
* Si el miembro del equipo debe suspender su tarea, debe parar el tiempo, dar la descripcion de lo realizado en la tarea.
* Debe registrar tambien los tiempos de los tipos de suspención que realiza durante el dia. Unos posibles tipos de suspencion pueden ser:
  * Ida al baño
  * Reunion
  * Hora de almuerzo
  * Descanso corto para comer snack
* Cada registro, debe quedar guardado en la informacion de la tarea que se estuvo trabajando. 
* Base de Datos NoSQL
