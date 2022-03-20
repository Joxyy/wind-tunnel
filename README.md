# wind-tunnel
Simple model of wind tunnel that consists of 1 sensor and 1 actuator. The idea is to control behaviour of flying pingpong ball.
Components:
  - Arduino Uno R3 platform to control this mechanism
  - HC-SR04 Ultrasonic sensor to get information about the distance (height)
  - CPU fan (BLDC motor, 24V/0.15A, 25x25 mm) - air flow is better when the tunnel is narrow
  - L298N - motor driver module (actually only 1 transistor and diode were enough, but I did it this way because of simplicity)
  - LCD display with I2C module to show information about height
  - in version1 -> 4x4 matrix keyboard (desired height enter)
  - in version2 -> 2 buttons (up and down commands)

  +3D printed holder for the tunnel designed to match the construction of the fan. The tunnel is built using transparent PVC foil and it is placed in the holder.
