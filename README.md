# Laboratorio 3 馃馃
Regresi贸n lineal

## Instrucciones: Realice un programa en Python para resolver el siguiente problema.
## Problema 1:
Anualmente en Estados Unidos, cerca de 1.5 millones de estudiantes de Educaci贸n Superior realizan un examen de aptitud escolar (SAT, por sus siglas en ingl茅s). Aproximadamente el 80% de las universidades e instituciones de Educaci贸n Superior usan las calificaciones obtenidas por los estudiantes en este examen como criterio de admisi贸n (College Board, marzo de 2006).
Un servicio de evaluaciones educativas ha recolectado la informaci贸n del examen del SAT y la informaci贸n del GPA de una muestra de 1000 estudiantes de una universidad (no se indica el nombre por temas de confidencialidad). El SAT consiste en m煤ltiples secciones medibles, las cuales incluye: Matem谩tica, lectura y escritura. Se prueba lectura y escritura juntas y Matem谩tica se eval煤a en una escala del 200 al 800. Una calificaci贸n perfecta es 1600 (800 en ambas secciones). En el caso de GPA es un t茅rmino que se emplea para asignar un valor num茅rico a las puntuaciones acumuladas por un estudiante en el sistema estadounidense. Este valor puede ser anual o agruparse en per铆odos acad茅micos y se calcula en una escala de 0 a 4 puntos (en algunos casos puede ser hasta 5).

Se tiene el siguiente juego de datos del archivo satgpa.csv, el cual tiene la siguiente informaci贸n:
Variables:
鈥? sex - sexo del estudiante (1=Mujer y 2=Hombre)
鈥? sat_v - percentil SAT verbal
鈥? sat_m - percentil SAT en Matem谩tica
鈥? sat_sum - total del percentil del SAT verbal y Matem谩tica
鈥? hs_gpa - promedio de calificaciones de la escuela secundaria
鈥? fy_gpa - promedio de calificaciones del primer a帽o de la universidad


Se tiene inter茅s en determinar si el 鈥渟exo鈥?, el 鈥渢otal del percentil de SAT verbal y Matem谩tica鈥? y el 鈥減romedio de calificaciones de la escuela secundaria鈥? predicen en forma lineal el 鈥減romedio de calificaciones de primer a帽o de la universidad鈥?. Utilice el m茅todo del descenso del gradiente para encontrar los par谩metros correspondientes (thetas). Estas caracter铆sticas podr铆an utilizarse en un futuro para calificar a las personas para su ingreso a esta universidad.

## Referencias:
鈥? Diez, Cetinkaya-Rundel & Barr, OpenIntro Statistics, Four Editiion. (OpenIntro, 2015).
鈥? Anderson, Sweeney & Williams, Estad铆stica para Negocios y Econom铆a, 11a. ed. (Cengage
Learning, 2011).
鈥? http://studentcaffe.com/preparate/estudiantes-de-la-secundaria/el-examen-
sat?lang=es#:~:text=Se%20prueba%20lectura%20y%20escritura,en%20ambas%20de%20las%20
secciones).
鈥? https://www.academica.school/news/como-se-calcula-el-gpa/
