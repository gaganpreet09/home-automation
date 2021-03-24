# Home automation
## Components Required

### ARDUINO UNO    
### HC 05  BLUETOOTH MODULE    
### RELAY BOARD    
### SMART PHONE OR TABLET    
### POWER SUPPLY  
### CONNECTING WIRES
### BREADBOARD (PROTOTYPING BOARD)
### APP FOR TRANSMITTING VOICE TO BLUETOOTH

# WORKING

### In this project, a simple Voice Activated Home Automation system is designed. Voice commands are used to control different appliances. We will now see the working of the project. All the connections are made as per the diagram below.
### After making the necessary connections, we have to switch on the power supply to the circuit. Now, we need to pair the Phone’s Bluetooth to the HC – 05 Bluetooth Module. Before that, we have to install the App mentioned above in the phone. 
### Next step is to connect the phone with the Bluetooth module. For this, choose the option “Connect Robot” and select the appropriate Bluetooth Device. If the devices aren’t paired earlier, we need to pair them now using the Pin of the HC – 05 Bluetooth Module.

### After successful connection, the devices are ready to transmit data. For that, press the press microphone icon on the app and start giving voice commands.
### NOTE: Make sure that the voice recognition feature is enabled on the phone (this is usually associated with Google app).
### For example, if we press the microphone icon and say “turn on light”, the app will recognise the command and the transfers it to the Bluetooth Module. Also, the command gets displayed on the screen for our reference.

### When the string “turn on light” is detected by the app, it will send the string as “*turn on light#”. So, the actual message received by the Bluetooth Module is in the format of “*Message#”. The reason for padding the ‘*’ and ‘#’ at the begging and end of the string is to identify the starting and ending of the message.
### We are able to delete the ‘#’ from the string but left out the ‘*’ in order to identify the starting of the string. The received message is compared with some predefined strings and if the message matches with any of them, then corresponding action like turning on or turning off the load happens.
### We have used the following commands: “turn on AC”, “turn off AC”, “turn on light”, “turn off light”, “turn on TV”, “turn off TV”, “turn on fan”, “turn off fan”, “turn on all” and “turn off all”.  


![20180627_000434-01](https://user-images.githubusercontent.com/70061105/107076607-a7919200-6811-11eb-9fda-270279f45a59.jpeg)
