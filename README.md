# ESPBoost
![2SDCT8eYnrJI9NF](https://i.loli.net/2020/06/06/2SDCT8eYnrJI9NF.jpg)


### Introduction
The ESPBoost is an ESP32 shield combines a **MPU6050** (3-axis gyro/accelerometer, via **SDA/SCL** GPIO), 2 H-Bridge motor drivers (**L9110s**, via GPIO **5**, **16**,**17**,**18** ), and a DC-DC (4.5V ~17v to 5V) power regulator (for powering up the ESP board via USB, allowing to charge Li-Po and the ESP32 MCU). Attaching this shield onto a Lolin32, actuations that demand high current (max. 800mA for each bridge), for example, driving two DC motors, and detections of angles, acceleration can be easily made possible. 

![7GoLlhcizVjvBqO](https://i.loli.net/2020/06/06/7GoLlhcizVjvBqO.gif)

### Components

* **Dual L9110s** (800 mA) DACs
* **MPU6050** Accelerometer and Gyroscope
* **TPS563201** Voltage regulator (4.5v to 17v input, 3A output)
* **FSR** (force sensitive resistor) connector  (A2 section)



### To-do

- [ ]  Include support for ESP32 minikit 
- [ ]  Incoporate [daisy chain support](https://i.imgur.com/pLPUlMk.jpg) for ESP boards (e.g. [TTGO T-Base](https://www.aliexpress.com/item/32888680096.html)) that come with an i2c connector (consisting of`SDA/SCL/3.3/GND` )
- [ ]  Add **ESPBoost-Input**, configured with 3-axis gyro/accelerometer (MPU6050), 12-pin capacitive sensor (MPR121q), FSR pull-down resistors
- [ ]  Add **ESPBoost-Actuation**, consisting of 2 sets of `TB6612FNG`
- [ ]  Add **ESPBoost-Power**, supporting battery charging, regulating voltage from 3.7V to 5V, 9V, 12V



### Pinout 

![9usdo4JG2DMlhZ7](https://i.loli.net/2020/06/05/9usdo4JG2DMlhZ7.png)

### Sample 
If you're interested in the field of Internet of Tangible Things, this shield may help. For sample inquiry, please drop me an email hi@pxing.design



### BibTex

```
@inproceedings{DBLP:conf/ewsn/XingC21,
  author    = {Sark Xing and
               Yaliang Chuang},
  title     = {ESPBoost: {A} Rapid Prototyping Toolkit for Helping Designers Create
               the Internet of Tangible Things},
  booktitle = {CHIIoT@EWSN/EICS},
  series    = {{CEUR} Workshop Proceedings},
  volume    = {2996},
  publisher = {CEUR-WS.org},
  year      = {2021}
}
```



### License

MIT License

Copyright (c) 2020 Sark Xing

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
