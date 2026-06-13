# Mezclador de Pintura

## Descripción

Sistema automatizado para la dosificación, mezcla y verificación de colores de pintura desarrollado en Arduino. El proyecto permite seleccionar un color desde una interfaz LCD, calcular las proporciones necesarias de pigmentos base y ejecutar automáticamente el proceso de llenado, mezclado y entrega de la pintura.

Además, incorpora un sensor de color para verificar el resultado final y determinar si la mezcla obtenida corresponde al color esperado.

## Archivos del Proyecto

- `codigo.ino` - Programa principal de control y automatización.

## Componentes Utilizados

- Arduino Mega
- Pantalla LCD I2C 20x4
- Sensor de color TCS34725
- Sensor ultrasónico HC-SR04
- Relés de potencia
- Motores DC
- Puente H
- Fines de carrera
- Buzzer
- Sistema de dosificación de pintura
- Sistema mecánico de mezcla

## Funcionalidad

- Selección de colores mediante menú interactivo.
- Dosificación automática de pigmentos base.
- Generación de diferentes tonalidades a partir de colores primarios.
- Posicionamiento automático del recipiente de mezcla.
- Control automático de las etapas de carga, mezcla y entrega.
- Agitación automática de la pintura.
- Verificación del color resultante mediante sensor TCS34725.
- Identificación automática de colores mediante análisis RGB.
- Retroalimentación visual a través de pantalla LCD.
- Señalización de estados mediante buzzer.

## Colores Disponibles

- Verde
- Verde Claro
- Verde Oscuro
- Naranja
- Naranja Claro
- Naranja Oscuro
- Violeta
- Violeta Claro
- Violeta Oscuro
- Turquesa
- Café
- Gris Claro
- Gris Oscuro

## Tecnologías Utilizadas

- Arduino IDE
- C++
- Comunicación I2C
- Sensores de color
- Automatización de procesos
- Control de actuadores

## Objetivo del Proyecto

Desarrollar un sistema automatizado capaz de preparar mezclas de pintura de forma repetible y controlada, reduciendo errores humanos mediante la dosificación automática de pigmentos y la verificación del color final obtenido.
