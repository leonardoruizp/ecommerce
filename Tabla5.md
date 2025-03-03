### **5. Tabla `inscripciones`**
Registra qué miembros están inscritos en qué clases.

**Campos:**
- `id_inscripcion` (INT, PK, AUTOINCREMENT)
- `id_miembro` (INT, FK a `miembros`)
- `id_clase` (INT, FK a `clases`)
- `fecha_inscripcion` (DATETIME)
