# Flask Basic API

Una API RESTful básica construida con Flask, con endpoints para la creación y recuperación de usuarios.

## Características
- **Obtener Información del Usuario:** Recuperar detalles del usuario por ID de usuario.
- **Crear Usuario:** Añadir un nuevo usuario a la base de datos.

## Endpoints

### Obtener Usuario
- **URL:** `/get-user/<user_id>`
- **Método:** `GET`
- **Parámetros de URL:**
  - `user_id=[string]` - ID del usuario.
- **Parámetros de Consulta:**
  - `extra=[string]` (opcional) - Información adicional para incluir.
- **Respuesta:**
  ```json
  {
    "user_id": "1",
    "name": "John Doe",
    "email": "john.doe@example.com",
    "extra": "información adicional" // Opcional
  }
