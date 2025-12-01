En la parte final de este proyecto, el programa que escribimos en nuestro propio lenguaje pasa por todas las etapas del traductor y termina convirtiéndose en código NASM. Esto quiere decir que todo lo que el usuario escribe en el lenguaje que definimos se transforma en instrucciones de ensamblador reales, que una computadora puede ejecutar.

Después de que el analizador léxico, sintáctico y semántico revisan que el código no tenga errores, el generador de código toma la estructura del programa y la traduce paso por paso a NASM. Al final, toda esta salida se guarda en un archivo .asm, que se puede ensamblar y correr usando NASM y un enlazador.

CADENA
![image alt](https://github.com/Binbounan/PROYECTO-FINAL-SEM-TRADUCTORES/blob/d24475b3f978cba9005d626a3df185df11243ab0/cadena.png)


LEXICO
![image alt](https://github.com/Binbounan/PROYECTO-FINAL-SEM-TRADUCTORES/blob/77d2fa8417106f411734e6deb57db7c6438964b3/ANALI.png)
