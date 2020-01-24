# LoRa Weather Station

 

 Our goal is to build a collection of different measurement boxes for quantitative recording of meteorological data. For the transmission of the measured data we use a low-power wide-area network technology - [LoRaWAN](https://en.wikipedia.org/wiki/LoRa). It is based on spread spectrum modulation techniques derived from chirp spread spectrum (CSS) technology. 



|Measured Variable  | Sensor  |   
|---|---|
| Particulate Matter  |  [SDS011](https://ecksteinimg.de/Datasheet/SDS011%20laser%20PM2.5%20sensor%20specification-V1.3.pdf) |   |
|  Temperature, Humidity, Pressure, VOCs | [BME680](https://www.mouser.de/datasheet/2/783/BST-BME680-DS001-1509608.pdf)   |   
|  Carbon Dioxide | [SCD30](https://www.mouser.de/datasheet/2/682/Sensirion_CO2_Sensors_SCD30_Datasheet-1510853.pdf)  |   

In order to read the sensors it is necessary to choose a useful microprocessor development board. The microprocessor is a central processing unit on a single integrated circuit (IC), it accepts binary data as input (given through the sensor), processes it according to instructions stored in its memory and provides results (also in binary form) as output. We decided on the [LoPy4](https://pycom.io/product/lopy4/) from [Pycom](https://pycom.io/). The LoPy from Pycom is a great module that mates an ESP32 processor running Python with LoRa, WiFi and BLE radios. 
