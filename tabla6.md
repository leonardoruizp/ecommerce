### **6. Tabla `pagos`**
Lleva un historial de los pagos realizados por los miembros.

**Campos:**
- `id_pago` (INT, PK, AUTOINCREMENT)
- `id_miembro` (INT, FK a `miembros`)
- `monto` (DECIMAL)
- `fecha_pago` (DATETIME)
- `metodo_pago` (ENUM: efectivo, tarjeta, transferencia)
