📊 Springfield bajo la lupa
Análisis interactivo de la evolución de The Simpsons (1989–2023)

📌 Resumen Ejecutivo

Springfield bajo la lupa es un proyecto de análisis y visualización interactiva desarrollado en Tableau Desktop Public Edition que examina la evolución de The Simpsons desde su estreno en 1989 hasta la temporada 34.

A través del análisis de métricas como rating promedio (IMDb) y audiencia en EE. UU., el proyecto estudia el ciclo de vida de una de las series más influyentes de la historia de la televisión.

El trabajo combina:

Análisis exploratorio de datos (EDA)

Limpieza y transformación

Modelado en Tableau

Storytelling visual

Interactividad avanzada

El objetivo es responder, con datos y no con nostalgia, a la siguiente pregunta:

¿Sigue brillando Springfield o sus años dorados quedaron atrás?

🎯 Objetivos del Proyecto
Objetivo general

Analizar la evolución histórica de la serie para identificar patrones de auge, estabilidad, desgaste y transformación.

Objetivos específicos

Evaluar la evolución del rating promedio por temporada.

Analizar la caída progresiva de la audiencia televisiva en EE. UU..

Identificar la concentración de calidad mediante el estudio de los episodios mejor y peor valorados.

Detectar cambios estructurales en el modelo de consumo audiovisual.

Construir una experiencia interactiva basada en visualización narrativa de datos.

🔎 Proceso Metodológico
1️⃣ Búsqueda y selección de datasets

El proyecto comenzó con una fase de investigación y búsqueda de fuentes en Kaggle.

Se analizaron múltiples datasets relacionados con The Simpsons, seleccionando finalmente dos conjuntos principales:

📁 Dataset 1: Información sobre personajes.

📁 Dataset 2: Información detallada de episodios (temporadas, títulos, fechas, rating IMDb, audiencia en EE. UU., etc.).

La selección se basó en:

Nivel de detalle disponible.

Consistencia estructural.

Presencia de métricas cuantificables.

Potencial para análisis longitudinal.

2️⃣ Exploratory Data Analysis (EDA)

Antes de diseñar cualquier visualización, se realizó un proceso completo de Exploratory Data Analysis (EDA) para comprender la estructura y calidad de los datos.

Durante esta fase se:

Analizó el número de registros y variables.

Identificaron valores nulos o inconsistencias.

Revisó la distribución de ratings por temporada.

Validó coherencia entre temporadas y episodios.

Exploró la evolución temporal de audiencia.

El objetivo fue entender exactamente con qué datos se estaba trabajando antes de construir la narrativa analítica.

3️⃣ Limpieza y preparación de datos

Posteriormente se realizó una fase de depuración y transformación:

Eliminación de registros incompletos.

Normalización de formatos (temporadas, fechas).

Corrección de inconsistencias en nombres.

Agrupación de variables para análisis por temporada.

Cálculo de métricas agregadas (rating promedio por temporada).

Preparación de tablas para comparación de episodios.

Esta etapa permitió construir una base de datos sólida y coherente para visualización.

4️⃣ Modelado y Visualización en Tableau

Una vez depurados los datos, se desarrolló el dashboard en Tableau Desktop Public Edition.

El proceso incluyó:

Creación de hojas individuales por tipo de análisis.

Diseño de dashboards estructurados por narrativa.

Implementación de filtros dinámicos.

Creación de botones de navegación entre páginas.

Desarrollo de tooltips iterativos.

Integración de elementos multimedia.

Diseño visual alineado con la temática Simpson.

Se priorizó:

Claridad visual.

Jerarquía informativa.

Interactividad intuitiva.

Coherencia estética.

Storytelling estructurado.

🧩 Estructura del Dashboard

El proyecto está organizado como una experiencia narrativa progresiva:

1️⃣ Portada – Springfield bajo la lupa

Pantalla introductoria con:

Diseño inspirado en la identidad visual de la serie.

Botón de navegación para iniciar el recorrido.

Enfoque narrativo desde el primer momento.

Función: establecer el tono del análisis.

2️⃣ Contexto general – “En el sofá desde 1989”

Panel de indicadores clave:

34 temporadas.

746 episodios.

6.722 personajes.

Estreno en 1989.

Función: dimensionar el fenómeno antes del análisis profundo.

3️⃣ Evolución del rating y audiencia
“¡Buenas noches, Springfield! Tenemos que hablar”

Visualización doble:

📈 Línea superior → Rating promedio por temporada (IMDb).

👥 Línea inferior → Audiencia promedio en millones (EE. UU.).

Principales hallazgos:

Pico de valoración en primeras temporadas.

Descenso progresivo a partir de temporada 8–10.

Caída sostenida en audiencia.

Desgaste acumulativo, no colapso repentino.

4️⃣ Análisis visual por temporadas
“Lisa lo sabía desde la temporada 1”

Gráfico de burbujas interactivo:

Tamaño → audiencia.

Color → rating.

Permite identificar visualmente cinco etapas:

Era dorada.

Estabilidad.

Transición.

Caída progresiva.

Baja audiencia sostenida.

5️⃣ Mejores y peores episodios
“Los episodios que Ned Flanders aprobaría… y los que no”

Comparación directa entre:

Top 10 mejor valorados.

Top 10 peor valorados.

Hallazgos:

Excelencia concentrada en primeras temporadas.

Mayor irregularidad en temporadas recientes.

Diferencia de hasta 5 puntos entre extremos.

Conclusión: pérdida de consistencia más que incapacidad creativa.

6️⃣ Interpretación estratégica
“¿Qué nos dicen los datos, señor Burns?”

Síntesis analítica en cuatro factores:

Desgaste creativo inevitable.

Cambio acelerado del contexto cultural.

Competencia del streaming.

Fin del fenómeno “evento TV”.

Conclusión estratégica:

La serie no necesita ser fenómeno cultural. Solo necesita ser rentable.

⚙️ Interactividad y Funcionamiento

El dashboard fue diseñado como una experiencia navegable e iterativa.

🔘 Botones de navegación

Botones personalizados para avanzar entre páginas.

Flujo lineal tipo presentación interactiva.

Experiencia guiada pero exploratoria.

🔁 Etiquetas iterativas (Tooltips dinámicos)

Información detallada al pasar el cursor.

Contextualización adicional sin sobrecargar visualmente.

Refuerzo del storytelling.

🎛️ Filtros dinámicos

Selección por temporada.

Segmentación por categorías:

Obras maestras.

Catástrofes de Springfield.

Actualización dinámica de gráficos según selección.

🎥 Integración multimedia

Inclusión de referencias audiovisuales.

Conexión entre datos cuantitativos y memoria cultural.

Refuerzo emocional del análisis.

🎨 Diseño y Enfoque Visual

El diseño cumple una función estratégica:

Tipografía inspirada en la serie.

Uso de personajes como recurso narrativo.

Color aplicado como variable semántica:

Amarillo → excelencia.

Tonos cálidos → transición.

Rojos → declive.

Principio aplicado:

Visualización de datos + narrativa temática = mayor retención cognitiva.

📊 Dataset

Variables principales utilizadas:

Temporada

Año

Título del episodio

Rating IMDb

Audiencia en millones (EE. UU.)

Personajes

Análisis longitudinal de 34 temporadas.

🛠️ Tecnologías Utilizadas

Tableau Desktop Public Edition

Kaggle (fuente de datos)

Procesamiento y limpieza de datos

Diseño gráfico personalizado

Integración multimedia

📈 Conclusiones Finales

La audiencia presenta una caída constante desde su máximo histórico.

La calidad percibida disminuye progresivamente.

Los mejores episodios se concentran en las primeras temporadas.

La serie continúa debido a su valor de marca y rentabilidad.

El cambio estructural en el consumo audiovisual explica su transformación.

La serie dejó de ser fenómeno masivo, pero se consolidó como producto cultural de largo ciclo de vida.

🚀 Futuras mejoras

Análisis de sentimiento de guiones.

Comparativa con otras series animadas.

Modelo predictivo de rating por temporada.

Incorporación de métricas de streaming.

Versión optimizada para mobile.

🧩 Valor del Proyecto

Este proyecto demuestra:

Capacidad de análisis longitudinal.

Dominio del proceso completo de Data Analytics.

Diseño de dashboards con narrativa integrada.

Implementación de interactividad avanzada.

Comunicación ejecutiva basada en datos.

👩‍💻 Autoras: Ana María Castro y Valentina Castillo Escobar

Proyecto desarrollado como análisis integral de datos aplicado a narrativa interactiva y visualización estratégica.
