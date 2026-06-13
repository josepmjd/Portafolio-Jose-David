# Grúa Tipo Puerto Controlada por Bluetooth

## Descripción

Sistema de control para una grúa tipo puerto desarrollado con Arduino y una aplicación móvil creada en MIT App Inventor. El proyecto permite controlar de forma inalámbrica los movimientos de la grúa.

## Archivos del Proyecto

* `codigo.ino` - Programa principal de control de la grúa y comunicación Bluetooth.
* `app.aia` - Proyecto de la aplicación móvil desarrollada en MIT App Inventor.

## Componentes Utilizados

* Arduino
* Módulo Bluetooth HC-05/HC-06
* Pantalla LCD I2C 20x4
* Servomotores
* Motor paso a paso
* Driver para motor paso a paso
* Finales de carrera
* Fuente de alimentación

## Funcionalidad

* Control inalámbrico mediante Bluetooth.
* Operación remota desde una aplicación Android.
* Control de desplazamiento de la grúa.
* Control de posicionamiento mediante motor paso a paso.
* Apertura y cierre de la garra de manipulación.
* Referenciación automática mediante finales de carrera.
* Monitoreo de variables mediante pantalla LCD.
* Protección de recorrido mediante sensores de límite.

## Tecnologías Utilizadas

* Arduino IDE
* C++
* MIT App Inventor
* Comunicación Bluetooth
* Comunicación I2C
* Control de servomotores
* Control de motores paso a paso

## Objetivo del Proyecto

Desarrollar un prototipo de grúa tipo puerto controlada de forma inalámbrica desde un dispositivo móvil, integrando sistemas de posicionamiento, actuadores y mecanismos de seguridad para la manipulación de objetos.
