# HC-SR04 Ultrasonic sensor

---
## DESCRIPTION

The HC-SR04 ultrasonic sensor uses sonar to measure the distance to an object, similar to how bats or dolphins navigate. It works by sending out a high‑frequency sound pulse and measuring the time it takes for the echo to return after bouncing off an object.

Unlike some optical sensors (such as Sharp infrared rangefinders), the HC-SR04 is not affected by sunlight or the color of an object, making it reliable in a wide range of lighting conditions. However, soft or sound‑absorbing materials like cloth or foam can be harder to detect.

A common real‑world example of this sensor is a car‑park occupancy detector, which checks whether a car is present in a parking space.

---
## SENSOR RANGE

The HC-SR04 performs non‑contact distance measurement with the following specifications:

- Minimum distance: 2 cm

- Maximum distance: 4 meters

- Accuracy: up to 3 mm

This makes it suitable for proximity detection, obstacle avoidance, and distance measurement projects.

---
## WIRING

| HC-SR04 Pin | Arduino Pin       |
|------------|-------------------|
| VCC        | 5V                |
| GND        | GND               |
| Trig       | Digital Pin 9     |
| Echo       | Digital Pin 10    |

See [diagram here](https://github.com/kingston-hackSpace/Distance_ultrasonic-pololuIR_sensors/blob/main/ultrasonic_bb.jpg)

⚠️ Note: The Echo pin outputs a 5V signal. If you are using a 3.3V microcontroller (such as ESP32 or Raspberry Pi Pico), use a voltage divider to protect the input pin.

---
## CODE ANS INSTRUCTIONS

- One you have wired your ultrasonic sensor to the Arduino board (as explained above), plug the board to your computer.

- Download [this 'ultrasonic sensor' code](https://github.com/kingston-hackSpace/Distance_ultrasonic-pololuIR_sensors/blob/main/ultrasonic.ino) and upload it to your Arduino board.

- Open the Arduino IDE's Serial Monitor to see the data coming from the sensor.

- See an [explanation of this code here](https://projecthub.arduino.cc/Isaac100/getting-started-with-the-hc-sr04-ultrasonic-sensor-7cabe1)
---
## MORE TUTORIALS

[Ultrasonic Sensor + LCD Display](https://howtomechatronics.com/tutorials/arduino/ultrasonic-sensor-hc-sr04/)

[Trigger a fan using an ultrasonic sensor](https://github.com/kingston-hackSpace/Fans)
