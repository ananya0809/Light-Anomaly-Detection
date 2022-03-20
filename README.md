### Anomaly Detection for Ambient Light
This code is used to detect sudden changes in ambient lighting by using a light sensor connected to a microcontroller.

It sends an SMS using Twilio service to the registered mobile number when an anomaly is detected.

Anomaly detection is based on Z-score analysis, where we can set a desired ``` FRAME_SIZE ``` and the ``` MUL_FACTOR``` to alter the upper and lower threshold bounds for normal and anomalous readings.