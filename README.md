# Foro Hub - API REST

Este es el desafío final de la formación **Spring Boot 3** en el programa **Oracle Next Education (ONE)**. Se trata de una API REST funcional para gestionar los tópicos de un foro de discusión.

## 🎯 Objetivo
El objetivo es replicar a nivel de back-end el funcionamiento de un foro, permitiendo a los usuarios realizar las operaciones básicas (CRUD):
- Crear un nuevo tópico.
- Listar todos los tópicos creados.
- Actualizar datos de un tópico (opcional).
- Eliminar un tópico.

## 🚀 Tecnologías Utilizadas
- **Java 17**
- **Spring Boot 3**
- **Spring Data JPA**: Para la persistencia de datos.
- **PostgreSQL**: Base de datos relacional.
- **Maven**: Gestión de dependencias.
- **Spring Security**: Para la protección de rutas (configuración base).

## 🛠️ Cómo se estructuró el proyecto
El proyecto sigue el modelo de arquitectura de Spring:
1. **Controller**: Maneja las solicitudes HTTP y define los endpoints.
2. **Domain/Model**: Representa la tabla `topicos` en la base de datos.
3. **Repository**: Interfaz para realizar las operaciones de base de datos sin escribir SQL.

## 📌 Configuración
Para que el proyecto funcione, se requiere:
- Una base de datos PostgreSQL llamada `forohub_db`.
- Configurar las credenciales en el archivo `application.properties`.

---
Desarrollado por **Tobías** como proyecto final de la formación Java G9 - ONE.
