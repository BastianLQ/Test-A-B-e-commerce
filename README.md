# Test-A-B-e-commerce
__Proyecto de análisis a la plataforma de delivery Instacart, análisis exploratiorio y visualización de datos__

<image src="https://github.com/BastianLQ/Analisis-Instacart/blob/main/N3.jpg" alt="Collage de gráficos">

_Fragmentos del notebook, para ver proyecto completo hacer click [aquí](https://portfoliodabastianlopez.on.drv.tw/Portafolio/An%C3%A1lisis%20Instacart.html)_

## Descripción del Proyecto
Junto con el departamento de marketing de la compañía en cuestión, se ha recopilado una lista de hipótesis que pueden ayudar a aumentar los ingresos. 
Se deben priorizar estas hipótesis, lanzar un test A/B y analizar los resultados.
  
## Herramientas Utilizadas
- __Lenguaje de Programación:__ Python.
- __Entorno de Desarrollo:__ Jupyter Notebook.
- __Bibliotecas:__ Pandas, Matplotlib.

## Proceso del Proyecto
Debido a las caracterísiticas del proyecto, su desarrollo se dividió en dos partes.

__Parte 1. Priorizar hipótesis__

El archivo `hypotheses_us.csv` contiene nueve hipótesis sobre cómo aumentar los ingresos de una tienda en línea con Reach, Impact, Confidence y Effort especificados para cada una.

Acciones a seguir:

- Aplicar el framework ICE para priorizar hipótesis. Ordenarlas en orden descendente de prioridad.
- Aplicar el framework RICE para priorizar hipótesis. Ordenarlas en orden descendente de prioridad.
- Mostrar cómo cambia la priorización de hipótesis cuando utilizas RICE en lugar de ICE. Proporcionar una explicación de los cambios.

__Parte 2. Análisis de test A/B__

Se realizó un test A/B y los resultados están en los archivos `orders_us.csv` y `visitors_us.csv`.

Analizar el test A/B:

- Representar gráficamente el ingreso acumulado por grupo. Hacer conclusiones y conjeturas.
- Representar gráficamente el tamaño de pedido promedio acumulado por grupo. Hacer conclusiones y conjeturas.
- Representar gráficamente la diferencia relativa en el tamaño de pedido promedio acumulado para el grupo B en comparación con el grupo A. Hacer conclusiones y conjeturas.
- Calcular la tasa de conversión de cada grupo como la relación entre los pedidos y el número de visitas de cada día. Representar gráficamente las tasas de conversión diarias de los dos grupos y describir la diferencia. Sacar conclusiones y hacer conjeturas.
- Trazar un gráfico de dispersión del número de pedidos por usuario. Hacer conclusiones y conjeturas.
- Calcular los percentiles 95 y 99 para el número de pedidos por usuario. Definir el punto en el cual un punto de datos se convierte en una anomalía.
- Trazar un gráfico de dispersión de los precios de los pedidos. Hacer conclusiones y conjeturas.
- Calcular los percentiles 95 y 99 de los precios de los pedidos. Definir el punto en el cual un punto de datos se convierte en una anomalía.
- Encontrar la significancia estadística de la diferencia en la conversión entre los grupos utilizando los datos en bruto. Hacer conclusiones y conjeturas.
- Encontrar la significancia estadística de la diferencia en el tamaño promedio de pedido entre los grupos utilizando los datos en bruto. Hacer conclusiones y conjeturas.
- Encontrar la significancia estadística de la diferencia en la conversión entre los grupos utilizando los datos filtrados. Hacer conclusiones y conjeturas.
- Encontrar la significancia estadística de la diferencia en el tamaño promedio de pedido entre los grupos utilizando los datos filtrados. Hacer conclusiones y conjeturas.
- Tomar una decisión basada en los resultados de la prueba. Las decisiones posibles son: 
    - 1. Parar la prueba, considerar a uno de los grupos como líder. 
    - 2. Parar la prueba, concluir que no hay diferencia entre los grupos. 
    - 3. Continuar la prueba.

## Relevancia de los descubrimientos
El análisis de datos de Instacart reveló patrones importantes en el comportamiento de compra de los clientes. Estos insights pueden ser utilizados para optimizar las estrategias de marketing, gestión de inventarios y mejorar la experiencia del cliente.

## Ejecuta el proyecto [aquí](https://portfoliodabastianlopez.on.drv.tw/Portafolio/An%C3%A1lisis%20Instacart.html)
Para ver el diccionario de datos, el desarrollo completo en código, todos los gráficos y las conclusiones, haga click en el enlace de arriba.
