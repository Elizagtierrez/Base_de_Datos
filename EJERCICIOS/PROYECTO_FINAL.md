# Proyecto Final de base de datos.
### Indicaciones de lo que se debe realizar

● Diseña el modelo entidad-relación del siguiente problema.

● Crea el script para la base de datos.
Proveedores

Tenemos que diseñar una base de datos sobre proveedores y disponemos de
la siguiente información:

● De cada proveedor conocemos su nombre, dirección, ciudad, provincia y
un código de proveedor que será único para cada uno de ellos.

● Nos interesa llevar un control de las piezas que nos suministra cada
proveedor. Es importante conocer la cantidad de las diferentes piezas
que nos suministra y en qué fecha lo hace. Tenga en cuenta que un
mismo proveedor nos puede suministrar una pieza con el mismo código
en diferentes fechas. El diseño de la base de datos debe permitir
almacenar un histórico con todas las fechas y las cantidades que nos ha
proporcionado un proveedor.

● Una misma pieza puede ser suministrada por diferentes proveedores.

● De cada pieza conocemos un código que será único, nombre, color,
precio y categoría.

● Pueden existir varias categorías y para cada categoría hay un nombre y
un código de categoría único.

● Una pieza sólo puede pertenecer a una categoría.

PROVEDOR:codigo_provedor,nombre, dirección, ciudad, provincia
SUMINISTRO:id_suministro, fecha, cantidad
PIEZA:codigo_pieza, nombre, color, precio
CATEGORIA:codigo_categoria, nombre de categoria

![image](https://user-images.githubusercontent.com/90996552/172239858-b8fd101a-4c35-4dc5-a53a-b5290194f837.png)

https://www.db-fiddle.com/f/2eY8fE64DpswZtbbda6ZpU/0

