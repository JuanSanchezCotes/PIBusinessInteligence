<p align="center"><img src="Images/HENRY.png"></p>

<p align="center"><img src="Images/Intro.png"></p>

## <h1 align=center> Siniestros Viales (CABA) </h1>

# <h1 align='center'> Proyecto Individual 2: Business Inteligence</h1>

<h2 align='center'> Data Analyst</h2>

<h2 align='center'> JUAN CARLOS SANCHEZ COTES, DATAPT06</h2>


¡Bienvenido al repositorio del Proyecto Integral de Análisis de Siniestros Viales en la Ciudad Autónoma de Buenos Aires (CABA)!<br>

# Indice del contenido:

- [Introducción](#introducción)
- [Contexto](#contexto)
- [Desarrollo del Proyecto](#desarrollo-del-proyecto)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Dashboard en Power BI](#dashboard-en-power-bi)
- [Análisis y Conclusiones](#análisis-y-conclusiones)
- [KPI](#kpi)
- [Recomendaciones](#recomendaciones)
- [Fuetes](#fuentes)
- [Contacto](#contacto)



# Introducción:
En el marco del Proyecto Integral de Análisis de Siniestros Viales en la Ciudad Autónoma de Buenos Aires (CABA), se plantea una propuesta de colaboración con el Observatorio de Movilidad y Seguridad Vial (OMSV). El objetivo principal de esta iniciativa es llevar a cabo un análisis detallado de los datos relativos a los siniestros viales ocurridos entre los años 2016 y 2021. La principal misión es proporcionar información valiosa que permita a las autoridades locales implementar medidas efectivas para reducir el número de víctimas fatales en accidentes de tráfico.

# Contexto:
Argentina se encuentra ante una situación alarmante en cuanto a las fatalidades causadas por accidentes de tráfico, según los reportes del Sistema Nacional de Información Criminal (SNIC). Entre 2018 y 2022, se documentaron 19.630 fallecimientos en siniestros viales en todo el país, equivalente a un promedio diario de 11 personas. Estas estadísticas revelan un problema de alcance nacional que requiere atención específica en la Ciudad de Buenos Aires.
El proyecto se centra en realizar un análisis exhaustivo de los accidentes de tráfico en CABA, buscando identificar patrones, tendencias y factores clave que puedan orientar la toma de decisiones fundamentadas. Adoptando un enfoque integral, se pretende comprender la dinámica de estos incidentes, considerando aspectos temporales, geográficos y la influencia de diversos tipos de vehículos y actores en las vías públicas.

# Desarrollo del Proyecto
El desarrollo del proyecto se divide en varias etapas:
- Extracción, transformación y carga (ETL): Se cargan y transforman los datos de siniestros viales para su posterior análisis.
- Análisis Exploratorio de Datos (EDA): Utilizando Pandas, Numpy, Seaborn, Matplotlib y entre otros, se identificaron patrones, relaciones y tendencias en los sets de datos. Se encontraron variables clave para la presentación en el tablero de mando (dashboard).
- Creación del Dashboard en Power BI: Se desarrolla un tablero de mando interactivo en Power BI destacando análisis clave por variables temporales, genero, geoespaciales y relacionadas con las víctimas.
- Definición y medición de KPIs: Se establecen Indicadores Clave de Desempeño (KPIs, por sus siglas en ingles) 
- Conclusiones: Se presentan conclusiones y recomendaciones para mejorar la seguridad vial en CABA.

# Estructura del Proyecto
Se establecion una estructura y definida del proyecto con la finalidad de cuidar el orden para facilitar la comprensión y reproducción. A continuación, se detalla la estructura de carpetas y archivos:

- /Data: Contiene los conjuntos de datos utilizados, los datos limpios
- /Images: Almacena imágenes relevantes para visualizaciones, armado del Dashboard y del README.
- /ETL y EDA: Se encuentran los archivos .ipynb de Análisis Exploratorio de Datos y Extracción, transformación y carga de los datos.
- README.md: descripción y documentación del proyecto

# Tecnologías Utilizadas

El proyecto hace uso de diversas tecnologías y herramientas para realizar un análisis exhaustivo de los siniestros viales. Algunas de las principales tecnologías utilizadas incluyen:

- [![Visual Studio Code](https://img.shields.io/badge/IDE-Visual%20Studio%20Code-blue)](https://code.visualstudio.com/)
- [![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)](https://jupyter.org/)
- [![Pandas](https://img.shields.io/badge/Library-Pandas-brightgreen)](https://pandas.pydata.org/)
- [![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-blue)](https://matplotlib.org/)
- [![Seaborn](https://img.shields.io/badge/Library-Seaborn-yellow)](https://seaborn.pydata.org/)
- [![GitHub](https://img.shields.io/badge/Platform-GitHub-lightgrey)](https://github.com/)
- [![Git](https://img.shields.io/badge/Version%20Control-Git-blue)](https://git-scm.com/)
- [![Power BI](https://img.shields.io/badge/BI%20Tool-Power%20BI-yellow)](https://powerbi.microsoft.com/)

# Dashboard en Power BI

<div style="display: flex; justify-content: center;">
    <div>
        <p align="center"><img src="Images\BIKPI.png"></p>
    </div>
    <div>
        <p align="center"><img src="Images\BITemp.png"></p>
    </div>
</div>

# Análisis y Conclusiones:

En el examen de los datos relacionados con los accidentes, se identificaron diversos patrones temporales y características de las víctimas.<br> En relación con la distribución anual, se resalta que alrededor del 60% de las fatalidades tuvieron lugar en los primeros tres años del conjunto de datos, observándose una disminución en los años más recientes, especialmente en 2020.<br> Es importante tener en cuenta que estos datos corresponden a la Ciudad Autónoma de Buenos Aires, y durante el año 2020, se experimentó una situación excepcional debido a la pandemia de COVID-19 a nivel mundial.

<p align="center"><img src="Images\CantAcc.png" width="600" height="350"></p>

De cada 4 víctimas, 3 son hombres (75%), y se nota que, en general, son más jóvenes que las mujeres. La mayoría de los hombres jóvenes (entre 15 y 30 años) actúan como conductores de motocicletas, mientras que las mujeres jóvenes suelen ser pasajeras de motocicletas. Los adultos mayores (65 años en adelante), tanto hombres como mujeres, son predominantemente peatones. En el caso de los hombres adultos (entre 30 y 65 años), siguen el mismo patrón que los jóvenes al ser conductores de motocicletas. En contraste, las mujeres mayores (entre 30 y 65 años) se asemejan a las mujeres adultas mayores, siendo mayormente peatones.

<p align="center"><img src="Images\genero.png" width="600" height="350"></p>

El examen de la distribución de edades según el sexo muestra que, en los hombres, a medida que la edad disminuye, aumenta la propensión a verse involucrados en siniestros viales. En cambio, en las mujeres, la edad parece no influir significativamente, mostrando una distribución más uniforme sin patrones claros.

<p align="center"><img src="Images\etareo.png" width="300" height="225"></p>

# KPI

Se plantearon 3 objetivos para disminuir las víctimas en siniestros, los 3 Indicadores Claves de Rendimiento (KPI) son los siguientes:

- *Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior*.
  
  Definimos a la **tasa de homicidios en siniestros viales** como el número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes en un área geográfica durante un período de tiempo específico.
  Su fórmula es: (Número de homicidios en siniestros viales / Población total) * 100,000
  
- *Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior*.
  
  Definimos a la **cantidad de accidentes mortales de motociclistas en siniestros viales** como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaban en moto en un determinado periodo temporal.
  Su fórmula para medir la evolución de los accidentes mortales con víctimas en moto es: (Número de accidentes mortales con víctimas en moto en el año anterior - Número de accidentes mortales con víctimas en moto en el año actual) / (Número de accidentes mortales con víctimas en moto en el año anterior) * 100

- *Reducir en un 10% la cantidad de accidentes mortales de peatones en el último año, en CABA, respecto al año anterior*.
  
  Definimos a la **cantidad de accidentes mortales de peatones en siniestros viales** como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas peatones en un determinado periodo temporal.
  Su fórmula para medir la evolución de los accidentes mortales con víctimas peatones es: (Número de accidentes mortales con víctimas peatones en el año anterior - Número de accidentes mortales con víctimas peatones en el año actual) / (Número de accidentes mortales con víctimas peatones en el año anterior) * 100

<p align="center"><img src="Images\kpi.png"  width="600" height="165"></p>

# Recomendaciones:

- Continuar monitoreando los objetivos propuestos acompañados de campañas puntuales, en especial a conductores de motos.
- Reforzar las campañas de seguridad vial principalmente en las primeras horas de la mañana.
- Mejorar la concientización sobre los accidentes, centrándose principalmente en los hombres en el rango de edad activos (15-64), quienes continúan siendo los más propensos a sufrir siniestros mortales.
- Generar campañas de reducción de velocidad y respetos al pare y/o semaforos.

# Fuentes:
- https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales Consultado el 28 febrero 2024
- https://data.buenosaires.gob.ar/dataset/estructura-demografica Consultado el 28 febrero 2024

# Contacto

<div style="display: flex; align-items: center;">
  <a href="https://www.linkedin.com/in/juan-sanchez-cotes/" style="margin-right: 10px;">
    <img src="./images/in_linked_linkedin_media_social_icon_124259.png" alt="LinkedIn" width="40" height="40">
  </a>
  <a href="mailto:juancsanchez1992@gmail.com" style="margin-right: 10px;">
    <img src="./images/gmail_new_logo_icon_159149.png" alt="Gmail" width="40" height="40">
  </a>
</div>
