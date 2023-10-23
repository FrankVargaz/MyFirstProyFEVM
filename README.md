# MyFirstProyFEVM
Para este primer repositorio se utilizarán los parámetros especificados del proyecto del primer módulo basado en el repositorio de Ucam del proyecto 1: Sistema de Costos.

Siendo explicado por los parámetros del programa:

**Objetivos de aprendizaje**
El objetivo principal de este proyecto es construir un pseudocódigo que permita:
Entender y aplicar conceptos básicos de algoritmos y programación estructurada.
Utilizar variables, constantes, operadores aritméticos y de comparación.
Implementar control de flujo mediante condiciones.
Utilizar Git como sistema de control de versiones y colaborar en GitHub.

**¿Qué construirás en este proyecto?**
Construirás un algoritmo en pseudocódigo que simule un sistema para calcular el costo de un producto con base en su precio original y el porcentaje de descuento aplicado. El algoritmo debe cumplir con los siguientes requisitos:

- Leer el precio original del producto.
- Aplicar un descuento al producto si es aplicable (por ejemplo, si el cliente tiene un cupón de descuento).
- Aplicar impuestos al producto (por ejemplo, el IVA u otros impuestos).
- Si el cliente compra más de un artículo, aplicar un descuento por cantidad.
- Calcular el costo de envío basado en el destino y el peso del paquete.
- Calcular el costo final del producto sumando el precio con descuento, impuestos, descuento por cantidad y costo de envío.
- Mostrar el costo final del producto, desglosando los diferentes componentes (descuentos, impuestos, descuento por cantidad y costo de envío).


**Ejemplo.** 

Imagina que un cliente desea comprar un par de zapatos deportivos en línea.
- Los siguientes son los detalles del producto y la información del cliente:
- Precio original: $100
- Cupón de descuento: 10% de descuento
- IVA (impuesto al valor agregado): 12%
- Cantidad: 2 pares de zapatos deportivos
- Peso del paquete: 3 kg
- Destino del envío: Nueva York
- De acuerdo con los requisitos del proyecto, el algoritmo deberá realizar lo siguiente:
- Leer el precio original del producto: $100
- Aplicar el descuento del cupón: 10% de descuento, es decir, el precio con descuento será $90.
- Aplicar el IVA: 12% del precio con descuento, es decir, $90 * 1.12 = $100.80.
- Aplicar el descuento por cantidad (2 pares de zapatos): 5% de descuento, es decir, $100.80 * 0.95 = $95.76.
- Calcular el costo de envío basado en el peso y el destino: $10 (costo fijo) + $2 * 3 kg = $16.
- Calcular el costo final del producto: ($95.76 * 2) + $16 = $207.52.
- Al final, el algoritmo deberá mostrar el costo final del producto ($207.52) y desglosar sus componentes: descuento, impuestos, descuento por cantidad y costo de envío.
- Subirás tu solución a un repositorio de GitHub, el cual compartirás con tu equipo educativo, posteriormente.

---
## MI PROJECTO.

Basado en las anteriores premisas del projecto, ahora muestro mi avance empezamos por la definicion de las variables:


![Captura de pantalla 2023-10-21 022438](https://github.com/FrankVargaz/MyFirstProyFEVM/assets/146491297/b25762d2-f841-45f5-aedd-812abc533f8a)

En la imagen de arriba demuestro el uso de las variables, considernado los siguientes puntos:
- Se deven de devolver valores no enteros.
- Ciertas variables requiren de utilizar enteros.
- Los descuentos e impuestos requiren de una denominacion diferente para la cotejacion de los operadores aritmeticos.

---
Ahora veremos las determinaciones estaticas de las vriables (las que ya son constantes).

![Captura de pantalla 2023-10-21 022552](https://github.com/FrankVargaz/MyFirstProyFEVM/assets/146491297/50337545-541e-4214-ae79-e42c9f25ed50)



Como se puede observar se determinaron las constantes:
- El valor del impuesto.
- El valor del envio.

---

Seguido por las llamadas del sistema "Escribir".

![Captura de pantalla 2023-10-21 022636](https://github.com/FrankVargaz/MyFirstProyFEVM/assets/146491297/4b0a048e-9f56-4458-ba6d-45e16893ad2a)


Como se puede observar añadi un bucle de repetir (aunque no supe si añadir mas instancias de **SiNo*.)

---
El procedimiento de los Operadores aritmeticos.


![Captura de pantalla 2023-10-21 022711](https://github.com/FrankVargaz/MyFirstProyFEVM/assets/146491297/55d94e5c-e24a-42ff-8101-22f14e063a95)

Esta sin duda fue la mas dificil, de todos los procedimientos del algoritmo.

---

Calculo del envio y precio final.

![Captura de pantalla 2023-10-21 022752](https://github.com/FrankVargaz/MyFirstProyFEVM/assets/146491297/d23e6fc2-d488-4854-991c-58496ee37049)

En esta parte me tarde en encontrar una letra que no coincidia con las variables de arriba, lo que me recuerda aun libro que lei y de manera mundana deja pasar de mi memoria "The Clean Code".

---

El final del pseudocodigo.

![Captura de pantalla 2023-10-21 022814](https://github.com/FrankVargaz/MyFirstProyFEVM/assets/146491297/a89e1c03-5135-4903-bb19-4622adde9914)

Esta es la seccion que mas facil se me hace por que todo lo que hiciste arriba ahora tiene sentido, es como llamar a alguien para que te pase el numero de un amigo por que le quieres pedir dinero.

---






---

## Conclucion


En este proyecto de manera mas compleja pude aprender en respecto a los operadores aritmeticos (aunque aun me falta practicar), de igual manera comprendi como dar los valores que son constantes como enteros, los reales como decimales o incompletos y los logicos como aquellos que determinan la verdad o lo falso siendo el punto de inicio que el programa (pseudocogigo), la respuesta de lo que lee o ingresas como valores, siento que me falta comprender de mejor manera los valores aritmeticos y los bucles me costaron tabajo tambien.

---
