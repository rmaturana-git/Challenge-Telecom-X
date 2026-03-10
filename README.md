# 📡 Telecom X - Análisis de Evasión de Clientes (Churn)

Este proyecto fue desarrollado como parte de un desafío de **ONE | TECH FOUNDATION - Especialización Data Science**. El objetivo principal es identificar los factores críticos que impulsan la pérdida de suscriptores en la empresa **Telecom X** y proponer estrategias basadas en datos para reducir la tasa de evasión.

## 🎯 Propósito del Análisis
Telecom X enfrenta una alta tasa de cancelaciones mensuales. Este análisis busca:
1.  **Comprender el perfil del cliente:** Analizar variables demográficas, tipos de servicios y hábitos de consumo.
2.  **Identificar patrones de fuga:** Determinar qué condiciones contractuales o métodos de pago están vinculados al *Churn*.
3.  **Proporcionar Insights accionables:** Entregar recomendaciones estratégicas al equipo de negocio para mejorar la retención y rentabilidad.

## 📂 Estructura del Proyecto
```text
TelecomX-Churn-Analysis/
├── TelecomX_Data.json                                         # Datos consumidos vía API de GitHub
├── Analisis_Churn_TelecomX.ipynb                              # Notebook con el flujo ETL y EDA
├── Grafico_conteo-de-evasion-por-variables-numericas.png      # Gráfico
├── Grafico_distribucion-de-evasion.png                        # Gráfico
├── Grafico_recuento-de-evasion-por-variables-categoricas.png  # Gráfico
└── README.md                                                  # Descripción y guía del proyecto

```

## 📉 Visualizaciones e Insights Clave

Tras realizar el Análisis Exploratorio de Datos (EDA), se identificaron los siguientes puntos críticos:

* **Tasa de Evasión (Churn):** El **26.5%** de los clientes han abandonado la compañía.
* **Contratos de Riesgo:** Los clientes con contrato **Mes a Mes** presentan una probabilidad de fuga significativamente mayor que aquellos con contratos de 1 o 2 años.
* **Servicio de Internet:** Existe una correlación negativa en usuarios de **Fibra Óptica**, quienes presentan tasas de cancelación más altas.
* **Antigüedad (Tenure):** La mayor densidad de abandono ocurre en los primeros **12 meses** de relación con la empresa.

## 🛠️ Tecnologías Utilizadas

* **Python 3.x**
* **Pandas:** Extracción (ETL), limpieza y manipulación de datos.
* **Matplotlib & Seaborn:** Creación de visualizaciones estadísticas y estratégicas.
* **JSON Normalize:** Procesamiento de estructuras de datos anidadas.

## 🚀 Instrucciones para Ejecutar

Para replicar este análisis en tu entorno local, sigue estos pasos:

1. **Clonar el repositorio:**
```bash
git clone [https://github.com/tu-usuario/telecom-x-churn.git](https://github.com/tu-usuario/telecom-x-churn.git)

```


2. **Instalar dependencias:**
Asegúrate de tener instaladas las librerías necesarias ejecutando:
```bash
pip install pandas matplotlib seaborn requests

```


3. **Abrir el Notebook:**
Inicia Jupyter Notebook o abre el archivo `.ipynb` en **VS Code** o **Google Colab**.
4. **Ejecución:**
Ejecuta las celdas de forma secuencial. El script descargará automáticamente los datos desde la fuente oficial del desafío.

---

**Análisis realizado por:**
  - Rodrigo Maturana

**Rol:** 
  - AI Solutions Architect / Junior Data Scientist

**Contacto**
  - rmaturanad@gmail.com
  - www.linkedin.com/in/rodrigo-maturana-donoso
