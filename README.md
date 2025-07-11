# SQL_Grupo_3
Proyecto SQL  para viernes 11 de Julio

# 📊 Proyecto de Creación de Base de Datos Relacional - Bootcamp

Este proyecto consiste en la creación de una base de datos relacional a partir de un conjunto de datos no normalizados correspondientes a estudiantes y profesores de una escuela de bootcamps.

---

## 🧠 Objetivo

Diseñar e implementar una base de datos escalable y funcional en PostgreSQL, aplicando procesos de normalización, modelado E/R y modelado lógico, para representar correctamente la estructura de la información de estudiantes, promociones, campus y proyectos evaluativos.

---

## 👥 Equipo

Este trabajo ha sido desarrollado por estudiantes del curso de **Data Science** y **Full Stack**:

- Ana Gutiérrez Méndez *(Data Science)*
- Laura Smichowski *(Full Stack)*
- Jaime Garcia *(Data Science)*
- Rufino Muñoz Ovilla *(Data Science)*
- Eduardo Limones *(Data Science)*

---

## 📦 Datos de Entrada

Los datos originales contienen información como:

- Nombre del estudiante
- Email
- Promoción
- Fecha de comienzo
- Campus
- Resultados de distintos proyectos: HLF, EDA, BBDD, ML y Deployment

---

## 🛠 Tareas Realizadas

- 📌 **Normalización de datos**
- 📐 **Diseño del modelo Entidad-Relación (E/R)**
- 📊 **Modelo lógico de la base de datos**
- 🧱 **Creación de tablas en PostgreSQL**
- 📥 **Ingesta de datos**
- 🗂️ **Consultas SQL para explotación de datos**
- 🌐 **Despliegue de la base de datos en Render**

---

## 🧩 Estructura del Modelo

### Entidades Principales:
- `alumno`
- `curso`
- `vertical`
- `proyecto`
- `nota`
- `campus`
- `claustro`

### Relaciones:
- curso    ↔️ vertical 🠮 n:1
- curso    ↔️ campus   🠮 1:n
- curso    ↔️ claustro 🠮 n:m
- vertical ↔️ proyecto 🠮 1:n
- proyecto ↔️ nota     🠮 n:1
- alumno   ↔️ nota     🠮 1:n
- alumno   ↔️ curso    🠮 n:m

---

## 🧪 Tecnologías Utilizadas

- PostgreSQL
- SQL
- draw.io (para diagramas)
- Render (para hosting de la base de datos)
- GitHub

---
