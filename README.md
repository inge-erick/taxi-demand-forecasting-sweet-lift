# 🚕 Pronóstico de Demanda de Taxis - Sweet Lift Taxi

## 📝 Caso de Negocio
La compañía **Sweet Lift Taxi** necesita atraer más conductores durante las horas pico en los aeropuertos. El objetivo es predecir la cantidad de pedidos para la próxima hora (`num_orders`) para que la empresa pueda planificar su oferta de manera eficiente.

## 🛠️ Metodología Técnica
- **Análisis Temporal:** Remuestreo de datos por hora y análisis de estacionalidad diaria y semanal.
- **Ingeniería de Características:** Creación de variables de desfase (lags), medias móviles y variables de calendario (hora, día de la semana) sin fuga de información.
- **Modelado:** Comparación de múltiples modelos, incluyendo Regresión Lineal, Árboles de Decisión y modelos de **Boosting**.
- **Validación Robusta:** Uso de una división temporal adecuada (80/20) para asegurar que el modelo sea capaz de generalizar hacia el futuro.

## 📊 Resultados
- **Métrica Lograda:** Se obtuvo un **RECM (RMSE) de [tu_valor_final]** en el conjunto de prueba, superando el objetivo de negocio de ser menor a 48.
- **Impacto:** El modelo identifica con precisión los picos de demanda, permitiendo a Sweet Lift Taxi reducir tiempos de espera y maximizar ingresos.

## 🧰 Stack Técnico
`Python`, `Pandas`, `Statsmodels`, `Scikit-Learn`, `LightGBM/CatBoost`, `Matplotlib`.
