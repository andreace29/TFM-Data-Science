# Fichas de las ideas de los proyectos

## 1. Equity Intelligence - Plataforma inteligente de análisis financiero y evaluación de oportunidades de inversión mediante Machine Learning

### 1.1. Idea

La idea consiste en el desarrollo de una plataforma interactiva de análisis financiero que permita a los usuarios evaluar empresas cotizadas, comprender su situación económica y analizar su potencial de inversión mediante la combinación de técnicas de análisis fundamental, estadística y Machine Learning.

El objetivo no es desarrollar únicamente un modelo predictivo, sino crear un producto funcional, intuitivo y basado en datos que facilite la toma de decisiones de inversión fundamentadas.

La plataforma centralizará información financiera, calculará indicadores relevantes y utilizará modelos estadísticos y de aprendizaje automático para estudiar las relaciones entre las características financieras y su comportamiento bursátil posterior.

### 1.2. Identificación del usuario y problema a solucionar.

Los usuarios objetivos son inversores particulares con conocimientos financieros básicos o intermedios, interesados en analizar empresas cotizadas antes de tomar decisiones de inversión.

Actualmente, estos inversores encuentran varios problemas:

1. **Información fragmentada:** necesitan consultar muchas fuentes para encontrar información relevante.
2. **Complejidad del análisis.**
3. **Dificultad para detectar oportunidades:** no siempre resulta sencillo determinar si una empresa presenta una valoraicón atractiva.
4. **Falta de contextualización:** disponer de muchos indicadores no implica necesariamente comprender su relevancia para tomar una decisión.

Existe una necesidad de contar con una herramienta accesible que transforme datos financieros y modelos matemáticos en información estructurada, comprensible y útil para evaluar posibles inversiones.

Nuestra propuesta aborda esta necesidad con la implementación de una plataforma que permita al usuario elegir una empresa y obtener un análisis financiero integrado. El producto combinará tres dimensiones:
- **Análisis financiero tradicional:** evaluación de la empresa mediante indicadores de rentabilidad, crecimiento, endeudamiento, solvencia y valoración.
- **Análisis estadístico y Machine Learning:** se desarrollarán modelos capaces de identificar patrones históricos y estimar indicadores para un horizonte temporal determinado.
- **Visualización y explicación de resultados:** análisis mediante gráficos, comparativas e indicadores interpretables.

El objetivo es poder dar respuesta a las siguientes preguntas: 
i) ¿Cuál es la salud financiera de la empresa?
ii) ¿Cómo se compara con las empresas del sector?
iii) ¿Qué indican los datos históricos sobre su potencial de rentabilidad y sus riesgos?

Conocemos de la existencia de plataformas como Investing que ayudan a tomar decisiones financieras basadas en datos e indicadores económicos, el problema fundamental de este tipo de plataformas es que no aportan feedback o justificación de la decisión que se toma; sin embargo, lo que se pretende con nuestra plataforma sería justamente solucionar este problema, no sólo ayudar a tomar una decisión, sino también justificar dicha decisión.

De esta manera, buscamos que el usuario no solo conozca los resultados del análisis, sino que también comprenda qué variables financieras han influido en ellos, en qué medida lo han hecho y qué limitaciones o incertidumbres presentan. Así, la plataforma aspira a fomentar una toma de decisiones más informada, transparente y fundamentada en datos.

El principal valor de esta plataforma reside en integrar el análisis financiero tradicional, la ciencia de datos y la inteligencia artificial en un único producto orientado al usuario. 

No pretendemos sustituir el criterio del inversor, sino facilitar el acceso a información financiera relevante, reducir la complejidad del análisis y aportar una perspectiva cuantitativa que complemente la valoración tradicional.

### 1.3. Datos a utilizar.
- SEC EDGAR: balances, cuentas de resultados y flujos de caja: https://www.sec.gov/edgar
- CNMV: informes financieros anuales: https://internet.cnmv.es/portal/consultas/busqueda?id=25&lang=es
- Yahoo finance: cotizaciones históricas, dividendos y operaciones corporativas: https://finance.yahoo.com/
- FRED: tipos de interés, inflación, desempleo y otras variables macroeconómicas: https://fred.stlouisfed.org/
- Demodaran: ratios de valoración, rentabilidad y riesgo por sectores: https://pages.stern.nyu.edu/~adamodar/pc/datasets/

### 1.4. Mínimo Producto Viable (MVP).

El Producto Mínimo Viable consistirá en una plataforma web interactiva que permita analizar empresas cotizadas, evaluar su situación financiera y estimar potencial de inversión mediante técnicas de Machine Learning, proporcionando explicaciones claras y fundamentadas sobre los resultados obtenidos. 

Esta primera versión incluirá las siguientes funcionalidades:
- **Selección de empresas:** buscador que permite consultar un conjunto de empresas cotizadas de las cuáles se tengan datos.
- **Análisis financiero:** visualización de indicadores clave de rentabilidad, crecimiento, solvencia, etc. Se pueden calcular y predecir tantos indicadores como queramos, lo único será que nuestro modelo será más complejo y necesitará más datos.
- **Predicción mediante ML:** modelos que permitan estimar la probabilidad de que una empresa supere una cierta rentabilidad en un cierto período de tiempo determinado.
- **Explicación:** incluir un apartado donde se identifique y se visualiza los factores financieros que más han influido en la predicción del modelo, permitiendo al usuario comprender y fundamentar sus decisiones.

### 1.5. Funcionalidad adicional.
Como posible ampliación se plantea incorporar una sección donde el usuario pueda consultar las noticias más relevantes relacionadas con la empresa seleccionada. 

Además, se puede incorporar un módulo de análisis del sentimiento del mercado mediante Procesamiento de Lenguaje Natural (NLP). Esta funcionalidad permite recopilar y analizar noticias financieras relacionadas con las empresas estudiadas y relacionarlas con los cambios del mercado. 

Es decir, la idea sería investigar cómo las noticias y el sentimiento del mercado generan comportamientos en las cotizaciones: variaciones del precio, volatilidad, etc.

Además, se podría comparar si incorporando este módulo de análisis adicional se mejoran las capacidades predictivas de la plataforma. 

Esta técnica permite integrar técnicas adicionales de inteligencia artificial, como es el NLP, y estudiar la percepción de los inversores y comportamiento de los mercados financieros.


## 2. Sistema de apoyo al diagnóstico dermatológico mediante Machine Learning

La idea consiste en desarrollar una aplicación web dirigida a profesionales sanitarios capaz de analizar imágenes de lesiones cutáneas mediante técnicas de Machine Learning y Deep Learning. El sistema identificará patrones visuales asociados a diferentes lesiones y proporcionará una clasificación orientativa con probabilidades estimadas, con el objetivo de ayudar a los médicos a evaluar posibles melanomas y otras enfermedades dermatológicas.




## 3. SmartTriage AI: Sistema inteligente para optimizar el flujo de pacientes en urgencias

SmartTriage AI es una herramienta digital que ayuda a los servicios de urgencias a gestionar el flujo de pacientes y visualizar los tiempos de espera. Combina un panel de seguimiento en tiempo real con análisis de datos y modelos predictivos para identificar periodos de alta demanda y apoyar la planificación de recursos. La herramienta complementa el trabajo del personal sanitario, pero no sustituye el triaje ni las decisiones clínicas.

