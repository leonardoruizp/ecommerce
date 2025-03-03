### **3. Tabla `membresias`**
Guarda los tipos de membresías y su estado.

**Campos:**
- `id_membresia` (INT, PK, AUTOINCREMENT)
- `tipo` (VARCHAR)
- `precio` (DECIMAL)
- `duracion_meses` (INT)
- `estado` (ENUM: activa, inactiva)
