# Detección de Vibraciones

## Descripción

Proyecto de detección, monitoreo y análisis de vibraciones en motores trifásicos mediante sensores inerciales y una aplicación de escritorio desarrollada en C#. El sistema permite adquirir datos en tiempo real, visualizar el comportamiento de la máquina, almacenar registros históricos y generar alertas según el nivel de vibración detectado.

## Archivos del Proyecto

* `codigo.ino` - Código Arduino para adquisición y procesamiento de datos.
* `codigo.cs` - Aplicación de escritorio en C# para visualización y gestión de información.

## Componentes Utilizados

* Arduino
* Sensor acelerómetro/giroscopio (MPU6050)
* Contactores industriales
* Relés
* Conversor RS232/USB
* Motor trifásico
* Computador con aplicación de monitoreo

## Funcionalidad

* Detección de vibraciones en tiempo real.
* Cálculo y monitoreo de niveles de vibración.
* Clasificación del estado del motor mediante umbrales configurables.
* Visualización gráfica de los datos adquiridos.
* Registro y almacenamiento de mediciones en archivos CSV.
* Consulta de datos históricos por fecha.
* Generación de alertas ante condiciones anormales.
* Apagado automático del sistema en condiciones críticas.

## Tecnologías Utilizadas

* Arduino IDE
* C#
* Windows Forms
* Comunicación Serial
* CSV para almacenamiento de datos

## Objetivo del Proyecto

Desarrollar una plataforma de monitoreo capaz de detectar condiciones anormales de funcionamiento en motores eléctricos mediante el análisis de vibraciones, facilitando la supervisión del equipo y la toma de decisiones de mantenimiento.
