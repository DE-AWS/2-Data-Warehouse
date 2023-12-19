# 2-Data-Warehouse
1. [Lesson 1- Exercise 1](#schema1)
2. [Lesson 1 - Exercise 2 ](#schema2)
3. [Lesson 3 - Exercise 2](#schema3)
4. [Lesson 3 - Exercise 3](#schema4)


<hr>

<a name="schema1"></a>

## 1- Lesson 1- Exercise 1

L1 E1 -Step 1 & 2.ipynb


<hr>

<a name="schema2"></a>

## 2- Lesson 1 - Exercise 2 

L1 E2 - 0 - OLAP Cubes - Solution.ipynb

<hr>

<a name="schema3"></a>

## 3- Lesson 3 - Exercise 2

L3 Exercise 2 - IaC.ipynb

Hay que crear un usuario con los permisos de admin y poner las claves que te descargas en el archivo conf del workspace
de udacity.
- Creamos clientes para IAM, EC2, S3 y Redshift 
- Creamos un role IAM que permita a Redshift acceder al depósito S3 (solo lectura)
- Creamos el cluster de Redshift.
- Abrir un puerto TCP entrante para acceder al endpoint del clúster
- Comprobamos que nos podemos conectar al cluster
- Eliminar el cluster y el role asociado a redshift

https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/redshift/client/create_cluster.html#


<hr>

<a name="schema4"></a>

## 3- Lesson 3 - Exercise 3

L3 Exercise 3 - Parallel.ipynb

Hay que tener el cluster creado del ejercicio anterior y comprobar que el archivo conf está como en el ejercicio 
anterior con las claves y secretos del rol administrador creado anteriormente.

- Conectarnos al cluster de Redshift
- Creamos las tablas
- Cargar datos particionados en el clúster
- Crear tablas para los datos no particionados
- Cargar datos no particionados en el clúster