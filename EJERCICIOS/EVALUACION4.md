## 7. Triggers en SQL
1.- Qué es in TRIGGER?

Un trigger o disparador es un script que se usa en lenguaje de programación SQL, en especial en bases de datos como MySQL o PostgreSQL.Consiste en una serie de reglas predefinidas que se asocian a una tabla. Estas reglas se aplican a la base de datos cuando se realizan determinadas operaciones en la tabla, por ejemplo, al añadir, actualizar o eliminar registros. Dicho de otra manera, el trigger desencadena determinadas acciones de forma automática en las tablas de la base de datos cuando se insertan, modifican y se añaden nuevos datos

2.- Cuál es la función de un TRIGGER?

La principal función de los trigger es contribuir a mejorar la gestión de la base de datos. Gracias a ellos muchas operaciones se pueden realizar de forma automática. Otra de sus funciones es aumentar la seguridad e integridad de la información. Esto lo consiguen gracias a la programación de restricciones o requerimientos de verificación que permiten minimizar los errores y sincronizar la información.

3.- Cuando se puede usar un TRIGGER?

Los trigger se puede ejecutar cuando el usuario realizar alguna acción relacionada con añadir, actualizar o eliminar información de una tabla. Es decir, al usar los comandos INSERT, UPDATE o DELETE. Por tanto, para poder usar un trigger es necesario que el usuario posea permisos INSERT y DELETE e dicha base de datos.

4.- Cuáles son los dos escenarios de uso de un TRIGGER?
Los triggers tienen dos escenarios principales de uso:
El primero es cuando no podemos intervenir en el código fuente de la aplicación que trabaja sobre la base de datos sobre la que queremos actuar o reaccionar a sus eventos.
El segundo es cuando a pesar de disponer del código, éste pertenece a un software desarrollado por terceros y existe una probabilidad relativamente alta de aplicar actualizaciones o instalar pluggins, y hemos decidido modificar el código fuente lo menos posible para facilitar este tipo de tareas.
