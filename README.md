# Documentos

# Descripción de tablas

| NOMBRE DE TABLA | CLAVE PRIMARIA |  DESCRIPCIÓN |
|-|-|-|
| USER |id_user |Almacena el código (llave primaria), nombre, apellidos, email  y password del usuario. |
| PROFESOR |id_profesor |La tabla se encarga de guardar la información del id de un profesor y la valoración que tiene éste(Si es un buen o mal profesor) como referencias.|
| STUDENT| id_student | Esta tabla sólo se encargará de almacenar los identificadores de los estudiantes.|
| COURSE_HISTORY | id_course_history | La tabla de COURSE_HISTORY existe para guardar su llave primaria, la llave foránea de un profesor para así saber qué cursos ha impartido a lo largo de su estancia en nuestra aplicación y la llave primaria del tabla COURSE |
| COURSE | id_course | Se retiene información a cerca de la llave primaria del curso, llave foránea del profesor, título o nombre de la asignatura, una breve descripción del curso, el temario, fecha de inicio, fecha de finalización, requerimientos y si es privado o público el curso.|
| TOPIC | id_topic | Nos ayuda a preservar información de la llave primaria de éste, la llave foránea del curso a la cual pertenece, y el nombre del tema o sección. |
| GROUP | id_group | Esta tabla mantendrá datos del grupo; el id primario, la llave foránea del estudiante y la llave foránea del course al que pertenece. | 
| EXAMINATION | id_examination | Nos ayuda a guardar toda la información referente a las pruebas aplicadas por un profesor; el id de la evaluación, la llave foránea del estudiante, la llave foránea del tema, el tipo de examen que se aplicará, nombre del examen, calificación y  la llave foránea de la calificación final | 
| FINAL_GRADE | id_final_grade | Esta tabla se encarga de la información de la calificación final de un estudiante, facilita a que persistan los siguientes datos; llave primaria de la calificación final, la llave foránea de la prueba, la llave foránea del estudiante, la calificación final y un campo para determinar si aprobó la materia. |

## Canales

Slack: https://join.slack.com/t/escuelaonline/shared_invite/zt-g8o9xnue-BA2aXT1zLfJNpiCg~1mMqg
