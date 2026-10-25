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
1. ¿Cuál es la salud financiera de la empresa?
2. ¿Cómo se compara con las empresas del sector?
3. ¿Qué indican los datos históricos sobre su potencial de rentabilidad y sus riesgos?

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

### 2.1. Idea.
La idea consiste en desarrollar una aplicación web dirigida a profesionales sanitarios capaz de analizar imágenes de lesiones cutáneas mediante técnicas de Machine Learning y Deep Learning. El sistema identificará patrones visuales asociados a diferentes lesiones y proporcionará una clasificación orientativa con probabilidades estimadas, con el objetivo de ayudar a los médicos a evaluar posibles melanomas y otras enfermedades dermatológicas.

### 2.2. Problema a solucionar y usuario.
La evaluación de determinadas lesiones cutáneas puede resultar compleja, y distinguir entre lesiones benignas y malignas es especialmente importante para detectar posibles melanomas. Los principales usuarios serían dermatólogos y, potencialmente, médicos de atención primaria que necesiten apoyo para evaluar este tipo de lesiones.

Actualmente, los profesionales se basan en la exploración clínica, la dermatoscopia y, cuando está indicado, pruebas complementarias como la biopsia. La aplicación pretende proporcionar información adicional que ayude a orientar la evaluación, sin sustituir el criterio médico ni los procedimientos diagnósticos habituales.

### 2.3. Uso y valor.
Un médico necesita evaluar una lesión cutánea y desea disponer de información adicional para orientar su valoración. Introduce una imagen en la aplicación y el modelo de inteligencia artificial la analiza, mostrando las categorías estudiadas, sus probabilidades estimadas y una representación visual de las zonas de la imagen que más han influido en la predicción.

Esta información puede ayudar al profesional a identificar lesiones que merezcan una evaluación más exhaustiva. El sistema no proporcionará un diagnóstico definitivo, sino una evaluación orientativa cuyo valor deberá comprobarse mediante pruebas experimentales y, posteriormente, validación clínica.

### 2.4. Funcionalidades.
Funcionalidades que podríamos implementar:
1. **Recopilación y tratamiento de datos:** Obtención de conjuntos de datos públicos con imágenes de lesiones cutáneas, limpieza y procesamiento de las imágenes, y preparación de los datos para entrenar y evaluar los modelos de inteligencia artificial.
2. **Análisis de imágenes dermatológicas:** Identificación de características visuales relevantes, como la asimetría, los bordes, el color, el diámetro y la variabilidad de las lesiones, para estudiar qué patrones pueden estar relacionados con el melanoma y otras afecciones cutáneas.
3. **Clasificación mediante Machine Learning y Deep Learning:** Entrenamiento de modelos capaces de distinguir entre diferentes tipos de lesiones cutáneas, incluyendo melanomas, nevus benignos y otras patologías dermatológicas, estimando la probabilidad de pertenencia a cada categoría.
4. **Evaluación del rendimiento y detección de lesiones sospechosas:** Análisis de la precisión, sensibilidad, especificidad y otras métricas de los modelos, prestando atención a la capacidad de detectar melanomas y reducir los falsos negativos. También se estudiará la fiabilidad de las predicciones en imágenes de características y procedencias diferentes.
5. **Plataforma interactiva:** Desarrollo de una aplicación web en la que el usuario pueda cargar una imagen de una lesión cutánea, obtener una clasificación orientativa y consultar las probabilidades estimadas por el modelo, acompañadas de una explicación visual de las características que han influido en la predicción.

El objetivo final sería construir un prototipo que demuestre cómo la inteligencia artificial puede contribuir al análisis de imágenes dermatológicas y servir como herramienta de apoyo para la investigación y la detección temprana de lesiones sospechosas. La plataforma no sustituirá el diagnóstico de un profesional sanitario, sino que ofrecería una evaluación orientativa que requeriría validación clínica antes de cualquier uso asistencial.

### 2.5. Datos.
Para entrenar y evaluar el modelo se necesitan imágenes dermatológicas previamente clasificadas y acompañadas de etiquetas diagnósticas fiables. Como fuentes iniciales se proponen:
- ISIC, The International Skin Imaging Collaboration​: https://www.isic-archive.com/
- The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi%3A10.7910%2FDVN%2FDBW86T
- DermNet: The world's leading free dermatology website: https://dermnetnz.org/
- DermAtlas: https://www.dermatlas.net/
- Dermatology Atlas: https://atlasdermatologico.com.br/browse.jsf
- Inclusive Dermatology: Creating a Diverse Visual Atlas of Skin Conditions: https://hsc.unm.edu/medicine/departments/dermatology/inclusive-dermatology/gallery.html
- Skin Deep: https://dftbskindeep.com/
- Wayne State University School of Medicine - Dermatology Photo Atlas: https://medtech.med.wayne.edu/dermatology/index.php?album=Atlas%20Contents

Estas fuentes están documentadas públicamente, pero todavía habría que descargar los datos, comprobar su disponibilidad efectiva y verificar las condiciones de uso y las licencias aplicables. Inicialmente se utilizarían datos públicos, sin incorporar información identificativa de pacientes reales. Si posteriormente se emplearan datos hospitalarios, sería necesario abordar las autorizaciones, la protección de datos y los requisitos éticos correspondientes.

### 2.6. Primera versión o MVP.
La primera versión se centrará en distinguir entre melanomas y lesiones benignas seleccionadas a partir de imágenes dermatológicas.

El prototipo incluirá un modelo de Deep Learning entrenado con datos públicos, una evaluación de su rendimiento mediante métricas como la sensibilidad y la especificidad, y una aplicación web que permita cargar una imagen y consultar los resultados de la clasificación. También se estudiará la incorporación de un mapa visual que ayude a interpretar qué regiones de la imagen han influido en la predicción.

Se dejarán para futuras versiones la clasificación de un mayor número de enfermedades, la integración con historiales clínicos y el seguimiento de pacientes. El prototipo tendrá inicialmente fines de investigación y demostración, no de uso asistencial.

### 2.7. Viabilidad y dudas.
La principal dificultad será conseguir que el modelo aprenda patrones relevantes y funcione adecuadamente con imágenes diferentes de las utilizadas durante su entrenamiento. Un modelo puede obtener buenos resultados experimentales y cometer errores con imágenes procedentes de otros dispositivos, centros sanitarios o grupos de pacientes.

Para comprobar la viabilidad será necesario verificar el acceso a los datos, estudiar la distribución de las categorías diagnósticas, entrenar y comparar distintos modelos y evaluar sus resultados con imágenes independientes. Se prestará especial atención a los falsos negativos, es decir, los melanomas que el sistema pudiera clasificar incorrectamente como lesiones benignas.

La viabilidad técnica inicial parece razonable con los recursos y las herramientas disponibles, pero demostrar su utilidad clínica requeriría una validación adicional. También habría que estudiar los requisitos regulatorios aplicables antes de utilizar la aplicación en decisiones asistenciales.

### 2.8. Ejemplos similares.
Al buscar en internet bases de datos que se pudieran usar para este proyecto, se encontraron algunos proyectos similares que pueden servir de apoyo o ejemplo:
1. Diverse Dermatology Images (DDI): https://ddi-dataset.github.io/
2. globalTone – AI-powered Dermoscopy: https://globaltone.tech/en
3. SkinVision: https://www.skinvision.com/

## 3. SmartTriage AI: Sistema inteligente para optimizar el flujo de pacientes en urgencias

### 3.1. Idea.
SmartTriage AI es una herramienta digital que ayuda a los servicios de urgencias a gestionar el flujo de pacientes y visualizar los tiempos de espera. Combina un panel de seguimiento en tiempo real con análisis de datos y modelos predictivos para identificar periodos de alta demanda y apoyar la planificación de recursos. La herramienta complementa el trabajo del personal sanitario, pero no sustituye el triaje ni las decisiones clínicas.

### 3.2. Problema y usuario.
Los servicios de urgencias pueden experimentar periodos de gran demanda, acumulación de pacientes y retrasos en los procesos de admisión y triaje. Cuando la información sobre las llegadas, las esperas y los recursos disponibles está dispersa, puede resultar más difícil identificar cuellos de botella y anticipar las necesidades del servicio.

Los usuarios principales serían los coordinadores de urgencias, responsables de operaciones y personal encargado de organizar los recursos. Actualmente, pueden recurrir a sistemas de información hospitalarios, registros administrativos y paneles de actividad, dependiendo del hospital. SmartTriage AI buscaría reunir información operativa relevante y convertirla en indicadores fáciles de interpretar.

### 3.3. Uso y valor.
**Ejemplo de uso:** durante una mañana, el responsable de urgencias observa en el panel que aumenta el número de pacientes pendientes de triaje y que los tiempos de espera están creciendo. El sistema muestra la evolución de las llegadas, el número de pacientes pendientes y una previsión de la demanda para las próximas horas.

Con esta información, el responsable puede revisar la disponibilidad de personal y valorar si necesita reorganizar los recursos. Las decisiones siguen siendo responsabilidad del equipo humano.

El valor esperado del producto sería:
- Facilitar la identificación de retrasos y cuellos de botella.
- Mejorar la visibilidad del flujo de pacientes.
- Anticipar períodos de mayor demanda.
- Apoyar la planificación operativa mediante datos.

Estos beneficios son hipótesis que habría que evaluar mediante pruebas; no se asumiría de antemano que el sistema reduce los tiempos de espera.

### 3.4. Datos.
Para desarrollar el proyecto, combinaríamos datos públicos para justificar la necesidad con datos de investigación o simulados para construir y probar el prototipo.

Fuentes candidatas:
1. **MIMIC-IV-ED — base de datos de urgencias.**
Enlace: https://physionet.org/content/mimic-iv-ed/
Contiene información desidentificada de visitas a urgencias, con datos como horarios de llegada, información de triaje y resultados de la visita. Puede ayudar a explorar los patrones de llegada y los procesos de atención.
**Acceso:** requiere completar los requisitos de acceso de PhysioNet, incluida formación y aceptación de un acuerdo de uso de datos. No debemos asumir que tendremos acceso inmediato a la base completa. Podemos evaluar la versión de demostración: https://physionet.org/content/mimic-iv-ed-demo/
2. **California Open Data — Emergency Department Volume and Capacity.**
Enlace: https://publish.data.ca.gov/dataset/emergency-department-volume-and-capacity
Es una fuente candidata para estudiar la relación entre volumen de actividad y capacidad de los servicios de urgencias.
**Acceso:** el conjunto se publica como dato abierto; antes de utilizarlo, debemos comprobar la disponibilidad actual, el formato, las variables y las condiciones de reutilización.
3. **Australian Institute of Health and Welfare — Emergency Department Waiting Times.**
Enlace: https://www.aihw.gov.au/hospitals/topics/emergency-departments/waiting-times
Sus estadísticas pueden servir para contextualizar el problema de los tiempos de espera y justificar la relevancia del proyecto.
**Acceso:** información estadística pública; es más adecuada para contextualizar el problema que para entrenar directamente un modelo predictivo.

**Variables que necesitaríamos:** fecha y hora de llegada, hora de inicio del triaje, estado del proceso, volumen de llegadas por intervalo y, si están disponibles, indicadores de capacidad y recursos. Los campos exactos dependen de la fuente seleccionada.

Para la primera versión, utilizamos datos sintéticos o datos públicos autorizados. No introduciremos información identificable de pacientes. Si en el futuro se trabajase con datos hospitalarios reales, sería necesario revisar el RGPD, las medidas de seguridad, los permisos de acceso y las autorizaciones correspondientes.

### 3.5. Primera versión o MVP.
El MVP sería un prototipo funcional que demuestre cómo los datos pueden ayudar a visualizar el flujo de pacientes y anticipar la demanda.

**Funciones incluidas:**
- Un panel interactivo que muestre las llegadas, los pacientes pendientes de triaje y los tiempos de espera.
- Gráficos para identificar las horas con mayor volumen de llegadas.
- Un modelo predictivo inicial para estimar la demanda de pacientes por intervalo de tiempo, si los datos disponibles lo permiten.
- Indicadores básicos para apoyar la planificación operativa.
- Una simulación con datos sintéticos que permita comparar distintos escenarios de demanda.

**Qué mostraríamos funcionando:** una aplicación sencilla en la que el usuario pueda consultar el estado simulado de urgencias, visualizar tendencias y ver una previsión de demanda.

**Qué dejaríamos fuera inicialmente:** integración con sistemas hospitalarios reales, registro real de pacientes, alertas clínicas automáticas, decisiones automáticas de triaje y despliegue en un hospital. Estas funciones exigirían más datos, validación y garantías de seguridad.

La tecnología propuesta sería Python, Pandas y Scikit-learn para el análisis y la predicción, Streamlit para la interfaz y Plotly para las visualizaciones. PostgreSQL podría utilizarse para almacenar los registros simulados; si el prototipo es muy pequeño, SQLite sería una alternativa más sencilla.

### 3.6. Viabilidad y dudas.
La principal incertidumbre es si podremos obtener datos con suficientes variables y marcas temporales para estudiar los retrasos que queremos mejorar. Los conjuntos públicos pueden registrar la llegada y el triaje, pero no necesariamente el tiempo dedicado a cada paso administrativo o la disponibilidad de personal en cada momento.

Para comprobar la viabilidad, necesitaríamos:
1. Revisar los campos y las condiciones de acceso de MIMIC-IV-ED y de las fuentes públicas.
2. Definir exactamente qué queremos predecir: por ejemplo, el volumen de llegadas durante la siguiente hora.
3. Construir una primera versión con datos sintéticos y comprobar que los cálculos y las visualizaciones funcionan.
4. Comparar las predicciones con los datos observados mediante métricas adecuadas.
5. Evaluar si los indicadores propuestos serían útiles para un responsable de urgencias.

Si no conseguimos datos adecuados para entrenar un modelo fiable, podremos mantener el objetivo principal del MVP en la visualización del flujo de pacientes y utilizar datos simulados para demostrar el funcionamiento del producto.

**Pregunta de investigación provisional:** ¿Puede una herramienta de análisis y predicción de la demanda ayudar a los responsables de urgencias a identificar periodos de alta demanda y mejorar la planificación operativa?

**Resultado esperado:** un prototipo que demuestre cómo la analítica de datos y la IA pueden apoyar la organización de urgencias, dejando para una fase posterior la validación en un entorno hospitalario real.

**Enlaces que justifican el proyecto:**
- https://pmc.ncbi.nlm.nih.gov/articles/PMC11193078/
- https://mhealth.jmir.org/2024/1/e54642/
- https://www.ncbi.nlm.nih.gov/books/NBK617247/
