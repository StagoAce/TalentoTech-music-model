# Predicción de Éxito de Canciones (Proyecto Académico)

Este repositorio contiene un proyecto académico para el programa Bootcamp Talento Tech de Inteligencia Artificial desarrollado para predecir el éxito de canciones utilizando características numéricas y espectrogramas extraídos de archivos de audio. Se trata de un proyecto de investigación y aprendizaje, y **no se utilizará para ningún fin comercial o ajeno al ámbito académico**.

## Descripción

El proyecto integra dos tipos de datos para la predicción:

- **Características numéricas:** Datos como duración, tempo, energía, etc.
- **Espectrogramas:** Imágenes generadas a partir del audio, las cuales se procesan mediante una Red Neuronal Convolucional (CNN).

La arquitectura del modelo es híbrida e integra:
- Una **Red Neuronal Densa (DNN)** para procesar las características numéricas.
- Una **Red Neuronal Convolucional (CNN)** para analizar los espectrogramas.

El modelo combina ambas salidas para predecir si una canción es exitosa (valor 1) o no (valor 0).

## Requisitos

- **Python 3.8+**
- **GPU (opcional):** Si deseas acelerar el entrenamiento, asegúrate de tener instalados los drivers de NVIDIA, CUDA y cuDNN.

### Dependencias

Instala las dependencias necesarias ejecutando:

pip install librosa numpy pandas matplotlib tensorflow opencv-python scikit-learn seaborn

## Configuración del Entorno Virtual
Se recomienda usar un entorno virtual para aislar las dependencias del proyecto:

Crear el entorno virtual:

python -m venv venv
# Activar el entorno virtual:

En Windows:


  venv\Scripts\activate

En macOS/Linux:


  source venv/bin/activate

Instalar las dependencias:

Puedes crear un archivo requirements.txt con el siguiente contenido:

nginx

librosa

numpy

pandas

matplotlib

tensorflow

opencv-python

scikit-learn

seaborn

Luego instala las dependencias con:


pip install -r requirements.txt

### Uso

## El proyecto incluye scripts para:

Cargar y preprocesar los datos: 

Se realiza la carga de las características numéricas y los espectrogramas, normalizando nombres de archivos para resolver problemas de codificación y espacios.
Entrenar el modelo: Se entrena un modelo híbrido (CNN + DNN) que integra ambos tipos de datos.
Evaluar el modelo: Se evalúa el desempeño utilizando métricas como F1-Score, AUC-ROC y se genera una matriz de confusión.
Para ejecutar el script principal, usa:

python main.py
Asegúrate de que el script principal se llame main.py o ajusta el nombre según corresponda.

## Notas Adicionales
Proyecto Académico: Este proyecto se ha desarrollado únicamente con fines académicos y de investigación. No se utilizará para fines comerciales ni para ningún otro propósito fuera del ámbito académico.
Ajustes y Mejoras: Se pueden realizar modificaciones en la arquitectura, parámetros de entrenamiento y preprocesamiento para adaptarlo a diferentes conjuntos de datos o requisitos.
Uso de GPU: Si tienes una GPU compatible, asegúrate de tener instalados los controladores de NVIDIA, CUDA y cuDNN para acelerar el entrenamiento.

## Licencia
Este proyecto es de uso académico y se proporciona "tal cual", sin garantías de ningún tipo. No se permite el uso comercial sin el consentimiento expreso del autor.

## INTEGRANTES
SANTIAGO CASTAÑO ACEVEDO

ALEJANDRO FLOREZ

SANTIAGO GALLEGO
