## ORACLE - TIPOS DE DATOS

- VARCHAR2(XXX): Se emplea para almacenar cadenas de caracteres. Una cadena es una secuencia de caracteres. Se coloca entre comillas simples; ejemplo: 'Hola', 'Juan Perez', 'Colon 123'. Este tipo de dato definen una cadena de longitud variable en la cual determinamos el máximo de caracteres entre paréntesis. Puede guardar hasta xxx caracteres.

- NUMBER(p,s): Se usa para guardar valores numéricos con decimales, de 1.0 x10-120 a 9.9...(38 posiciones). Definimos campos de este tipo cuando queremos almacenar valores numéricos con los cuales luego realizaremos operaciones matemáticas, por ejemplo, cantidades, precios, etc.
Puede contener números enteros o decimales, positivos o negativos. El parámetro "p" indica la precisión, es decir, el número de dígitos en total (contando los decimales) que contendrá el número como máximo. El parámetro "s" especifica la escala, es decir, el máximo de dígitos decimales. Por ejemplo, un campo definido "number(5,2)" puede contener cualquier número entre 0.00 y 999.99 (positivo o negativo).
Para especificar número enteros, podemos omitir el parámetro "s" o colocar el valor 0 como parámetro "s". Se utiliza como separador el punto (.).

