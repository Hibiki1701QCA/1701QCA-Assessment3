# 1701QCA Final project journal: *Hibiki Oka (s5222030)*

<!--- As for other assessments, fill out the following journal sections with information relevant to your project. --->

<!--- Markdown reference: https://guides.github.com/features/mastering-markdown/ --->

## Related projects ##
<!--- Find about 6 related projects to the project you choose. A project might be related through  function, technology, materials, fabrication, concept, or code. Don't forget to place an image of the related project in the appropriate folder and insert the filename in the appropriate places below. Copy the markdown block of code below for each project you are showing. --->


### Related project 1 ###
*Name: micro:bit Smart Home (with BH1750, BME280, HC-SR501, SW-420 sensors and LCD 1602)*

![Image](Rel1.PNG)

*URL: https://www.youtube.com/watch?v=m64T7HHNOII*

This project relates through the concept of building a smart home through a microbit. I found this project after starting mine as I didn’t have enough related projects and I found that this was really similar to the functions I’ve included for mine such as the automatic fan and light. *.

### Related project 2 ###
*Name: Smarthon Smart House Kit for micro:bit (model 2)*

![Image](Rel2.PNG)

*URL: https://www.youtube.com/watch?v=us7mOg1nLG8*

This project relates through the concept of building a smart home through a microbit. This was also found after I began and I found that the creator also has a similar function with the fan however, can be manually turned on through the microbit buttons. *.

### Related project 3 ###
*Name: micro:bit SOKIT : Making a smart house.*

![Image](Rel3.PNG)

*URL: https://it-it.facebook.com/thinksokit/videos/vb.1651182875206612/319983735368250/?type=2&theater*


This project relates through the concept of a smart home, with the functions of turning on light and changing colour.*.

### Related project 4 ###
*Name: BBC micro:bit - Door Alarm system with smart Light*

![Image](Rel4.PNG)

*URL: https://www.youtube.com/watch?v=ZOLvpmQ5HOs*


This project relates through the concept, with the functions of a smart light and uses the buzzer to create a door alarm system.*.

### Related project 5 ###
*Name: Micro:bit Smart Home - light, fan and alarm system.*

![Image](Rel5.PNG)

*URL: https://www.hackster.io/73125/micro-bit-smart-home-light-fan-and-alarm-system-bd1e6f*


This project is related to mine because it includes an automatic light and fan.*.

### Related project 6 ###
*Microbit Smart Home Kit: Smart Home [BM]*

![Image](Rel6.PNG)

*URL:https://www.youtube.com/watch?v=O-ALLqKYfRo&t=83s*


This project is related to mine because the material they have used to make this project is cardboard which is the material I have mainly used.

## Other research ##
<!--- Include here any other relevant research you have done. This might include identifying readings, tutorials, videos, technical documents, or other resources that have been helpful. For each particular source, add a comment or two about why it is relevant or what you have taken from it. You should include a reference or link to each of these resources. --->

*1. Micro:bit - Heat activated Fan*

*This was used in the previous project of the temperature gauge, and helped me in the process of making the functions of the ceiling fan.*

*2. Micro:bit Pins*

*This helped me understand more about the pins as I was having trouble with space which can be seen in the fifth design process discussion.*

*3. Blinking LED*

*The coding helped me in making the settings of the dollroom.*

### *Brief resource name/description* ###

*1. https://www.youtube.com/watch?v=iilfeimMDjM*

*2. https://makecode.microbit.org/device/pins*

*3. https://learn.adafruit.com/micro-bit-lesson-2-controlling-leds-on-breadboard/blinking-an-led*


## Conceptual development ##

### Design intent ###
<!--- Include your design intent here. It should be about a 10 word phrase/sentence. --->

My design intent is to create a toy that is interactive for young kids to play with. 

### Design ideation ###

### Design concept 1 ###

*The first concept was based off of the game Animal Crossing. The recent release of Animal Crossing New Horizons is where the inspiration came from however, I have based it off a feature in the previous game of a train station in Animal Crossing New Leaf. Some of the functions in this concept that I was going to implement are an object that represents the train in the game would be placed on the track which the lights would flicker, the bars would go down and it would make a beeping sound just like in the game.*

![Image](Concept1.PNG)

### Design concept 2 ###
*The second concept would be a flower lamp that opens up when dark which lights up in the middle and closes when it is bright.*

![Image](Concept2.PNG)

### Final design concept ###
<!--- This should be a description of your concept including its context, motivation, or other relevant information you used to decide on this concept. --->
    

*The third and chosen concept would be a room which the light would turn on when its dark, the fan would turn on when the temperature is high and different songs would be played with one button.*
*The main materials to be used would be cardboard for the structure of the room and furniture and paper for covering the cardboard.*

![Image](FinalConcept.PNG)




### Interaction flowchart ###
<!--- Include an interaction flowchart of the interaction process in your project. Make sure you think about all the stages of interaction step-by-step. Also make sure that you consider actions a user might take that aren't what you intend in an ideal use case. Insert an image of it below. It might just be a photo of a hand-drawn sketch, not a carefully drawn digital diagram. It just needs to be legible. --->

![Image](Flow.jpg)
![Image](floww.jpg)

## Process documentation ##
<!--- In this section, include text and images (and potentially links to video) that represent the development of your project including sources you've found (URLs and written references), choices you've made, sketches you've done, iterations completed, materials you've investigated, and code samples. Use the markdown reference for help in formatting the material.

This should have quite a lot of information! It will likely include most of the process documentation from assessment 2 which can be copied and pasted here.

Use subheadings to structure this information. See https://guides.github.com/features/mastering-markdown/ for details of how to insert subheadings.

There will likely by a dozen or so images of the project under construction. The images should help explain why you've made the choices you've made as well as what you have done. --->

## Design process discussion ##
*I worked on getting the fan blade to work with the piezo element buzzer making sounds. I have used similar coding to the previous project I have done with the temperature gauge and included the coding for when the external button is pressed, sounds would be made through the buzzer with the help of experiment 6 from the Inventor’s Kit Tutorial Book.*

![Image](FirstPic.PNG)

## Design process discussion ##
*The digital write pin was set to P2 instead of P4 for the fan as this was taken after testing the LED lights.*

![Image](TempCode.PNG)

## Design process discussion ##
*Before, I had a default tune that can be found in the “play melody” block however, I played around with the tones to create a tune from a film by Ghibli Studios.*

![Image](MusicCode.PNG)

## Design process discussion ##
*I also started building the room with cardboard, paper, and the scraps of material that I had. *

![Image](Prototype.jpg)

## Design process discussion ##
*Next I worked on including the automatic light. I was having some issues with space as I had no more of the large pins left. Pin 0 was connected to the buzzer, pin 1 was connected to the external button for the buzzer and pin 2 was connected to the fan. I changed the pin that was connected to the button to pin 5 as I found that the pin is a GPIO shared with button A, which opened up space for pin 1. I still needed one more pin for the LED, as I used pin 1 to place the phototransistor.*

![Image](21-April.jpg)
![Image](LightCode.PNG)

## Design process discussion ##
*I was using the microbit LED screen to show icons so I could see if the phototransistor was working. I removed the function of this as I found that some of the pins had the same functions as the large pins with the GPIO and ADC but can only be used when the LED is not on. I switched the pin for the fan with the LED so that it is in pin 2 and placed the wire connected to the fan to pin 4 as it wouldn’t work oppositely. *

![Image](ThirdPic.PNG)

*In the final development of the project, I have restarted the room to be a bit bigger as there was not enough space to place the mounting plate. I have also slightly changed the design of the room from the sketch I had drawn and built in the prototype as I was not very satisfied with the design and was not sure how to implement the buttons.*

*In the protoype, a lot of the cardboard could be seen which was not really what I wanted in the final result. So I used white sheets of paper to cover the majority of the material, with printed out wood for the flooring. More furnature has been added such as a seat which was just made out of origami paper and a book shelf which is cardboarded covered in paper. I also included a flag garland just to make it look more interesting.*

![Image](process1.jpg)

*In the next picture, it can be seen that I have removed the furnature, added a platform for the room and cut out the area where the shelf was. I was having trouble figuring out how I should implement the buttons as the wires on the breadboard would get in the way. I thought that maybe if I indented the wall and place the shelf in between the walls, the problem would be less annoying. I also redid the border of the window as I thought they were too wide.*

![Image](process2.jpg)

I added the furniture back inside the room with new props such as the pillow, the shelf I referred and some small tiny props on the seat which are moved later. The microbit has also been added behind the right wall. The next two pictures show the light sensor working.

![Image](process3.jpg)

![Image](process4.jpg)

I added a roof on the room which would cover the motor of the fan.

![Image](process5.jpg)

Finally I added a wall behind the shelf and put the buttons that will change the setting on it.

![Image](final.jpg)

## Final code ##

<!--- Include here screenshots of the final code you used in the project if it is done with block coding. If you have used javascript, micropython, C, or other code, include it as text formatted as code using a series of three backticks ` before and after the code block. See https://guides.github.com/features/mastering-markdown/ for more information about that formatting. --->

![Image](finalcode.PNG)

## Design process discussion ##
<!--- Discuss your process used in this project, particularly with reference to aspects of the Double Diamond design methodology or other relevant design process. --->

Refering to the Double Diamond design methodology, I have discovered that the younger generation seem to be more attached with screens. I have a younger sister who spends her time playing video games or watching Youtube a lot. At least twice a day, I would find her eyes staring at the screen and would not really do anything unless told to. When she is told to do something else other than that, she says there is nothing to do.

Being in the define part of the diamond, boredom seems to be an issue with many children (at least for my sister) so they turn to staring at the screen a lot which can be unhealthy for your eyes. So I wanted to create something that will help expand their list of things they can do to resolve boredom, which is the doll room.

Moving to the second diamond, I came up with an idea of an interactive doll room which can light up when dark, activate the fan when the temperature is high and make sounds. 

The feedback that I recieved in the prototype was to make it more interactive options beyond the automatic on/off mechanism of the features. So I return to the developing stage and was given the idea that I could make different settings depending on the buttons. 


## Reflection ##

<!--- Describe the parts of your project you felt were most successful and the parts that could have done with improvement, whether in terms of outcome, process, or understanding.

What techniques, approaches, skills, or information did you find useful from other sources (such as the related projects you identified earlier)?

The Micro:bit Pins has given me information and better understanding of the pins and what their capabilities are.

What parts of your project do you feel are novel. This is IMPORTANT to help justify a key component of the assessment rubric.

I think it is unique in creating different settings for the dollroom. I have not seen or heard this kind of toy so I feel that this part of the project are novel.

What might be an interesting extension of this project? In what other contexts might this project be used? --->

I think it would be interesting if I could make multiple rooms so it can be a full doll house with many more features that would make it more entertaining. I also think it could have more settings.

