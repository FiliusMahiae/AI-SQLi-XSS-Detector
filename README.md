# AI-SQLi-XSS-Detector

## Descripción
Este proyecto implementa un modelo de **Inteligencia Artificial** para la detección de ataques **SQL Injection (SQLi) y Cross-Site Scripting (XSS)** en fragmentos de texto. Utiliza **procesamiento de lenguaje natural (NLP)** y **redes neuronales convolucionales (CNNs)** para mejorar la detección de estos ataques comunes en aplicaciones web.

## Contenido del Notebook
El notebook documenta todo el proceso de desarrollo del modelo, incluyendo:
- **Exploración y preprocesamiento de datos**: Carga de datasets, limpieza y tokenización de texto.
- **Creación del modelo**: Implementación de una **CNN** para clasificar fragmentos de texto como benignos o maliciosos.
- **Entrenamiento y evaluación**: Ajuste de hiperparámetros y comparación del rendimiento con modelos base como **Naïve Bayes**.
- **Explicabilidad**: Uso de **LIME (Local Interpretable Model-agnostic Explanations)** para analizar las decisiones del modelo.
- **Resultados y conclusiones**: Análisis de métricas y discusión sobre la efectividad del modelo.

## Instalación
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/AI-WebAttack-Detection.git
   cd AI-WebAttack-Detection
   ```
2. Instalar dependencias:
   ```bash
   pip install -r requirements.txt
   ```

## Uso
Ejecutar el notebook:
```bash
jupyter notebook XSS_SQLi_CNN.ipynb
```

## Resultados
El modelo ha demostrado un alto rendimiento en la detección de ataques SQLi y XSS, con métricas satisfactorias en precisión y recall. Se proporciona un análisis detallado en el notebook.

## Licencia
Este proyecto se publica bajo la licencia **MIT**, permitiendo su uso, modificación y distribución bajo sus términos. El autor no se hace responsable del uso que terceros puedan darle, incluyendo su empleo en el ámbito académico.

## Autor
**Sergio Mahía** 

