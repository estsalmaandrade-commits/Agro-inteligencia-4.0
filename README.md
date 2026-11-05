# Agro-inteligencia-4.0

Sistema automatizado de riego y monitoreo ambiental (humedad, CO2 y temperatura) con pantalla OLED e indicadores LED.

## Integrantes del Grupo
* Salma Lorena Andrade Neira – Técnico / Dev
* Mauren Dayana Florez Núñez – Técnico / Dev
* Shara Valeria García Navarro – Líder / PM
* Michael Leonardo Torrealba Torres – Diseñador / UX
* Saray Daniela Villareal Zúñiga – Investigador

## Objetivos
* **General:** Diseñar y construir el prototipo Agro-Inteligencia 4.0 para automatizar el riego y monitorear variables ambientales.
* **Específicos:**
  1. Integrar y calibrar los sensores YL-69, DHT11 y MQ-7.
  2. Programar la lógica de control en Arduino UNO y ESP-32.
  3. Estructurar la documentación y código colaborativamente en GitHub.

## Presupuesto (BOM)
* **Costo Total del Prototipo:** $170.000 COP

## Tabla de Conexiones del Circuito
* Sensor YL-69 (Humedad) -> Pin A0
* Sensor DHT11 (Temperatura) -> Pin D4
* Sensor MQ-7 (CO2) -> Pin A1
* Display OLED -> Bus I2C
* Micro bomba de agua -> Pin D2

## Instrucciones de Compilación y Carga (ESP32)
1. Abrir el IDE de Arduino y seleccionar la tarjeta ESP32 Dev Module.
2. Instalar las librerías DHT sensor library, Adafruit SSD1306 y Adafruit GFX.
3. Seleccionar el puerto COM asignado al ESP32.
4. Compilar y cargar el firmware.
