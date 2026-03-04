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
**Resumen Ejecutivo de Ventas para Walmart | Tripleten – Data Analyst Bootcamp (2025-2026)**

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

**Análisis de Desempeño Financiero | Tripleten – Data Analyst Bootcamp (2025-2026)**
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

**Movilidad Urbana y Productividad Económica | Tripleten – Data Analyst Bootcamp (2025-2026)**
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

## Contacto
- Email: valerianinoa@gmail.com
- Teléfono: +57 3136925084
- Linkedin: (https://www.linkedin.com/in/valeria-nino/)
