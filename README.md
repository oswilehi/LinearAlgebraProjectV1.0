# LinearAlgebraProjectV1.0

# LinearAlgebraProject

### Preguntas

1. **¿En que consiste la convolución y cómo puede ser calculada?**
La definición matemática es que es un operador matemático que transforma dos funciones f y g en una tercera función que en cierto sentido representa la magnitud en la que se superponen f y una versión trasladada e invertida de g. Pero en otras palabras para entenderlo de una mejor manera, es la manera en que modificamos un píxel de las imagenes con la ayuda de otra pequeña matrix llamada kernel, la cual nos dará el nuevo píxel ya modificado.

2. **¿Qué es el Kernel de un filtro y para que se utiliza?**
Es una matriz más pequeña que la imagen original que nos permite modificar un pixel seleccionando una proporción de la imagen del mismo tamaño que el kernel para poder realizar una multiplicación de elemento por elemento.

3. **¿En que consiste un filtro Gaussiano?**
El filtro gaussiano consiste en desenfocar una imagen. Hacerla ver como difuminada.

4. **¿En qué consiste el filtro Sobel?**
Es el filtro que nos permite resaltar los bordes horizontales y verticales de una imagen.

5. **Describa el algoritmo de detección de bordes Canny.**
El propósito de Canny era descubrir el algoritmo óptimo de detección de bordes. Para que un detector de bordes pueda ser considerado óptimo debe cumplir los siguientes puntos:

    * Buena detección- el algoritmo debe marcar el mayor número real en los bordes de la imagen como sea posible.
    * Buena localización- los bordes de marca deben estar lo más cerca posible del borde de la imagen real.
    * Respuesta mínima - El borde de una imagen sólo debe ser marcado una vez, y siempre que sea posible, el ruido de la imagen no debe         crear falsos bordes.
Para satisfacer estos requisitos Canny utiliza el cálculo de variaciones - una técnica que encuentra la función que optimiza un funcional indicado. La función óptima en el algoritmo de Canny es descrito por la suma de cuatro términos exponenciales, pero se puede aproximar por la primera derivada de una gaussiana.

### Prueba en Imagen

#### Tiempos en imagenes

TIEMPOS:
![alt text](https://github.com/oswilehi/LinearAlgebraProjectV1.0/blob/master/LinearAlgebraProject/Imagenes%20README/Tiempos_Imagenes.PNG "Imagen de perro")

#### Tiempo en video

TIEMPO:
1. ![alt text](https://github.com/oswilehi/LinearAlgebraProjectV1.0/blob/master/LinearAlgebraProject/Imagenes%20README/Tiempo_VIDEO_NUEVO.PNG)
2. ![alt text](https://github.com/oswilehi/LinearAlgebraProjectV1.0/blob/master/LinearAlgebraProject/Imagenes%20README/Tiempo_video.PNG "Video de Batman")
