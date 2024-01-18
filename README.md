Proyecto Personas Desaparecidas - CNDES
Este proyecto tiene como objetivo la recopilación y análisis de datos relacionados con personas desaparecidas utilizando como fuente principal el Centro Nacional de Desaparecidos (CNDES), un órgano del Ministerio del Interior que coordina el sistema de personas desaparecidas en España.

Descripción del Proyecto
Fuentes de Datos
El Centro Nacional de Desaparecidos (CNDES) actúa como la principal fuente de datos para este proyecto. El CNDES, dependiente del Ministerio del Interior, es el órgano encargado de la coordinación efectiva del sistema de personas desaparecidas utilizado por las Fuerzas y Cuerpos de Seguridad en España. Este proyecto se centra en la recopilación y procesamiento de información proporcionada por el CNDES, incluyendo la extracción de datos de su sitio web y la creación de conjuntos de datos relacionados.

Estructura del Proyecto
Scripts de Extracción de Datos: El código fuente utilizado para extraer datos de la página web del CNDES y otros archivos relacionados.

Conjuntos de Datos: Archivos CSV que contienen información recopilada sobre personas desaparecidas. Estos datos se utilizan para análisis y visualización.

Instrucciones de Uso
Requisitos:

Asegúrate de tener instaladas las dependencias necesarias, como bibliotecas de Python mencionadas en los scripts.
Ejecución de Scripts:

Ejecuta los scripts de extracción de datos para obtener la información más reciente del CNDES y actualizar los conjuntos de datos.
Análisis y Visualización:

Utiliza los conjuntos de datos generados para realizar análisis y visualizaciones relacionadas con personas desaparecidas en España.
Referencias
Centro Nacional de Desaparecidos (CNDES): [Página oficial del CNDES.](https://cndes-web.ses.mir.es/publico/Desaparecidos)
Contribuciones
Contribuciones y sugerencias son bienvenidas. Si encuentras errores o tienes ideas para mejorar el proyecto, no dudes en abrir un problema o enviar una solicitud de extracción.

LIBRERIAS UTILIZADAS
from selenium import webdriver
from selenium.webdriver.support.ui import WebDriverWait
from selenium.webdriver.support import expected_conditions as EC
from selenium.webdriver.common.by import By
import time
import pandas as pd
import os
import base64

