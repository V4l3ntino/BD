Un sistema gestor de ficheros es un conjunto de programas que se utilizan para administrar información en una empresa de manera descentralizada. La información se organiza en archivos, que son conjuntos de bytes relacionados sobre un tema específico. Dentro de estos archivos, la información se divide en **registros**, que son estructuras de datos homogéneas que se refieren a la misma entidad y contienen campos de información. Las operaciones básicas que se pueden realizar en un archivo incluyen búsqueda, inserción, borrado y modificación de registros. 
Los tipos de archivos pueden ser de texto plano, que asignan un valor numérico a cada carácter y no necesitan un formato específico, o binarios, que requieren un formato para su interpretación.

**ORGANIZACIÓN DE FICHEROS**
- **Secuencial**: Los registros se almacenan consecutivamente.  A la hora de buscar un registro, los registros se leen desde el inicio hasta que se encuentre dicho registro o hasta el final sino se encuentra el registro buscado.
- **Indexado**: Permite seleccionar un registro indirectamente mediante una tabla que contiene la clave y la dirección relativa de los registros del fichero. Con este método no es necesario leer todos los registros que preceden al registro buscado.
- **Encadenado**: Cada registro contiene un puntero que permite localizar el siguiente registro.
- **Directo**:Permite seleccionar un registro directamente a partir del valor de la clave, sin necesidad de leer los que le preceden.


**Ventajas**  
- Programas eficientes.  
- Programas independientes.  

**Inconvenientes.**  
- Aislamiento de datos, siendo difícil obtener a   la vez toda la información relativa a un mismo   objeto.  
- Problemas de redundancia.

