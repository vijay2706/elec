# elec
projects
## 1. ARDUINO SOLAR TRACKER
In modern olar tracking systems,the solar panels are fixed on a structure that moves according to the position of sun.
Materials required:  Arduino UNO, Servo Motor, LDRs (Light Sensors) , Resistors.
        LDRs are used as main light sensors. Two servo motors are fixed to the solar panel.The program for arduino is uploaded to the microcontroller.
        LDRs sense the amount of sunlight falling on them.Four LDRs are divided into top,bottom,left and right.
        For east-west tracking, the anaog values from two top LDRs and two bottom LDRs are coompared and if the top set of LDRs receive more light, the vertical servo will move in that direction.
        For angular deflection of the solar panel, the analog values from two left LDRs and two right LDRs are compared. If the left set of LDRs receive more light than the right set, the horizontal servo will move in that direction.
     
     This is really very useful, by this setup we can extract maximum sunlight and convert it to useful power. So we can use the renewable source of the energy for the required power and for our daily usage.
