# ⚡ Análisis del Comportamiento Energético de una Pila Pública

## 🚀 Desafío

Se propone desarrollar una **solución de análisis de datos** que permita **caracterizar el comportamiento energético** de una **pila pública**, entendida como un punto fijo de entrega de energía con **dos conectores activos simultáneamente**, utilizados por múltiples usuarios.

---

## 🎯 Objetivos del Proyecto

Este análisis tiene como finalidad explorar diferentes aspectos relacionados con el uso y desempeño energético de la pila pública. Entre los objetivos se encuentran:

### 📈 1. Perfil de Consumo en el Tiempo
- Estudiar cómo varía el consumo energético en diferentes escalas temporales (horaria, diaria, semanal, mensual).
- Visualizaciones para identificar picos y valles de uso.

### ⚙️ 2. Análisis por Variables Energéticas
- Estudiar la **potencia**, **voltaje** y **corriente** entregados en los conectores.
- Comparaciones entre ambos conectores y entre distintos usuarios.

### 📊 3. Patrones de Uso Mensuales
- Identificación de tendencias o patrones repetitivos mes a mes.
- Análisis de comportamiento según el calendario (fines de semana, festivos, etc.).

### 🔋 4. Comparación vs. Capacidad Nominal
- Evaluar qué tan cerca está el uso real del límite de capacidad de la pila.
- Detección de posibles sobrecargas o subutilización.

### ♻️ 5. Análisis de Energía Reactiva
- Medir y caracterizar el comportamiento de la **energía reactiva**.
- Evaluar el impacto sobre la eficiencia del sistema.

### 🚨 6. Detección de Eventos y Alarmas
- Identificación automática de anomalías o eventos fuera de lo común.
- Generación de alertas basadas en umbrales configurables o algoritmos de detección.

---

## 🛠️ Tecnologías

- Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
- Jupyter Notebooks
- SQL (para consulta de bases de datos si aplica)
- Herramientas de visualización interactivas

---

## 📂 Estructura del Proyecto

```bash
📁 data/              # Datos crudos y procesados
📁 notebooks/         # Análisis exploratorios y visualizaciones
📁 src/               # Código fuente y scripts de análisis
📁 reports/           # Resultados, gráficas, informes
README.md             # Descripción del proyecto
