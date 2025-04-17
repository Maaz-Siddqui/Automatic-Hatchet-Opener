## Features
- Measures distance using an ultrasonic sensor.
- Toggles the motor direction (open/close) when the distance is between 10 and 50 cm.
- Uses PWM for motor control.

## Hardware Required
- **Arduino Board** (e.g., Arduino MEGA)
- **Ultrasonic Sensor** (URM37)
- **DC Motors** 
- **Motor Driver**

## Connections
- **Ultrasonic Sensor**:
  - Echo Pin → Pin 3
  - Trigger Pin → Pin 10
- **Motor Driver**:
  - Right Motor Enable → Pin 6
  - Left Motor Enable → Pin 7
  - Right Motor PWM → Pin 4
  - Left Motor PWM → Pin 5
