# Dashboard de desempeño comercial - Andes Retail Group

Este proyecto desarrolla una solución analítica de inteligencia de negocios para evaluar el rendimiento comercial y la eficiencia del catálogo de una empresa de retail durante el periodo 2024-2025. El trabajo integra el procesamiento de datos en python con la creación de tableros de control interactivos en tableau public, visible en: https://public.tableau.com/app/profile/jos.miguel.ruiz/viz/Proyecto9Dashboarddedesempeocomercial_17818201490570/Dashboarddetalledeproductos 

## Estructura del repositorio

* `notebooks/`: Libreta de jupyter con la limpieza, exploración de datos y segmentación analítica.
* `dashboards/`: Enlaces directos a la solución visual interactiva.

## Resumen del proyecto

El análisis se estructuró en dos niveles metodológicos clave:

1. **Overview ejecutivo (Vista 1):** Tablero orientado a la alta dirección que mapea la evolución temporal de los ingresos, la distribución geográfica mediante mapas interactivos y el comportamiento de las ventas por segmento de cliente y categoría.
2. **Análisis detallado (Vista 2):** Matriz operativa que cruza el catálogo de productos con la métrica física de unidades vendidas y una variable calculada denominada nivel de venta para identificar ineficiencias en la rotación y el valor generado.

## Principales hallazgos

* Se identificó una alta concentración de ingresos en mercados específicos, lo que representa un riesgo de centralización para la compañía.
* La vista de detalle reveló que múltiples categorías registran un alto volumen de movimiento logístico (unidades vendidas) pero con un retorno financiero marginal, lo que sugiere la necesidad de una reestructuración estratégica de precios o revisión de márgenes de ganancia.

## Herramientas utilizadas

* Python (pandas, jupyter notebooks).
* Tableau public (maquetación responsiva y filtros globales sincronizados).
