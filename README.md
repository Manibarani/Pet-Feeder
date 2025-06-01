PET FEEDER
           This project is a pet feeder that uses Internet of Things (IoT) technology and Google Assistant to help pet owners feed their furry friends remotely.
           The pet feeder can be controlled through a mobile application(Google Home) using Google Assistant.

SOFTWARE REQUIREMENTS
                     
            ->Arduino IDE: Used for programming the NodeMCU microcontroller to control the feeding schedule and portion control of the pet feeder.

            ->IFTTT (If This Then That): Integrated with the Smart Pet Feeder to enable automation and remote control.
              IFTTT allows users to create applets that trigger actions based on predefined conditions or events, enhancing the functionality of the pet feeder.

             ->Adafruit IO: Used as a cloud platform for data logging and communication between the Smart Pet Feeder and the mobile/web interface. 
               Adafruit IO provides an easy-to-use platform for managing and visualizing data from the pet feeder.

LIBRARIES TO BE INSTALLED

                             ->Adafruit MQTT
                             ->NTP Client
                             ->Wire
                             ->Liquid Crystral I2C

HARDWARE REQUIREMENTS

->LCD 16x2: A 16x2 LCD display is used to provide a visual interface for displaying information such as feeding schedules, Time of the day of the pet feeder.

->I2C: I2C (Inter-Integrated Circuit) protocol is utilized to interface the LCD with the NodeMCU microcontroller, enabling efficient communication between the two devices.

->NodeMCU: The NodeMCU microcontroller serves as the brain of the Smart Pet Feeder, controlling the feeding schedule, communication with other components.

->Servo Motor: A servo motor is employed to dispense the correct portion of food from the storage container into the pet's bowl. The motor's precise movement ensures accurate portion control by making causing a delay between opening and closing time.

->Breadboard: The breadboard provides a platform for easily connecting and prototyping the various electronic components of the Smart Pet Feeder, allowing for quick and convenient assembly and testing.

WORKING 

 Connect all the devices according to the circuit diagram

->create IFTTT and ardafruit account

->IFTT, for this tag,Create an applet and create a trigger(voice command) for functioning.

->For then tag, create a Feedname (onoff in my code), then data as 'ON' (in my code).

->create another applet for a timed feeding.

->GoogleHome,

->In this go to works with google add the IFTTT account and link it.

->Now open the mic and speak into the mic the feedname which you have entered in the IFTTT. 
  Make sure that you connect your laptop and NodeMCU in same wifi hotspot.
 
