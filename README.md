# 📦 Kuman Arduino & Robotics Starter Kits — Archivo Completo del Disco Original

[![Arduino](https://img.shields.io/badge/Arduino-Compatible-00979C?style=flat&logo=arduino&logoColor=white)](https://www.arduino.cc/)
[![Hardware](https://img.shields.io/badge/Hardware-Kuman%20Sensors%20%26%20Kits-orange?style=flat)]()
[![Archive](https://img.shields.io/badge/Status-Preserved%20CD%20Archive-blue?style=flat)]()

Este repositorio contiene la **colección completa y original de recursos, tutoriales, esquemas, librerías y código fuente** incluidos en el disco (CD-ROM) de los kits de **Kuman** para **Arduino** y proyectos de robótica/electrónica.

> 💡 **¿Por qué este repositorio?**  
> La gran mayoría de los kits de electrónica Kuman incluían un mini-CD con todo el material didáctico, controladores y librerías. Hoy en día, casi ninguna computadora moderna cuenta con unidad de disco óptico (CD/DVD), y muchos de estos archivos ya no están disponibles en línea o los enlaces del fabricante se encuentran caídos. Este repositorio fue creado para **preservar y compartir todo el contenido** con la comunidad maker, estudiantes y entusiastas.

---

## 📑 Tabla de Contenidos
1. [Contenido y Catálogo de Kits](#-catálogo-de-kits)
2. [Guía de Lecciones Prácticas (Kits K1, K4, K6, K11, K25, K31, K52, K62, K64, K66)](#-lecciones-prácticas-incluidas)
3. [Kit de 20 Sensores en 1 (K63)](#-kit-de-20-sensores-en-1-k63--ky63-20)
4. [Proyectos Especiales y Módulos Avanzados (K27, K17, K24)](#-proyectos-especiales-y-módulos-avanzados)
5. [Librerías de Arduino Incluidas](#-librerías-de-arduino-incluidas)
6. [Materiales Educativos y Libros (PDF)](#-materiales-educativos-y-libros-pdf)
7. [Cómo Usar este Material](#-cómo-usar-este-material)
8. [Estructura del Directorio](#-estructura-del-directorio)
9. [Licencia y Créditos](#-licencia-y-créditos)

---

## 🧰 Catálogo de Kits

| Directorio | Nombre del Kit / Contenido | Descripción |
| :--- | :--- | :--- |
| **`K1`** | **Kuman K1 Arduino Starter Kit** | Kit básico de iniciación: 28 lecciones de código, manual completo (`.doc`), lista de partes (`.xls`) y conjunto de librerías. |
| **`K4`** | **Kuman K4 Arduino Kit (Multi-idioma)** | Kit completo con manuales en **inglés**, **francés** y **japonés**, además de librerías y las lecciones estándar. |
| **`K6`** | **Kuman K6 Arduino Advanced Kit** | Incluye las 28 lecciones base más carpetas dedicadas para: **RFID RC522** (control de acceso), **RTC DS1302** (reloj en tiempo real), **DHT11**, **Teclado matricial 4x4**, **Joystick PS2**, **Relé** y **Sensor de sonido**. |
| **`K11`** | **Kuman K11 Kit** | Conjunto completo de tutoriales de Arduino, lista de materiales, lecciones prácticas y librerías. |
| **`K17`** | **Kuman K17 3D Printer / CNC RAMPS 1.4 Kit** | Kit para impresoras 3D y control CNC. Incluye manual de **RAMPS 1.4** para Arduino Mega 2560, firmware con soporte para pantalla LCD gráfica 12864 y librerías necesarias. |
| **`K22`** | **Kuman K22 Sensor Module Kit** | Módulos individuales de fotorresistencia (LDR), pulsadores y prueba de centelleo LED. |
| **`K24`** | **Kuman K24 MQ Gas Sensors Series** | Guías de conexión y códigos de lectura analógica para sensores de gas serie MQ (humo, metano, GLP, alcohol, CO, etc.). |
| **`K25`** | **Kuman K25 Arduino Kit** | Kit de iniciación con tutoriales, lista de componentes, librerías y 28 lecciones prácticas. |
| **`K27`** | **Kuman K27 Mega Sensor & Robotics Kit** | Kit extenso con más de **34 proyectos documentados**: módulo relé Bluetooth HC-06, encoders rotativos, acelerómetro ADXL335, HC-SR04, driver de motores L293D, giróscopo MPU6050, pantalla LCD1602, display MAX7219, etc. |
| **`K31`** | **Kuman K31 Kit** | Tutoriales dedicados de Arduino K31, lista de partes, código y librerías. |
| **`K52`** | **Kuman K52 Kit** | Tutoriales, lista de componentes, código y librerías. |
| **`K62`** | **Kuman K62 Kit** | Tutoriales detallados para Arduino, librerías y lecciones. |
| **`K63`** | **Kuman K63 (KY63-20) 20-in-1 Sensor Kit** | 20 módulos y sensores individuales con su propio documento explicativo y código de prueba (`.txt`/`.doc`). |
| **`K64`** | **Kuman K64 Kit** | Kit de experimentación Arduino con tutorial, librerías y código. |
| **`k66`** | **Kuman K66 Kit** | Tutoriales, lista de piezas, código de lecciones y documentación para termistores y sensores. |
| **`arduino Learning materials`** | **Biblioteca de Aprendizaje Arduino** | 5 libros completos en PDF, guía de trucos y técnicas, diagramas esquemáticos del Arduino UNO R3 y drivers de instalación. |

---

## 📚 Lecciones Prácticas Incluidas

Los kits principales (`K1`, `K4`, `K6`, `K11`, `K25`, `K31`, `K52`, `K62`, `K64`, `k66`) comparten un plan de estudio estructurado de 28 lecciones progresivas ubicadas en `code/code/`:

| Lección | Nombre del Experimento | Componentes Utilizados |
| :---: | :--- | :--- |
| **Lesson 2** | `Blink` | LED integrado y pin digital 13 |
| **Lesson 4** | `button` | Pulsador con resistencia pull-up / pull-down |
| **Lesson 5** | `button module` | Módulo de botón táctil |
| **Lesson 6** | `Fire alarm test` | Sensor de flama/fuego + zumbador |
| **Lesson 7** | `flame module` | Módulo detector de llama analógico/digital |
| **Lesson 8** | `8x8 dot matrix experiment` | Matriz de LEDs 8x8 conexión directa |
| **Lesson 9** | `8x8 dot matrix experiment` | Matriz de LEDs 8x8 con circuito integrado |
| **Lesson 10** | `Active Buzzer module` | Zumbador (Buzzer) activo con señal digital |
| **Lesson 11** | `Passive buzzer` | Zumbador pasivo con modulación de frecuencia (`tone`) |
| **Lesson 12** | `1602 liquid crystal experiment` | Pantalla LCD 16x2 estándar HD44780 |
| **Lesson 13** | `74HC595 experiment` | Registro de desplazamiento de 8 bits (Shift Register) |
| **Lesson 14** | `digital tube display experiment` | Display de 7 segmentos de 1 dígito |
| **Lesson 15** | `Four bit digital tube` | Display de 7 segmentos de 4 dígitos multiplexado |
| **Lesson 16** | `Hit module` | Sensor de impacto / vibración |
| **Lesson 17** | `Tilt-Switch` | Interruptor sensor de inclinación |
| **Lesson 18** | `ultrasonic distance measuring module` | Sensor de ultrasonido HC-SR04 |
| **Lesson 19** | `thermal resistance` | Termistor NTC para medición de temperatura |
| **Lesson 20** | `step motor test` | Motor paso a paso 28BYJ-48 con controlador ULN2003 |
| **Lesson 21** | `steering gear control experiment` | Servomotor SG90 controlado por PWM |
| **Lesson 22** | `photosensitive lamp experiment` | Fotorresistencia (LDR) con control de luz automática |
| **Lesson 23** | `LM35 Temperature Sensor` | Sensor de temperatura analógico de precisión LM35 |
| **Lesson 24** | `LED Scintillation test` | Efectos y secuencias de luces LED |
| **Lesson 25** | `Infrared-Receiver` | Lectura de receptor infrarrojo con decodificación de tramas |
| **Lesson 26** | `Potentiometer` | Lectura analógica ADC con potenciómetro rotativo |
| **Lesson 27** | `PWM control light intensity` | Modulación por ancho de pulsos (PWM) para regular brillo |
| **Lesson 28** | `Infrared remote control` | Control remoto por infrarrojos para accionar cargas |

---

## 🔬 Kit de 20 Sensores en 1 (K63 / KY63-20)

Ubicado en `K63/KY63-20 sensor/`, contiene una carpeta independiente para cada uno de los 20 sensores del kit, cada uno con su manual `.doc` y código de prueba:

1. **DHT11 temperature humidity sensor**: Sensor digital de temperatura y humedad ambiental.
2. **DS18B20 Temperature Sensor Module**: Sensor digital de temperatura de alta precisión mediante protocolo 1-Wire.
3. **Digit light Sensor**: Sensor digital de luminosidad ambiental.
4. **Full color LED RGB module**: Módulo LED RGB de cátodo/ánodo común con control PWM.
5. **Garden Soil Moisture Sensor**: Sensor resistivo de humedad para tierra y plantas.
6. **HC06 Bluetooth Module**: Manual de configuración y comandos AT para comunicación inalámbrica serie.
7. **Hall magnetic field sensor**: Sensor de campo magnético por efecto Hall.
8. **Infrared Receiver Module**: Módulo receptor IR 38 kHz.
9. **Infrared obstacle avoidance sensors**: Sensor óptico para detección y evasión de obstáculos.
10. **Laser transmitter module**: Módulo de diodo láser rojo de 650 nm.
11. **Photo Interrupt Sensor module**: Barrera óptica (sensor foto-interruptor) para conteo o tacómetros.
12. **Relay Module**: Módulo de relé electromecánico para control de cargas de alta tensión (110V/220V).
13. **Smoke Sensor**: Sensor de humo analógico y digital.
14. **Sound sensor module**: Sensor acústico con micrófono y comparador LM393.
15. **TCRT5000 infrared optical tracking sensor**: Sensor seguidor de líneas por reflexión infrarroja.
16. **Touch sensor module**: Sensor táctil capacitivo.
17. **flame module**: Sensor óptico de llama de fuego.
18. **infrared transmitter module**: Diodo emisor de infrarrojos para control remoto.
19. **mercury tilt switch module**: Interruptor de inclinación basado en ampolla de mercurio.
20. **reed switch module**: Interruptor magnético de láminas (contacto seco activado por imán).

---

## 🚀 Proyectos Especiales y Módulos Avanzados

### 1. Kit K27 (Proyectos Especiales)
La carpeta `K27/` incluye guías y programas para módulos más avanzados:
- **`30-Relay Module`**: Control de relé por comandos inalámbricos vía Bluetooth HC-06.
- **`31 Rotary Encoders`**: Lectura de codificador rotativo con interrupciones por hardware (`attachInterrupt`) y control de sentido de giro.
- **`32 ADXL335 sensor`**: Acelerómetro analógico de 3 ejes (X, Y, Z).
- **`33 HCSR04Ultrasonic`**: Medición de distancia por eco ultrasónico.
- **`34 4x4 keypad`**: Lectura y matriz de teclado de 16 teclas.
- **`Experiment 26 MPU6050`**: Sensor inercial I2C de 6 grados de libertad (acelerómetro + giroscopio).
- **`Experiment 28 DC motor & Experiment 29 L293D`**: Control de velocidad y dirección de giro de motores DC mediante puente H L293D.
- **`HC-SR501 Code`**: Sensor de movimiento por infrarrojos pasivos (PIR).
- **`MAX7219`**: Controlador de pantallas y matrices LED en cascada.

### 2. Kit K17 (Impresoras 3D & CNC RAMPS 1.4)
La carpeta `K17/` contiene:
- Firmware preconfigurado para impresoras 3D con Arduino Mega 2560 (`12864固件 081.rar`).
- Soporte para controlador inteligente con pantalla gráfica LCD 12864 con lector de tarjetas SD.
- Manual de usuario paso a paso (`Ramps1.4 instructions.docx`).
- Paquete de librerías (`libraries-07.zip`).

### 3. Kit K6 (RFID y Reloj en Tiempo Real)
La carpeta `K6/` añade módulos indispensables para automatización:
- **RFID RC522**: Lectura de tarjetas y llaveros RFID a 13.56 MHz para sistemas de acceso y control de asistencia.
- **RTC DS1302**: Reloj de tiempo real con respaldo de batería para conservar fecha y hora exactas.

---

## 📦 Librerías de Arduino Incluidas

Ubicadas dentro de la carpeta `Library/` de cada kit (como `K1/Library/` o `K4/Library/`):

- **`dht11` / `Dht`**: Lectura de sensores de temperatura y humedad DHT11 / DHT22.
- **`Ds18b20` / `OneWire`**: Comunicación 1-Wire para sondas de temperatura Dallas.
- **`IRremote` / `IR`**: Codificación y decodificación de protocolos infrarrojos (NEC, Sony, RC5, etc.).
- **`LiquidCrystal` / `LiquidCrystal_I2C`**: Manejo de pantallas de cristal líquido tanto por pines paralelos como mediante módulo I2C (PCF8574).
- **`NewPing`**: Manejo eficiente y optimizado de sensores ultrasónicos HC-SR04.
- **`SFE_BMP180`**: Sensor barométrico de presión atmosférica y altitud.
- **`Servo`**: Control de servomotores estándar por hardware.
- **`Stepper`**: Control de motores paso a paso unipolares y bipolares.
- **`Encoder`**: Lectura rápida de encoders en cuadratura.
- **`Matrix` / `Sprite`**: Animación y control de matrices LED.
- **`TimerOne_r11`**: Temporizadores por interrupción de hardware con resolución de microsegundos.
- **`TFTLCD`**: Controladores para pantallas gráficas TFT a color.
- **`EEPROM`, `SPI`, `Wire`, `SoftwareSerial`, `SD`, `Firmata`**: Bibliotecas base para almacenamiento, comunicación serie emulada e interfaces con tarjetas SD y PC.

---

## 📖 Materiales Educativos y Libros (PDF)

En la carpeta `arduino Learning materials/` se encuentran libros y documentación técnica en formato PDF de gran valor formativo:

1. **`Arduino-book1.pdf` a `Arduino-book5.pdf`**: Colección didáctica sobre fundamentos de programación en C++, electrónica básica, sensores, actuadores y proyectos.
2. **`arduino-tips-tricks-and-techniques.pdf`**: Consejos avanzados para optimizar memoria, consumo de energía y velocidad de ejecución en microcontroladores AVR.
3. **`UNO R3 schematics.png`**: Diagrama esquemático electrónico oficial del microcontrolador ATmega328P y convertidor USB ATmega16U2.
4. **`arduino uno r3 driver install.doc`**: Guía para la correcta instalación del puerto COM virtual en sistemas operativos Windows.

---

## 🛠️ Cómo Usar este Material

### 1. Instalación del Software
1. Descarga e instala la versión más reciente de **[Arduino IDE](https://www.arduino.cc/en/software)** (compatible con Windows, macOS y Linux).
2. Si utilizas una placa compatible (clon) con chip USB **CH340** o **CP2102**, asegúrate de tener instalado su respectivo driver (en Linux generalmente viene integrado en el kernel; en Windows puedes requerir el driver CH341SER).

### 2. Cómo Agregar las Librerías
Para utilizar las librerías incluidas en `K1/Library/` o cualquiera de los kits:
1. Copia la carpeta de la librería deseada (por ejemplo `LiquidCrystal_I2C` o `IRremote`).
2. Pégala en tu directorio de librerías de Arduino:
   - **Linux**: `~/Arduino/libraries/`
   - **Windows**: `Documentos\Arduino\libraries\`
   - **macOS**: `~/Documents/Arduino/libraries/`
3. Reinicia el Arduino IDE para que reconozca las librerías instaladas.

### 3. Abrir los Códigos de Ejemplo
- Los archivos con extensión `.pde` o `.ino` pueden abrirse directamente con Arduino IDE haciendo doble clic o desde **Archivo > Abrir**.
- Los archivos `.txt` presentes en carpetas como `K27` o `K63` contienen el código en texto plano; simplemente copia y pega su contenido en una ventana nueva de Arduino IDE.
- Selecciona tu placa en **Herramientas > Placa** (normalmente *Arduino Uno* o *Arduino Mega 2560*) y el puerto serie correspondiente en **Herramientas > Puerto**, y pulsa **Subir** (Upload).

---

## 📁 Estructura del Directorio

```text
kuman/
├── README.md                          <-- Esta guía principal
├── kuman.code-workspace               <-- Espacio de trabajo para VS Code
├── arduino Learning materials/        <-- Libros en PDF, esquemáticos y drivers
│   ├── Arduino-book[1-5].pdf
│   ├── arduino-tips-tricks-and-techniques.pdf
│   └── UNO R3 schematics.png
├── K1/                                <-- Kit de inicio Kuman K1 (28 lecciones)
│   ├── Kuman K1Arduino KIT tutorials.doc
│   ├── Library/
│   └── code/code/Lesson[2-28]...
├── K4/                                <-- Kit Kuman K4 (Tutoriales EN, FR, JP)
├── K6/                                <-- Kit K6 + Módulos RFID, RTC, Teclado, PS2
├── K11/                               <-- Kit K11
├── K17/                               <-- Kit Impresora 3D / CNC RAMPS 1.4 + LCD 12864
├── K22/                               <-- Módulos individuales de sensores básicos
├── K24/                               <-- Módulos de Gas serie MQ (código y diagramas)
├── K25/                               <-- Kit K25
├── K27/                               <-- 34+ Proyectos y sensores avanzados
├── K31/                               <-- Kit K31
├── K52/                               <-- Kit K52
├── K62/                               <-- Kit K62
├── K63/                               <-- Kit KY63-20 (20 sensores en 1)
│   └── KY63-20 sensor/
│       ├── DHT11, DS18B20, Soil, Bluetooth, Hall, Laser, Relay, etc...
├── K64/                               <-- Kit K64
└── k66/                               <-- Kit K66
```

---

## ⚖️ Licencia y Créditos

- Los tutoriales, diagramas, códigos y esquemáticos originales son propiedad de **Kuman** ([www.kumantech.com](http://www.kumantech.com)).
- Las librerías de código abierto de terceros incluidas pertenecen a sus respectivos autores originales y se rigen bajo sus correspondientes licencias (GPL, LGPL, MIT, BSD).
- Este repositorio se comparte con fines puramente **educativos, de divulgación científica y de preservación histórica** para la comunidad mundial de electrónica y robótica maker.