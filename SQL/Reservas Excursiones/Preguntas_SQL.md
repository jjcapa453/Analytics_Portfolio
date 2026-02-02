# 🧠 Preguntas de SQL — Base de Datos de Excursiones

Este documento contiene una colección de **preguntas de SQL** diseñadas para practicar consultas básicas, intermedias y avanzadas sobre una **base de datos de excursiones**.  
Las preguntas están organizadas por entidad para facilitar su uso y comprensión.

---

## 🏞️ Excursiones

- Seleccionar todas las excursiones con un precio **superior a 40 € e inferior a 50 €**.
- Encontrar la excursión con la **fecha más reciente**.
- Mostrar excursiones con un **precio superior al precio medio**.
- Mostrar el **nombre y número de excursiones por categoría**.
- Encontrar la **excursión más cara en cada categoría**.
- Enumerar las excursiones que **no se han reservado** en absoluto.
- Calcular el **total acumulado de reservas** para cada excursión.
- Enumerar las excursiones que tengan **más de 5 plazas disponibles** y cuyo precio sea **superior al precio medio** de todas las excursiones.

---

## 🧑‍🏫 Guías

- Listar todos los guías en **orden alfabético por apellido**.
- Encontrar el **guía con más excursiones**.
- Obtener los **nombres y apellidos de los guías** junto con la **disponibilidad total** de sus excursiones.
- Mostrar los guías cuyas excursiones tienen un **precio medio superior al precio medio general**.
- Encontrar guías que hayan realizado excursiones en **más de una categoría**.

---

## 🗂️ Categorías

- Contar el **número total de categorías**.
- Encontrar la **categoría con más excursiones**.
- Enumerar las categorías en **orden alfabético**, junto con el **precio promedio** de las excursiones en cada categoría.

---

## 📅 Reservas

- Enumerar las reservas realizadas por un **cliente específico** (por ejemplo, cliente con ID = 3).
- Calcular el **número de excursiones reservadas por mes** en un año específico.
- Seleccionar el **título de cada excursión** junto con el **número de veces que ha sido reservada**.
- Encontrar la **excursión más reservada**.
- Seleccionar el **nombre y apellidos del cliente** junto con el **título de la excursión** (solo excursiones reservadas).
- Calcular los **ingresos totales** generados por las reservas de cada excursión.
- Encontrar la **duración promedio de las reservas** para cada cliente.

---

## 🚀 Extras — Consultas SQL Avanzadas

- Encontrar excursiones que han sido **reservadas más veces que el promedio**.
- Encontrar excursiones que han sido **reservadas por todos los clientes**.
- Encontrar excursiones reservadas por clientes que también reservaron una excursión específica  
  *(por ejemplo: "Senderismo en la montaña")*.
- Obtener una lista detallada de excursiones que incluya:
  - Título de la excursión  
  - Nombre completo del guía  
  - Precio redondeado  
  - Categorización basada en rangos de precio
- Obtener una lista detallada de excursiones que incluya:
  - Título  
  - Nombre completo del guía  
  - Breve descripción  
  - Longitud total de la descripción
- Obtener una lista detallada de guías que incluya:
  - Nombre completo  
  - Número total de excursiones dirigidas en **cada categoría**

---

📌 **Objetivo:**  
Estas preguntas están pensadas para reforzar el uso de:
- `JOIN`, `GROUP BY`, `HAVING`
- Subconsultas
- Funciones de agregación
- Funciones de ventana
- Manipulación de texto y fechas

