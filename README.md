# 🌤️ Estación Meteorológica Azul

> **Proyecto Integrador de la Especialidad**  
> 🎓 **Escuela ProA** | 5to Año — 2026

---

## 📌 Presentación del Proyecto

¡Bienvenidos/as a nuestro repositorio! Somos un grupo de estudiantes de 5to año de la **Escuela ProA**. Como parte del programa de nuestra especialidad técnica, estamos desarrollando una **Estación Meteorológica Automatizada** basada en microcontroladores Arduino.

Este proyecto integra conocimientos de programación, electrónica y diseño físico, permitiendo medir variables ambientales clave en tiempo real, procesar alertas térmicas y de gases, y presentar la información a través de una interfaz visual clara.

---

## 🛠️ Componentes y Conexiones del Hardware

A continuación se detallan los componentes electrónicos utilizados en la estación meteorológica y su esquema de conexiones al Arduino:

| Componente | Función Principal | Pin / Conexión |
| :--- | :--- | :--- |
| **Pantalla LCD 16x2 + Módulo I2C** | Visualización de datos meteorológicos y alertas | Pines SDA / SCL (I2C) |
| **Sensor DHT11** | Lectura de temperatura ambiental y humedad relativa | Pin Digital |
| **Sensor MQ-2** | Detección de humo, inflamables y calidad del aire | Pin Analógico |
| **LED Calor** | Indicador visual de alerta por alta temperatura | Pin Digital 13 *(con res. 220Ω)* |
| **LED Frío** | Indicador visual de alerta por baja temperatura | Pin Digital 12 *(con res. 220Ω)* |
| **Buzzer Piezoeléctrico** | Alarma sonora para advertencias o umbrales | Pin Digital 11 |
| **Protoboard & Cableado** | Interconexión de componentes | Cables M-M, H-H y M-H |

---

## 📐 Enmaquetado y Diseño Estructural

Además del circuito electrónico y el desarrollo del software en Arduino (`.ino`), el proyecto contempla la elaboración de un **enmaquetado y carcasa protectora** para la estación.

### Objetivos del Enmaquetado:
1. **Protección:** Salguardar la placa Arduino y los sensores de factores externos.
2. **Distribución Sensorial:** Ubicar el sensor DHT11 y el MQ-2 en zonas ventiladas para lecturas precisas sin interferencia del calor del circuito.
3. **Interfaz de Usuario:** Montar la pantalla LCD y los LEDs en el frente de la estructura para facilitar la visualización de los datos.

---

## 🚀 Instalación y Uso

1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/martinabarrionuevo/estacion_Metereologica_azul.git](https://github.com/martinabarrionuevo/estacion_Metereologica_azul.git)
