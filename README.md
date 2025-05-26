## Features
- Real-time motion detection with adjustable sensitivity
- Visual (LED) and audible (buzzer) alerts
- Configurable detection timeout period
- Serial monitor logging for debugging
- 
## Circuit Diagram
```plaintext
Arduino Uno
│
├── PIR Sensor
│   ├── VCC → 5V
│   ├── OUT → Digital Pin 2
│   └── GND → GND
│
├── LED
│   ├── Anode → Digital Pin 13
│   └── Cathode → GND via 220Ω resistor
│
└── Buzzer
    ├── Positive → Digital Pin 7
    └── Negative → GND
