# Un poco de historia
El lenguaje fue concebido por Dennis Ritchie, le inventó en 1972. Su propósito era escribir un sistema operativo, el mismo que en contemporaneidad conocemos denominado como Unix.  A veces se dice que C es un ensamblador portátil; es un sistema de implementación de sistemas. Depende, además de otros lenguajes, del diseño prístino de Algol 60. Algol 60 fue un lenguaje codificado por un grupo internacional de científicos de la computación en 1960, justo al principio de la existencia de ciencias de la computación; muchos de los conceptos que a día de hoy empleamos han nacido o comenzado con Algol 60. **Es el resultado de dos lenguajes anteriores, el BCPL y el B. Fueron Kernighan y Ritchie los que publicaron una descripción definitiva del lenguaje conocida como "K&R C".**

![image](https://github.com/ainfanthe/ongoingLearning/assets/105471058/ed144107-b536-4eec-b267-82caf07e12ac)

> **A raiz de la creciente popularidad de los microordenadores, comenzaron a surgir numerosas implementaciones de C que diferían en parte de la definición de K&R, creando pequeñas incompatibilidades y disminuyendo la portabilidad del lenguaje. Esto hizo necesaria la búsqueda de un C estandard, representado por el ANSI* C.**

Originalmente el Lenguaje C estuvo muy ligado al sistema operativo UNIX que, en su mayor parte, está escrito en C. Más adelante se comenzó a utilizar en otros sistemas operativos para programar editores, compiladores, etc. Aunque se le conoce como un lenguaje de programación de sistemas, no se adapta mal al resto de aplicaciones. De hecho, hoy en día un alto porcentaje de software para ordenadores personales está escrito en Lenguaje C. Por ejemplo, el sistema operativo MS-DOS.

![image](https://github.com/ainfanthe/ongoingLearning/assets/105471058/e0319029-bdb9-4801-885a-ec6d5324cb57)

# Sintaxis básica: interpretación

``` c
#include <stdio.h>
int main() {
    printf("Hello world");
    return 0;
}
```

``` c
#include <stdio.h>
```

`#include <stdio.h>` es una directiva de preprocesador que le indica al compilador que incluya el archivo de encabezado (header) `stdio.h`. Este archivo es una biblioteca que contiene las declaraciones necesarias para usar funciones de entrada-salida estándar, como `printf`.
`#include` es una palabra especial que le dice al compilador que la siguiente librería debe ser incluida, en este preciso ejemplo ya hemos hecho uso de la "standar IO (Input-Output)": `<stdio.h>`

```c
int main() {
```

La línea `int main() {` define la función principal del programa, llamada `main.` Es el punto de entrada de cualquier programa en C.

```c
printf("Hello world");
```

La línea `printf("Hello world");` es una llamada a la función `printf`, que se utiliza para imprimir texto en la consola. En este caso, se está imprimiendo la cadena "Hello world".

```c
return 0;
```

La línea `return 0;` indica que el programa ha finalizado exitosamente y devuelve el valor 0 al sistema operativo. Este valor se utiliza a menudo para indicar que el programa se ejecutó correctamente. Sin embargo, el uso de `return 0;` en `main` es opcional en lenguaje C moderno, ya que se asume un valor de retorno de 0 si no se proporciona explícitamente.

```c
}
```

El corchete de cierre `}` indica el final de la función `main`, y el final del programa en sí. Esto ha sido un ejemplo comúnmente utilizado para familiarizarse con la sintaxis básica de C.