# Balanza Electrónica con Celda de Carga

## Descripción

Sistema de medición de peso desarrollado con Arduino utilizando una celda de carga y el amplificador HX711. El proyecto permite visualizar mediciones en diferentes unidades mediante una pantalla LCD, realizar operaciones de tara y alternar entre distintas escalas de medición utilizando pulsadores.

## Archivos del Proyecto

* `codigo.ino` - Programa principal para adquisición, procesamiento y visualización de datos.

## Componentes Utilizados

* Arduino
* Celda de carga
* Amplificador HX711
* Pantalla LCD I2C 20x4
* Pulsadores
* Fuente de alimentación

## Funcionalidad

* Medición de peso mediante celda de carga.
* Calibración de la señal utilizando HX711.
* Función de tara para compensación de peso.
* Visualización de datos en pantalla LCD.
* Cambio de unidades mediante pulsadores.
* Conversión automática entre gramos y onzas.
* Estimación de volumen en cm³ para líquidos con densidad conocida.
* Control de iluminación de la pantalla LCD.

## Tecnologías Utilizadas

* Arduino IDE
* C++
* HX711
* Comunicación I2C
* Instrumentación Electrónica
* Adquisición de Datos

## Objetivo del Proyecto

Desarrollar una balanza electrónica de bajo costo capaz de medir peso con una celda de carga, proporcionando diferentes escalas de visualización e incorporando funciones de tara e interacción mediante botones para facilitar su uso.
