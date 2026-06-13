# ADR-01: Selección del estilo arquitectónico basado en arquitectura por capas

| Campo  | Valor |
| ------ | ----- |
| Autor  | Scarlet Angelina Ruelas |
| Fecha  | 12/06/2026 |
| Estado | Aceptado |

---

## Contexto

El proyecto de Biblioteca Digital tiene como objetivo gestionar libros, usuarios, préstamos, reservas y pagos de manera digital y organizada. El sistema debe ser escalable, mantenible y fácil de desarrollar dentro del tiempo académico disponible.

Se requiere definir formalmente el estilo arquitectónico del sistema para garantizar una estructura clara que permita separar responsabilidades y facilitar el mantenimiento del código.

---

## Decisión

Se decidió utilizar el estilo arquitectónico de **arquitectura por capas (Layered Architecture)**, compuesto por:

- Capa de presentación (Web Application - ASP.NET Core MVC)
- Capa de API (ASP.NET Core Web API)
- Capa de servicios (Business Logic)
- Capa de repositorios (Data Access Layer)
- Base de datos (PostgreSQL)

---
