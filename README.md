<h1 align="center"> Proyecto Individual 02 </h1>
#  Análisis de Datos de Accidentes Aereos
¡Bienvenido al análisis de datos de accidentes aereos! 
Este proyecto tiene como finalidad identificar patrones y ofrecer recomendaciones para mejorar la seguridad aereonautica.

## Problemática
El proyecto se enfoca en analizar accidentes aéreos, que son eventos inesperados y potencialmente catastróficos que involucran aeronaves. Estos accidentes pueden ser causados por una variedad de factores, como errores humanos, fallos técnicos, condiciones meteorológicas adversas y problemas de mantenimiento. Tanto las vidas humanas como los aspectos económicos pueden verse afectados por estos incidentes.

La Organización de Aviación Civil Internacional (OACI), como parte de la ONU, lidera este esfuerzo para analizar accidentes aéreos que han ocurrido desde principios del siglo XX. Su objetivo es realizar un análisis de datos exhaustivo y crear un dashboard con visualizaciones que ayuden a comprender mejor la causalidad de estos accidentes. 
 
## Estructura del Repositorio 

-   **Archivos csv**: Es la carpeta donde están los dataset reducidos para hacer las transformaciones de los datos.

-   **ETL**: Notebook en donde se hace la carga de datos y las transformaciones.

-   **EDA.ipynb**: Notebook que contiene el análisis exploratorio de datos.

-   **Analisis**: Dashboard donde estan los datos visualizados y KPIs.

## Desarrollo del Proyecto

Durante el desarrollo del proyecto, se han generado los siguientes archivos:

1. **Datasets**: Disponemos de varios archivos CSV que contienen datos esenciales para nuestro análisis. Estos conjuntos de datos abarcan información sobre accidentes, víctimas mortales, pasajeros y fechas. Todos estos datasets han pasado por un proceso ETL (Extract, Transform, Load) para garantizar su utilidad en el EDA (Exploratory Data Analysis) y en Power BI.

2. **ETL**: Se ha desarrollado un archivo en Python específicamente para el proceso de Extracción, Transformación y Carga de datos. Durante este proceso, se llevaron a cabo varias acciones, entre las cuales se incluyen:

- Eliminación de columnas no relevantes para nuestro análisis.
- Cambio de tipos de datos para una manipulación más efectiva.
- Normalización de nombres de columnas para uniformidad entre los archivos.
- Manejo de valores faltantes o atípicos mediante la asignación de NaN.
- Ajuste de formatos de fechas para su procesamiento adecuado.

3. **EDA**: Se realizó un análisis exploratorio de datos que incluye visualizaciones y tablas detalladas. Algunas de las acciones destacadas en este proceso abarcan:

- Creación de tablas para profundizar en aspectos como la ubicación de los accidentes, el número de víctimas mortales, la identificación de años con valores atípicos y comparativas con la cantidad de pasajeros a bordo.

4. **Dashboard en Power BI**:
El dashboard en Power BI consta de múltiples páginas que ofrecen información significativa sobre accidentes aéreos y sus víctimas. A continuación, se detallan estas páginas:

- Página de Accidentes: En esta página se presenta la frecuencia y ubicación de los accidentes aéreos. Esta información es valiosa para identificar las zonas con mayor incidencia de víctimas mortales, lo que puede ayudar al OACI a enfocar sus esfuerzos en investigar y prevenir estos accidentes.

- Página de Víctimas por Década: Aquí se analizan las tendencias a lo largo de las décadas y se exploran los factores que pueden haber contribuido a los accidentes aéreos en diferentes épocas. Esto proporciona una perspectiva histórica para comprender mejor los cambios en la tecnología aeronáutica y las posibles razones detrás de los accidentes.

- Página de KPIs: En esta página se presentan los Indicadores Clave de Desempeño (KPI) que permiten evaluar las acciones tomadas por el OACI para reducir los accidentes aéreos y sus víctimas. Estos KPI incluyen:

## KPI 1: Evaluación de la Tasa de Fatalidad de la Tripulación

El primer Indicador Clave de Desempeño (KPI) se enfoca en la seguridad de la tripulación en los últimos 10 años, en comparación con la década anterior. Su objetivo es evaluar la disminución de un 10% en la tasa de fatalidad de la tripulación. Este KPI es crucial para medir la eficacia de las medidas de seguridad implementadas, con un enfoque específico en la protección de la vida de los miembros de la tripulación. Una disminución del 10% indicaría un progreso significativo en la seguridad de las operaciones aéreas, lo que potencialmente reduce el riesgo para el personal a bordo de las aeronaves.

## KPI 2: Evaluación de la Reducción de Accidentes

El segundo Indicador Clave de Desempeño (KPI) se centra en la reducción de accidentes en los últimos 10 años, en comparación con la década anterior. El objetivo es evaluar la reducción de un 30% en la cantidad total de accidentes. Este KPI apunta a medir el impacto de las medidas de seguridad en la prevención de accidentes aéreos en general. Una disminución del 30% en el número de accidentes indicaría que las acciones y políticas implementadas han tenido un efecto positivo en la seguridad general de la aviación. La reducción de accidentes es un objetivo fundamental para preservar vidas y minimizar daños materiales.

5. **Conclusiones**

**La OACI cuenta con unas medidas de seguridad que pueden ser complementadas con ciertas recomendaciones que a continuación daremos de acuerdo a los hallazgos encontrados en cada una de las páginas del dashboard:**

- Es fundamental llevar a cabo evaluaciones detalladas, especialmente en aeronaves antiguas, con el propósito de asegurar que cumplan con los estándares de seguridad actuales.
- La implementación de un conjunto más riguroso de precauciones y reglamentos es esencial para mitigar los riesgos.
- Se recomienda impulsar y promover el uso de aeronaves modernas por parte de las aerolíneas, gradualmente retirando las aeronaves más antiguas del servicio.
- La planificación a largo plazo, hasta el año 2035, para la progresiva retirada de aeronaves fabricadas antes del año 2000 es un paso significativo.
- La donación de materiales de aeronaves desechadas a instituciones de investigación puede contribuir a avances tecnológicos y científicos.
- Aumentar la presencia de agentes de control en zonas con históricos de alto riesgo es esencial para una supervisión más efectiva.

## Autor
* **Santiago Ituyan Figueroa**  - [Santiago Ituyan Figueroa](https://www.linkedin.com/in/santiago-ituyan-a3274613a/)
