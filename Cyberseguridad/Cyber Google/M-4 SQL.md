## SELECT
Indica que columnas va a devolver.

## From
Indica que  tabla va a consultar

## Syntax
Son el conjunto de reglas que determinan que esta bien estructurado en un lenguaje de computación.

## **ORDER BY (ordenar por)**

Las tablas de bases de datos suelen ser muy complicadas, y por ello resultan útiles otras palabras clave de SQL. ORDER BY es una palabra clave importante para organizar los datos que extraes de una tabla.

ORDER BY ordena en secuencia los registros devueltos por una consulta con base en una o más columnas especificadas. Este orden puede ser ascendente o descendente.

**Orden ascendente**

Para usar la palabra clave ORDER BY, escríbela al final de la consulta y especifica una columna en la que se basará el orden. En este ejemplo, SQL devolverá las columnas customerid (ID del cliente), city (ciudad) y country (país) de la tabla customers (clientes), así como los registros se mostrarán secuencialmente en función de la columna city (ciudad):
``SELECT customerid, city, country

``FROM customers

``ORDER BY city;

La palabra clave ORDER BY ordena los registros en función de la columna especificada después de esta palabra clave. Por defecto, como se muestra en este ejemplo, la secuencia estará en orden ascendente. Esto significa que:

- si eliges una columna que contiene datos numéricos, esta organiza los resultados de menor a mayor. Por ejemplo, si organizas en función de customerid (ID del cliente), los números de identificación se ordenan de menor a mayor.
    
- si la columna contiene caracteres alfabéticos, como en el ejemplo con la columna city (ciudad), esta organiza los registros de la A a la Z. 
    

**Orden descendente**

También puedes usar ORDER BY con la palabra clave DESC para ordenar los datos en sentido descendente. La palabra clave DESC es la abreviatura de “descendente”, e indica a SQL que ordene los números de mayor a menor o, en el caso de caracteres alfabéticos, de la Z a la A. Para hacerlo, después de ORDER BY, escribe la palabra clave DESC. A modo de ejemplo, puedes ejecutar esta consulta para observar cómo se diferencian los resultados cuando aplicas DESC:
``SELECT customerid, city, country

``FROM customers

``ORDER BY city DESC;

Ahora, aparecen primero las ciudades que comienzan con las últimas letras del alfabeto. 

**Ordenar en función de varias columnas**

Adicionalmente, puedes elegir varias columnas en las que basar el orden. Por ejemplo, primero puedes elegir la columna country (país) y luego, la columna city (ciudad). A continuación, SQL ordena los resultados en función de la columna country (país) y, en el caso de que haya filas con el mismo valor de country (país), las organiza en función de la columna city (ciudad). Puedes practicar este ejemplo para averiguar cómo SQL muestra esto:
``SELECT customerid, city, country

``FROM customers``

``ORDER BY country, city;``

# Practica
![[Pasted image 20231109104103.png]]
![[Pasted image 20231109104157.png]]
![[Pasted image 20231109104415.png]]
![[Pasted image 20231109104523.png]]
![[Pasted image 20231109104722.png]]
![[Pasted image 20231109104847.png]]
![[Pasted image 20231109104952.png]]
![[Pasted image 20231109105135.png]]
![[Pasted image 20231109105317.png]]


## Filtering
Selecting data that match a certain condition.

## Operator
A symbol or keyword that represents an operation.
country = 'USA'


## WHERE
Indicates the condition for a filter.
![[Pasted image 20231109110416.png]]

![[Pasted image 20231109110436.png]]

## **%**
Para buscar un patron, usamos el signo %, que es el comodín de caracteres no especificados. no se puede utilizar el operador *=* en su lugar se utiliza el operador *LIKE*
![[Pasted image 20231109110658.png]]
Devuelve todos los registros que empiezan con EAST

## *LIKE*
Usado con WHERE  se utiliza para buscar un patron en una columna.
![[Pasted image 20231109110927.png]]


## **Filtrado por patrones**

También puedes filtrar en función de un patrón. Por ejemplo, puedes identificar las entradas que comienzan o terminan con uno o varios caracteres determinados. Filtrar en función de un patrón te exige incorporar dos elementos más en tu cláusula WHERE:

- un comodín 
    
- el operador LIKE
    

**Comodines**

Un **comodín** es un carácter especial que se puede sustituir por cualquier otro carácter. Dos de los comodines más útiles son el signo de porcentaje (%) y el guion bajo (_):

- El signo de porcentaje puede sustituir cualquiera de los demás caracteres. 
    
- El símbolo de guion bajo solo puede sustituir uno de los demás caracteres.
    

Puedes colocar estos comodines después de una cadena, antes de una cadena o en ambas ubicaciones, dependiendo del patrón según el cual estás filtrando.

La tabla siguiente incluye estos comodines aplicados a la cadena 'a' y ejemplos de los resultados que devolverá cada patrón.

|**Patrón**|**Resultados que puede devolver**|
|---|---|
|'a%'|apple123, art, a|
|'a_'|as, an, a7|
|'a__'|ant, add, a1c|
|'%a'|pizza, Z6ra, a|
|'_a'|ma, 1a, Ha|
|'%a%'|Again, back, a|
|'_a_'|Car, ban, ea7|

**LIKE (como)**

Para aplicar comodines al filtro, debes usar el operador LIKE en lugar de un signo igual (=). LIKE se usa con WHERE para buscar un patrón en una columna. 

Por ejemplo, si quieres enviar un correo electrónico a empleados/as con el cargo 'IT Staff' (personal de TI) o 'IT Manager' (gerente de TI), puedes usar el operador LIKE combinado con el comodín %:


`SELECT lastname, firstname, title, email

`FROM employees

`WHERE title LIKE 'IT%';

EjecutarRestablecer

Esta consulta devuelve todos los registros con valores en la columna title (cargo) que comienzan con el patrón de 'IT'. Esto significa que se devuelve tanto 'IT Staff' (personal de TI) como 'IT Manager' (gerente de TI).

Como ejemplo adicional, si quieres buscar en la tabla de facturas a todos/as los/las clientes ubicados en estados con la abreviatura 'NY', 'NV', 'NS' o 'NT', puedes usar el patrón 'N_' en la columna state (estado):

`SELECT firstname,lastname, state, country

`FROM customers

`WHERE state LIKE 'N_';

# Practica
![[Pasted image 20231109111312.png]]![[Pasted image 20231109112022.png]]
![[Pasted image 20231109112458.png]]
![[Pasted image 20231109112533.png]]
![[Pasted image 20231109112809.png]]

![[Pasted image 20231109112951.png]]![[Pasted image 20231109113138.png]]

## BETWEEN
Es un  operador que filtra números o fechas dentro de un intervalo.

![[Pasted image 20231109123606.png]]

# Practica

![[Pasted image 20231109123759.png]]![[Pasted image 20231109123907.png]]
![[Pasted image 20231109123948.png]]
![[Pasted image 20231109124054.png]]
![[Pasted image 20231109124335.png]]
![[Pasted image 20231109124552.png]]![[Pasted image 20231109124739.png]]
![[Pasted image 20231109124840.png]]
## *AND*
El operador AND especifica que ambas condiciones deben de cumplirse.
![[Pasted image 20231109194937.png]]
**AND (y)**

En primer lugar, AND se usa para filtrar por dos condiciones. AND especifica que se deben satisfacer ambas condiciones de manera simultánea. 

A modo de ejemplo, una inquietud de ciberseguridad puede afectar solo a aquellas cuentas de clientes que cumplen la condición de ser gestionadas por un/a representante de soporte con una ID de 5 y la condición de estar ubicadas en EE.UU. Para encontrar los nombres y correos electrónicos de esos/as clientes específicos/as, debes colocar las dos condiciones a cada lado del operador AND en la cláusula WHERE:
## *OR*
Indica que cualquiera de las dos condiciones debe cumplirse.
![[Pasted image 20231109195109.png]]
**OR (o)**

El operador OR también vincula dos condiciones, pero OR especifica que se puede satisfacer cualquiera de las dos. Este devuelve resultados que satisfacen la primera condición, la segunda condición o ambas.

Por ejemplo, si eres responsable de encontrar a todos/as los/las clientes que se encuentran en EE.UU. o Canadá para informarles sobre una actualización de seguridad, puedes usar un operador OR para buscar todos los registros necesarios. Como lo demuestra la consulta siguiente, puedes colocar dos condiciones a cada lado del operador OR en la cláusula WHERE:
## *NOT*
Niega una condición.
![[Pasted image 20231109195253.png]]
**NOT (no)**

A diferencia de los dos operadores anteriores, el operador NOT solo funciona con una sola condición y no con varias. El operador NOT niega una condición. Esto significa que SQL devuelve todos los registros que no coinciden con la condición especificada en la consulta. 

Por ejemplo, si un problema de ciberseguridad no afecta a clientes en EE.UU. pero puede afectar a clientes en otros países, puedes obtener como resultado todos/as los/las clientes que no se encuentren en EE.UU. Esto resulta más eficiente que crear condiciones individuales para todos los demás países. Para usar el operador NOT en esta tarea, escribe la siguiente consulta y escribe NOT directamente después de WHERE:


**Consejo profesional:** Otra manera de encontrar valores que no son iguales que cierto valor es usar el operador <> o el operador !=. Por ejemplo, WHERE country <> 'USA' y WHERE country != 'USA' son filtros iguales que WHERE NOT country = 'USA'.

## **Combinación de operadores lógicos**

Los operadores lógicos se pueden combinar en filtros. Por ejemplo, si sabes que tanto EE.UU. como Canadá no se vieron afectados por un incidente de ciberseguridad, puedes combinar operadores para obtener clientes en todos los países excepto estos dos. En la consulta siguiente, NOT se coloca antes de la primera condición, se combina con una segunda condición con AND y luego también se coloca NOT antes de esa segunda condición. Puedes ejecutarla para revisar los resultados:
`SELECT firstname, lastname, email, country

`FROM customers

`WHERE NOT country = 'Canada' AND NOT country = 'USA';
# Practica
![[Pasted image 20231109195632.png]]
![[Pasted image 20231109200012.png]]
![[Pasted image 20231109200328.png]]
![[Pasted image 20231109200538.png]]
![[Pasted image 20231109202049.png]]![[Pasted image 20231109202836.png]]![[Pasted image 20231109203123.png]]
## Actividad
![[Pasted image 20231109203358.png]]

## *INNER JOIN*
Una combinación interna devuelve filas que coinciden en una columna especificada que existe en más de una tabla.

![[Pasted image 20231109224048.png]]

![[Pasted image 20231109224251.png]]
![[Pasted image 20231109224408.png]]

## *LEFT JOIN*
Devuelve todos los registros de la primera tabla, pero solo devuelve filas de la segunda tabla que coinciden con una columna especificada.

![[Pasted image 20231109224724.png]]
SELECT *

FROM employees

LEFT JOIN machines ON employees.device_id = machines.device_id;

## *RIGHT JOIN*
Devuelve solo los registros de la segunda tabla, pero solo filas de la primera fila que coinciden con una columna especificada.

![[Pasted image 20231109224911.png]]
SELECT *

FROM employees

RIGHT JOIN machines ON employees.device_id = machines.device_id;

## *FULL OUTER JOIN*
Devuelve los registros de ambas tablas
![[Pasted image 20231109225014.png]]SELECT *

FROM employees

FULL OUTER JOIN machines ON employees.device_id = machines.device_id;

# Practica
![[Pasted image 20231109225317.png]]
![[Pasted image 20231109225524.png]]
![[Pasted image 20231109225739.png]]
![[Pasted image 20231109225830.png]]
![[Pasted image 20231109230200.png]]

## **Funciones de agregado**

En SQL, las **funciones de agregado** son funciones que realizan un cálculo en varios puntos de datos y devuelven el resultado de este. No devuelven los datos en sí. 

Existen diversas funciones de agregado que realizan distintos cálculos:

- COUNT devuelve un solo número que representa la cantidad de filas devueltas por tu consulta.
    
- AVG devuelve un solo número que representa el promedio de los datos numéricos en una columna.
    
- SUM devuelve un solo número que representa la suma de los datos numéricos en una columna. 
    

**Sintaxis de las funciones de agregado**

Para usar una función de agregado, coloca la palabra clave para está después de la palabra clave SELECT y luego, entre paréntesis, indica la columna en la que deseas realizar el cálculo.

Por ejemplo, cuando trabajas con la tabla customers (clientes), puedes usar las funciones de agregado para resumir información importante acerca de la tabla. Si quieres averiguar cuántos/as clientes hay en total, puedes usar la función COUNT en cualquier columna y SQL devolverá el número total de registros, excepto los valores NULL (nulos). Puedes ejecutar esta consulta y analizar sus resultados:
`SELECT COUNT(firstname)`

`FROM customers;`
El resultado es una tabla con una columna titulada COUNT(firstname) y una fila que indica el recuento.

Si quieres obtener el número de clientes de un país específico, puedes agregar un filtro a tu consulta:
`SELECT COUNT(firstname)`

`FROM customers`

`WHERE country = 'USA';`