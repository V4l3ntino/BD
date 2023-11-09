

## BD Distribuida
Son un grupo de datos que pertenecen a un sistema pero a su vez esta reapartido entre ordenadores de una misma red, ya sea a nivel local o cada uno en una diferente localizacion geografica, cada sitio en la red es autónomo en sus capacidades de procesamiento y es capaz de realizar operaciones locales y en cada uno de estos ordenadores debe estar ejecutandose una aplicación a nivel global que permita la consulta de todos los datos como si se tratase de uno solo.

![[Pasted image 20231109005922.png]]

## Tipos de almacenamiento

__Replica__: El sistema conserva varias copias o réplicas idénticas de unatabla. Cada réplica se almacena en un nodo diferente.

__Fragmentación__: Es el proceso de dividir una tabla en dos subtablas y que su contenido representen la misma información que la tabla original. Esta fragentación puede ser de dos formas:
	- ___Horizontal___: Los fragmentos se definen a través de una operación de selección y se agrupa la tabla por filas a través de campos que tengan redundancia de datos
	![[Pasted image 20231109010636.png]]
	- ___Vertical___: Lo fragmentos se definen a través de una operación de proyección y se agrupa por columnas donde cada fragmento debe incluir la clave primaria de la tabla.
	![[Pasted image 20231109010705.png]]
	- ___Mixta___: es una combinación de las dos anteriores