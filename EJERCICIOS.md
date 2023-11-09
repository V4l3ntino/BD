
1. __¿Qué es un SI?, componentes__
	Es un conjunto de procesos que trabajan juntos para gestionar datos importantes con el fin de proporcionar a una organización la información necesaria para alcanzar sus metas. Sus componentes:
		- Datos
		- Software y Hardare
		- Recursos humanos (usuarios, Administrador)
2. __Cita las ventajas e inconvenientes de los Sistemas de ficheros__
		**Ventajas**
	
	- Programas eficientes.
	- Programas independientes.
	
	**Inconvenientes.**
	
	- Aislamiento de datos, siendo difícil obtener a la vez toda la información relativa a un mismo objeto.
	- Problemas de redundancia.
3. __Cita las ventajas e inconvenientes surgidos con el uso de BD y sistemas de BD.__
		**Ventajas**
	
	- Integridad y coherencia de datos
	- Redundancia menor
	- Menor espacio almacenado con datos duplicados
	- Independencia entre los datos y los programas que lo utilizan
	- Aumento de la seguridad
	
	**Inconvenientes**
	
	- El personal debe estar especializado en el uso de BD
	- El desembolso inicial es elevado.
4. __Indique las diferencias entre sistemas de de ficheros y sistemas de BD__
	El sistema de ficheros se organiza en una estructura descentralizada mientras que el sistema de BD tiene una ustructura centralizada.
5. __¿Qué es un SGBD?__
	Un SGBD es el software que permite a los usuarios definir, crear y mantener la base de datos garantizando el acceso controlado y la integridad de los datos.
6. Servicios proporcionados por el SBGD
	- **Definición y creación de la base de datos**: Describe la estructura, tipos de datos, restricciones, etc. **_Utilizando para ello el lenguaje de definición de datos (LDD)._**
	- **Manipulación de los datos**: la información almacenada debe poder manipularse cuando se precise actualizar o consultar los datos existentes. Para esto **_utiliza el lenguaje de manipulación de datos (LMD)_**
	- **Acceso controlado a la base de datos**: garantiza en todo momento
	    - La integridad de los datos
	    - La seguridad de los datos
	- **Recuperación de los datos**
7. Describe los niveles externo, conceptual y físico de una base de datos
		Los niveles de una base de datos son:
	
	1. Nivel Externo: Se centra en cómo los usuarios interactúan con la base de datos y proporciona vistas personalizadas para diferentes usuarios.
	    
	2. Nivel Conceptual: Define la estructura lógica de la base de datos, como tablas y relaciones, sin preocuparse por la implementación física.
	    
	3. Nivel Físico: Trata la implementación concreta de la base de datos en hardware y software, incluyendo almacenamiento, rendimiento y seguridad.
9. Cita los inconvenientes del modelo jerárquico
	- Rigidez en la estructura de datos
	- Falta de flexibilidad para cambios
	- Dificultad en la realización de consultas y navegación
	- Redundancia de datos

10. Explique las funciones del administrador de la BD.
	 Mantener un control centralizado de los datos, diseñar la estructura de la BD, definir quién puede acceder a qué información, crear métodos de acceso y asegurarse de que todo funcione de manera eficiente.

### Modelo de datos en red
Los datos se representan como registros que están unidos mediante punteros o enlaces

### Modelo de datos jerárquico
Los registros están conectados entre sí mediante enlaces y se organizan por ramas.

### Modelos de datos relacional
Los datos se representan mediante tablas y cada tabla se identifica de manera única por un atributo denominado clave primaria, las tablas se relacionan entre sí por otro atributo llamado clave ajena.

### Modelo orientado a objetos
Se basa en una colección de objetos que se comunican entre sí por medio de mensajes. Dichos objetos tienen las siguientes características:
	- Los objetos a nivel conceptual son equivalentes a las entidades.
	- Un objeto está definido por un conjunto de propiedades que se denominan atributos.
	- El código que se utiliza para implementar los mensajes se denomina método. Éste devuelve un valor como respuesta al mensaje
	- Los objetos que tienen los mismos valores y los mismos métodos se agrupan en clases.
	- Todo objeto se identifica de manera única mediante una característica que se denomina identificador de objeto.

## Diferencias entre los modelos

En el modelo jerárquico y en el modelo en red los datos se representan mediante registros y las relaciones entre ellos mediante enlaces. La diferencia entre ellos está en que el primero utiliza para ello árboles y el segundo grafos.
En el modelo relacional, debido a que los datos y las relaciones se representan mediante tablas, la organización de la información de esta manera resulta muy flexible y ha propiciado la construcción de interfaces de manejo sencillo y de lenguajes de consulta, lo cuál ha contribuido para que este modelo sea uno de los más utilizados.
El modelo orientado a objetos proporciona algunas ventajas sobre el relacional, como la representación de tipos de datos complejos como imágenes o el acceso a los datos pero tiene una desventaja importante y es que el modelo no está totalmente desarrollado.

18. Realiza un breve resumen de las arquitecturas utilizadas para implantar el SGBD
	__Arquitectura centralizada__: El sistema gestor de base de datos está implantado en un solo ordenador y desde ahí controla todos los recursos.
	__Arquitectura cliente/servidor__:Se basa en un grupo de ordenadores conectados entre sí, uno servidor y resto clientes.
	__Arquitectura distribuida__: el SGBD y la base de datos no están asociados a un determinado ordenador sino a la red, en la cuál sus componentes se reparten las funciones.


20. __Describe Modelo de datos y la relación existente entre modelo de datos y el SGBD__
	El modelo de datos es una representación abstracta de la estructura de una base de datos, mientras que el Sistema de Gestión de Bases de Datos (SGBD) es el software que implementa y administra esa estructura.