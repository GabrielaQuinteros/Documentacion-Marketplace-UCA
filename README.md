# 🎓 Marketplace UCA | Documentación Central

> **Repositorio oficial de documentación, arquitectura y lógica del proyecto.**

Bienvenido al centro de información de **Marketplace UCA**, la plataforma de comercio seguro exclusiva para la comunidad universitaria. Este repositorio centraliza todos los recursos técnicos, guías de despliegue y planes de calidad del sistema.

---

## 📂 Índice de Documentación

### 🚀 Guías de Despliegue (Start Here)
Si necesitas levantar el proyecto desde cero, consulta estos archivos principales:

| Componente | Archivo | Descripción |
| :--- | :--- | :--- |
| **Backend** | [📥 Ver README Backend](./README%20BACKEND.md) | Configuración de **Spring Boot**, **Java 21** y despliegue de base de datos con Docker (PostgreSQL/Redis). |
| **Frontend** | [🖥️ Ver README Frontend](./README%20FRONTEND.md) | Instalación del cliente web con **React 19**, **Vite 7** y configuración de variables de entorno. |

### 📘 Arquitectura y Desarrollo
Documentos detallados sobre la construcción del sistema:

- **[🛠️ Manual de Desarrollo](./Manual%20de%20Desarrollo.md)** *Guía normativa para el equipo: implementación de **Git Flow**, estrategias de ramificación (master/develop) y convenciones de código (PascalCase/camelCase)*.

- **[🏗️ Documentación Técnica](./Documentacion%20Tecnica.md)** *Especificaciones técnicas profundas: listado de endpoints protegidos (`/admin`, `/user`), códigos de error HTTP, validaciones de seguridad y estructura de base de datos*.

- **[🧠 Lógica de Negocio](./Documentacion%20de%20Logica%20de%20Negocio.md)** *Reglas de negocio documentadas, diagrama UML de secuencia (ej. Flujo OTP), Matriz de validaciones, documentacion de dominio*.

### ✅ Calidad y Testing
- **[🧪 Plan de Pruebas](./Plan%20de%20Pruebas.md)** *Estrategia de QA: cobertura de **13 historias de usuario**, validación funcional de épicas (Comentarios, Reseñas, Favoritos) y criterios de aceptación*.

---

## 🛠️ Tecnologías Principales

El sistema está construido sobre una arquitectura moderna y escalable:

* **Frontend:** React 19 + Vite 7 + Tailwind CSS 4
* **Backend:** Java 21 + Spring Boot (Security, Data Redis, JPA)
* **Base de Datos:** PostgreSQL & Redis (Dockerizados)
* **Infraestructura:** Digital Ocean & Cloudinary

---

<div align="center">
  <p>© 2025 Marketplace UCA - Proyecto de Ingeniería de Software</p>
</div>
