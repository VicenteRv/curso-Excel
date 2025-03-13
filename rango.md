En Excel, un **rango** es un conjunto de celdas seleccionadas o agrupadas que se identifican por sus coordenadas. Los rangos son fundamentales para realizar operaciones, aplicar fórmulas, crear gráficos y organizar datos. Pueden ser tan pequeños como una sola celda o tan grandes como miles de celdas.

---
# **Cómo se define un rango**
Un rango se define por la **celda inicial** y la **celda final**, separadas por dos puntos (`:`). Por ejemplo:
- `A1:A10` → Es un rango que incluye las celdas desde **A1** hasta **A10** en una columna.
- `B2:D5` → Es un rango rectangular que incluye todas las celdas desde **B2** hasta **D5**.
# **Tipos de rangos*
1. **Rango de una sola celda**:  
    Ejemplo: `A1` (solo la celda A1).
2. **Rango de una fila o columna**:
    - Fila: `A1:D1` (celdas de la fila 1, desde A hasta D).
    - Columna: `A1:A10` (celdas de la columna A, desde 1 hasta 10).
3. **Rango rectangular**:  
    Ejemplo: `B2:D5` (celdas desde B2 hasta D5, formando un rectángulo).
4. **Rango no contiguo**:  
    Ejemplo: `A1:A5, C1:C5` (dos rangos separados por una coma).
---
### **Cómo seleccionar un rango**
1. **Manualmente**:
    - Haz clic en una celda y arrastra el mouse para seleccionar un grupo de celdas.
    - O escribe el rango directamente en la barra de fórmulas (por ejemplo, `B2:D5`).
2. **Con el teclado**:
    - Selecciona una celda, mantén presionada la tecla **Shift** y usa las flechas para expandir la selección.
3. **Rangos no contiguos**:
    - Selecciona un rango, mantén presionada la tecla **Ctrl** y selecciona otro rango.
---
# **Usos comunes de los rangos**
1. **Fórmulas**:
    - Ejemplo: `=SUMA(A1:A10)` suma todos los valores en el rango `A1:A10`.
2. **Funciones**:
    - Ejemplo: `=PROMEDIO(B2:D5)` calcula el promedio de los valores en el rango `B2:D5`.
3. **Gráficos**:
    - Los gráficos se crean a partir de rangos de datos.
4. **Filtros y tablas**:
    - Los rangos se usan para aplicar filtros o crear tablas dinámicas.
5. **Formato condicional**:
    - Aplicar reglas de formato a un rango específico.
---
# **Ejemplo práctico**

Supongamos que tienes los siguientes datos en Excel:

| A   | B   | C   |
| --- | --- | --- |
| 5   | 10  | 15  |
| 20  | 25  | 30  |
| 35  | 40  | 45  |

- Si quieres sumar todos los valores de la columna A, usarías el rango `A1:A3` en la fórmula:  
    `=SUMA(A1:A3)` → Resultado: **60**.
- Si quieres calcular el promedio de todos los valores en el rango `B1:C3`, usarías:  
    `=PROMEDIO(B1:C3)` → Resultado: **27.5**.
---
En resumen, un **rango** en Excel es una herramienta básica pero poderosa que te permite trabajar con grupos de celdas de manera eficiente.