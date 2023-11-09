Es un conjunto de conceptos y reglas que definen la estructura de una Base de Datos, los modelos se clasifican en:

- MODELO EXTERNO: representan los datos que necesita cada usuario
- MODELO GLOBAL: representan la información a nivel de empresa
	- Modelo conceptual
	- Modelo lógico
		- Modelo relacional
		- Modelo jerárquico
		- Modelo en red
		- Modelo orientado a objetos
- MODELO INTERNO: describen como se almacenan los datos en el ordenador


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

