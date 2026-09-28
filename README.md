# Python I2C Driver for Sensirion SPS30

This repository contains the Python driver to communicate with a Sensirion SPS30 sensor over I2C.

<img src="https://raw.githubusercontent.com/Sensirion/python-i2c-sps30/master/images/product-image-sps30.png"
    width="300px" alt="SPS30 picture">


Click [here](https://sensirion.com/products/catalog/SPS30) to learn more about the Sensirion SPS30 sensor.


Not all sensors of this driver family support all measurements.
In case a measurement is not supported by all sensors, the products that
support it are listed in the API description.



The default I²C address of [SPS30](https://sensirion.com/products/catalog/SPS30) is **0x69**.



## Connect the sensor

You can connect your sensor over a [SEK-SensorBridge](https://developer.sensirion.com/product-support/sek-sensorbridge/).
For special setups you find the sensor pinout in the section below.

<details><summary>Sensor pinout</summary>
<p>
<img src="https://raw.githubusercontent.com/Sensirion/python-i2c-sps30/master/images/product-pinout-sps30.jpg"
     width="300px" alt="sensor wiring picture">

| *Pin* | *Cable Color* | *Name* | *Description*  | *Comments* |
|-------|---------------|:------:|----------------|------------|
| 1 | red | VDD | Supply Voltage | 5V
| 2 | green | SDA | I2C: Serial data input / output |
| 3 | yellow | SCL | I2C: Serial clock input |
| 4 | blue | SEL | Interface select | Pull to GND to select I2C
| 5 | black | GND | Ground |


</p>
</details>


## Documentation & Quickstart

See the [documentation page](https://sensirion.github.io/python-i2c-sps30) for an API description and a
[quickstart](https://sensirion.github.io/python-i2c-sps30/quickstart.html) example.


## Contributing

In case you want to contribute to this project, please read the [contribution guidelines]((https://sensirion.github.io/python-i2c-sps30/contributing.html)).

## License

See [LICENSE](LICENSE).