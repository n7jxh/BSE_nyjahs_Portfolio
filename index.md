# Ball-Tracking Robot
  Many times when I walked into the Makerspace where we hold robotics practice, I was greeted by the sight of my team captain pulling his hair out while trying to understand image detection. So I thought why not take a stab at it with a robot that also uses image detection, but this time tries to track it as it moves. How hard could it be, right?

| **Name** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Nyjáh H. | Poly Prep Country Day School | Chemical Engineering | Incoming Senior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

# First Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/CaCazFBhYKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation about the different components of your project and how they will all integrate together
- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones
- What your plan is to complete your project

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```python
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

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Raspberry Pi 4 Starter Kit | A kit that contains helpful tools needed to use the Raspberry Pi, the 'computer' that runs the code for the robot.| $99.95 | <a href="https://www.canakit.com/raspberry-pi-4-starter-kit.html"> Canakit </a> |
| Robot Smart Car Chassis Kit | Acts as the base for the robot and includes 2 motors and 2 wheels.| $19.95 | <a href="https://www.amazon.com/perseids-Chassis-Encoder-Wheels-Battery/dp/B07DNYQ3PX?th=1"> Amazon </a> |
| Dupont Wires | Used to make connections between the Raspberry Pi and the motor driver, breadboard, and ultrasonic sensors. | $6.98| <a href="https://www.amazon.com/Elegoo-EL-CP-004-Multicolored-Breadboard-arduino/dp/B01EV70C78/ref=sr_1_1_sspa?crid=30HUPDYRPWQHC&keywords=elegoo+dupont+wire&qid=1689857701&s=industrial&sprefix=elegoo+dupont+wire%2Cindustrial%2C71&sr=1-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"> Amazon </a> |
| Soldering Kit | Used to lengthen the wires from the battery pack. | $17.99 | <a href="https://www.amazon.com/Soldering-Iron-Kit-Temperature-Desoldering/dp/B07S61WT16/ref=sr_1_6?crid=3PT39V64H24MG&keywords=soldering+kit&qid=1689858115&s=industrial&sprefix=soldering+kit%2Cindustrial%2C89&sr=1-6"> Amazon </a> |
| Mini Solderless Breadboard | To allow for more space for the wires to power the system. | $7.45 for 3 | <a href="https://www.amazon.com/HiLetgo-Solderless-Breadboard-Circuit-Prototyping/dp/B00LSG5BJK/ref=sr_1_6?crid=1MFE7HDZU058H&keywords=solderless+breadboard&qid=1689858234&s=industrial&sprefix=solderless+breadboard%2Cindustrial%2C76&sr=1-6"> Amazon </a> |
| Ultrasonic Sensors | Used to sense the ball and calculate the distance to it. | $8.99 | <a href="https://www.amazon.com/ELEGOO-HC-SR04-Ultrasonic-Distance-MEGA2560/dp/B01COSN7O6/ref=sr_1_1_sspa?crid=1E3L0NTD1MSQB&keywords=ultrasonic+sensors&qid=1689859122&s=industrial&sprefix=ultrasonic+sensors%2Cindustrial%2C83&sr=1-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"> Amazon </a> |
| Arducam | The camera for the Raspberry Pi, used to 'see' the ball. | $9.99 | <a href="https://www.amazon.com/Arducam-Megapixels-Sensor-OV5647-Raspberry/dp/B012V1HEP4/ref=sr_1_1_sspa?keywords=raspberry+pi+camera&qid=1689946690&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"> Amazon </a> |

