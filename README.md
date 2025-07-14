# mi-proyecto-creative
1.Integrantes
Wilfrank Camilo Cuesta – Encargado del código
Geraldyn Hernández Gómez – Encargada de la documentación 
Delsy Causil Flores- Encargada de pruebas

2.Vinculos académicos
Wilfrank- Soy estudiante de ingeniería industrial. No tengo ningún tipo de experiencia en programación, pero con lo que llevamos del curso y videos alaternos he aprendido de ciertos tipos de herramientas que nos podrían ser útiles a la hora de resolver este tipo de trabajo y me esmero en que lo que sé, salga de la mejor manera y lo que no sé, trato investigar y consultar para llegar a un buen desarrollo de la actividad.
Geraldyn- Soy estudiante de ingeniería Industrial, primera vez que veo esta materia y no tengo mucho conocimiento, pero con lo visto en el curso e investigaciones apartes siento que puedo ser de mucha ayuda al grupo y aportar un poco de mi conocimiento adquirido.
Delsy- Soy estudiante de Ingeniería Industrial con afinidad por áreas como contabilidad, economía y gestión de procesos. Me destaco por mi capacidad para estructurar, organizar y liderar, cualidades que aplico tanto en el trabajo individual como en equipo. Me siento especialmente cómoda en entornos donde el orden, la planificación y la toma de decisiones estratégicas son clave. Aunque actualmente enfrento el reto de adaptarme a herramientas avanzadas de simulación y optimización, asumo este proceso como parte de mi crecimiento profesional, con disposición constante para aprender y mejorar. Creo en el valor del equilibrio entre la técnica y la gestión, y aspiro a desarrollarme como una profesional integral dentro del campo industrial.

3.Nombre del proyecto
Hotel palmeras 
¨Disfrutaras de unas vacaciones al estilo tropical con vistas al mar, además dentro del hotel cuenta con una piscina con toboganes para disfrutar de ella, dispone de una zona de spa relajante y sauna de vapor que te hará sentir en las nubes, y por su puesto con un pequeño restaurante para que disfrutes de diferentes platillos y bebidas tropicales¨.
![image](https://github.com/user-attachments/assets/459b309d-b493-4c54-93de-b3842fbe23ef)

4 Lisencia sotfware: 
Untitled  © 1999 by Jane Doe is licensed under Creative Commons Attribution-NonCommercial 4.0 International. To view a copy of this license, visit https://creativecommons.org/licenses/by-nc/4.0/
<a href="https://creativecommons.org">Untitled</a> © 1999 by <a href="https://creativecommons.org">Jane Doe</a> is licensed under <a href="https://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International</a><img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/nc.svg" style="max-width: 1em;max-height:1em;margin-left: .2em;">
Untitled  © 1999 by Jane Doe is licensed under Creative Commons Attribution-NonCommercial 4.0 International. To view a copy of this license, visit https://creativecommons.org/licenses/by-nc/4.0/

5 Reporte de vision.
Este software busca ayudar a un Hotel a gestionar de manera eficiente la administración de huéspedes, reservas, ingresos, salidas, cobros y reportes. 
El programa tiene como objetivo facilitar el trabajo diario de los recepcionistas, reduciendo errores manuales y mejorando la organización de la información del hotel. 
Si funciona correctamente, permitirá un control claro y ordenado de la operación del hotel las 24 horas del día, contribuyendo a una mejor atención al cliente y una administración más efectiva.

6. Especificación de requisitos.
Este sistema que estamos desarrollando busca hacerle la vida más fácil al personal del Hotel Palmeras. Su objetivo es dejar atrás los registros en papel y llevar todo a un programa de consola que permita tener la información organizada, segura y accesible.
¿Qué debe poder hacer el sistema?
	Registrar huéspedes: Cuando una persona llegue al hotel, se le deben pedir sus datos personales y el sistema debe validarlos para asegurarse de que estén bien escritos.
	Hacer reservas: Solo se podrá hacer una reserva si el huésped ya está registrado. El sistema mostrará qué habitaciones hay disponibles, preguntará las fechas y guardará todo.
	Registrar ingresos (check-in) y salidas (check-out): Cuando el huésped llegue, se activa su estadía. Cuando se vaya, el sistema calcula cuánto debe pagar, genera una factura en pantalla y actualiza la disponibilidad de la habitación.
	Generar facturas: El sistema debe mostrar una factura clara con todos los datos del huésped y de su estadía, incluyendo los valores cobrados.
	Ver reportes administrativos: Las personas con clave de administrador pueden entrar a un menú exclusivo donde verán estadísticas como cuántos huéspedes hay, cuántas habitaciones están ocupadas, cuánto dinero ha ingresado, entre otros.
	Mostrar gráficas (con matplotlib): Se debe poder visualizar información de manera gráfica para entender fácilmente lo que está pasando en el hotel (por ejemplo, cuántas suites están ocupadas, cuánto se ha ganado, etc.).
	Guardar todo en archivos: El sistema debe guardar datos como huéspedes, reservas, facturas y registros de actividades en archivos .csv o .txt para tener respaldo y poder analizarlos después.
	Crear un log de eventos: Todo lo que se haga en el programa (como registrar a alguien, generar una factura o hacer una reserva) debe quedar anotado en un archivo de texto como si fuera una bitácora del sistema.


¿Qué debe hacer bien?
	Validar bien los datos (por ejemplo, no dejar poner nombres con números).
	Evitar errores como registrar dos veces a la misma persona o reservar una habitación ocupada.
	Ser fácil de usar: el programa debe guiar paso a paso al recepcionista o al administrador.
	Funcionar sin conexión a internet (todo es local y en consola).


 ¿Qué cosas no debe hacer?
	No se debe permitir reservar si el huésped no está registrado.
	No se debe permitir alojar mascotas (esto es una política del hotel).
	No debe aceptar claves erróneas para acceder como administrador.
	No se debe perder la información entre una ejecución y otra (todo debe guardarse bien en archivos).

¿Qué librerías vamos a usar?
	datetime – para manejar fechas.
	csv – para guardar y leer datos en archivos planos.
	re` – para validar formatos de texto como nombres o correos.
	time – para medir cuánto tarda cada acción del sistema.
	getpass – para ocultar la contraseña del administrador.
	os, platform y getpass – para registrar quién está usando el programa.
	matplotlib – para generar las gráficas requeridas.


 ¿Qué funciones vamos a crear?
	Registrar huésped
	Validar datos personales
	realizar reserva
	Check in
	check out
	generar factura
	mostrar menú administrador
	generar reportes admin
	crear graficas
	guardar log evento
	cargar datos
	guardar datos

¿Qué estructuras de datos vamos a usar?
Diccionarios para almacenar temporalmente la información de cada huésped, reserva o factura.
Listas de diccionarios para agrupar múltiples registros.
DataFrames de pandas para leer y trabajar fácilmente con archivos `.csv`.
Archivos de texto o CSV como almacenamiento permanente.

7. Plan de proyecto: 
(Realizado en Excel)

8. Plan de versionado

El control de versiones del proyecto “Hotel Palmeras” se ha llevado a cabo mediante el uso de Git y un repositorio en GitHub. Este sistema ha permitido mantener un historial detallado de los avances del desarrollo, la colaboración entre los integrantes y la trazabilidad del código fuente, almacenado en la carpeta src.
 se describen las versiones más relevantes durante el proceso de desarrollo:
 
Versión 1.0 – 1 de junio:
Creación del repositorio en GitHub. Se definió la estructura del proyecto: carpetas src (código fuente), doc (documentación) y data (archivos CSV). Se subió el archivo principal del menú y se dejó el esqueleto del sistema.

Versión 1.1 – 3 al 7 de junio:
Se programó la función menú () principal con opciones numeradas.
Se implementó la función registrar_huesped () incluyendo validaciones con expresiones regulares (re) para nombre, apellido, correo, teléfono y documento.
Los datos validados se guardan temporalmente en una lista de diccionarios.

Versión 1.2 – 9 al 14 de junio:
Se añadieron estructuras de datos para simular una base de datos de habitaciones (habitaciones = [...]) y reservas.
Se implementó la función reservar_habitacion () y se enlazó al menú principal.
Se ajustaron las validaciones y errores de entrada para robustecer la usabilidad.

Versión 1.3 – 14 al 18 de mayo:
Se incorporó el check-out de los huéspedes con actualización del estado de las habitaciones.
Se agregaron las funciones buscar huésped () y controles de errores para búsquedas.
Se cargó la primera versión del archivo admin.txt y funciones para acceso del administrador.

Versión 1.4 – 9 al 12 de julio:
Se integraron las funciones estadísticas y de reporte con acceso restringido por contraseña (getpass).
Se añadió generación de logs del sistema (bitácora de eventos).
Se incluyó compatibilidad con archivos csv para guardar y recuperar reservas, huéspedes y habitaciones.

Versión 1.5 – 13 al 16 de julio:
Se desarrollaron las funciones de visualización gráfica con matplotlib.
Se completaron los módulos de administración, menú gráfico y reportes.
Se revisó y comentó el código para dejarlo listo para documentación y pruebas finales.

Cada versión fue registrada en GitHub, utilizando ramas para pruebas y mejoras. Esto permitió mantener un orden cronológico y colaborativo durante el desarrollo del proyecto.
