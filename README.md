# ELEC CLUB
# PROJECTS

## 1. ARDUINO SOLAR TRACKER
https://www.electronicshub.org/arduino-solar-tracker/

In modern solar tracking systems,the solar panels are fixed on a structure that moves according to the position of sun.
Materials required:  Arduino UNO, Servo Motor, LDRs (Light Sensors) , Resistors.
        LDRs are used as main light sensors. Two servo motors are fixed to the solar panel.The program for arduino is uploaded to the microcontroller.
        LDRs sense the amount of sunlight falling on them.Four LDRs are divided into top,bottom,left and right.
        For east-west tracking, the anaog values from two top LDRs and two bottom LDRs are coompared and if the top set of LDRs receive more light, the vertical servo will move in that direction.
        For angular deflection of the solar panel, the analog values from two left LDRs and two right LDRs are compared. If the left set of LDRs receive more light than the right set, the horizontal servo will move in that direction.
     
     This is really very useful, by this setup we can extract maximum sunlight and convert it to useful power. So we can use the renewable source of the energy for the required power and for our daily usage.



## 2. SNAKE ROBOT USING ARDUINO
https://www.youtube.com/watch?v=abMJAapfmeo

This snake robot is made using arduino, servo motors, sensors and PCB. 
The design of the snake is made by 3d printing and servo motors are connected such that some moves longitudinally and vertically.
Small camera is attached to this bot, which can travel anywhere. This can be controlled by an android app using bluetooth. And the suitable code is written

       Humans and other robots cannot inspect all tight places like narrow industrial pipes, drains, walls and floorings. This smart snake bot can crawl these narrow places with camera and give us information. This is very useful in almost all places mainly defence, medical, etc..



## 3. IoT BASED SMART DUSTBIN
https://www.youtube.com/watch?v=LKnq1SnlGaM&t=262s

![project 3](https://user-images.githubusercontent.com/62617598/80908224-d5562180-8d3b-11ea-96b5-0f02c3bf9688.gif)

This project is to monitor whether the Dustbin is full or not and if full then notify the owner through a notification on their phone and to open or close automatically.
Software requirements: Blynk app, Arduino IDE
Hardware requirements: Arduino nano, Wifi module, Ultrasonic Sensor, Servo motor, IR sensor module.
Connecting all components to the arduino board with wires. And uploading suitable code to Arduino Uno. And configuring the Blynk app and connect to the Wifi and press play button.

     This project is very useful to keep the places clean. It helps the owner by triggering when the bin is full.


## 4. Generate Electricity by Walking Power Generator Floor Tiles Project
https://www.youtube.com/watch?v=xliPAZJAVcY

This project starts with the designing. Designing can be done in many softwares such as solid works, autocad etc..and then fabricating the system.
Materials required: Gears, shaft, generator motor, racks, springs.
It uses the motion of the footstep to generate power with the help of metallic racks. These are mounted on the upper panel and these are pressed against the optimised gearing. 
The gear is used transfer the power to the generator motors. And it has springs which helps the platform to get back to original position.

     This projecct is very useful at almost all places. We can produce power automatically by just walking. We can actually save many resources by using this project. 
 
 
 ## 5. THIRD EYE FOR BLIND
 https://create.arduino.cc/projecthub/muhammedazhar/third-eye-for-the-blind-8c246d
 
 This is very simple project but it is very much useful to blind people. This is made with five ultrasonic sensors, blind people can detect objets in  five dimensional view around them. These five modules are connectec to differen parts of body. Among them, two for both shoulders, another two for both knees and one for the hand. When the sensor detects obstacle the device will notify th user through vibrations and sound beeps. The intensity of beeeping increases with decrease in distance and this is a fully automated device.
 
 
 ## 6. ARDUINO BASED SMARTPHONE CHARGING CONTROLLER
 https://www.electronicshub.org/arduino-based-smartphone-charging-controller/
 
   Components Required: Arduino UNO, LCD display, Rotary encoder, 5V relay module, transistor, Breadboard, charging adapter.
    Connect the IN1 Pin of the Relay Module to Pin 12 of Arduino,the rotary encoder, its CLK, DT and SW pins are connected to Pins 10, 11 and 2 of Arduino UNO, the LCD, Pins 8 through 3 of Arduino are connected to RS, E, D4 – D7 of the LCD.
    After making the necessary connections as per the circuit diagram, upload the code to Arduino and turn on the power supply.You will get Hours (HH), Minutes (MM), Seconds (SS) on the 16×2 LCD Display. Set the desired time.and after that countdown reaches "0", the rely is turned off(power to adapter is off).
   
       Most of us forget that we put our mobile to charge and we don't remove it even after battery full. This effects the lifetime of the battery. In this case you can plug in your phone to the charger, set the time for which your phone gets charged and forget as the project will automatically disconnect power to the charger. 
 
 
 ## 7. METAL DETECTOR CIRCUIT
   Components Required: TDA0161 Proximity Detector IC,Capacitors, Resistors, Potentiometer, NPN Transistor, Buzzer, LED.
 The LC Circuit, which consists of L1 (coil) and C1, is the main metal detector part of the circuit. With the help of this LC Circuit, which is also called as Tank Circuit or Tuned Circuit, the TDA0161 IC acts as an oscillator and oscillates at a particular frequency.
 When the LC circuit detects any resonating frequency from any metal which is near to it, electric field will be created which will lead to induces current in the coil and changes in the signal flow through the coil.When the metal is detected, the LC circuit will have changed signal.
 The changed signal is given to the proximity detector (TDA 0161), which will detect the change in the signal and react accordingly. The output of the proximity sensor will less than 1mA when there is no metal detected and it will be around 10mA (usually greater than 8mA) when coil is near to the metal.
 When the output pin is high, the resistor will provide positive voltage to transistor. Transistor will be turned on and LED will glow (not shown in the circuit) and buzzer will be activated.

  ## 8. LINE FOLLOWER ROBOT
  https://www.electronicshub.org/arduino-line-follower-robot/
  
  Components Required: Arduino UNO,L293D Motor Driver IC, Geared Motors, Robot Chassis, IR Sensor Module, Power supply.
  The IR sensors detect the black line, which consists of IR LED and Photodiode. They are placed in a reflective way i.e. side – by – side so that whenever they come in to proximity of a reflective surface, the light emitted by IR LED will be detected by Photo diode.
   As the reflectance of the light coloured surface is high, the infrared light emitted by IR LED will be maximum reflected and will be detected by the Photodiode.
   In case of black surface, which has a low reflectance, the light gets completely absorbed by the black surface and doesn’t reach the photodiode.
 The two IR Sensors are placed on the either side of the black line on the floor. In order to turn right, the motor on the right side of the robot is slowed down using PWM, while the motor on the left side is run at normal speed and vice versa.


      These are used for automation process in industries, military applications and consumer applications. They work as automatic guided vehicles.
  

## 9. FARADAY'S GUITAR
https://www.electronicsforu.com/electronics-projects/hardware-diy/faradays-guitar

   Here is an electronic project that demonstrates Faraday’s law of electromagnetic induction and gives musical output. The law talks about electromagnetic induction and production of electromotive force (EMF) across a conductor when it is exposed to a varying magnetic field.
 The circuit is built around transistors BC549 (T1 and T2), low-power audio amplifier LM386 (IC1), a speaker (LS1) and a few other components. The circuit is powered by 12V battery. An on/off toggle switch (S1) is used to switch on the circuit.
 
 
 ## 10. IoT BASED ACCIDENT PREVENTION AND TRACKING
 http://www.ijircce.com/upload/2015/april/101_45_AN.pdf
 
 Components Required: LCD Display, Drowse sensors(IR sensors), LM358 Comparator, NXP RD25 (Microcontroller), Buzzer, Analog to Digital Converter, 3-axis accelerometer, GSM & GPRS Module, Power supply.
 This project involves measurement of eye blink using IR sensor and head movement using accelerometer. The IRtransmitter is used to transmit the infrared rays in our eye. 
 The IR receiver is used to receive the reflected infrared rays of eye. If the eye is closed then the output of IR receiver would be high ,otherwise the IR receiver output is low. 
 To know whether the eye is in closing or opening position. The output is provided to a logic circuit for alarm indication and status will displayed on LCD display. 
 Accelerometer is placed on driver fore-head it measures tilt angle of the drivers in vertical either forward or backward direction and left or right direction from the driver knee. 
 If tilting angle exceeds certain threshold range, This output is give to logic circuit to indicate the alarm and status is displayed on LCD.
 The subject (night drivers) drowsiness can be effectively measured based on eye blink monitoring system.If drowsiness is detected then automatic responses from designed embedded system is possible such as alarm and reducing the speed of vehicle.
 The GSM module involved in the designed system is used to effectively track the location of the vehicle. The location of vehicle and nearby emergency service facilities are effectively displayed on the portable android devices of host device and embedded device through Google Maps.
 
  ## 11. AUTOMATED SOIL TESTING DEVICE
  http://www.irdindia.in/journal_itsi/pdf/vol1_iss5/22.pdf
  
   Components Required: Microcontroller, Liquid Crystal Display, ADC, Signal Conditioning, Sensor, Wireless Trans-receiver, I/O Interface.
   Whenever a farmer wants to analyze the soil fertility, he needs to take the soil sample of about 150g and 60ml of water should be added to the soil sample, and allow the sample to settle down. The sensor will be placed in the sample. Here copper electrodes are used as sensor which measures the ionic particles present in the soil and converts it in to electrical signal. The electrical signal is amplified using signal conditioning and this amplified signal is sent to microcontroller in the form of digital signal from ADC. The microcontroller plays a key role in processing data received from the sensor, where it compares the data already pre-stored with the sensor output signal. The microcontroller after comparison gives the output and the values are displayed on the LCD display. The output not only provides the information on fertility present in the soil but also suggests crops to be grown on that soil. The wireless trans-receiver transmits the data to a remote location or designated authority in the agriculture department for further analysis & suggestions.
   
    This is very useful for farmers to check the fertility of soil and decide what crops can be grown.
 
 ## 12. MUSIC REACTIVE LED STRIP
 https://www.hackster.io/buzzandy/music-reactive-led-strip-5645ed
 
 Components Required:Arduino NANO, PCB Board,9v Battery,Heat Shrink Tube,LED strip,Sound Sensor,IRFZ44N MOSFET,BC547 Transistor.
 The microcontroller gives a signal to the connected Transistor’s Base and it drives an N-Channel MOSFET. And this MOSFET drives the higher loads like LED strips. The Audio sensor’s out pin gives a signal. Then it is taken through Arduino. If the signal is in a certain limit then only the led strip will run.If the Condenser mic didn’t get a signal then the sensor module doesn’t give output. So, in this case, the LED strip will not run. This process repeats over and over.
 
 ## 13. RFID DOOR ACCESS CONTROL SYSTEM USING 8051
 https://www.electronicshub.org/rfid-security-access-control-system/
 
  A RFID based Door Lock or Access Control System is based on some simple concepts. We store a set of RFID card data in our system. When the person with the right RFID card (compatible to data preloaded in our program/system) come and swipes his RFID tag, access will be granted. When the person with the wrong RFID card (whose data is not loaded in our system) swipes his RFID tag, access will be denied. 
 The unique ID code in the RFID card is read by the circuit and displayed on the 16×2 LCD display. Tx pin of the RFID module is connected to Port 3.5 of the microcontroller. The microcontroller receives data from the RFID module through this channel. 
  
  ## 14. AUTOMATIC ROOM LIGHT CONTROLLER WITH VISITOR CONTROL
  https://www.projectsof8051.com/automatic-room-light-controller-with-visitor-counter/
  
   Wastage of electricity is one of the main problems which we are facing nowadays. In our home, school, colleges or industry we see that fan/lights are kept on even if there is nobody in the room or area/passage. To avoid all such situations we have designed this project called “Automatic room light controller with visitor counter”. This project has two modules, the first one is known as “Digital Visitor counter” and the second module is known as “Automatic room light controller”. The main concept behind this project is known as “Visitor counter” which measures the number of persons entering any room like seminar hall, conference room, classroom. This function is implemented using a pair of Infrared sensors. LCD display placed outside the room displays this value of person count. This person count will be incremented if somebody enters the room and at that time lights are turned on. And in a reverse way, person count will be decremented if somebody leaves the room. When the number of persons inside the room is zero, lights inside the room are turned off using a relay interface.
  
  ## 15. FINGERPRINT BASED BANK LOCKER SYSTEM
  https://www.youtube.com/watch?v=lFSJyh6-NrM
  
  The present scenario to operate a bank locker is with locks which are having keys. By this we can’t say that we are going to provide good security to our lockers. To provide perfect security and to make our work easier, we are taking the help of two different technologies viz. EMBEDDED SYSTEMS and BIOMETRICS. Firstly discussing about Biometrics we are concentrating on Fingerprint scanning. For this, we are using FIM 3030N high voltage module as a scanner. This module has in-built ROM, DSP and RAM. In this, we can store the fingerprints of up to 100 users. This module can operate in 2 modes i.e., Master mode and User mode. We will be using Master mode to register the fingerprints which will be stored in the ROM present on the scanner with a unique id. The fingerprint module will be interfaced with the microcontroller through serial interface. The persons who can access bank locker, first need to enroll in the biometric scanner. But everyone can’t enroll in the bank locker, because it has unique password for enrolling. Bank employees only know the password. If password is wrong we cannot enroll in the scanner. This system allows persons who are enrolled. If they didn’t enroll it alerts through message on 16X2 LCD. If the scanned image matches the stored image, the person is allowed to enter into the locker room. The main door of the locker room will be opened by rotating the motor fixed to it. The door closes automatically after a small delay. If it is not matched, indication is given to alert the buzzer. This project uses regulated 5V, 500mA power supply. 7805 three terminal voltage regulator is used for voltage regulation. Bridge type full wave rectifier is used to rectify the ac output of secondary of 230/12V step down transformer. 
   
  
