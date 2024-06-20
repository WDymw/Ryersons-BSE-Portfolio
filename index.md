| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Ryerson | Saint Andrews School (Delaware) | Aerospace | 10th grade



<!--Not completed-->

![Picture of myself](assets/Ryerson.png)

<!--Not completed--
# Final Milestone
**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone
<!--Not completed--
**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 
<!--Completed-->
# First Milestone

I chose the sound-reactive paper lantern to be my main project. This project functions on LED rings which are placed in the lanterns. The LED lights receive information from the microcontroller that was passed from the computer. They react to sound through a microphone on the computer, which is transcribed by the software. I planned to first assemble a prototype (Which is the first milestone). This prototype consists of simply a power supply, a switch, a microcontroller, and an LED ring. The power, when the switch is pressed, would pass onto the microcontroller and the LED ring at the same time, powering both. The commands would be sent from the software on the computer, which is received by the controller. The data is then transmitted through the data input wire to the LED ring, which controls the lighting pattern of the LED ring.
I have so far succeeded in applying the software, soldering three wires together, using a screw terminal, and connecting LEDs to the microcontroller.
One challenge faced was the complicated schematic, which I hope will be solved in the future by drawing a more detailed schematic map. Also, this project requires precise soldering in many spots, which I am excited to learn more about and do better on. 
My next step is to desolder my prototype and move on to create a schematic with 7-8 LED rings wired, and make all of them reactive to music. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/NpqBCa7kghs?si=nl133czFQXI5RgUp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


# Code
    
    void setup() {
      pinMode(ledPin, OUTPUT);
      pinMode(buttonPin, INPUT);
    
    void loop() {
      buttonState = digitalRead(buttonPin);
    
      if (buttonState == HIGH) {
        digitalWrite(ledPin, HIGH);
      } else {
        digitalWrite(ledPin, LOW);


# Bill of Materials
| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Arduino Board R3 | Provides a space and power converter for many inputs and outputs | $24.5 | [Link](https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/) |
| Adafruit ESP32 Feather V2 | Microcontroller of the main project | $19.95 | [Link](https://www.adafruit.com/product/5400) |
| Neo Pixel Ring | The output, the light | $7.5 | [Link](https://www.adafruit.com/product/1643) |
| Switch | Control the status of the lanterns | $2.95 | [Link](https://www.adafruit.com/product/3064) |
| Female DC Power Adapter | Adapt power from the ground power supply | $2 | [Link](https://www.adafruit.com/product/368) |
| Power Supply | Supply Power | $7.95 | [Link](https://www.adafruit.com/product/276) |
| Item Name | What the item is used for | $Price | [Link](https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/) |
| Item Name | What the item is used for | $Price | [Link](https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/) |
| Item Name | What the item is used for | $Price | [Link](https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/) |


# Starter Project
My starter project is the Arduino Board with specific modifications to enable it to receive information from a button and light up the LED. I chose to install a button as my input and use the LED light on the board as my output because I believe that a button is the simplest input, and light is the most direct way to see an output. I chose this project because I thought it would be beneficial to produce a project that involves coding and circuits.
The 5V of the battery passing on from the board, travels to a rail which is connected to one of the legs of the button. When the button is pressed, the current passes through the button and then onto another wire which is connected to the digital pin 2 on the Arduino board. By doing so, the board would notice that the button is pressed, and the light would be turned on.
Another set of wires are ground, which are not charged, and what they do is provide a reference for the board in terms of the voltage difference.
This was quite a challenging project since I began with no knowledge of circuits and soldering, both topics cost me hours and hours. I am satisfied with what I learned and I hope I would do even more. 
<iframe width="560" height="315" src="https://www.youtube.com/embed/1ndPM6ghYaU?si=MM73s4r1F4oPDMNJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
##Starter project schematic
![Schematic of the Starter project](assets/Untitled4_bb.png)
