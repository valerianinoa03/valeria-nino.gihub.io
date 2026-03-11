---
layout: default
---

## Acerca de mi
Economista con master en desarrollo económico, con más de 3 años de experiencia en análisis de datos, manejo de bases de datos y preparación de reportes estratégicos. Sólidas habilidades en Excel avanzado, SQL y Power BI. Enfoque en toma de decisiones estratégicas y generación de insights accionables en contextos de negocio e inversión.

## Habilidades
- **Programación** – SQL | Python | Stata | R
- **Herramientas** – Excel | Power BI
- **Idiomas** – Español (Nativo) | Inglés (Fluido)
  
## Proyectos
#**Resumen Ejecutivo de Ventas para Walmart | Tripleten – Data Analyst Bootcamp (2025-2026)**

Contexto:
- Se analizaron las ventas semanales de Walmart por departamento en el año 2012, para ver las categorías de departamento más eficientes, los departamentos que aportaron más al negocio y qué departamento es el más volatil en ventas.

Preguntas Clave:
- ¿Qué categorías de departamento fueron más eficientes para generar ventas en 2012?
- ¿Qué departamentos aportaron más al negocio y cuáles estuvieron por debajo de su potencial?
- ¿Dónde está el mayor riesgo por volatilidad de ventas en 2012?

Herramienta: Excel

Metodología:
- Limpieza de datos: normalización y estandarización de variables
- Cálculo de KPIs: uso de tablas dinámicas para crear y visualizar KPIs
- Creación de Dashboards: hoja donde los diferentes stakeholders pueden filtrar los datos y visualizar tablas y gráficos.

- Gráfico presentado en el dashboard:

<p align="center">
  <img src="Proyecto1_1.png" alt="Proyecto 1" width="650">
</p>

Conclusiones y Recomendaciones:
- Las categorías con más ventas por metro cuadrado fueron "Despensa y Básicos" y "Comida Fresca", Se recomienda priorizar el inventario y presupuesto para estos departamentos. Además, se recomienda promocionar las categorías de baja proporción a través de descuentos y campañas para impulsar todavía más las ventas en estas categorías.

- El departamento No. 16 (Sin nombre), tiene un comportamiento extremadamente irregular y alta variación . Dado que no tiene nombre, puede ser un departamento mal definido o una categoría para productos residuales. Se sugiere reorganizar el departamento, ya sea dandole un nombre correspondiente a sus productos o integrándolo a otro/s departamento/s

Link: [Ver Proyecto](https://docs.google.com/spreadsheets/d/10mYf93PDdfszHY9myBj8fTfIAiVieMn6rVXztoEHvxU/edit?usp=edit)

#**Análisis de Desempeño Financiero | Tripleten – Data Analyst Bootcamp (2025-2026)**

Contexto:
- Se analizaron datos de 2017 de ventas, catálogo de productos, territorios y campañas para la empresa Adventure Works, con el fin de saber qué mercados generan más ingresos y cuál es la rentabilidad de cada uno teniendo en cuenta los gastos de marketing.

Preguntas Clave:
- ¿Cuánto estamos ganando por país?
- ¿Qué tan rentable es cada mercado considerando los gastos de marketing?

Herramienta: SQL

Metodología:
- Extraer y limpiar datos: unión de tablas, selección de columnas relevantes y tratamiento de valores nulos 
- Cálculo de KPIs: Se calculó el beneficio bruto, márgen de ventas y ROI sobre los datos.
- Valudación de resultados y análisis de calidad: se revisó consistencia en los datos, que no hubiera nulos ni duplicados, y se detectarn anomalías.

- Código realizado para calcular KPIs:

<p align="center">
  <img src="Proyecto2.png" alt="Proyecto 2" width="650">
</p>

Conclusiones y Recomendaciones:
- El país más rentable en el mercado es Estados Unidos, con un ROI de 75.75%, indicando que por cada dolar invertido en marketing, se obtuvo una ganancia de $0.76. El mercado con mayor margen de ganancia es Canadá, con 44.76%, indicando que por cada dolar vendido, se obtuvo una ganancia de $0.45. Esto pasa a pesar de que tiene el ROI más bajo de todos.

- Los margenes de ganancia no tienen una variación muy alta - oscilan ente el 41 y 45%, mientras que el ROI es muy variable, con porcentajes entre 17 a 75%. Esto significa que el problema no está en la rentabilidad de cada producto sino en la eficiencia de la inversión en campañas de marketing.

- Se recomienda optimizar los gastos de marketing en Francia y Canadá. Estos paises tienen un márgen alto pero un ROI bajo, lo que significa que ganan bien por venta pero gastan mucho en marketing. Se pueden probar estrategias de márketing de menor costo como programas de referidos, revisar canales de segmentación y hacer encuestas a clientes actuales.

Link: [Ver Proyecto](https://docs.google.com/spreadsheets/d/1Rg-u6mktpbrfiJfg1akyJxSABdissCfN8OIeEz7hRDw/edit?usp=edit)

#**Movilidad Urbana y Productividad Económica | Tripleten – Data Analyst Bootcamp (2025-2026)**

Contexto:
- Crear un reporte para el Latin American Development Bank, para entender cómo la movilidad urbana (niveles de congestión, tiempos de viaje, retrasos) se relaciona con la productividad económica (PIB per cápita, desempleo) en las principales ciudades latinoamericanas.

Preguntas Clave:
- ¿Qué ciudades de América Latina presentan alta congestión y baja productividad económica?
- ¿Cuáles muestran los mejores indicadores combinados (movilidad eficiente y economía fuerte)?
- ¿Qué variables parecen tener una relación más fuerte con el desarrollo urbano?

Herramientas: 
- Jupyter Notebook
- Python: pandas, numpy, seaborn, matplotlib

Metodología:
- Explorar, limpiar y preparar los datos: Se inspeccionó la estructura, tipos de datos, columnas y valores faltantes. Se estandarizaron los nombres de las columnas y se corrigieron formatos.
- Cálculo de variables relevantes: se calcularon variables y se unieron las tablas con toda la información relevante.
- Visualizaciones: Se calculó un boxplot, histograma y un gráfico de barras para analizar visualmente los datos.

- Gráfico de barras para comparar variables:
  
<p align="center">
  <img src="Proyecto3.png" alt="Proyecto 3" width="650">
</p>

Conclusiones y Recomendaciones:
- Se comparó una variable de movilidad (tiempo en atrasos por tráfico) y una variable económica (PIB per cápita). Se determinó que no hay una relación clara entre las dos variabes: Montevideo cuenta con el PIB per cápita más alto de la muestra pero no tiene un índice de retrasos en las vías muy alto, y Bogotá tiene una los índices de congestión más altos pero no tiene un PIB per cápita muy alto. Vemos que la congestión puede estar más relacionada con factores como el tamaño, densidad de población y organización del sistema de transporte que con el ingreso promedio de las personas.

- Se recomienda pririzar la ciudad de Bogotá, ya que es la que en general muestra mayor correlación entre alta congestión y baja productividad económica. Lima también muestra esta correlación pero a menor nivel, así ue le podemos asignar una prioridad media. En Bogotá se propone seguir invirtiendo en la construcción del metro y en Lima mejorar la integración de sistemas existentes. En ambas se recomienda incentivar a la población al tele trabajo y/o a horarios escalonados.

Link: [Ver Proyecto](https://drive.google.com/file/d/1FbEfrsiRpvNV2tXdLPPRp5N5ZiRDhjYJ/view?usp=sharing)

#**Análisis de una empresa de telecomunicaciones (ConnectaTel) | Tripleten – Data Analyst Bootcamp (2025-2026)**

Contexto:

- Entregar un reporte para entender cómo los clientes usan realmente los servicios móviles (llamadas y mensajes). El objetivo es identificar patrones de uso, detectar comportamientos atípicos y comprender qué segmentos de clientes muestran necesidades diferenciadas, con el fin de optimizar la oferta comercial y mejorar la experiencia del usuario.

Preguntas Clave:
- ¿Qué segmentos de clientes muestran mayor o menor uso de llamadas y mensajes?
- ¿Qué usuarios presentan valores atípicos que puedan indicar comportamientos inusuales, fraude o errores de registro?
- ¿Cómo varía el uso según la edad y el tipo de plan contratado?
- ¿Qué patrones pueden ayudar a diseñar mejores planes, optimizar la oferta y mejorar la satisfacción del cliente?

Herramientas: 
- Jupyter Notebook
- Python: pandas, numpy, seaborn, matplotlib

Metodología:
- Cargar y explorar datos: Se cargaron los datasets para obtener una visión clara de la estructura y tipos de columna de cada dataset.
- Identificación de problemas de calidad: se contaron nulos, se detectaron valores sentinels y se revisó el formato de los datos para obtener una lisa de problemas que pueden sesgar decisiones.
- Limpieza de datos: Se reemplazaron sentinels, se convirtieron formatos y se imputaron valores NA según el caso para tener datos consistentes y listos para el análisis.
- Summary statistics: Se revisaron medidas clave como la media, median y  percentiles en variables numéricas y categoricas para mostrar comportamientos típicos y extremos.
- Visualización de outliers: Se crearon histogramas y boxplots para visualizar sesgos, patrones y datos atípicos.
- Segmentación: Se crearon segmentaciones por edad y por nivel de uso para visualizar sus proprciones y con base en estos diseñar acciones como ofertas, campañas o cambios de plan.

- Histograma y Boxplot de la variable 'cantidad de mensajes':

<p align="center">
  <img src="Proyecto 4_1.png" alt="Proyecto 4.1" width="650">
</p>

<p align="center">
  <img src="Proyecto 4_2.png" alt="Proyecto 4.2" width="650">
</p>

- Visualizaciones de segmentación:
<p align="center">
  <img src="Proyecto 4_3.png" alt="Proyecto 4.3" width="650">
</p>

<p align="center">
  <img src="Proyecto 4_4.png" alt="Proyecto 4.4" width="650">
</p>

Conclusiones y Recomendaciones:

- Al segmentar los datos de usuarios de servicios móviles por edad, se encontró que los usuarios adultos entre los 30 y 60 años son los que más usan el servicio. Vimos que no hay outliers notables y que el servicio se distribuye equitativamente por edades desde 18 a 80 años. Por nivel de uso vemos que los clientes que tienen mayor frecuencia son los que dan un alto uso al servicio telefónico. Se evidenciaron varios outliers sesgados a la derecha, mostrando que unos pocos usuarios realizaban más llamadas y mensajes que el promedio. Esto sugiere que el cliente típico de la compañía son los adultos de 30 a 60 años con alto uso del servicio. 

- Se recomienda impulsar el plan premium para los clientes actuales de alto uso, mejorándolo con aún más beneficios como llamadas y mensajes ilimitados, al igual que descuentos por permanencia. Esto daría más uso al plan premium sin necesidad de conseguir nuevos clientes. También se recomienda que se debe capturar el mercado jóven ofreciendo planes enfocados en el internet ilimitado y descuentos estudiantiles, ya que esto es importante en ese mercado.

Link: [Ver Proyecto](https://colab.research.google.com/drive/1LfKVW-KR4OIMVMacFDfG5nx74INgN6c5?usp=sharing)

#**Explorando factores de comportamiento en NovaRetail | Tripleten – Data Analyst Bootcamp (2025-2026)**

Contexto:
- Construir un análisis correlacional estructurado que combine variables de comportamiento del cliente, segmentación y valor económico para usuarios de NovaRetail+,  una plataforma de comercio electrónico en Latinoamérica con millones de usuarios, durante el año 2024. El objetivo es generar un reporte de análisis de correlación claro, responsable y accionable, que permita entender qué comportamientos del cliente están más fuertemente asociados con el ingreso generado, sin caer en interpretaciones causales incorrectas.

Preguntas Clave:
- ¿Qué factores del comportamiento del cliente están más fuertemente asociados con el ingreso anual generado?

Herramientas: 
- Jupyter Notebook
- Python: pandas, numpy, seaborn, matplotlib

Metodología:
- Cargar y explorar el dataset: Entender la estructura, columnas, tipos y métricas clave.
- Preparar datos y documentar supuestos: Tener los datos sin errores y listos para el reporte. Definir variables relevantes y reglas del análisis.
- Visualizar relaciones iniciales: Crear heatmap para patrones globales y scatterplots para visualizar relaciones. 
Calcular correlaciones adecuadas: Pearson/Spearman, Punto biserial, V de Cramér

- Heatmap de Correlaciones:

<p align="center">
  <img src="Proyecto 5_1.png" alt="Proyecto 5.1" width="650">
</p>

- Scatterplot con las correlaciones más relevantes:

  <p align="center">
  <img src="Proyecto 5_2.png" alt="Proyecto 5.2" width="650">
</p>

Conclusiones y Recomendaciones:
- La publicidad influye sobretodo en las visitas, pero su impacto en ingresos es más indirecto y débil. No podemos afirmar que aumentar el gasto en publicidad aumente proporcionalmente los ingresos. Hay que optimizar conversión hacia las ventas, no solo tráfico en la web del negocio. Para esto se debe analizar más a fondo la inversión publicitaria, segmentando por diferentes tipos de campañas y clientes, y ver la tasa de conversión para cada uno, para poder dirigir la publicidad al público adecuado.

- El ingreso anual parece estar más relacionado con comportamiento transaccional que con características demográficas o de perfil. No podemos afirmar que no existan relaciones no lineales o interacciones más complejas o que estas variables no influyan levemente en el ingreso para algunos clientes. Para maximizar ingresos se debe tener un enfoque en el comportamiento del cliente, más que en sus características demográficas, y segmentar para ver en qué clientes se debe hacer un enfoque.

Limitaciones:
- Correlación ≠ causalidad
- No se hizo segmentación, esto puede cambiar las correlaciones y reflejar paradoja de Simpson
- Puede haber caso de variables no controladas, como antigüedad del cliente, temporaa del año, promociones, que afecten la relación de otras variables

Próximos pasos: 
- Probar segmentación adicional y hacer análisis por cohortes, para poder crear estrategias para aumentar ingresos. 
- Enfocar el gasto en publicidad a campañas drigidas a los tipos de clientes que más generan ingresos
- Mejorar automatización y programas de recompra y descuentos para asegurar conversión hacia ventas y no solo visitas.

Link: [Ver Proyecto](https://drive.google.com/file/d/1IjIx-PfypHi7JecTwBPWmQ8hcZ2ZqYlU/view?usp=sharing)

## Contacto
- Email: valerianinoa@gmail.com
- Teléfono: +57 3136925084
- Linkedin: (https://www.linkedin.com/in/valeria-nino/)
