EXPLORATORY DATA ANALYSIS 
AUTOR: JOSE LUIS SENA ARBONA
FECHA: NOVIEMBRE 2024

ÍNDICE
1. Introduccion
2. Objetivos
3. Fuente de datos
5. Desafíos y Soluciones
6. Conclusiones


1. Introduccion
Este análisis se centra en entender el comportamiento de compra de los usuarios en un ecommerce a través de datos de ventas y eventos relacionados. El objetivo es identificar patrones de uso por dispositivo, país y horario, así como analizar la relación entre el uso del carrito de compras y las conversiones. Estos hallazgos ayudarán a definir estrategias de marketing que aumenten las ventas mediante acciones basadas en el comportamiento del usuario.

2. Objetivos

Los objetivos principales del análisis son:

    Identificar los dispositivos más utilizados por los usuarios para realizar compras en los tres países con más ventas.
    Determinar los días y horas de mayor actividad de compra para implementar promociones en los momentos clave.
    Analizar el comportamiento de los usuarios en el proceso de compra, especialmente aquellos que añaden productos al carrito pero no completan la compra.
    Evaluar la relación entre el número de "add to cart" (añadir al carrito) y las compras finales para mejorar la tasa de conversión.

3. Fuentes de datos

Incluye aquí una breve descripción del dataset o datasets de los que partirás para poder evaluar tu hipótesis.
También incluye el origen de estos datos y su fuente:

events1.csv: Incluye eventos especificos del usuario en la tienda online. Lo que me permitirá mapear los recorridos de los usuarios en el embudo de conversión, identificar las acciones previas al abandono del carrito o a la compra, y analizar la frecuencia y secuencia de eventos clave.

item.csv: Contiene detalles de productos como el nombre, marca o categorías de productos. Este archivo me ayudará a entender que productos o categorías de productos tienen mayor conversión o tienen un alto porcentaje de rebote. Esto es útil para segmentar usuarios en función del tipo de producto de interés y poder crear estrategias personalizadas de marketing para esos usuarios.

users.csv: Contiene información de usuarios (ID, LTV y fecha de registro). Me servirá para buscar patronces de comportamiento de los usuarios.


4. Desafios y Soluciones

        Datos incompletos o faltantes: Algunos valores en las columnas no estaban estandarizados. Para abordar esto, se limpiaron y organizaron los datos antes de proceder al análisis.

        Clasificación de dispositivos: Los dispositivos debían estar organizados en categorías específicas (móvil, ordenador y tablet). Se utilizó un enfoque de reindexación para asegurar que todos los dispositivos estuvieran representados.

        Interpretación de la relación “Add to Cart” y compras: La correlación no era muy alta, por lo que se necesitó un análisis adicional para identificar barreras en el proceso de compra y comprender mejor el comportamiento de los usuarios.     

5. Conclusiones

    Este análisis proporciona insights clave para optimizar la experiencia de usuario y crear estrategias de marketing específicas. La implementación de promociones en momentos de alta actividad, la optimización para dispositivos móviles y la recuperación de carritos abandonados son tácticas que podrían ayudar a maximizar las ventas en este ecommerce.
