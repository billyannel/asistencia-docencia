1	Introducción
Desarrollo de una aplicación para la institución IPP, con el fin de llevar a cabo un orden y registro de asistencia Presencial de los docentes de la institución. Puntualidad, hora de entrada y salida. Además se encarga de comunicar curso que debe dictar.
Eliminación de la carpeta.

1.1	Propósito
Esta Aplicación será ocupada por el todo el personal docente de la institución IPP.

1.2	Alcance
La aplicación constara de un aparato de huella digital. Los docentes registraran su hora de llegada atreves de su huella digital, entonces la pantalla mostrara  nombre, apellido, cod asignatura a dictar y nº de sala.
Luego guardara los datos del docente con su registro de llegada.

1.3	Personal involucrado
Nombre	Denis Nuñez
Rol	Toma de requerimientos
Responsabilidades	Entrevistas con el cliente.
Información de contacto	Denis\_gwen@hotmail.com

Nombre	Katherine Cartagena
Rol	Documentación
Responsabilidades	Procesos documentados. Inicio y termino de estos.
Información de contacto	katherine.cartagena.r@gmail.com

Nombre	Ariel Ladrón de Guevara
Rol	Desarrollo de Software
Responsabilidades	Desarrollo e implementación del Software
Información de contacto	ariel.ladrondeguevara@gmail.com

1.4	Definiciones, acrónimos y abreviaturas
Glosario:

Software:
Hardware:
Sistema:
Procesos:

1.5	Referencias

(NA)
Relación completa de todos los documentos relacionados en la especificación de requisitos de software, identificando de cada documento el titulo, referencia (si procede), fecha y organización que lo proporciona.

2	Descripción general

2.1	Perspectiva del producto

Es un sistema que interactúa de manera independiente.

2.2	Funcionalidad del producto

Se compara la huella insertada en el lector de huellas y se compara con la huella almacenada en el sistema. Reflejando los datos relevantes del docente en la pantalla táctil y espera la aceptación de la transacción.

2.3	Características de los usuarios
Tipo de usuario	Docentes registrados en la institución.
Habilidades	Cualquier tipo
Actividades	Registrar asistencia de docente, entrada y salida.

2.4	Restricciones

Descripción de aquellas limitaciones a tener en cuenta a la hora de diseñar y desarrollar el sistema, tales como el empleo de determinadas metodologías de desarrollo, lenguajes de programación, normas particulares, restricciones de hardware, de sistema operativo etc.

2.5	Suposiciones y dependencias
(NA)

2.6	Evolución previsible del sistema

Una mejora evidente podría ser la interfaz grafica.

3	Requisitos específicos

Número de requisito	1

Nombre de requisito	Información personal de los docentes.
Tipo                    Requisito
Prioridad del requisito	Alta/Esencial

Número de requisito	2

Nombre de requisito	Red de internet
Tipo	                Requisito
Prioridad del requisito	Alta/Esencial

Número de requisito	3

Nombre de requisito	Hardware necesario.
Tipo	                Requisito
Prioridad del requisito	Alta/Esencial

3.1	Requisitos comunes de los interfaces

Descripción detallada de todas las entradas y salidas del sistema de software.

3.1.1	Interfaces de usuario

prototipo

3.1.2	Interfaces de hardware

(NA).

3.1.3	Interfaces de software

No hay integración con otro sistema.

3.1.4	Interfaces de comunicación

El sistema se comunica con el servidor mediante un protocolo tcp/ip.

3.2	Requisitos funcionales

Acciones de cómo funciona el sistema de inicio a fin.

	Comprobación de validez de las entradas
	Secuencia exacta de operaciones
	Respuesta a situaciones anormales (desbordamientos, comunicaciones, recuperación de errores)
	Parámetros
	Generación de salidas
	Relaciones entre entradas y salidas (secuencias de entradas y salidas, formulas para la conversión de información)
	Especificación de los requisitos lógicos para la información que será  almacenada en base de datos (tipo de información, requerido)

Las requisitos funcionales pueden ser divididos en sub-secciones.

3.3	Requisitos no funcionales

3.3.1	Requisitos de rendimiento

Alto rendimiento de procesamiento, lee las huellas en solamente un segundo permitiendo el acceso a través de la comprobación de la huella dactilar, soportando el acceso simultaneo de usuarios conectados.

3.3.2	Seguridad

La seguridad viene dada de la verificación de huella dactilar registrada en el sistema junto con la del docente al momento de presionar el lector.

3.3.3	Fiabilidad

Especificación de los factores de fiabilidad necesaria del sistema. Esto se expresa generalmente como el tiempo entre los incidentes permisibles, o el total de incidentes permisible.

3.3.4	Disponibilidad
Su uso es rápido, no se cae.

3.3.5	Mantenibilidad

Es perdurable en el tiempo

3.3.6	Portabilidad

Uso de lenguaje .NET para cualquier plataforma que soporte Microsoft.
Para plataforma .NET se utiliza Visual Studio 2010 proveniente de Microsoft.
Sistema Operativo desde Windows XP hacia adelante.

3.4	Otros requisitos

(NA).

4     Apéndices

El software propiamente tal ya existe en el mercado, por tanto, sería factible comprar la solución e integrar.