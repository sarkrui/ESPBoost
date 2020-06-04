# ESPBoost
The ESPBoost is an ESP32 shield combines a **MPU6050** (6-axis gyro/accelerometer, via **SDA/SCL** GPIO), 2 H-Bridge motor drivers (**L9110s**, via GPIO **5**, **16**,**17**,**18** ), and a DC-DC (12v - 5v) power regulator (for powering up the ESP board via USB, allowing to charge Li-Po and the ESP32 MCU). Attaching this shield onto a Lolin32, actuations that demand high current (max. 800mA for each bridge), for example, driving two DC motors, and detections of angles, acceleration can be easily made possible. 

![ekb3YD4FxWSRAgo](https://i.loli.net/2020/06/04/ekb3YD4FxWSRAgo.png)

### Components

* **Dual L9110s** (800 mA) DACs
* **MPU6050** Accelerometer and Gyroscope
* **TPS563201** Voltage regulator (4.5v to 17v input, 3A output)
* **FSR** (force sensitive resistor) connector  (A2 section)

### Pinout 

![9usdo4JG2DMlhZ7](https://i.loli.net/2020/06/05/9usdo4JG2DMlhZ7.png)

### Sample 
If you're interested in the field of Internet of Tangible Things, this shield may help. For sample inquiry, please drop me an email hi@pxing.design

