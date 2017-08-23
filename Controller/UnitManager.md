##### UnitManager
- *Description*:
    + Handle temperature, humidity, heat index, dewpoint
- *Contidion*:
	+ calibrated (Get from storate, +- into origin value)
	- C/F degree (Get from storage)
- *Exception*:
	- Temp/humidity is NULL
	- Temp/humidity is Nan

- *Call when ble receive new value, update temperatureOrigin/humidityOrigin*
    - setTemperature()
    - setHimidity()

- *Call to display*
    - getTemperature(usedCalibrated(boolean), F/C)
    - getHumididty(usedCalibrated(boolean), F/C)
    - getDewPoint(usedCalibrated(boolean), F/C)
    - getHeatIndex(usedCalibrated(boolean), F/C)