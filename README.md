# 1º : Definición de las relaciones y 5 ejemplos de c/u

Las relaciones indican como van a interactuar dos tablas.
Dentro de una base de datos existen 3 tipos de relaciones:

### - uno a uno
Para establecer la relación colocamos la llave primaria de una tabla como llave foránea en la tabla a la que queremos hacer referencia.


##### Ejemplo:

uno | uno
------------ | -------------
Persona | Dirección
Auto | Patente
Provincia | Ciudad
Usuario | Email
Autor | Libro


### - uno a muchos
La tabla que tenga cardinalidad uno le sede la llave primaria a la tabla que tenga cardinalidad muchos como llave foránea.


##### Ejemplo:

uno | muchos
------------ | -------------
DNI | Personas
Empleado | Empresa
Profesor | Curso
País | Habitantes
Avión | Pasajeros


### - muchos a muchos
En este tipo de relaciones se utiliza una tabla intermedia (tabla pivot). Esta tabla tiene como mínimo 3 datos: una llave primaria (PK) y dos llaves foráneas (FK), las cuales hacen referencia a cada llave primaria de las tablas relacionadas. 


##### Ejemplo:

muchos | muchos
------------ | -------------
Actores | Películas
Clientes | Productos
Estudiantes | Materias
Usuarios | Publicaciones
Empleados | Tareas


# 2º : Investigar que es un SGBD (cuales son los mas famosos)

Un SGBD (Sistema Gestor de Base de Datos) es un software que accede, extrae y administra los datos guardados en una base de datos, los usuarios accedan a esta información usando herramientas específicas de consulta y generalmente se accede a los datos mediante lenguajes de consulta como lo es SQL (Structured Query Language).

Es importante saber que un SGBD y una base de datos no son lo mismo, una base de datos está conformada de datos en forma estructurada y el SGBD es una herramienta para materializar la base de datos y su estructura.

## Los más famosos son:
* Microsoft Access
* Microsoft SQL Server
* MySQL
* Oracle Database

# 3º : En que se diferencian las bases de datos relacionales y las no relacionales

Las bases de datos relacionales se basan en la organización de la información en partes pequeñas que se integran mediante identificadores; a diferencia de las bases de datos no relacionales que, como su nombre lo indica, no tienen un identificador que sirva para relacionar dos o más conjuntos de datos.
