# bluetooth-motion-trigger
A lightweight, low-cost motion detection node. By interfacing an IR sensor with an Arduino, this project registers physical intrusions and broadcasts an immediate status update via Bluetooth. This setup is ideal for basic security tripwires, doorway monitors, or automated proximity notifications.
# components-used 
* **Arduino Uno:** The main microcontroller board processing the sensor data and controlling the output.
* **IR Obstacle Avoidance Sensor:** The blue module on the left, featuring IR LEDs and a potentiometer, used to detect motion or physical presence.
* **Bluetooth Module (HC-05):** The green module on the right, featuring a red status LED, used to wirelessly transmit the alert signal.
* **Resistor:** Placed in the center of the breadboard, typically configured as a voltage divider to step down the 5V logic from the Arduino to the 3.3V required by the Bluetooth module's receive pin.
# circuit diagram
<img width="747" height="561" alt="Screenshot 2026-09-30 125012" src="https://github.com/user-attachments/assets/3a77b656-815c-4976-9210-cbcb838963c8" alt="Alt text describing the image" width="500">
