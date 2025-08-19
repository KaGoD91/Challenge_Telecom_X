# Análisis de Evasión de Clientes (Churn) - TelecomX

Este proyecto tiene como objetivo analizar el **comportamiento de evasión de clientes (Churn)** en una compañía de telecomunicaciones ficticia llamada **TelecomX**.  
El análisis permite identificar patrones de cancelación de servicios y proponer recomendaciones estratégicas para reducir la tasa de evasión.

---

##  Contenido del proyecto

- **Carga de datos**: Se extraen los datos desde un archivo JSON proporcionado (TelecomX_Data.json).
- **Limpieza y tratamiento**: Se corrigen valores faltantes, categorías inconsistentes y se crean nuevas variables derivadas como `Cuentas_Diarias`.
- **Análisis exploratorio de datos (EDA)**:
  - Estadísticas descriptivas.
  - Distribución de la evasión (Churn).
  - Relación de churn con variables categóricas (género, contrato, método de pago).
  - Relación de churn con variables numéricas (permanencia, cargos).
- **Visualizaciones**: Gráficos de barras, tortas y boxplots para interpretar los patrones de evasión.
- **Conclusiones e Insights**: Identificación de factores clave que influyen en la cancelación.
- **Recomendaciones estratégicas**: Propuestas para reducir la tasa de churn mediante campañas de retención, incentivos y optimización de precios.

---

##  Instalación y dependencias

Clona el repositorio y asegúrate de tener instaladas las siguientes librerías de Python:

```bash
git clone <URL_REPO>
cd TelecomX-Churn
pip install -r requirements.txt
