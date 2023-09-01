# Alexa-Blinds-Project
An inexpensive device to open and close your blinds with an Alexa-enabled device

# Materials 
- D1 Mini Wifi Board
- DC Hobby Motor
- L298N Motor Controller
- 3D Printer
- 9V Battery

# Description
Utilizes a L298N Motor Controller and D1 Mini wifi card to control the speed and direction of the motor, which ultimately opens and closes the blinds. The D1 Mini is used as the main microcontroller of the project, which communicates to the motor controller when connected to wi-fi. To send the signal to the D1 mini when prompted by the Alexa, we utilize the SinricPro Alexa Skill, which allows us to specify what happens when we tell the Alexa to turn on and off the blinds. In code, using the L298N library, we can specify the opening/closing directions, and the required amount of time to fully open or close the blinds. The blinds wheel and enclosure for the device were created in Fusion 360, which were then 3D printed using the Cura Slicer. 
