# ProyectoVisionArtificial

# Detección de Vehículos con YOLO

## Integrantes

- Aldo André Rubio Cortez Registro: 22310381
- Jose Raymundo Sandoval Souza Registro: 23310309
- 6E
---

## Descripción

Este proyecto implementa un modelo YOLO para detectar y clasificar distintos tipos de vehículos utilizando un dataset de tráfico.
Dataset obtenido de roboflow https://universe.roboflow.com/roboflow-100/vehicles-q0x2v  

Las clases detectadas son:

- big bus
- big truck
- bus-l-
- bus-s-
- car
- mid truck
- small bus
- small truck
- truck-l-
- truck-m-
- truck-s-
- truck-xl-

---

## Tecnologías utilizadas

- Python
- Google Colab
- YOLOv8 (Ultralytics)

---

## Instalación

Instalar las dependencias:

!pip install ultralytics opencv-python matplotlib
---

## Ejecución

1. Abrir el notebook `6E_ProyectoYOLO.ipynb`.
2. Montar Google Drive.
3. Ejecutar todas las celdas.
4. Esperar a que finalice el entrenamiento.
5. Utilizar el modelo generado (`best.pt`) para realizar nuevas detecciones.

---

# Caso de Estudio

## Problema a resolver

En muchas ciudades es importante conocer el flujo vehicular para reducir congestionamientos y mejorar la planeación vial. El conteo manual de vehículos requiere mucho tiempo y puede presentar errores.

## Hardware propuesto

- Cámara de alta resolución instalada sobre una avenida.
- Computadora industrial o NVIDIA Jetson para ejecutar el modelo YOLO.
- Servidor para almacenar estadísticas.
- Red de comunicación para enviar la información al centro de monitoreo.

## Flujo de funcionamiento

1. La cámara captura video continuamente.
2. El dispositivo procesa cada fotograma utilizando YOLO.
3. El modelo detecta y clasifica los vehículos.
4. Se contabilizan los vehículos por tipo.
5. La información se almacena y puede utilizarse para analizar el tráfico en tiempo real.

## Beneficios

- Conteo automático.
- Clasificación por tipo de vehículo.
- Monitoreo en tiempo real.
- Apoyo para la sincronización de semáforos.
- Mejor planeación de infraestructura vial.

---

## Evidencias

Las imágenes de prueba con las detecciones realizadas por el modelo se encuentran en la carpeta **evidencias/**.

##

enlace drive: https://drive.google.com/drive/folders/1CGgYZdjJyn_MfQhjkCnCI34kJEmGQ3qL?usp=drive_link 
enlace google colab: https://colab.research.google.com/drive/1n537M5W5RXy1sn6X6Gfl4sO2PanTKQT7?usp=sharing