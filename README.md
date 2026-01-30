# 🔐 Spring Boot Security Application

Aplicación desarrollada en **Java 17** con **Spring Boot 2.7**, enfocada en la implementación de **seguridad, autenticación y autorización**, integrando JWT, sesiones persistentes y una arquitectura backend moderna.

---

## 📌 Descripción del Proyecto

Este proyecto implementa un sistema backend seguro utilizando **Spring Security**, con soporte para:

- Autenticación basada en **JWT**
- Manejo de sesiones persistentes
- Persistencia de datos con **JPA + MySQL**
- Renderizado de vistas con **Thymeleaf**
- Envío de correos electrónicos
- Generación de documentos PDF
- Preparación para despliegue en **Google Cloud (App Engine)**

El objetivo principal es servir como **base sólida para aplicaciones empresariales** que requieran seguridad y control de acceso.

---

## 🧱 Arquitectura y Tecnologías

### 🔧 Backend
- **Java 17**
- **Spring Boot 2.7**
- **Spring Security**
- **JWT (JSON Web Tokens)**
- **Spring Data JPA**
- **Spring Session (JDBC)**

### 🗄️ Base de Datos
- **MySQL 8**

### 🎨 Frontend (Server Side Rendering)
- **Thymeleaf**
- **Thymeleaf Layout Dialect**

### 📄 Documentos
- **Flying Saucer PDF**
- **JTidy (HTML → XHTML)**

### ☁️ Cloud
- **Google Cloud Platform**
- **App Engine**

---

## 🔐 Seguridad

El sistema de seguridad incluye:

- Autenticación con JWT
- Control de acceso basado en roles
- Protección de endpoints
- Manejo de sesiones persistentes en base de datos
- Integración con Spring Security

> ⚠️ Las credenciales y secretos **no están versionados** en el repositorio.

---

## ⚙️ Requisitos Previos

Antes de ejecutar el proyecto asegúrate de tener:

- Java 17+
- Maven 3.8+
- MySQL 8+
- Git

---

## 🚀 Ejecución del Proyecto

### 1️⃣ Clonar el repositorio
```bash
git clone https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio
