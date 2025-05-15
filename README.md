## Features
- Real-time motion detection with adjustable sensitivity
- Visual (LED) and audible (buzzer) alerts
- Configurable detection timeout period
- Serial monitor logging for debugging 

## Hardware Requirements
| Component              | Specification                     | Qty |
|------------------------|-----------------------------------|-----|
| Arduino Board          | Uno R3 or compatible             | 1   |
| PIR Sensor             | HC-SR501                          | 1   |
| LED                    | 5mm (Any color)                   | 1   |
| Buzzer                 | Active 5V                         | 1   |
| Resistor               | 220Ω                              | 1   |
| Breadboard             | 400/800 points                    | 1   |
| Jumper Wires           | Male-to-Male                      | 10  |

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
