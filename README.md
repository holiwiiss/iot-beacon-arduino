# IOT Beacon Arduino

Proyecto basado en **Arduino** que emite señales **Bluetooth Beacon** para ser detectadas por una aplicación móvil.

## Proyecto relacionado

Sistema IoT basado en beacons compuesto por: Arduino Sensor → Android App → Web Dashboard

Este repositorio forma parte de un proyecto completo compuesto por tres partes:

- Arduino Beacon Sensor → https://github.com/holiwiiss/iot-beacon-arduino
- Android Scanner App → https://github.com/holiwiiss/iot-beacon-android-studio
- Web Monitoring Platform → https://github.com/holiwiiss/iot-beacon-web

## Tecnologías

- Arduino
- Bluetooth Beacon
- SparkFun nRF52840 Mini Breakout

## Configuración

1. Conectar correctamente el sensor.
2. Seleccionar la placa en Arduino IDE: `SparkFun nRF52840 Mini Breakout`
3. Seleccionar el puerto correspondiente.
4. Subir el programa al dispositivo.

Una vez cargado el programa, el sensor comenzará a **emitir beacons** que podrán ser detectados por la aplicación Android.
