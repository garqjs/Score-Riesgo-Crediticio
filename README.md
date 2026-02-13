# Credit-Risk-Scorecard-Optimizacion-con-XGBoost
Pipeline profesional de riesgo crediticio que integra 4 fuentes de datos, ingeniería de variables financieras y un modelo de Machine Learning con restricciones monotónicas para una toma de decisiones auditable y transparente.

📂 Descripción del Proyecto
Este proyecto simula un entorno de producción bancaria para predecir el default de clientes. Se utilizaron datos de aplicaciones, historial en Buró de Crédito, pagos previos y rechazos internos para construir un modelo de scoring robusto.

🛠️ Tech Stack
Data Engine: DuckDB (Procesamiento SQL de alto rendimiento).

Modelado: XGBoost con monotone_constraints (Restricciones de negocio).

Explicabilidad: SHAP (Valores de Shapley para transparencia).

Validación: Scikit-learn (Métricas KS, Gini y AUC).


📈 Ingeniería de Variables (Features de Negocio)
Se crearon indicadores clave para la evaluación de riesgo:

Ratio Global Leverage: Exposición total de deuda vs. ingresos.

Payment Friction: Score de morosidad acumulada y retrasos en pagos.

Annuity Burden: Capacidad de pago mensual real.
