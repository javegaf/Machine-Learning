# 📊 Análisis de Clientes y Pagos - Proyecto CRISP-DM

Este repositorio documenta el desarrollo de un proyecto de análisis de datos financieros orientado al estudio del comportamiento de clientes del banco Monopoly, recientemente adquirido por **Dormammu**. El análisis se guía por la metodología **CRISP-DM** (Cross-Industry Standard Process for Data Mining), asegurando un enfoque estructurado desde la comprensión del negocio hasta la evaluación de modelos predictivos.

---

## 🧠 Descripción del Proyecto

El objetivo principal de este proyecto es analizar una base de datos compuesta por **574 variables** y más de **51.000 registros de clientes**, con información mensual sobre pagos, transacciones y otras actividades financieras. Este análisis busca comprender la relación entre las **transacciones realizadas** y los **pagos efectivos**, identificar patrones de comportamiento, detectar posibles anomalías y anticipar escenarios futuros mediante modelos predictivos.

Actualmente, el proyecto se encuentra en las fases de **Comprensión de los Datos** y **Preparación**, abarcando procesos como:

- Limpieza y transformación de variables  
- Creación de nuevas columnas (como pagos totales)  
- Detección y tratamiento de valores nulos  
- Conversión de formatos y estructuras  
- Visualización inicial mediante mapas de calor y diagramas de dispersión  
- Análisis de correlaciones relevantes  

---

## 🎯 Propósito y Justificación

### Propósito

Brindar a Dormammu una plataforma analítica capaz de interpretar el comportamiento financiero de los clientes de Monopoly. A través del análisis de pagos y transacciones, se busca apoyar la toma de decisiones estratégicas para mejorar la **retención de clientes**, **optimizar productos financieros** y **anticipar comportamientos clave**.

### Justificación

- **📈 Optimización Estratégica:** Identificar patrones mensuales de actividad (alta/baja) que faciliten la planificación de campañas y recursos.  
- **🔍 Análisis Predictivo:** Construir modelos que permitan prever pagos futuros, periodos de inactividad o probabilidad de impago.  
- **💡 Mejora de la Experiencia del Cliente:** Detectar fricciones en los procesos de pago o señales de descontento del cliente.  
- **⚠️ Reducción de Riesgos:** Identificar anomalías y caídas de desempeño para activar medidas preventivas ante comportamientos inusuales.  

---

## 🌍 Contexto de Negocio

Banco Monopoly, con años de operación en el mercado chileno, ha sido adquirido por Dormammu, una entidad financiera con sede en Nueva York. Como parte de su proceso de integración, Dormammu ha solicitado un estudio exhaustivo sobre el comportamiento de los clientes de Monopoly, con el fin de diseñar estrategias efectivas para abordar este nuevo mercado.

Los datos fueron extraídos por el equipo técnico de Monopoly y representan 12 meses de información mensual por cliente, organizada en una base de datos estructurada por columnas (variables mensuales por cliente, sin duplicados de registros).

---

## 🧪 Proceso del proyecto (CRISP-DM)

| Etapa                   | Estado       | Descripción                                                                 |
|-------------------------|--------------|------------------------------------------------------------------------------|
| Comprensión del Negocio | ✅ Completada | Definición de objetivos analíticos, preguntas clave y contexto del banco    |
| Comprensión de los Datos| ✅ Completada | Exploración inicial, detección de problemas de calidad, visualización       |
| Preparación de los Datos| ✅ Completada | Limpieza, transformación, creación de variables derivadas                   |
| Modelado                | ❌ Bloqueado  | Desarrollo de modelos para predecir pagos, inactividad o comportamiento     |
| Evaluación              | ❌  Bloquedo  | Validación de resultados y comparación con expectativas de negocio          |
| Despliegue              | ⏳ Pendiente  | Documentación de hallazgos, recomendaciones y visualizaciones clave         |

---

## 📌 Próximos Pasos

- Finalización del preprocesamiento de datos.  
- Selección y entrenamiento de modelos supervisados y no supervisados.
- Evaluación de precisión, recall y utilidad empresarial de los modelos.  

---