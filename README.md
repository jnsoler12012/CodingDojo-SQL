# Bootcamp Coding Dojo Java - SQL activity

<p align="center">
<img src="https://github.com/jnsoler12012/CureCore-website-GitPage/assets/63087709/cdcffdd2-28a1-4499-b58c-45df86427ecc">
</p>

Actividad requerida por Coding Dojo para la complencion de el programa


# Repositorio de Comandos SQL para Relaciones Avanzadas

Este repositorio contiene una serie de comandos SQL diseñados para aprender y comprender conceptos avanzados de relaciones en bases de datos, incluyendo relaciones uno a uno, uno a muchos y otros conceptos relacionados. Los comandos están diseñados para ser utilizados con sistemas de gestión de bases de datos relacionales como MySQL, PostgreSQL, SQLite, entre otros.

## Contenido

- [Bootcamp Coding Dojo Java - SQL activity](#bootcamp-coding-dojo-java---sql-activity)
- [Repositorio de Comandos SQL para Relaciones Avanzadas](#repositorio-de-comandos-sql-para-relaciones-avanzadas)
  - [Contenido](#contenido)
  - [Relaciones Uno a Uno](#relaciones-uno-a-uno)
      - [Ejemplo 2: Actualizar Datos en Relación Uno a Uno](#ejemplo-2-actualizar-datos-en-relación-uno-a-uno)
    - [Relaciones Uno a Muchos](#relaciones-uno-a-muchos)
  - [Otros Conceptos Avanzados](#otros-conceptos-avanzados)
      - [Instrucciones de Uso](#instrucciones-de-uso)
  - [Contribuciones](#contribuciones)

---



En esta sección, encontrarás comandos SQL específicos para comprender y trabajar con relaciones uno a uno en bases de datos relacionales.

## Relaciones Uno a Uno

```sql
-- Obtener datos de dos tablas relacionadas
SELECT *
FROM tabla1
JOIN tabla2 ON tabla1.id = tabla2.id;
```

#### Ejemplo 2: Actualizar Datos en Relación Uno a Uno
```sql
-- Actualizar datos en relación uno a uno
UPDATE tabla1
SET columna = valor
WHERE id = 1;
```

### Relaciones Uno a Muchos

```sql
-- Consulta de datos con relación uno a muchos
SELECT *
FROM cliente
JOIN orden ON cliente.id = orden.cliente_id;
```

## Otros Conceptos Avanzados

Esta sección incluye comandos SQL para otros conceptos avanzados relacionados con bases de datos, como subconsultas, transacciones, etc.

```sql
-- Subconsulta para filtrar resultados
SELECT columna
FROM tabla
WHERE columna IN (SELECT columna FROM otra_tabla WHERE condicion);
```

#### Instrucciones de Uso

1. Clona este repositorio en tu máquina local.
2. Importa los comandos SQL en tu sistema de gestión de bases de datos.
3. Explora y modifica los comandos según tus necesidades de aprendizaje.

## Contribuciones

Siéntete libre de contribuir a este repositorio. Si tienes ejemplos adicionales, correcciones o mejoras, ¡abre un pull request!