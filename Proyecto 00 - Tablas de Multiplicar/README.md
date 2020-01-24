# Proyecto 00 - Tablas de Multiplicar 
20/08/2019
Semana: 0

## Objetivos de aprendizaje y competencias

1. Objetivos de aprendizaje:
   1. Leer números enteros usando input
   2. Usar `print()`, sin cambio de línea, y con cambio de línea
   3. Tabular en `print()`
   4. Usar `range(m,n)`
   5. Usar `for`
   6. Usar comentarios


2. Competencias que se desarrollan:
   1. Analizar un problema para formular una solución
   2. Idear un algoritmo para resolver un problema
   3. Presentar los resultados de un proyecto

## Descripción
Se requiere que desarrollen un programa en Python para generar una tabla de multiplicar  desde el 1 hasta un número que se debe leer y escribir en el formato indicado a continuación.



​		  1        2        3        4        5

1        1        2        3        4        5
2        2        4        6        8      10
3        3        6        9      12      15
4        4        8      12      16      20
5        5       10     15      20      25
	

________________

## Antecedentes

Estudie el siguiente programa de ejemplo para que saque ideas de como hacer lo pedido:`

```python
n = int(input('numero: ')) #lee el último número que se imprimirá
for i in range(1,n+1):    
   print(i,'\t',end='')    #imprime el siguiente número y tabula
   if i % 10 == 0:         #el % calcula el resto de la división      
       print()             #print() equivale a una nueva línea
                           #cambia de línea cada 10 números
```

Este programa lee un número N y escribe los números desde el 1 hasta N de a 10 por línea:

  1       2         3         4         5         6         7         8         9         10         
11     12       13      14       15       16       17       18       19        20         
21     22       23      24       25       26       27       28       29        30         
31     32       33      34       35 
	

Fíjense en como se lee, como se usa `print`, `range` y `for `


Para realizar este proyecto deberán considerar la siguiente documentación del tutorial de Python en python.org (abrir en Google Chrome y traducir).




* 3.1 Usando Python como calculadora 
https://docs.python.org/3/tutorial/introduction.html#using-python-as-a-calculator
* 4.2 Ciclo `for `
https://docs.python.org/3/tutorial/controlflow.html#for-statements
* 4.3 la función `range() `
https://docs.python.org/3/tutorial/controlflow.html#the-range-function
Instrucciones 
La entrega de los trabajos se debe hacer en un Cuaderno Jupyter, documentando las partes del código y los resultados como sea necesario.