# CONVERSOR DE MONEDAS
## Etapa 01. Descripcion del Problema 
Se requiere un programa en Java para convertir una cantidad de dinero en otros tipos de monedas (al menos a cinco tipos de monedas distintas)

## Etapa 02. Definicion de la Solucion
 ~~~
-Entrada
 float cantidad
 String moneda1, moneda2, moneda3, moneda4, moneda5
 double conversion
 
-Proceso
 Solicitar moneda a convertir
 Solicitar cantidad a convertir
 Solicitar moneda para procesar conversion
 
 Si la cantidad es mayor o igual que cero, entonces se convertira a la moneda deseada 
 Si la cantidad es menor que cero entonces se cancela la operacion
 
 
-Salida
+--------+-------------+-------------------+--------------+
|CANTIDAD|MONEDA ORIGEN|CANTIDAD CONVERTIDA|MONEDA DESTINO|
+--------+-------------+-------------------+--------------+
|   10   |     DLLS    |         189.79    |     MXN      |
+--------+-------------+-------------------+--------------+
+--------+-------------+-------------------+--------------+
|   10   |     DLLS    |        0.00043    |     BTC      |
+--------+-------------+-------------------+--------------+
+--------+-------------+-------------------+--------------+
|   10   |     DLLS    |         189.79    |     MXN      |
+--------+-------------+-------------------+--------------+
~~~
 ## Etapa 03. Diseño de la Solucion 
 
 ![](https://github.com/rigo1012/Ejercicio1/blob/main/Diagrama%20de%20clases.png)
 
 ## Etapa 04. Desarrollo de la Solucion
