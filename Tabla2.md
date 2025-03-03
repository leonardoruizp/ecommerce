### **2. Tabla `miembros`**
Registra los datos de los clientes del gimnasio.

**Campos:**
- `id_miembro` (INT, PK, AUTOINCREMENT)
- `nombre` (VARCHAR)
- `fecha_nacimiento` (DATE)
- `telefono` (VARCHAR)
- `correo` (VARCHAR, UNIQUE)
- `id_membresia` (INT, FK a `membresias`)
