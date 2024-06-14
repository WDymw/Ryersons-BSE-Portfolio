| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Ryerson | Saint Andrews School(Delaware) | Aerospace | 10th grade



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

I chose the sound-reactive paper lantern to be my main project. This project functions on LED rings which would be placed in the lanterns. The LED lights would receive information from the microcontrollers that was passed from the computer. They react to sound through a microphone on the computer, which is transcribed by the software. I planned to first assemble a prototype (Which is the first milestone). This prototype consists of simply a power supply, a switch, a microcontroller, and an LED ring. The power, when the switch is pressed, would pass onto the microcontroller and the LED ring at the same time, powering both. The commands would be sent from the software on the computer, which is received by the controller. The data is then transmitted through the data input wire to the LED ring, which controls the lighting pattern of the LED ring.
I have so far succeeded in terms of applying the software, soldering three wires together, using a screw terminal, and connecting LEDs to the microcontroller.
One challenge I currently face is the complicated schematic, which I hope will be solved in the future by drawing a more detailed schematic map. Also, this project requires precise soldering in many spots. Given that I'm not skillful in soldering, it would be difficult for me to complete this project. 
The next part would be to desolder my prototype and move on to create a schematic with 7-8 LED rings wired. And make all of them reactive to music. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/NpqBCa7kghs?si=nl133czFQXI5RgUp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!--Not completed--
# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 
# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 
```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}
void loop() {
  // put your main code here, to run repeatedly:
}
```
# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 
| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
|Arduino Board R3 | Provides a space and power converted for many inputs and ouutputs| $24.5 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name| What the item is used for| $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)
To watch the BSE tutorial on how to create a portfolio, click here.

<!--Completed-->
# Starter Project
My starter project is the Arduino Board with specific modifications to enable it to receive information from this button and light up the LED. I chose to install a button as my input and use the LED light on the board as my output because I believe that a button is the simplest way for an input, and light is the most direct way to see an output. I chose this project because I thought it would be beneficial to produce a project that involves coding and circuits.
This board performs its functions through the electric circuit. The 5V of the battery passing on from the board, travels to a rail which is connected to one of the legs of the button. When the button is pressed, the current passes through the button and then onto another wire which is connected to the digital pin 2. By doing so, the board would notice that the button is pressed, and the light would be turned on.
The few wires here are ground wires, which are not charged, and what they do is provide a reference for the board in terms of the voltage difference.
This was quite a challenging project since I began with no knowledge of circuits and soldering, both topics cost me hours and hours. 
<iframe width="560" height="315" src="https://www.youtube.com/embed/1ndPM6ghYaU?si=MM73s4r1F4oPDMNJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
