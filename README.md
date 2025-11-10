# Tecnológico de Software  
## Materia: Fundamentos de Álgebra  
### Alumno: David Morales Guerrero  
### Actividad #16 – Documentación de matrices  

---

## Objetivo de la documentación  
El objetivo de esta actividad es documentar las soluciones y procedimientos de los ejercicios de matrices vistos en clase, aplicando el formato Markdown para mostrar el razonamiento y los resultados paso a paso de manera clara y profesional.

---

## Ejercicio 1: Clasificar matrices

**Enunciado:**  
Identifica el tipo de cada una de las siguientes matrices:

A = ( 1 0 )
( 0 1 )

B = ( 3 0 0 )
( 0 -2 0 )
( 0 0 5 )

C = ( 2 1 4 )
( 1 3 5 )
( 4 5 6 )

D = ( 1 2 3 )
( 0 4 5 )
( 0 0 6 )


---

### Solución y clasificación

1. **Matriz A:**  
   Es matriz identidad, porque todos los elementos de la diagonal principal son 1 y el resto son 0.  
   Tipo: Matriz cuadrada e identidad.

2. **Matriz B:**  
   Todos los valores fuera de la diagonal son 0, pero los elementos en la diagonal son distintos.  
   Tipo: Matriz diagonal.

3. **Matriz C:**  
   Es cuadrada (3×3), pero tiene valores tanto arriba como abajo de la diagonal principal.  
   Tipo: Matriz simétrica (ya que a_ij = a_ji).

4. **Matriz D:**  
   Tiene ceros debajo de la diagonal principal.  
   Tipo: Matriz triangular superior.

---

### Procedimiento

1. Se analizó si cada matriz era cuadrada (mismo número de filas y columnas).  
2. Se observó la ubicación de los ceros para determinar si es diagonal, triangular o identidad.  
3. En el caso de C, se compararon los valores simétricos respecto a la diagonal.  
4. Se clasificó según sus propiedades específicas.

---

## Ejercicio 2: Operaciones básicas con matrices

**Enunciado:**  
Dadas las matrices:

A = ( 2 -1 )
( 3 4 )

B = ( 5 2 )
( -1 3 )


Calcula:
a) A + B  
b) 2A – B  
c) AB  
d) BA  
e) Aᵀ

---

### Solución

**a) Suma de matrices**

A + B = ( 2+5 -1+2 )
( 3+(-1) 4+3 )

A + B = ( 7 1 )
( 2 7 )


---

**b) 2A – B**

2A – B = 2( 2 -1 ) - ( 5 2 )
( 3 4 ) ( -1 3 )

2A = ( 4 -2 )
( 6 8 )

2A – B = ( 4-5 -2-2 )
( 6-(-1) 8-3 )

2A – B = ( -1 -4 )
( 7 5 )


---

**c) Producto AB**

AB = ( 2 -1 ) ( 5 2 )
( 3 4 ) ( -1 3 )

AB = ( (2)(5)+(-1)(-1) (2)(2)+(-1)(3) )
( (3)(5)+(4)(-1) (3)(2)+(4)(3) )

AB = ( 11 1 )
( 11 18 )


---

**e) Transpuesta de A**

Aᵀ = ( 2 3 )
( -1 4 )


---

### Procedimiento

1. Se aplicaron las operaciones correspondientes a cada caso:  
   - Suma y resta elemento a elemento.  
   - Multiplicación de matrices aplicando la regla (AB)_ij = Σ a_ik * b_kj.  
   - Transposición intercambiando filas por columnas.  
2. Se simplificaron los resultados hasta obtener las matrices finales.

---

## Ejercicio 3: Multiplicación en cadena

**Enunciado:**  
Verifica que se cumpla la propiedad asociativa de la multiplicación de matrices, es decir:  
\((AB)C = A(BC)\)

Dadas las matrices:

A = ( 1 2 )
( 3 4 )

B = ( 2 0 )
( 1 3 )

C = ( 1 1 )
( 0 2 )


---

### Solución

**1. Calcular (AB)**

AB = ( 12 + 21 10 + 23 )
( 32 + 41 30 + 43 )

AB = ( 4 6 )
( 10 12 )


---

**2. Calcular (AB)C**

(AB)C = ( 4 6 ) ( 1 1 )
( 10 12 ) ( 0 2 )

(AB)C = ( (4)(1)+(6)(0) (4)(1)+(6)(2) )
( (10)(1)+(12)(0) (10)(1)+(12)(2) )

(AB)C = ( 4 16 )
( 10 34 )


---

**3. Calcular (BC)**

BC = ( 2 0 ) ( 1 1 )
( 1 3 ) ( 0 2 )

BC = ( (2)(1)+(0)(0) (2)(1)+(0)(2) )
( (1)(1)+(3)(0) (1)(1)+(3)(2) )

BC = ( 2 2 )
( 1 7 )


---

**4. Calcular A(BC)**

A(BC) = ( 1 2 ) ( 2 2 )
( 3 4 ) ( 1 7 )

A(BC) = ( (1)(2)+(2)(1) (1)(2)+(2)(7) )
( (3)(2)+(4)(1) (3)(2)+(4)(7) )

A(BC) = ( 4 16 )
( 10 34 )


---

### Verificación

\[
(AB)C = A(BC) =
\begin{pmatrix}
4 & 16 \\
10 & 34
\end{pmatrix}
\]

Por lo tanto, **la propiedad asociativa se cumple**, ya que ambos resultados son iguales.

---

### Procedimiento paso a paso

1. Se realizaron los productos de matrices en el orden indicado.  
2. Se verificó que los resultados de \((AB)C\) y \(A(BC)\) fueran idénticos.  
3. Se comprobó que la multiplicación de matrices es **asociativa**, pero **no conmutativa**.

---

---

## Conclusión general

Durante esta actividad se reforzaron los conocimientos sobre el manejo de matrices, abarcando su clasificación, las operaciones básicas y la comprobación de propiedades algebraicas.  
La documentación permitió aplicar buenas prácticas de redacción técnica utilizando Markdown y estructuración jerárquica del contenido, tal como se realiza en proyectos reales de programación.  
Con ello, se cumple el objetivo de comprender la manipulación matricial y su correcta presentación profesional dentro de repositorios de control de versiones como GitHub.
