
## Práctica 4
### Data warehouse

Objetivo: Demostrar la identificación de los elementos que componen data warehouse y
su esquema

Ejercicio:

1. ¿Qué es un DataWarehouse?(valor 2)

Data warehouse es un sistema que agrega y combina información de diferentes fuentes en un almacén de datos único y centralizado; consistente para respaldar el análisis empresarial, la minería de datos, inteligencia artificial y Machine Learning. Data warehouse permite a una organización o empresa ejecutar análisis potentes en grandes volúmenes petabytes y petabytes de datos históricos de formas que una base de datos estándar simplemente no puede.

2. Realiza un diseño del modelo en estrella (valor 2)

![image](https://user-images.githubusercontent.com/90996552/171663070-ba9ed514-a016-4aeb-acd2-81a4d81a5db8.png)


3. Realiza un diseño del modelo copo de nieve (valor 2)

![image](https://user-images.githubusercontent.com/90996552/171747714-74aa305d-d5f6-47e0-86b6-3232f5b48ff5.png)



## Práctica 7
### Funciones en SQL
Objetivo: Demostrar el uso y aplicación en una base de datos para mejorar la gestión

Ejercicio:

1. Calcula el número total de productos que hay en la tabla productos. (valor 4.5)

![image](https://user-images.githubusercontent.com/90996552/171750699-61f41827-cdf7-4483-890c-259724d75971.png)

![image](https://user-images.githubusercontent.com/90996552/171750768-0f79b203-c01e-4fac-a3e5-9721547ef2c8.png)

2. Muestra el número total de productos que tiene cada uno de los fabricantes. El listado
también debe incluir los fabricantes que no tienen ningún producto. El resultado
mostrará dos columnas, una con el nombre del fabricante y otra con el número de
productos que tiene. Ordene el resultado descendentemente por el número de
productos. (valor 4.5)

![image](https://user-images.githubusercontent.com/90996552/171751179-6896172f-5901-4493-ad74-8ea97899809b.png)

![image](https://user-images.githubusercontent.com/90996552/171751295-34dd982a-c244-44be-995d-58d275d21d6d.png)



3. Muestra el precio máximo, precio mínimo y precio medio de los productos de cada
uno de los fabricantes. El resultado mostrará el nombre del fabricante junto con los
datos que se solicitan. (valor 4.5)

![image](https://user-images.githubusercontent.com/90996552/171751577-4730d7c6-3c5e-4efc-9714-0c667bd13dc8.png)

![image](https://user-images.githubusercontent.com/90996552/171751711-4dca3db3-ea5b-4745-90a2-14282f159a85.png)


4. Muestra el nombre de cada fabricante, junto con el precio máximo, precio mínimo,
precio medio y el número total de productos de los fabricantes que tienen un precio
medio superior a 200€. Es necesario mostrar el nombre del fabricante. (valor 4.5)

![image](https://user-images.githubusercontent.com/90996552/171751943-637b477e-913b-4e42-99c2-f9b3310e52f8.png)

![image](https://user-images.githubusercontent.com/90996552/171751909-de3b717f-cc25-49f1-ad0b-6ab42e9d3bcd.png)

https://www.db-fiddle.com/f/aoMPqbEVc4tDarFwDNZdcQ/1


## Práctica 8.
### Disparadores (Triggers)

Objetivo: Demostrar las operaciones que se realizan en una base de datos.

Ejercicio: Crea una base de datos llamada test que contenga una tabla llamada
alumnos con las siguientes columnas. (valor 18)

Evaluación:

Creación de la base de datos : 9 puntos.

Creación de los Disparadores(Triggers): 9 puntos.

Tabla alumnos:

● id (entero sin signo)

● nombre (cadena de caracteres)

● apellido1 (cadena de caracteres)

● apellido2 (cadena de caracteres)

● nota (número real)

Una vez creada la tabla escriba dos triggers con las siguientes características:

● Trigger 1: trigger_check_nota_before_insert

  o Se ejecuta sobre la tabla alumnos.
  
  o Se ejecuta antes de una operación de inserción.
  
  o Si el nuevo valor de la nota que se quiere insertar es negativo, se guarda
  como 0.
  
  o Si el nuevo valor de la nota que se quiere insertar es mayor que 10, se
  guarda como 10.
  
  ![image](https://user-images.githubusercontent.com/90996552/171910308-7bfcf7cc-730c-4edd-8ebf-4ded65f22b79.png)


● Trigger2 : trigger_check_nota_before_update
  o Se ejecuta sobre la tabla alumnos.
  
  o Se ejecuta antes de una operación de actualización.
  
  o Si el nuevo valor de la nota que se quiere actualizar es negativo, se guarda
  como 0.
  
  o Si el nuevo valor de la nota que se quiere actualizar es mayor que 10, se
  guarda como 10.
  
  ![image](https://user-images.githubusercontent.com/90996552/171910382-ebae8bb8-cfb6-48df-b900-f652e3589839.png)

  
Una vez creados los triggers escribe varias sentencias de inserción y actualización
sobre la tabla alumnos y verifica que los triggers se están ejecutando
correctamente.

https://www.db-fiddle.com/f/oiebs96PHUbFeFYtFjD1e9/0
