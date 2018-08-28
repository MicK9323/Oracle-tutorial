## ORACLE - TABLAS

### Crear tabla
La sintaxis básica para crear tablas en Oracle es la siguiente:

~~~
create table NOMBRETABLA(
  NOMBRECAMPO1 TIPODEDATO,
  ...
  NOMBRECAMPON TIPODEDATO
 );
~~~

Si queremos ver un listado de todas las tablas existentes se puede hacer uso del comando:

~~~
select * from all_tables;
select * from tabs;
~~~

Para ver la estructura de una tabla se usa el comando describe junto al nombre de la tabla.

~~~
describe NOMBRETABLA;
~~~

### Eliminar tablas
Para eliminar una tabla usamos el comando

~~~
drop table NOMBRETABLA;
~~~

### Insertar datos en una tablas
Al ingresar los datos de cada registro debe tenerse en cuenta la cantidad y el orden de los campos.

La sintaxis básica y general es la siguiente:
~~~
insert into NOMBRETABLA (NOMBRECAMPO1, ..., NOMBRECAMPOn)
  values (VALORCAMPO1, ..., VALORCAMPOn);
~~~
