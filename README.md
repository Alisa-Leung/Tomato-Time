# Tomato Time

### Draft Ideas:
I drafted some ideas (designs, features, etc.) of things I wanted to try out in this project. I iterated with some sketches first, messing around with a food theme. In terms of features, I originally wanted to create an alarm clock but decided that a pomodoro timer would allow me to explore more on the software side of things while also learning more CAD. From there, I narrowed down my ideas and sketched out a more 3D design to lay out my project more. [Sketch below]

<img width="300" alt="sketch" src="https://github.com/user-attachments/assets/c0a066c5-f25c-4f05-b03e-79ec2c373f0f" />

### Components:
* Keyboard Switch
* Lolin C3 Mini ESP32 Devboard
* 2.25in TFT LCD Display
* 3.3v Piezo Buzzer
* <a href="https://handsontec.com/index.php/product/ky040-rotary-encoder-module-for-arduinoraspberry/">KY-040 Rotary Encoder Module</a> -- $1.20
* <a href="https://www.digikey.com/en/products/detail/e-switch/EG1218/101726">SPDT Slide Switch</a> -- $0.72
* <a href="https://www.aliexpress.us/item/3256808547528857.html?src=google&gatewayAdapt=glo2usa#nav-specification">TP4056 Battery Charger & 5v Boost Module</a> -- $1.42
* <a href="https://ydlbattery.com/products/3-7v-2000mah-654065-lithium-polymer-ion-battery">3.7v 2000mah 654065 Rechargeable Lithium Polymer Battery</a> -- $5.87

The project is fully powered by a rechargeable lipo battery. Power is managed through an integrated TP4056 charger/booster module and controlled by a physical SPDT slide switch. When powered, the Lolin C3 Mini controls a display, buzzer, keyboard switch button, and a rotary encoder.

<img width="600" alt="wiring diagram" src="https://github.com/user-attachments/assets/e199f518-aae7-405d-9a40-60cfeb21088e" />
