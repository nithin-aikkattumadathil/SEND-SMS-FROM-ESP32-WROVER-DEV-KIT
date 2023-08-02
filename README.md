# SEND-SMS-FROM-ESP32-WROVER-DEV-KIT
* In this project I'm aiming at sending an SMS from ESP32 WROVER DEV KIT  to a specific mobile number mentioned in the code. The IDE I'm using is Arduino IDE . 
* first install latest version of arduino IDE
* paste the url inside additional code url ,through file  ->  preference  ->  additional code url  -> http://arduino.esp8266.com/stable/package_esp8266com_index.json,https://dl.espressif.com/dl/package_esp32_index.json
* in tools -> board -> board manager -> install esp32 by expressif systems
* in tools -> manage libraries -> install tinygsmclient.h
* connect the board 
* select the board as ESP32 WROVER DEV KIT
* give the correct COM port
* put the code
* verify
* upload
* once uploaded we can see the status indide serial monitor and we will receive sms in specified mobile number
