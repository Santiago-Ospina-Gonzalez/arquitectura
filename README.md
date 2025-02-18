# arquitectura

Josefo: 
3. Ensamblador:

Ley de Benford y su Implementación en Ensamblador
Implementar la Ley de Benford en lenguaje ensamblador implica procesar una lista de números y contar la frecuencia de los primeros dígitos. Para ello, necesitamos:

Leer o almacenar datos numéricos en memoria.
Extraer el primer dígito de cada número.
Incrementar un contador para cada posible primer dígito (del 1 al 9).
Mostrar los resultados para analizar la distribución.

    - Instrucciones:

Instrucciones Claves en Ensamblador
En un programa en ensamblador, podríamos usar instrucciones como:

MOV: Para mover valores entre registros y memoria.
DIV: Para dividir números y extraer dígitos.
CMP y JUMP (JMP, JE, JNE, etc.): Para comparar y controlar el flujo del programa.
LOOP: Para recorrer los datos en un ciclo.
INT 21h (DOS) o SYSCALL (Linux): Para entrada/salida de datos.
