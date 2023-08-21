# Car-Parking-Management-System
in this Project, we built a car management system using Java socket programming
and Arduino microcontroller programmed using a C/C++ like language specific for
the microcontroller and ultrasonic sensor

the connections look like this :
![Screenshot 2023-08-21 084225](https://github.com/Abdulelah-aljarboa/Car-Parking-Management-System/assets/105386716/6e11ee87-f0cf-488c-8d2f-215a30492375)



# Technologies 🧠
  we used the following for this project:
  - Java
  - Arduino board
  - Ultrasonic sensor
  
  
  # SetUp⚙️
  - Download the sensor file
  - Edit lines 5-8 with the following
  - SSID -->  your wifi name
  - Password --> the wifi password
  - port --> is set to 28002 you could change it if you want(change in the server also)
  - host --> the server IP address (the IP of the computer running the server)
  - upload it to your Arduino board and turn it on
  - go to the server and run it
  - if everything is working well the connection sequence will start which is the following
     1-light blinking blue -> looking for the HotSpot
     2-static green for 5 seconds -> WiFI connection established
     3-no light -> trying to connect to the server
     4-green light ->done with WiFI/Server connection sensor is working and active
     *whenever the connection is lost the sequence will repeat
  - 


