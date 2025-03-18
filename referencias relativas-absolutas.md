Las **referencias relativas** y **absolutas** en Excel son conceptos fundamentales que determinan cómo se comportan las fórmulas cuando las copias o mueves a otras celdas. Entender la diferencia entre ambas es clave para trabajar eficientemente con fórmulas y evitar errores en tus cálculos.

---
### **1. Referencias relativas**
- **Definición**: Una referencia relativa es una referencia a una celda que **cambia automáticamente** cuando copias la fórmula a otra celda. Esto ocurre porque Excel ajusta la referencia en función de la nueva ubicación.
- **Sintaxis**: Se escribe simplemente como la coordenada de la celda (por ejemplo, `A1`).
- **Comportamiento**:
    - Si copias una fórmula con una referencia relativa hacia abajo, la referencia se ajusta en filas.
    - Si la copias hacia la derecha, la referencia se ajusta en columnas.
#### **Ejemplo**:
Supongamos que tienes la siguiente fórmula en la celda `B2`:
```excel
=A1
```
- Si copias esta fórmula a la celda `B3`, la fórmula se ajustará a:
```excel
=A2
```
- Si la copias a la celda `C2`, la fórmula se ajustará a:
```excel
=B1
```

---
### **2. Referencias absolutas**

- **Definición**: Una referencia absoluta es una referencia a una celda que **no cambia** cuando copias la fórmula a otra celda. Esto se logra usando el símbolo `$` antes de la columna y/o fila.
- **Sintaxis**: Se escribe con `$` antes de la columna y/o fila (por ejemplo, `$A$1`).
- **Comportamiento**:
    - La referencia permanece fija, sin importar a dónde copies la fórmula.
#### **Ejemplo**:
Supongamos que tienes la siguiente fórmula en la celda `B2`:
```excel
=$A$1
```
- Si copias esta fórmula a la celda `B3`, la fórmula seguirá siendo:
```excel
=$A$1
```
- Si la copias a la celda `C2`, la fórmula seguirá siendo:
```excel
=$A$1
```
---
### **3. Referencias mixtas**

- **Definición**: Una referencia mixta es una combinación de referencia relativa y absoluta. Puedes fijar solo la columna o solo la fila.    
- **Sintaxis**:
    - Fijar columna: `$A1` (la columna `A` es absoluta, pero la fila `1` es relativa).
    - Fijar fila: `A$1` (la fila `1` es absoluta, pero la columna `A` es relativa).
- **Comportamiento**:
    - Dependiendo de qué parte esté fija, la referencia se ajustará parcialmente.
#### **Ejemplo**:

Supongamos que tienes la siguiente fórmula en la celda `B2`:
```excel
=$A1
```
- Si copias esta fórmula a la celda `B3`, la fórmula se ajustará a:
```excel
=$A2
```
- Si la copias a la celda `C2`, la fórmula seguirá siendo:
```excel
=$A1
```
---
### **¿Cuándo usar cada tipo de referencia?**

1. **Referencias relativas**:
    - Útiles cuando quieres que una fórmula se ajuste automáticamente al copiarla.
    - Ejemplo: Sumar una columna de números en diferentes filas.
2. **Referencias absolutas**:
    - Útiles cuando necesitas que una fórmula siempre haga referencia a una celda específica.
    - Ejemplo: Multiplicar valores por una tasa fija almacenada en una celda.
3. **Referencias mixtas**:
    - Útiles cuando necesitas fijar solo una parte de la referencia (columna o fila).
    - Ejemplo: Crear una tabla de multiplicar donde una fila o columna sea fija.

>[!Summary]
>- **Referencia relativa**: Cambia al copiar la fórmula (por ejemplo, `A1`).
>- **Referencia absoluta**: No cambia al copiar la fórmula (por ejemplo, `$A$1`).
>- **Referencia mixta**: Fija solo la columna o la fila (por ejemplo, `$A1` o `A$1`).
