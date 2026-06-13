# Brazo con Control PID

## Descripción

Sistema de control de posición para un brazo mecánico accionado mediante un motor brushless. El proyecto implementa un controlador PID en Arduino y una interfaz gráfica desarrollada en C# para supervisar el comportamiento del sistema y ajustar parámetros de control.

## Archivos del Proyecto

* `codigo.ino` - Código Arduino para adquisición de datos y control.
* `codigo.cs` - Aplicación de escritorio desarrollada en C#.

## Componentes Utilizados

* Arduino
* Motor brushless
* ESC (Electronic Speed Controller)
* Sensores de realimentación
* Conversor RS232/USB
* Computador con aplicación de monitoreo

## Algoritmo PID

* Control Proporcional (P)
* Control Integral (I)
* Control Derivativo (D)
* Ajuste de parámetros de control

## Funcionalidad

* Control de posición del brazo mecánico.
* Ajuste de parámetros PID desde la interfaz gráfica.
* Monitoreo de variables del sistema en tiempo real.
* Comunicación serial entre Arduino y la aplicación de escritorio.
* Visualización del comportamiento del controlador.

## Tecnologías Utilizadas

* Arduino IDE
* C#
* Windows Forms
* Comunicación Serial
* Control PID

## Objetivo del Proyecto

Implementar un sistema de control realimentado utilizando un controlador PID para regular la posición de un brazo mecánico accionado por un motor brushless, permitiendo analizar el desempeño del sistema y realizar ajustes de control desde una interfaz de usuario.
