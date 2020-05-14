# ESPBoost
The ESPBoost is an ESP32 shield combines a **MPU6050** (6-axis gyro/accelerometer, via **SDA/SCL** GPIO), 2 H-Bridge motor drivers (**L9110s**, via GPIO 5, 16, 17,18 ), and a DC-DC (12v-5v) power regulator. Attaching this shield onto a Lolin32, actuations that demand high current (max. 800mA for each bridge) and detections of angles, acceleration can be easily made possible.  

![ESPBoost20200504 v3](https://i.loli.net/2020/05/14/ULQxYGg987HXnOf.jpg)

### Components

* **Dual L9110s** (800 mA) DACs
* **MPU6050** Accelerometer and Gyroscope
* **TPS563201** Voltage regulator (4.5v to 17v input, 3A output)
* **FSR** (force sensitive resistor) connector  (A2 section)