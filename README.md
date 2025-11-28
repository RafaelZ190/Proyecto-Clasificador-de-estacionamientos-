# Proyecto-Clasificador-de-estacionamientos-
Proyecto de teachable machine 

🚗 Clasificador de Estacionamientos con Teachable Machine

Este proyecto implementa un modelo de inteligencia artificial diseñado para identificar el estado actual de un espacio de estacionamiento. Su objetivo es apoyar en la automatización y gestión inteligente de estacionamientos, permitiendo detectar condiciones específicas a partir de imágenes generadas o cargadas manualmente.

🔗 Visualizar el Proyecto

Puedes probar el clasificador directamente en tu navegador sin necesidad de cámara web ni instalaciones adicionales:

📹 Video presentación : 
🌐Prueba de modelo : https://rafaelz190.github.io/Proyecto-Clasificador-de-estacionamientos-/

Nota: El sistema no utiliza webcam. Solo acepta imágenes generadas desde el generador de estacionamientos o imágenes reales que el usuario decida cargar.

📋 Requisitos del Sistema

Navegador web moderno (Chrome, Firefox, Edge, Safari)

El archivo del modelo exportado desde Teachable Machine (model.json, metadata.json, weights.bin)

Conexión a internet para ejecutar TensorFlow.js

🚀 ¿Cómo Usar el Sistema?

Abre el enlace de la página del sistema

Genera una imagen con el generador integrado o carga una imagen desde tu dispositivo

El sistema procesa la imagen con el modelo

Se mostrará el estado detectado del estacionamiento

Puedes probar distintas imágenes repetidamente

🅿️ Clases Soportadas

El modelo es capaz de identificar los siguientes estados:

🟩 Espacio Vacío

🚗 Espacio Ocupado

♿ Minusválidos Vacío

♿ Minusválidos Ocupado

🚧 Obstruido / Cerrado

🗑️ Con Basura / Sucio

🎨 Cómo se Entrenó el Modelo

Para crear un dataset robusto, se desarrolló un generador artificial de estacionamientos que produce imágenes sintéticas representando:

Líneas de estacionamiento

Asfalto

Autos con variaciones

Señalizaciones para discapacitados

Basura

Conos de obstrucción

Iluminación aleatoria

Ruido visual

Estas imágenes se usaron para entrenar las seis clases del modelo.
Además, el sistema permite subir imágenes reales para evaluar su funcionamiento fuera del entorno simulado.

🛠️ Tecnologías Utilizadas

Teachable Machine — Entrenamiento del modelo

TensorFlow.js — Ejecución del modelo en el navegador

JavaScript — Funcionamiento de la lógica del clasificador

HTML / CSS — Interfaz gráfica y diseño

Canvas API — Generación de imágenes simuladas

🤖 Acerca del Modelo

Tipo: Clasificación de imágenes

Tamaño de entrada: 224×224

Uso principal: Detección visual del estado de espacios de estacionamiento

Entrenamiento: Dataset sintético + imágenes opcionales

📄 Licencia

Este proyecto es de uso académico para la Universidad Autónoma de Baja California.

👨‍💻 Autor

Rafael Alexander Zamora Carrillo
Licenciatura en Inteligencia de Negocios
Universidad Autónoma de Baja California
