# 🗃️ SQL - Ejemplos de Operadores Importantes

## 📝 Descripción

Este repositorio contiene ejemplos prácticos de los **operadores SQL** más importantes. Cada consulta está diseñada para demostrar el uso de operadores clave como comparaciones, operadores lógicos, aritméticos, de cadenas y más.

---

## 📚 Contenido

Este repositorio cubre los siguientes operadores:

- **Operadores de comparación**: `=`, `>`, `<`, `<=`, `>=`, `!=`, `BETWEEN`
- **Operadores lógicos**: `AND`, `OR`, `NOT`
- **Operadores de conjunto**: `IN`, `EXISTS`, `NOT EXISTS`
- **Operadores de cadenas**: `LIKE`, `CONCAT`
- **Operadores aritméticos**: `+`, `-`, `*`, `/`
- **Operadores de agregación**: `AVG`, `SUM`, `COUNT`, `MIN`, `MAX`
- **Operador de nulos**: `IS NULL`

---

## 🚀 Cómo Usar

1. **Configura la base de datos**:
   - Ejecuta las consultas para crear las tablas necesarias con `CREATE TABLE`.
   - Inserta los datos de ejemplo en las tablas con `INSERT INTO`.

2. **Ejecuta las consultas**:
   - Abre cualquier cliente SQL (por ejemplo, **MySQL Workbench**, **pgAdmin**, **DBeaver**).
   - Copia y pega los ejemplos SQL en tu entorno de base de datos y ejecútalos.

3. **Personaliza el código**:
   - Modifica los datos o los operadores según tus necesidades.

---

## 🔍 Ejemplos Destacados

### ⚖️ Operadores de Comparación

```sql
-- Productos con precio mayor a 100
SELECT * FROM productos
WHERE precio > 100;

-- Productos con precio entre 50 y 500
SELECT * FROM productos
WHERE precio BETWEEN 50 AND 500;

