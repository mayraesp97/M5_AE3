# Ejercicio Individual: Base de Datos de Clientes y Pedidos

Este repositorio contiene la solución al ejercicio individual de SQL, diseñado para practicar la creación de tablas, inserción de datos y consultas de diversa complejidad.

## 
* **[Escribe tu nombre aquí]**

## 
* **Curso:** [Nombre de tu curso o asignatura]
* **Profesor:** [Nombre de tu profesor/a]
* **Fecha:** [Fecha de hoy]

---

## 
Este proyecto consiste en un único archivo `.sql` que resuelve una serie de requerimientos prácticos sobre un modelo de datos de Clientes y Pedidos.

### Contenido del Script (`.sql`)

El archivo SQL incluye los siguientes pasos en orden:

1.  **Creación de Tablas:**
    * `CREATE TABLE clientes`: Crea la tabla para almacenar datos de clientes.
    * `CREATE TABLE pedidos`: Crea la tabla para pedidos, vinculada a `clientes` mediante una Llave Foránea (FK).
    * Se utiliza `ON DELETE CASCADE` en la llave foránea para cumplir con el requisito de eliminación en cascada.

2.  **Inserción de Datos:**
    * `INSERT INTO clientes`: Se añaden 5 clientes de ejemplo.
    * `INSERT INTO pedidos`: Se añaden 10 pedidos de ejemplo, asignados a los clientes creados.

3.  **Consultas (Queries):**
    * **Q1:** Proyectar todos los clientes y sus pedidos (usando `LEFT JOIN`).
    * **Q2:** Proyectar pedidos de un cliente específico por ID (usando `WHERE`).
    * **Q3:** Calcular el total gastado por cada cliente (usando `SUM` y `GROUP BY`).
    * **Q4:** Actualizar la dirección de un cliente (usando `UPDATE`).
    * **Q5:** Eliminar un cliente y sus pedidos asociados (usando `DELETE`).
    * **Q6:** Proyectar los 3 clientes con más pedidos (usando `COUNT`, `GROUP BY`, `ORDER BY` y `LIMIT`).

### Cómo Utilizar

Para probar este ejercicio, puedes ejecutar el script `.sql` en cualquier motor de base de datos compatible con SQL (como MySQL, PostgreSQL, o un entorno online). Las consultas están separadas por comentarios que indican el requisito que resuelven.
