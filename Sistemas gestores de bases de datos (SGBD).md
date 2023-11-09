
Conjunto de programas que permiten a los usuarios definir, crear y mantener la base de datos garantizando el acceso controlado y la integridad de los datos almacenados.
Actúa cómo intermediario entre los programas de aplicación utilizados por los usuarios y los datos. Ejemplo: ORACLE, MYSQL, MONGODB, CASSANDRA, SQLITE

## EL SGBD ofrece los siguientes servicios
- __Definición y creación de la base de datos__: Describe la estructura, tipos de datos, restricciones, etc. ___Utilizando para ello el lenguaje de definición de datos (LDD).___
- __Manipulación de los datos__:  la información almacenada debe poder manipularse cuando se precise actualizar o consultar los datos existentes. Para esto ___utiliza el lenguaje de manipulación de datos (LMD)___
- __Acceso controlado a la base de datos__: garantiza en todo momento
	- La integridad de los datos
	- La seguridad de los datos
- __Recuperación de los datos__

## Funciones de un SGBD
- __Función de descripción o definición__
	- El administrador  utiliza el lenguaje de definición de datos (LDD) proporcionado por el SGBD para definir la estructura de la base de datos, los métodos de acceso, y las vistas lógicas de los usuarios. Esta definición se convierte en tablas almacenadas en el diccionario de datos del sistema. Esta función abarca la descripción de los datos en cada uno de los niveles de abstracción que forman la arquitectura de la BD.
		- Nivel interno
		- Nivel conceptual
		- Nivel externo
- __Función de manipulación de datos__
	- Esta función permite a los usuarios buscar, agregar, cambiar o eliminar información almacenada, siempre siguiendo las reglas de seguridad establecidas por el administrador del sistema. Para llevar a cabo estas acciones, se utiliza un lenguaje específico llamado lenguaje de manipulación de datos (LMD).
- __Función de control o utilización__
	- Incluye las interfaces para que los usuarios se comuniquen con la base de datos y herramientas para ayudar al administrador. Esto involucra la carga de archivos, auditoría, protección contra accesos no autorizados y seguridad física, como copias de seguridad y recuperación del sistema en caso de fallos.

## Lenguaje SQL (Structured Query Language)
El lenguaje SQL (Structured Query Language) permite a los usuarios hacer preguntas al servidor y obtener respuestas. Se divide en cuatro categorías: __DML__ ***para manipulación de datos***, __DDL__ ***para definición de datos***, __DCL__ ***para control de datos*** y __TCL__ ***para control de transacciones.***

- LMD -> Lenguaje de __Manipulación__ de datos
- LDD -> Lenguaje de __Definición__ de Datos
- LCD -> Lenguaje de __Control__ de __Datos__
- LCT -> Lenguaje de __Control__ de __Transacciones__

## Base de datos NOSQL
NoSQL se destaca por su flexibilidad de esquema, escalabilidad para grandes volúmenes de datos, alto rendimiento, capacidad de manejar datos diversos y distribución eficiente. Como por ejemplo: CASSANDRA, MONGODB, NEO4J, REDIS, HBASE


