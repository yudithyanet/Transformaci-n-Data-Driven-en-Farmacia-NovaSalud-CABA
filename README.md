🏥 Transformación Data-Driven en Farmacia NovaSalud – CABA
Sistema Predictivo para Optimización de Inventario, Ventas y Rentabilidad

Proyecto de analítica descriptiva y predictiva desarrollado íntegramente en Python, aplicado a una farmacia minorista ubicada en la Ciudad Autónoma de Buenos Aires.

El objetivo fue transformar una gestión tradicional basada en histórico e intuición en un modelo estratégico basado en datos, capaz de anticipar demanda, optimizar inventarios y mejorar la rentabilidad.

🚀 Descripción del Proyecto

En un contexto económico volátil como el argentino, la correcta planificación de inventario es crítica para la sostenibilidad financiera.

Este proyecto integra un pipeline completo de análisis de datos desarrollado en Python que incluye:

🧹 Creación y preparación del dataset
📊 Análisis exploratorio de datos (EDA)
📈 Visualización analítica
🔮 Modelado predictivo con series temporales
🚨 Sistema de evaluación de riesgo de inventario
💡 Propuestas estratégicas basadas en datos

Todo el flujo de trabajo fue realizado en Python, desde el procesamiento de datos hasta la generación de visualizaciones y predicciones.

📂 1️⃣ Creación y Preparación del Dataset

Se construyó un dataset histórico de ventas que incluye:

Fecha de venta

ID de producto

Categoría

Unidades vendidas

Precio unitario

Costo unitario

Ingresos

Ganancia

Procesos realizados

Limpieza de datos (valores nulos y formatos de fecha)

Conversión de variables

Creación de variables derivadas

ingresos = unidades * precio
ganancia = ingresos - costo_total

Agregaciones temporales por día y mes

📌 Resultado: dataset estructurado y preparado para análisis descriptivo y modelado predictivo.

📊 2️⃣ Análisis Exploratorio de Datos (EDA) en Python

Herramientas utilizadas:

Python

Pandas

NumPy

Matplotlib

Seaborn

Principales análisis realizados

Tendencia de ventas a lo largo del tiempo

Identificación de patrones estacionales (semanales y anuales)

Identificación de productos con mayor participación en ventas

Análisis de rotación de inventario

Evaluación de márgenes y rentabilidad

Distribución de ventas por categoría

Hallazgos clave

La demanda presenta patrones estacionales definidos.

Un grupo reducido de productos concentra la mayor parte de las ventas.

Existen productos de baja rotación que inmovilizan capital.

Se detecta riesgo potencial de quiebre de stock en productos estratégicos.

📈 3️⃣ Visualización Analítica en Python

Todas las visualizaciones del proyecto fueron desarrolladas utilizando bibliotecas de Python.

Herramientas utilizadas:

Matplotlib

Seaborn

Visualizaciones generadas:

Evolución temporal de ventas

Comparación de ingresos y ganancias

Distribución de ventas por categoría

Ranking de productos más vendidos

Análisis de rentabilidad por producto

🎯 Objetivo: traducir el análisis de datos en visualizaciones claras que faciliten la toma de decisiones.

🔮 4️⃣ Modelado Predictivo

Se implementó un modelo de series temporales utilizando Prophet para:

Predecir demanda futura

Proyectar ventas anuales

Estimar ganancias futuras

Evaluar cobertura de inventario

Validación del modelo

Error SMAPE aproximado: 2–3%

Modelo con estacionalidad semanal y anual

Ajuste de changepoints para capturar cambios estructurales en la demanda

🚨 Sistema de Evaluación de Riesgo de Inventario

Se desarrolló un indicador basado en demanda proyectada:

Ratio de Cobertura
Ratio de Cobertura=Stock ActualDemanda Proyectada (7 dıˊas)
Ratio de Cobertura=
Demanda Proyectada (7 d
ı
ˊ
as)
Stock Actual
	​


Clasificación del riesgo:

🔴 Alto riesgo → Ratio < 1
🟡 Riesgo medio → 1 – 1.5
🟢 Bajo riesgo → > 1.5

Este indicador permite anticipar posibles quiebres de stock y planificar reposiciones de forma preventiva.

💡 5️⃣ Estrategias Propuestas

A partir del análisis se plantearon mejoras en la gestión operativa.

📦 Política de Inventario Inteligente

Punto de reposición dinámico

Cálculo estadístico de stock de seguridad

Revisión semanal basada en forecast de demanda

💰 Optimización del Capital de Trabajo

Mayor inversión en productos de alta rotación

Reducción de inventario en productos de baja demanda

Mejor planificación financiera

🚨 Sistema de Alertas

Monitoreo automático del ratio de cobertura

Identificación temprana de riesgo de quiebre de stock

📌 Conclusiones

La demanda de productos farmacéuticos presenta patrones predecibles que pueden modelarse con alta precisión.

Se identificaron riesgos críticos de quiebre de stock en productos estratégicos.

La planificación basada en datos reduce la incertidumbre operativa.

La implementación de modelos predictivos mejora la eficiencia en la gestión del inventario y del capital de trabajo.

Este enfoque permite que la farmacia evolucione de una gestión reactiva a una gestión estratégica basada en datos.

🏆 Impacto del Proyecto

Este proyecto demuestra que pequeñas y medianas empresas pueden:

Implementar analítica avanzada

Reducir pérdidas por quiebre de stock

Optimizar inventario

Mejorar rentabilidad

Tomar decisiones basadas en evidencia

🛠 Tecnologías Utilizadas

Python

Pandas

NumPy

Matplotlib

Seaborn

Prophet
