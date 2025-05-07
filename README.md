# Final-Project-Data-Scientist
Final Project - Estimación del Valor de un jugador de futbol Profesional
# Predicción del valor de mercado de jugadores de fútbol

&#x20;*Figura 1.* Jugadores de fútbol entrenando. En este notebook realizamos un proyecto de ciencia de datos paso a paso para predecir el **valor de mercado** de futbolistas a partir de datos físicos y estadísticos. Usamos el dataset de Kaggle “Soccer players values and their statistics” (datos de Transfermarkt y FBRef) como fuente principal. 

El objetivo es limpiar los datos, explorar patrones, crear nuevas variables, entrenar modelos de regresión y evaluar su desempeño para explicar los factores que influyen en el precio de los jugadores.

## Configuración de Kaggle en Google Colab

Primero configuramos el acceso a Kaggle en Colab mediante la API oficial. Instalamos la librería Kaggle, subimos nuestra clave (`kaggle.json`) y la guardamos en el directorio adecuado. Luego usamos el comando de Kaggle para descargar y descomprimir el dataset completo. Esto permite reproducir exactamente los datos originales en el entorno de Colab. 
