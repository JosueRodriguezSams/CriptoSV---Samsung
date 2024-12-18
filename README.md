# CriptoSV---Samsung

En junio de 2021, El Salvador se convirtió en el primer país en adoptar Bitcoin como moneda de curso legal. Este proyecto tiene como objetivo analizar y evaluar si esta decisión ha tenido un impacto significativo en la macroeconomía salvadoreña.

Para ello, hemos recopilado y comparado datos históricos de variables económicas clave, como el Producto Interno Bruto (PIB), el Índice de Precios al Consumidor (IPC), la deuda externa pública, las reservas de divisas, y la inversión, con el precio histórico del Bitcoin. Utilizamos técnicas de análisis de datos para explorar correlaciones y patrones entre estas variables, buscando evidencia sobre cómo la adopción del Bitcoin ha influido en la economía del país.

Este análisis proporciona una base para comprender los posibles efectos de la implementación del Bitcoin en la economía salvadoreña y contribuye al debate sobre la influencia del uso de criptomonedas en contextos macroeconómicos.

## Tabla de contenidos

1. [Arquitectura](#Arquitectura)
2. [Proceso](#Proceso)
3. [Funcionalidades](#Funcionalidades)
4. [Estado del proyecto](#EstadoDelProyecto)
5. [Agradecimientos](#Agradecimientos)

## Arquitectura del proyecto + imagen

## Proceso de desarrollo:

- Fuentes de datasets

    <br>A continuación, una lista de los enlaces a los diferentes datasets utilizados: <br><br>

    - [Deuda pública](https://estadisticas.bcr.gob.sv/serie/deuda-publica-total-anual)
    - [Precio histórico del bitcoin](https://www.kaggle.com/datasets/shiivvvaam/bitcoin-historical-data)
    - [Posición de inversión internacional](https://estadisticas.bcr.gob.sv/serie/ii-7a-posicion-de-inversion-internacional)
    - [Índice de precios al consumidor](https://estadisticas.bcr.gob.sv/serie/indice-de-precios-al-consumidor-ipc)
    - [Producto interno bruto](https://estadisticas.bcr.gob.sv/serie/producto-interno-bruto-produccion-gasto-e-ingreso-a-precios-corrientes)
    - [Reservas internacionales netas](https://estadisticas.bcr.gob.sv/serie/reservas-internacionales-netas-bcr)
    <br>

- Fusión de todos los datasets en un DataFrame

    <br>En un inicio, todos los dataset estaban separados en distintos daraframes, entonces lo fusionamos en uno solo:<br><br>

    ![dataframe_fusionado](assets/dataframe_fusionado.png)<br><br>

- Limpieza de datos

    - Valores faltantes:
    ![Valores_faltantes](assets/valores_faltantes.png)
    - Filas duplicadas:
    ![filas_duplicadas](assets/filas_duplicadas.png)
    - Valores atípicos:
    ![Valores_atipicos](assets/valores%20atípicos.png)

- Estadísticos:
    - Gráficas lineales:
        Precio historico del bitcoin:
        ![bitcoin_history](assets/bitcoin_history.png)<br>
        Reservas internacionales netas:
        ![rin](assets/rin.png)<br>
        Posición de inversión internacional neta:
        ![niip](assets/niip.png)<br>
        Producto interno bruto:
        ![pib](assets/pib.png)<br>
        Índice de precios al consumidor:
        ![ipc](assets/ipc.png)<br>
        Deusa externa pública:
        ![dep](assets/dep.png)<br><br>
    - Gráficas de puntos e historigrama (pairplot)
        ![pairplot](assets/pairplot.png)<br><br>
    - Análisis de normalidad de los datos:
        ![qqplot](assets/qqplot.png)<br><br>
    - Correlación de los datos
        ![correlacion](assets/correlacion.png)

## Funcionalidades extra:

Ejem 1: Integración del proyecto en una pág web

- Tecnología/Herramientas usadas …
- Arquitectura (img)


## Estado del proyecto

El proyecto se encuentra en una fase avanzada de desarrollo. Se han implementado las funcionalidades principales y se están realizando pruebas para asegurar su correcto funcionamiento. A continuación, se detallan los próximos pasos:

- Realizar pruebas adicionales y corregir posibles errores.
- Completar la documentación del proyecto.
- Preparar la versión final para su lanzamiento.

Se espera que el proyecto esté listo para su lanzamiento en las próximas horas.

## Agradecimientos

Queremos agradecer a todas las personas y organizaciones que han contribuido al desarrollo de este proyecto:

- A nuestro equipo de desarrollo por su dedicación y esfuerzo.
- A nuestros mentores y asesores por su valiosa orientación.
- A la comunidad de código abierto por las herramientas y recursos proporcionados.
- A Samsung Innovation Campus por darnos la oportunidad de educarnos y presentar este proyecto.

Gracias a todos por su apoyo y colaboración.
