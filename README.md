# smartglass
This project aims to design and develop a Smart Glass system to assist visually impaired individuals in detecting nearby obstacles. The system uses ultrasonic sensing and audio feedback to alert the user about objects or barriers within a certain range, enabling safe and independent mobility.

The device is lightweight, embedded within a regular eyeglass frame, and powered by a rechargeable battery. When an object is detected within a preset distance, a buzzer or vibration module is triggered to inform the user in real-time.

🔧 Components Used:
Arduino Nano – Microcontroller to process sensor input

Ultrasonic Sensor (HC-SR04) – Detects distance to obstacles

NE-555 Timer IC – Generates pulse signal for the buzzer

Resistors – 10 KΩ and 1 KΩ

Capacitors – 10µF and 100µF (25V) for debouncing/filtering

5V Buzzer – Alerts the user with sound

3.7V Rechargeable Battery – Powers the entire circuit

Tactile Switch – For turning the system on/off

Standard Eyeglass Frame – Base structure for mounting components

🎯 Objectives:
Enable blind individuals to sense nearby obstacles using sound.

Make a compact, wearable device using low-cost components.

Provide real-time distance feedback using an ultrasonic sensor.

Minimize complexity while maximizing reliability and safety.

🛠️ Working Principle:
The ultrasonic sensor emits sound waves and detects reflections from nearby obstacles.

The distance is calculated using the time delay between emission and reception.

If an object is detected within the threshold range, a signal is sent to the NE-555 Timer IC.

The IC triggers the buzzer, alerting the user to the obstacle.

The system remains active until switched off by the tactile button.

🧠 Learning Outcomes:
Understood real-world applications of digital logic and embedded systems

Gained experience with sensor integration and timer circuits

Practiced building and testing a practical assistive device

Improved knowledge of circuit design, debugging, and soldering

🌍 Applications:
Assistive technology for the blind and visually impaired

Integration with smart canes, IoT navigation, or wearable safety systems

