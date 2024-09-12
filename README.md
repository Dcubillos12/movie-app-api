# MovieApp Backend

Bienvenido al backend de MovieApp, una aplicación web de cine. Este backend está desarrollado con **NestJS** y proporciona funcionalidades para gestionar usuarios, autenticación, y favoritos. La base de datos utilizada es **PostgreSQL** y la API está desplegada en **Render**.

## Tabla de Contenidos

- [Características](#características)
- [Instalación](#instalación)
- [Configuración](#configuración)
- [Uso](#uso)
- [Despliegue](#despliegue)
- [Documentación de la API](#documentación-de-la-api)
- [Recursos](#recursos)
- [Contribución](#contribución)
- [Licencia](#licencia)

## Características

- **Gestión de Usuarios:**
  - Crear usuario
  - Encontrar usuario por ID
  - Encontrar todos los usuarios
  - Actualizar usuario
  - Soft delete usuario

- **Autenticación y Gestión de Sesiones:**
  - Registro de nuevos usuarios
  - Inicio de sesión con JWT
  - Cierre de sesión

- **Gestión de Favoritos:**
  - Marcar y desmarcar favoritos
  - Obtener lista de favoritos

## Instalación

1. **Clonar el repositorio:**

   ```bash
   git clone https://github.com/Dcubillos12/movie-app-api.git
