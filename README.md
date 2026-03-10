# Challenge Telecom X Parte 2
# 📊 Challenge Telecom X: Análisis de Evasión de Clientes

## 📝 Descripción del Proyecto
Este proyecto aborda el desafío de predecir y comprender la evasión de clientes en una empresa de telecomunicaciones. A través del análisis de datos exploratorio y la implementación de algoritmos de Machine Learning, el objetivo es identificar los factores principales que impulsan las cancelaciones y proponer estrategias de retención viables para el negocio.

## 🛠️ Tecnologías y Librerías Utilizadas
* **Lenguaje:** Python
* **Manipulación de Datos:** Pandas, NumPy
* **Visualización:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Decision Tree, Logistic Regression, Random Forest, KNN)
* **Tratamiento de Datos Desbalanceados:** Imbalanced-Learn (SMOTE)

## ⚙️ Flujo de Trabajo
1. **Preparación de Datos:**
   * Eliminación de variables no predictivas
   * Codificación de variables categóricas mediante One-Hot Encoding
   * Escalamiento de datos continuos
2. **Análisis Exploratorio (EDA):**
   * Visualización del desbalance de clases
   * Análisis de correlación de variables frente al Churn
   * Análisis dirigido utilizando Boxplots y Countplots para variables clave
3. **Modelado Predictivo:**
   * División del dataset en conjuntos de Entrenamiento (80%) y Prueba (20%)
   * Balanceo de la clase minoritaria en el conjunto de entrenamiento usando **SMOTE**
   * Entrenamiento y evaluación de múltiples algoritmos
4. **Análisis de Importancia de Variables:**
   * Extracción de coeficientes (Regresión Logística)
   * Reducción de impureza (Random Forest)
   * Importancia por permutación (KNN)

## 💡 Principales Descubrimientos (Insights)
* **Tiempo de Permanencia (`tenure`):** Es la métrica de retención más crítica. La mayoría de las deserciones ocurren durante los primeros meses.
* **Tipo de Contrato:** Los clientes con suscripciones de mes a mes (`Month-to-month`) son altamente volátiles frente a los de contratos anuales o bianuales.
* **Servicio de Fibra Óptica:** Poseer este servicio aumenta significativamente la probabilidad de cancelación, sugiriendo problemas de precio o calidad.
* **Cargos Mensuales (`Monthly`):** Cargos más altos generan mayor fricción y empujan a los clientes a abandonar la empresa.

## 🚀 Estrategias de Retención Propuestas
* **Programa de Fidelización Temprana:** Implementar beneficios exclusivos durante los primeros 6 a 12 meses para anclar al cliente en su etapa de mayor riesgo.
* **Incentivar la Migración de Contratos:** Lanzar campañas para convertir a los usuarios mensuales a contratos de 1 o 2 años, ofreciendo rebajas en instalación o precios congelados.
* **Auditoría al Servicio de Fibra Óptica:** Investigar métricas de interrupciones y competitividad de precios, además de brindar soporte técnico prioritario a estos usuarios.

##
Proyecto desarrollado como parte del programa de ONE | TECH FOUNDATION - Especialización Data Science de Alura Latam.
