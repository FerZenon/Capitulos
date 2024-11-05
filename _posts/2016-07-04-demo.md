---
title: CAPITULO 10    
layout: post
permalink: /demo/
---

<section>
   <h1 style="font-size: 30px;">Deteccion y Corrección de Errores</h1>
</section>

<section>
   <h1 style="font-size: 30px;">Concepto</h1>
   <h3 style="font-size: 40px;">La detección y corrección de errores son mecanismos esenciales para garantizar la integridad de los datos en las comunicaciones digitales.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Corrupción de datos</h1>
   <h3 style="font-size: 40px;">Los datos pueden corromperse durante la transmisión por diversas razones, lo que requiere que los sistemas sean capaces de detectar y corregir errores.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Tipos de errores</h1>
   <h3 style="font-size: 40px;">Existen diferentes tipos de errores en la transmisión de datos principalmente errores de un solo bit y errores de ráfaga de longitud 8, que afectan múltiples bits de datos.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Erros de un solo bit </h1>
   <h3 style="font-size: 40px;">Ocurre cuando un bit en una unidad de datos cambia.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Error de ráfaga de longitud 8</h1>
   <h3 style="font-size: 40px;">Este error afecta a múltiples bits consecutivos en una transmisión. Estos pueden distorsionar una porción significativa del mensaje original.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Redundancia</h1>
   <h3 style="font-size: 40px;">La redundancia es una técnica de detección de errores en la que se añaden bits adicionales al mensaje para verificar su precisión.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Detección vs Corrección</h1>
   <h3 style="font-size: 40px;">La detección de errores identifica la presencia de errores en los datos, mientras que la corrección no solo los detecta sino que también intenta corregir los errores encontrados.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Corrección de error hacia adelante vs Retransmisión</h1>
   <h3 style="font-size: 40px;">La corrección de errores hacia adelante (FEC) permite corregir errores en el receptor sin necesidad de retransmitir los datos, mientras que la retransmisión solicita al transmisor que envíe nuevamente el paquete cuando se detecta un error.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Codificación</h1>
   <h3 style="font-size: 40px;">El emisor añade redundancia a los bits mientras un proceso crea una relación entre los bits redundantes y los bits verdaderos detectados.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Aritmética modular</h1>
   <h3 style="font-size: 40px;">La aritmética modular es un sistema matemático que se usa para detectar y corregir errores. Trabaja con operaciones dentro de un rango finito y es la base de muchas técnicas de verificación de errores.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Aritmética módulo 2</h1>
   <h3 style="font-size: 40px;">La aritmética módulo 2 utiliza operaciones de suma y multiplicación en un sistema binario. Es común en algoritmos de detección de errores, como la verificación de redundancia cíclica (CRC).</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Codificación por bloques</h1>
   <h3 style="font-size: 40px;">En la codificación por bloques, los datos se dividen en bloques de longitud fija y cada bloque se procesa de forma independiente. Esta técnica permite detectar y corregir errores en segmentos específicos del mensaje.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Detección de errores</h1>
   <h3 style="font-size: 40px;">Existen maneras de detectar errores usando la codificación por bloques. - El receptor encuentra la lista de los 'Códigos' válidos. - El 'Código' original ha sido cambiado a uno invalido.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Distancia de Hamming</h1>
   <h3 style="font-size: 40px;">La distancia de Hamming mide el número de posiciones en las que los bits de dos palabras binarias son diferentes. Es una herramienta útil en la detección de errores y en la corrección de un solo bit.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Tres parámetros de Hamming</h1>
   <h3 style="font-size: 40px;">Los códigos de Hamming están definidos por tres parámetros: longitud de la palabra de código (n), longitud de los datos (k), y el número de bits de verificación.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Distancia y error de Hamming</h1>
   <h3 style="font-size: 40px;">La distancia de Hamming se usa para cuantificar errores en los datos, ayudando en la corrección de errores, especialmente para corregir errores de un solo bit y detectar de dos bits.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Distancia mínima para la detección de errores</h1>
   <h3 style="font-size: 40px;">La distancia mínima determina la capacidad de un código para detectar errores: una distancia mínima de 2 detecta errores de un bit, mientras que una de 3 permite detectar errores de hasta dos bits.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Codificación de bloques</h1>
</section>
<section>
   <h1 style="font-size: 30px;">¿Qué son?</h1>
   <h3 style="font-size: 40px;">Casi todos los códigos de bloques que se utilizan hoy en día pertenecen a un subconjunto denominado códigos de bloques lineales. El uso de códigos de bloques no lineales para la detección y corrección de errores no está tan extendido porque su estructura dificulta el análisis teórico y la implementación.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Distancia mínima para códigos de bloques lineales</h1>
   <h3 style="font-size: 40px;">En un código de bloque lineal, la distancia mínima entre palabras de código define la cantidad de errores que el código puede detectar y corregir.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Códigos de Hamming</h1>
   <h3 style="font-size: 40px;">Los códigos de Hamming son códigos de corrección de errores que permiten detectar y corregir errores de un solo bit en palabras de datos binarias.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Rendimiento de un código de Hamming</h1>
   <h3 style="font-size: 40px;">El código de Hamming es eficiente en la corrección de errores de un solo bit y tiene una baja sobrecarga, lo que lo hace ideal para aplicaciones de transmisión de datos básicas.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Códigos cíclicos</h1>
</section>

<section>
   <h1 style="font-size: 30px;">¿Qué son?</h1>
   <h3 style="font-size: 40px;"> En un código cíclico, si una palabra de código se desplaza (rota) cíclicamente, el resultado es otra palabra de código</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Comprobación de redundancia cíclica (CRC)</h1>
   <h3 style="font-size: 40px;">CRC es un tipo de código cíclico usado ampliamente en redes y telecomunicaciones para detectar errores en los datos transmitidos.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Codificador y descifrador</h1>
   <h3 style="font-size: 40px;">El codificador CRC genera una palabra de código basada en el polinomio divisor, y el descifrador verifica la precisión de los datos recibidos aplicando el mismo polinomio.</h3>
</section>


<section>
   <h1 style="font-size: 30px;">Diseño general</h1>
   <h3 style="font-size: 40px;">El diseño de sistemas de códigos cíclicos implica el uso de polinomios para definir la estructura del código y asegurar su eficacia en la corrección de errores.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Polinomios</h1>
   <h3 style="font-size: 40px;">Un patrón de ceros y unos puede representarse como un polinomio con coeficientes de 0 y 1.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Grado de un polinomio</h1>
   <h3 style="font-size: 40px;">El grado de un polinomio se define como el exponente más alto de sus términos. Es crucial en la determinación de la longitud y la complejidad de los códigos cíclicos.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Tipos</h1>
   <h3 style="font-size: 40px;">Los tipos son suma y resta de polinomios y multiplicar dos polinomios.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Análisis de código cíclico</h1>
   <h3 style="font-size: 40px;">El análisis de código cíclico implica la evaluación de la capacidad del código para detectar y corregir errores.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Error de un solo bit</h1>
   <h3 style="font-size: 40px;">Los códigos cíclicos son efectivos para detectar y corregir errores de un solo bit, asegurando la integridad de los datos transmitidos.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Números impares de errores</h1>
   <h3 style="font-size: 40px;">Los códigos cíclicos pueden ser diseñados para detectar errores en números impares de bits, mejorando su robustez en entornos de transmisión con interferencias.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Errores de ráfaga</h1>
   <h3 style="font-size: 40px;">Los códigos cíclicos son especialmente útiles en la detección de errores de ráfaga, que afectan a múltiples bits consecutivos en una transmisión.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Polinomios estándar</h1>
   <h3 style="font-size: 40px;">Los polinomios estándar son aquellos que cumplen con ciertos criterios, y su elección es fundamental para el rendimiento de los códigos cíclicos.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Ventaja de los códigos cíclicos</h1>
   <h3 style="font-size: 40px;">Los códigos cíclicos permiten la detección y corrección eficiente de errores en datos transmitidos, además de facilitar la implementación en hardware.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Suma de verificación</h1>
</section>

<section>
   <h1 style="font-size: 30px;">¿Qué es?</h1>
   <h3 style="font-size: 40px;"> La suma de comprobación se basa en el concepto de redundancia. Varios protocolos aún utilizan la suma de comprobación para la detección de errores.</h3>
</section>

<section>
   <h1 style="font-size: 30px;">Suma de comprobación de Internet</h1>
   <h3 style="font-size: 40px;">La naturaleza de la suma de comprobación es tratar las palabras como números y sumarlas y complementarlas es muy adecuada para la implementación de software.</h3>
</section>

<section style="text-align: left;">
   <h1 style="font-size: 30px;">THE END</h1>
   <p>
       - <a href="http://slides.com">Try the online editor</a> <br>
       - <a href="https://github.com/hakimel/reveal.js">Source code &amp; documentation</a>
   </p>
</section>
