# PI-Data-Analist
Analisis MOOCS

Proyecto MOOCs - Análisis de Datos de Cursos Online
Este proyecto tiene como objetivo analizar datos de cursos online (MOOCs) de diferentes plataformas y extraer conclusiones relevantes sobre las ventas, segmentación de cursos y tasas de conversión. El análisis se realiza desde el rol de un Data Analyst en una startup de tecnología interesada en ingresar al mercado de cursos online.

Estructura del Repositorio
Notebooks: Contiene el notebook principal del proyecto donde se realiza el análisis exploratorio de los datos y se generan visualizaciones.
Data: Carpeta donde se almacenan los archivos de datos utilizados en el proyecto.
Dashboard: Carpeta que contiene los archivos relacionados con el dashboard interactivo creado en Power BI.
README.md: Documento actual con información relevante sobre el proyecto.
Tareas Realizadas
Exploratory Data Analysis (EDA): Se llevó a cabo un análisis exploratorio de los datos de los cursos online. Se realizaron los siguientes pasos:

Carga de los datasets de cursos y reviews.
Limpieza y transformación de los datos.
Análisis de variables clave como precio, idioma, nivel y rating de los cursos.
Generación de visualizaciones para entender la demanda de los cursos en función de las variables analizadas.
Dashboard Interactivo: Se creó un dashboard interactivo en Power BI para presentar los resultados del análisis. El dashboard incluye filtros y permite explorar detalladamente los datos. Se utilizó una presentación clara y estética para facilitar la interpretación de la información.

KPIs: Se propusieron y se implementaron tres KPIs relevantes para el análisis de los MOOCs. Estos KPIs se incluyeron en el dashboard y se presentaron junto con su análisis y funcionalidad.

README: Se creó el archivo README.md actual con la estructura del repositorio y una descripción general del proyecto.

Instrucciones de Uso
Clona el repositorio en tu máquina local.
Abre el notebook principal (ETL and EDA.ipynb) en Jupyter Notebook y lee el dash boar interactivoo con sus bases de Datasets contenidos en el siguiente Link de Google Drive: https://drive.google.com/drive/folders/15mFiB_VQMWaNkTDje26RPNEWPyu4Xr1y?usp=sharing.
Ejecuta las celdas del notebook para realizar el análisis exploratorio y generar las visualizaciones.
Abre el archivo del dashboard interactivo (dashboard.pbix) en Power BI para explorar los resultados con mayor detalle.
En la presentación, explora el análisis y las conclusiones obtenidas, prestando especial atención a los KPIs propuestos.
Conclusiones
En este proyecto, se analizaron los datos de cursos online (MOOCs) para comprender la demanda y los factores que influyen en las ventas. A través del análisis exploratorio, se identificaron patrones interesantes y se generaron visualizaciones que ayudan a entender mejor el mercado de cursos online. El dashboard interactivo en Power BI permite explorar los datos de manera interactiva y brinda información clave para la toma de decisiones estratégicas.

## Hallazgos 


A través del análisis de los datasets, se ha identificado una serie de características distintivas en los cursos ofrecidos por las plataformas de educación en línea. En particular, se observa que Udemy cuenta con una amplia variedad de cursos enfocados en el desarrollo web, así como en el aprendizaje de estructuras creativas y financieras.

Al analizar los ingresos generados por estos cursos, se ha encontrado que el curso de diseño web y desarrollo web ha generado aproximadamente 630 millones de dólares, posicionándose como el curso más lucrativo para la empresa. Le sigue en importancia el campo de negocios y finanzas, con 123 millones de dólares, seguido por el diseño gráfico con 76 millones de dólares y, por último, la música e instrumentos con 53 millones de dólares.

Además, se ha observado que los cursos dirigidos a un público general suscitan un mayor interés, y la mayoría de los ingresos provienen de cursos destinados a todos los niveles de conocimiento, incluyendo aquellos diseñados para principiantes. En este sentido, una estrategia efectiva para impulsar el crecimiento sería establecer una secuencia de cursos encadenados, que permita a los estudiantes avanzar de manera progresiva en su aprendizaje.

Durante el análisis, se identificó que la mayoría de los suscriptores de la plataforma optan por una membresía de pago, representando un 69.6% del total de usuarios. Por otro lado, un 30.4% de los suscriptores utiliza la opción de membresía gratuita.

Además, se ha observado que un considerable porcentaje del 68.4% de los suscriptores está inscrito en cursos de desarrollo web, lo cual refleja un interés significativo en esta área de estudio. Por otro lado, el 15% de los suscriptores ha optado por inscribirse en cursos relacionados con el ámbito de los negocios.

Estos hallazgos destacan la preferencia de los usuarios por adquirir membresías pagas y su interés particular en los cursos de desarrollo web, así como en el ámbito de los negocios. Estos datos resultan valiosos para comprender el comportamiento de los usuarios y orientar estrategias futuras de desarrollo y oferta de cursos.

En complemento con el análisis realizado, se ha encontrado una relación significativa entre la cantidad de reviews y la cantidad de suscriptores en los cursos. Además, se ha observado que la condición de pago de un curso tiene una influencia inversamente proporcional en la cantidad de suscriptores y reviews.

Se identificaron palabras clave relevantes, como "aprender", "crear", "tradeo", "acondicionamiento", "inicio", "Photoshop", "computación", "masterizar", "forex" y "diseño". Estas palabras reflejan áreas de interés y temas recurrentes en los cursos analizados.

En cuanto a la plataforma Edx, se ha observado que los sujetos más atractivos están relacionados con la computación, ingeniería, negocios, humanidades y análisis de datos. La mayoría de los cursos son de nivel introductorio (63.4%), seguidos de cursos de nivel intermedio (27.7%) y cursos enfocados en un público avanzado (8.9%). Al analizar la cantidad de cursos suministrados por institución, se destaca que la Universidad de Harvard y la Universidad Politécnica de Valencia son las que más cursos ofrecen.

En el caso de Coursera, se ha observado una tendencia de crecimiento lineal en el rating de los cursos, con un promedio aproximado de 4.67 puntos. Al realizar un análisis de proyección simple, se estima que la calificación promedio para los próximos 5 años será de 4.675 puntos. Sin embargo, al aplicar una regresión lineal, se ha encontrado que habrá un crecimiento lineal adicional de 0.01 puntos después del 2021, alcanzando una calificación promedio de 4.76 puntos para el año 2027. En este análisis se han identificado palabras clave como "negocios", "javascript", "guitarra", "diseño", "aprender" y "Photoshop".

Finalmente, se ha realizado un análisis de wordcloud para los cursos con mayor rendimiento y mayor cantidad de suscriptores. Se ha encontrado que las palabras más repetidas y demandadas por los usuarios son "web development", "css", "cc50", "angular", "Java", "introducción" y "ciencia". Además, se ha evidenciado un enfoque destacado en cursos para principiantes, como se puede observar en los cursos de fundamentos.

## Concluciones 

En conclusión, se recomienda a la organización enfocar la oferta de cursos en el segmento de principiantes, pero implementando una ruta de aprendizaje que guíe a los usuarios hacia la adquisición de nuevos productos. Es importante evitar estancar su crecimiento y aprendizaje, lo que garantizará la fidelización de los clientes y los motivará a acceder a cursos de todos los niveles, desde principiante hasta avanzado o experto.

Se sugiere que la organización dirija sus cursos hacia las áreas de ciencias, tecnología, informática, negocios y finanzas, ya que se ha identificado un mayor interés y demanda en estos campos. Además, se recomienda aprovechar el crecimiento actual en el mercado de cursos online para alcanzar a nuevos clientes y expandir la base de usuarios.

Al seguir esta estrategia, la organización podrá satisfacer las necesidades de aprendizaje de diferentes segmentos de usuarios, promoviendo el desarrollo continuo y brindando oportunidades de aprendizaje en diversas disciplinas. Esto contribuirá a su crecimiento y éxito en el competitivo mercado de cursos online.

## Contacto
![Escribir](Edit.gif)


Para cualquier pregunta o consulta adicional, no dude en ponerse en contacto con el autor del repositorio:

![Crecer](9TLY.gif)


- Email: david.foca@hotmail.com
- Github: Daforyc - [https://github.com/Daforyc](https://github.com/Dafory

