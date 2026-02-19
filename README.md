## ProximAlert

ProximAlert es un detector de proximidad utilizando Arduino UNO R3 y sensor ultrasónico HC-SR04.
Activa una alerta visual mediante un LED rojo cuando detecta un objeto a menos de 10 cm.
Desarrollado en C++ con Arduino IDE.

## Componentes
- Arduino UNO R3
- Sensor ultrasónico HC-SR04
- LED rojo
- Resistor 220 Ω
- Cables jumper

## Conexiones
| HC-SR04 | Arduino |
|---------|---------|
| VCC     | 5V      |
| GND     | GND     |
| TRIG    | Pin 7   |
| ECHO    | Pin 6   |
| LED     | Pin 13  |

## Uso
1. Cargar el código en Arduino IDE
2. Conectar los componentes según la tabla
3. Abrir el monitor serial a 9600 baudios
