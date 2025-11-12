# Tecnológico de Software
## Materia: Fundamentos de álgebra
## Alumno: Rodrigo Barrera García
## Actividad \#16 - Matrices doc

---
# Identificación de matrices
## EJERCICIO 1
### Tipo de Matriz: Identidad

$$ A 
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
$$

### Tipo de Matriz: Diagonal

$$ B
\begin{pmatrix}
3 & 0 & 0 \\
0 & -2 & 0 \\
0 & 0 & 5\\
\end{pmatrix}
$$

### Tipo de Matriz: Cuadrada

$$ C
\begin{pmatrix}
2 & 1 & 4 \\
1 & 3 & 5 \\
4 & 5 & 6 \\
\end{pmatrix}
$$

### Tipo de Matriz: Triangulo Superior

$$ D
\begin{pmatrix}
1 & 2 & 3 \\
0 & 4 & 5 \\
0 & 0 & 6 \\
\end{pmatrix}
$$

## EJERCICIO 2

Calcula la suma de A y B

$$ A =
\begin{pmatrix}
2 & -1 \\
3 & 4 \\
\end{pmatrix}
$$

$$ B =
\begin{pmatrix}
5 & 2 \\
-1 & 3 \\
\end{pmatrix}
$$

$$ A + B =
\begin{pmatrix}
2 + 5 & -1 + 2 \\
3 + -1 & 4 + 3\\
\end{pmatrix}
$$

$$ A + B =
\begin{pmatrix}
7 & 1 \\
2 & 7 \\
\end{pmatrix}
$$

Calcula la resta de 2A y B

$$ A =
\begin{pmatrix}
2 & -1 \\
3 & 4 \\
\end{pmatrix}
$$

$$ B =
\begin{pmatrix}
5 & 2  \\
-1 & 3 \\
\end{pmatrix}
$$

$$ 2A  =
\begin{pmatrix}
4 & -2 \\
6 & 8 \\
\end{pmatrix}
$$

$$ 2A + B =
\begin{pmatrix}
4 - 5 & -2 - 2 \\
6 - -1 & 8 - 3\\
\end{pmatrix}
$$

$$ 2A + B =
\begin{pmatrix}
-1 & -4 \\
7 & 5 \\
\end{pmatrix}
$$

Calcula AB

$$ A =
\begin{pmatrix}
2 & -1 \\
3 & 4 \\
\end{pmatrix}
$$

$$ B =
\begin{pmatrix}
5 & 2  \\
-1 & 3 \\
\end{pmatrix}
$$

$$ AB =
\begin{pmatrix}
(2 * 5 + -1 * -1) (2 * 2 + -1 * 3)  \\
(3 * 5 + 4 * -1) (3 * 2 + 4 * 3) \\
\end{pmatrix}
$$

$$ AB =
\begin{pmatrix}
11 & 1 \\
11 & 18 \\
\end{pmatrix}
$$

Calcula BA

$$ A =
\begin{pmatrix}
2 & -1  \\
3 & 4  \\
\end{pmatrix}
$$

$$ B =
\begin{pmatrix}
5 & 2  \\
-1 & 3 \\
\end{pmatrix}
$$

$$ BA =
\begin{pmatrix}
(5 * 2 + 2 * 3) (5 * -1 + 2 * 4)  \\
(3 * 5 + 4 * -1) (-1 * -1 + 3 * 4) \\
\end{pmatrix}
$$

$$ BA=
\begin{pmatrix}
16 & 3 \\
7 & 13 \\
\end{pmatrix}
$$

Transpuesta de A

$$ A =
\begin{pmatrix}
2 & -1  \\
3 & 4  \\
\end{pmatrix}
$$

$$ AT =
\begin{pmatrix}
2 & 3  \\
-1 & 4  \\
\end{pmatrix}
$$

---
# EJERCICIO 3

Muliplicacion de cadena

$$ A =
\begin{pmatrix}
1 & 2 \\
3 & 4 \\
\end{pmatrix}
$$

$$ B =
\begin{pmatrix}
2 & 0 \\
1 & 3 \\
\end{pmatrix}
$$

$$ C =
\begin{pmatrix}
1 & 1 \\
0 & 2 \\
\end{pmatrix}
$$
-------
## Parte 1 
$$ AB =
\begin{pmatrix}
(1 * 2 + 2 * 1) (1 * 0 + 2 * 3) \\
(3 * 2 + 4 * 1) (3 * 0 + 4 * 3) \\
\end{pmatrix}
$$

$$ AB =
\begin{pmatrix}
4 & 6 \\
10 & 12 \\
\end{pmatrix}
$$

## Parte 2 

$$ (AB)C =
\begin{pmatrix}
(4 * 1 + 6 * 0) (4 * 1 + 6 * 2)  \\
(10 * 1 + 12 * 0) (10 * 0 + 12 * 2) \\
\end{pmatrix}
$$

$$ (AB)C =
\begin{pmatrix}
4 & 16 \\
10 & 34 \\
\end{pmatrix}
$$
-------
## Parte 1 

$$ BC =
\begin{pmatrix}
(2 * 1 + 0 * 0) (2 * 1 + 0 * 2)  \\
(10 * 1 + 3 * 0) (1 * 1 + 3 * 2) \\
\end{pmatrix}
$$

$$ BC =
\begin{pmatrix}
2 & 2 \\
1 & 7 \\
\end{pmatrix}
$$

## Parte 2

$$ A(BC) =
\begin{pmatrix}
(1 * 2 + 2 * 1) (1 * 2 + 2 * 7)  \\
(3 * 2 + 4 * 1) (3 * 2 + 4 * 7) \\
\end{pmatrix}
$$

$$ A(BC) =
\begin{pmatrix}
4 & 16 \\
10 & 34 \\
\end{pmatrix}
$$









