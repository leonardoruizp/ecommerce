### **4. Tabla `clases`**
Administra las clases ofrecidas en el gimnasio.

**Campos:**
- `id_clase` (INT, PK, AUTOINCREMENT)
- `nombre` (VARCHAR)
- `id_entrenador` (INT, FK a `usuarios`)
- `capacidad_maxima` (INT)
- `horario` (DATETIME)
