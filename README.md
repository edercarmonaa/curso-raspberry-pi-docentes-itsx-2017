# Curso de Raspberry Pi para Docentes del Instituto Tecnológico de Xalapa (2017)

> **Descripción Corta:** Curso práctico impartido en 2017 a docentes del Instituto Tecnológico de Xalapa para iniciar, configurar y programar una Raspberry Pi.

## 📌 Descripción General

Este repositorio contiene materiales formativos en PDF y PowerPoint correspondientes a un curso introductorio-práctico de Raspberry Pi impartido en el año 2017 a docentes del Instituto Tecnológico de Xalapa (ITSX). El flujo del contenido avanza desde la preparación inicial del sistema operativo y la configuración básica del dispositivo, hasta el uso de Raspbian/Linux, programación en Python, manejo del puerto GPIO, comunicación con periféricos y uso del módulo de cámara.

El objetivo general es que el participante adquiera las bases técnicas para instalar y administrar una Raspberry Pi, trabajar desde consola, desarrollar scripts en Python y controlar hardware externo mediante entradas, salidas digitales, protocolos de comunicación y captura de imagen/video. Por su enfoque docente, el material puede servir como base para prácticas de laboratorio, actualización académica o introducción a sistemas embebidos y cómputo físico.

## 🛠️ Tecnologías y Herramientas

- Raspberry Pi
- Raspbian / Raspberry Pi OS
- Linux / GNU/Linux
- Terminal de comandos
- NOOBS
- `raspi-config`
- Python
- Librería `RPi.GPIO`
- Librería `picamera`
- OpenCV
- I2C
- SPI
- 1-Wire
- UART
- `i2c-tools`
- `smbus`
- SSH
- VNC
- Wi-Fi
- Micro SD / FAT32
- `raspistill`
- `raspivid`
- Presentaciones PowerPoint (`.pptx`)
- Documentos PDF (`.pdf`)

## 📂 Estructura del Curso

El contenido está organizado como una secuencia de siete módulos numerados. Cada módulo cuenta con material en PDF y, en la mayoría de los casos, con una presentación PowerPoint asociada.

```text
├── 1 Configuracion Inicial.pdf                  # Preparación de Micro SD, instalación del sistema operativo, actualización y configuración inicial.
├── 1 Configuracion Inicial.pptx                 # Presentación del módulo de configuración inicial.
├── 1 Configuracion  Inicial.pptx                # Copia duplicada de la presentación del módulo 1.
├── 2 Introduccion a Raspbian.pdf                # Introducción a Raspbian, sistema de archivos Linux y comandos básicos.
├── 2 Raspbian.pptx                              # Presentación sobre uso de terminal y comandos de GNU/Linux.
├── 3 Programacion en Python.pdf                 # Fundamentos de Python para Raspberry Pi.
├── 3 Programacion en Python RPi.pptx            # Presentación con operadores, estructuras de control, funciones y excepciones.
├── 4 Puerto GPIO.pdf                            # Uso del puerto GPIO para entradas, salidas y detección de eventos.
├── 4 GPIO RPi.pptx                              # Presentación con ejemplos prácticos usando RPi.GPIO.
├── 5 Comunicaciones I2C, SPI, 1-Wire, UART.pdf  # Protocolos de comunicación para periféricos y sensores.
├── 6 Comunicaciones RPi.pdf                     # Material complementario de comunicaciones en Raspberry Pi.
├── 6 Comunicaciones RPi.pptx                    # Presentación sobre I2C, SPI, 1-Wire, UART, bits, bytes y representaciones numéricas.
├── 7 Camara RPi.pdf                             # Uso del módulo de cámara en Raspberry Pi.
└── 7 Camara RPi.pptx                            # Presentación sobre raspistill, raspivid, picamera y OpenCV.
```

Módulo 1 - Configuración inicial: cubre los sistemas operativos disponibles para Raspberry Pi, preparación de la tarjeta Micro SD, instalación mediante NOOBS, actualización de Raspbian y configuración de zona horaria, idioma, contraseña, hostname, Wi-Fi, SSH y VNC.

Módulo 2 - Introducción a Raspbian: introduce Raspbian como sistema basado en Debian, la jerarquía de archivos en GNU/Linux y comandos esenciales de terminal como `pwd`, `cd`, `ls`, `mkdir`, `cp`, `mv`, `rm`, `clear`, `chmod` y `grep`.

Módulo 3 - Programación en Python: presenta los fundamentos del lenguaje para desarrollo en Raspberry Pi, incluyendo comentarios, números, operadores aritméticos, operadores de asignación, operadores lógicos, comparaciones, cadenas, listas, condicionales, ciclos, funciones, `break`, `continue`, `else` en ciclos y manejo de excepciones.

Módulo 4 - Puerto GPIO: explica consideraciones eléctricas del puerto GPIO, instalación y uso de `RPi.GPIO`, modos de numeración `BOARD` y `BCM`, configuración de pines, salidas digitales, entradas digitales, resistencias pull-up/pull-down, detección de flancos y manejo de eventos.

Módulo 5 - Comunicaciones I2C, SPI, 1-Wire, UART: aborda buses y protocolos de comunicación usados para conectar sensores y periféricos con Raspberry Pi. El material se centra en conceptos de comunicación, configuración de interfaces y trabajo con protocolos de hardware.

Módulo 6 - Comunicaciones Raspberry Pi: profundiza en unidades de información, complemento a dos, operaciones a nivel de bits, representaciones numéricas en Python e implementación práctica de I2C, SPI, 1-Wire y UART. Incluye ejemplos con `i2cdetect`, `i2cget`, `i2cset`, `i2cdump`, `smbus` y lectura de sensores como MPU6050.

Módulo 7 - Módulo de cámara: cubre la habilitación de la cámara, captura de fotos y video desde línea de comandos con `raspistill` y `raspivid`, uso de la cámara desde Python con `picamera`, grabación por detección de movimiento e instalación de OpenCV para procesamiento de imágenes.

## Licencia

Este material se distribuye bajo la licencia Creative Commons Attribution 4.0 International (CC BY 4.0). Consulta el archivo `LICENSE` para más detalles.
