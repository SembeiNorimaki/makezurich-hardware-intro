# #MakeZurich hardware intro
Hello, this is some of the hardware available at [MakeZurich.ch](http://makezurich.ch/).

Found a bug or have a question? [Submit an issue](../../issues).

## Arduino Nano BLE Sense
The [Arduino Nano BLE Sense](https://store.arduino.cc/arduino-nano-33-ble-sense) is a microcontroller.

The Nano uses 3.3V logic, here is the pinout:

<img src="https://live.staticflickr.com/65535/49558575858_893cb7d59e_b.jpg" width="512" style="border-color: coral; border-width: thin;" />

### Getting started with the Nano
See https://www.arduino.cc/en/Guide/NANO33BLESense

### Measuring humidity and temperature with the Nano
The Arduino Nano BLE Sense has a humidity and temperature sensor, the ...

### Measuring barometric pressure with the Nano
The Arduino Nano BLE Sense has a barometric pressure sensor, the ...

### Measuring light intensity with the Nano
The Arduino Nano BLE Sense has a light intensity sensor, the ...

It can detect gestures, proximity, light color and light intensity.

### Measuring orientation in space of the Nano
The Arduino Nano BLE Sense has a 9-axis inertial measuring unit (IMU) built-in.

The [LSM9DS1](https://www.st.com/resource/en/datasheet/lsm9ds1.pdf) includes an accelerometer, a gyroscope and a magnetometer.

To use it, install the [ArduinoLSM9DS1 library](https://www.arduino.cc/en/Reference/ArduinoLSM9DS1) and check the examples.

### Measuring noise and recording audio with the Nano
The Arduino Nano BLE Sense has a built-in microphone, the ...

### Measuring air quality with the Sensirion ESS-C3 shield
The [Sensirion ESS-C3 shield](https://developer.sensirion.com/platforms/environmental-sensor-shield/) has environmental sensors to measure temperature, humidity, TVOC and CO2.

To connect the Sensirion shield to the Arduino Nano you need an adapter, e.g. the [NanUno v2](https://www.thingiverse.com/thing:4171213).

To use it, install the [Sensirion ESS library](https://github.com/Sensirion/arduino-ess) and check the examples.

### Sending data to TheThingsNetwork with the Murata LoRaWAN module

### Sending data from the Nano with Bluetooth Low Energy (BLE)

## Arduino Uno
The [Arduino Uno](https://store.arduino.cc/arduino-uno-rev3) is a microcontroller.

The Uno uses 5V logic, the pinout is printed right on the board:

<img src="https://store-cdn.arduino.cc/uni/catalog/product/cache/1/image/1040x660/604a3538c15e081937dbfbd20aa60aad/a/0/a000066_featured_3.jpg" width="512" />

### Getting started

### Measuring air quality with the Sensirion ESS-C3 shield
The [Sensirion ESS-C3 shield](https://developer.sensirion.com/platforms/environmental-sensor-shield/) has environmental sensors to measure temperature, humidity, TVOC and CO2.

To connect the Sensirion shield to the Arduino Nano you need an adapter, e.g. the [NanUno v2](https://www.thingiverse.com/thing:4171213).

To use it, install the [Sensirion ESS library](https://github.com/Sensirion/arduino-ess) and check the examples.

### Sending data to TheThingsNetwork with the Dragino LoRaWAN shield
Follow the steps in [this tutorial](http://www.tamberg.org/chopen/2018/LoRaWANIoTWorkshop.pdf) (PDF).
