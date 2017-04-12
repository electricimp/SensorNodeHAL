# Sensor Node Hardware Abstraction Layer

Use the SensorNode_003 table to access the hardware pins, i2c sensor addresses, i2c and uart bus objects.

## SensorNode_003

* LED_BLUE
* LED_GREEN
* SENSOR_I2C
* TEMP_HUMID_I2C_ADDR
* ACCEL_I2C_ADDR
* PRESSURE_I2C_ADDR
* RJ45_ENABLE_PIN
* ONEWIRE_BUS_UART
* RJ45_I2C
* RJ45_UART
* WAKE_PIN
* ACCEL_INT_PIN
* PRESSURE_INT_PIN
* TEMP_HUMID_INT_PIN
* NTC_ENABLE_PIN
* THERMISTER_PIN
* FTDI_UART

### Example:

```
SensorNode_003.SENSOR_I2C.configure(CLOCK_SPEED_400_KHZ);
tempHumid <- HTS221(SensorNode_003.SENSOR_I2C, SensorNode_003.TEMP_HUMID_I2C_ADDR);
```


## License

Sensor Node Hardware Abstraction Layer is licensed under the [MIT License](/LICENSE).