### **1. Tabla `usuarios`**
Almacena la información de los usuarios del sistema.

**Campos:**
- `id_usuario` (INT, PK, AUTOINCREMENT)
- `nombre` (VARCHAR)
- `correo` (VARCHAR, UNIQUE)
- `contraseña` (VARCHAR, HASH)
- `rol` (ENUM: admin, entrenador, cliente)
