# external requirements

- Adafruit BluefruitLE nRF51 version 1.9.5
- Adafruit GFX Library version : 1.4.11
- Adafruit SSD1306 version : 1.2.9
- HX711 Arduino Library Bogdan Necula version : 0.7.2


TODO


- add a reset mode (10" hang at 20%)
- add warmup mode
- add tut fo workout + avgload in timezone

- add a workout to workout comparison chart to see if performance is incresing or decreasing (time to rest = over training)




# BLE client

```
pip3 install Adafruit_BluefruitLE
```

needs Adafruit Python BluefruitLE : https://github.com/adafruit/Adafruit_Python_BluefruitLE

    python ./ble_client.py

will save incomming data into out.csv file


# References
- https://www.reddit.com/r/climbharder/comments/doqioq/isometryx_opensource_digital_hangboard/
- https://www.trainingbeta.com/the-simplest-finger-training-program/

