**Brenton Larsen - https://hiphop-operation.github.io/Des222ProcessJournal/**
# Process journal
# Week one
**23/8/24**

Week one is the beginning of my brainstorming sessions as well as starting to learn how to use the micro-bit to its fullest potential.

immediately i am thinking of creating a website or app that responds to the weather and alerts the user of certain conditions. I want to do this because i think its something everyone can benefit from and is easily accessibly through mobile phones and computers.

Another idea could be to use the acceloromator in the micro-bit to sense the movement on the back of a basketball hoop backboard to alert the user of activity in the area. this could be like a signal to say that people are playing nearby. I could also encorporate the microphone on the micro-bit to listen in and use the speaker to play an alert tone.  

I started by working through the modules for knowledge and inspiration.
<br>


**Meat Queen:**
i found the MeatQueen project to be particularly interesting especially the interaction itself. the connection between user and artwork creates an exciting and immersive experience and is something im very interested in exploring. 

![MeatQueen](./Images/MeatQueen.png)



**Responsive Roulette:**
Playing around with the Responsive roulette page found in the modules was a creative way to get me thinking about the possibilites with this project. As well as thinking about the indivuidal components that will come together in my project.
![ResponsiveRoulette](./Images/ResponsiveRoulette.png) 


**Micro-Bit MakeCode:**
By experimenting with the micro-bit by following some of the introductory tutorials found on the micro-bit makecode editor. I was able to creating an acceloromator that would light up the LEDs if it was tilted to the right.

I see alot of potential with this design already. Such as a simple pedometor that can be attached to the ankle and counts each shake it feels. or to be placed inside a basketball to also count the amount of bounces. 
![AccelCode](./Images/AccelCode.png)

Though once i created this i noticed that when i sat it down and left it on it would feel the vibrations though the floor and start to flicker when it sensed movement. This video shows how it flashing while i walk in place. 
<video width="320" height="240" controls>
  <source src="./Images/Motion.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

I have found this particularly useful while im at my desk with headphones on i can tell when someone is opening the door or walking through the house. (it even works for the big dog) It stops my roommates from sneaking up behind me and scaring me.

I just found this intersting and kind of enjoy the interaction and how seemless it is. Im not sure if i can work further with this but i though it was worth mentioning.

# Week 2
**14/9/24**

In week 2 i began exploring more options for my device such as wearable devices and data responsive art. 


**albedo of clouds:**
The data responsive art made me think back to the albedo of clouds experiment that we read about earlier in the course in the book by Randerson et al 2015 (https://learn.usc.edu.au/courses/27670/files/1795139?wrap=1#) where government astronomers from australia "Robert Ellery and P. Baracchi" attempted to photograph the same cloud at the same time from two different locations. The melbourne observatory and the roof of victorias parliment house.
 
This made me think i could create something that is data driven and relates to cloud albedo levels in specific areas.

maybe i could try recreate the 1950s experiment of trying to photograph the same cloud from different perspectives at the same time and create a platform for posting and collaborating.

**wearable techonology:**
Looking at the devices shared in the modules such as the celestial sensing jumpsuit (https://www.theverge.com/2018/4/14/17233430/wearable-media-fashion-tech-nyc-ceres-jumpsuit-interactive) and learning about the light up back-pack straps that respond to sound to warn deaf people of potential hazards made me think of potential wearable devices i could create.
![JumpSuit](./Images/JumpSuit.png)

I could create something that it worn on the wrist in a game of basketball using the micro bit that can use the acceloromotor to retrieve the angles of someones arm so they can compare how their movement might change during practise. 

A device for pets to be worn around the collar that when the device reaches a certain decible level a sound will play to discourage them. This could useful to prevent loud animals becoming disruptive. 

# Week 3
**21/9/24**

Working through the modules i added the device orientation and media capture apis to the weather api web page that we created earlier in the course.

![WeatherApiWebPage](./Images/WeatherApi1.png)
![WeatherApiWebPage](./Images/WeatherApi2.png)
![WeatherApiWebPage](./Images/WeatherApi3.png)
![WeatherApiWebPage](./Images/WeatherApi4.png)

I figured it would be a good idea to have all the information in one location for easier access in the future and could be something i keep coming back to in the future to work off of. 

# Week 4
**28/9/24**

Reading deeper into human computer interaction specifically has made me think more about making my device be something that seemlessly integrates with life as opposed to something that creates an alert to grab the users attention. Using the environtment around users to create an interaction that makes sense and feels natural seems to be the ultimate goal of this project. and so far my ideas are based more around retriving information and displaying it in someway. I think the most natural idea i have has so far would be the wrist band to retrieve postioning and angles of a basketball players wrist during jumpshots. This uses cognitive processes to display information that is not easily accessible that can be then be used to inform future decisions in the user reaches conclusion they might not have reached without the device. 

**29/9/24**

Revisiting earlier material ive been thinking about doing a wearable device similar to the light up backpack. Maybe using the pedomotor to track steps and illuminate led in some shoelaces or building off this i could use the motion sensor on the microbit to sense when a basketball passes through a hoop and illuminates the net. this interaction seems approriate since its seemless and doesnt require any physical interaction.

Ive bought a led strip to that can be controlled with the micro bit i hope to use that in my final project

# Week 5 
**1/10/24**

turns out the led strips were not compatible with the micro bit 

i decided to use the onboard accelerometor to be used as a device used for practise in sport. 

what ive been working on so far has been a device that counts your dribbles while playing a game of basketball 

![bouncecode](./Images/bouncecode.png)

This method would involve holding the microbit on the users wrist while they practise a drill 

# Similar devices

**2/10/24** 


Similar devices can be found in the shot tracker. This device uses an array of sensors on the court and players to track the postition and movement of the players and ball. 
![shotTracker](./Images/shotTracker.png)

teams of tomorrow use a wrist sensor and a net sensor to track your attempts and misses. The accompanying smartphone app captures and displays your data, including your time on the court, the number of points you scored and your performance in each part of the court. The court zone map tells you where you need to brush up and where your best shot remains.

![waistbandTech](./Images/waistbandTech.png)

The blastbasketball replay is said to be a waist worn device that tracks the users vertile leap angles of spin moves and length of hangtime 

**3/10/24**

i have been working on the code for the wrist worn device. This uses the acceleromotor to display the x axis. Ive added some smoothing to make the data easier to read. I feel like this could be useful to build of off and add more features. potentially some mobile connectivity, user feedback and mini games built in. 

my biggest struggle so far is finding a way to display the information in a meaningful and exciting way. 
 
![DataCollection](./Images/DataCollection.png)

**4/10/24**
I think the bounce code i created earlier will be the focus for my assignment 3 i think the applications and ease of access make this a really viable option 
<video width="320" height="240" controls>
  <source src="./Images/bounce.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

**11/10/24**
Experimenting with time!

Today i thought about using time as way to create levels of difficulty. I think this will be good for users as it will show progress and create rewarding experiences.

![CreatingRhythm](./Images/CreatingRhythm.png)

Ive been struggling to get the numbers to increase when the dribbles happen at the right rhythm i will have to review my code again and try another method

![BounceRhythm](./Images/BounceRhythm.png)

**14/10/24**

Today i want to be able to make the numbers increase when the micro bit has been shaken at a steady rhythm. so far im only working through the MakeCode website and using the digital micro bit to ensure that the it works before moving it onto the physical one. 

**20/10/24**

![GameRestart](./Images/GameRestart.png)

I have now programmed the micro-bit to count in ascending order for each dribble of the basketball done in a specific rhythm. The game will also reset the dribble count back to 0 as well as reset the rhythm timer for the dribbles. I feel this is how i want the game to work in the final product with the possibilty of adding both hard and easy modes that change the rhythm accorindly to better suit begginers and experienced players.

<video width="320" height="240" controls>
  <source src="./Images/GameDemo.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

**Week 9**

Ive been having trroubles with the first inital dribble after failed attempts at maintaing rhythm to ive add a new varible that makes the first dribble of an attempt always successful. 

![FirstDribble](./Images/FirstDribble.png)

With this issue addressed i think i will move onto making a truly wearble device. My first thoughts are to sew the microbit onto a glove that the player will wear during practise or games. My initial concerns are surrounding the weight of the microbit and how i can attach it to the glove without it being cumbersome or getting damaged in the process. 

**WEEK 10**

my first attempt at making the device wearable started with velcro strips to make a wrist band that attached to the microbit 

![WristBand](./Images/WristBand.jpg) 

Now that the microbit is wearable ive started testing the feedback of the device and how it might work with the physical edition.

This video shows the microbit reacting to the dribbles when done in the correct rhythm it also show an 'X' and resets the count to 0 when an incorrect dribble is detected

<video width="320" height="240" controls>
  <source src="./Images/BounceTest.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

The mirobit accurately recieves feedback from dribbling the basketball however i found the rhythm to be too slow for it to be an enjoyabel experience. I think this is a good base line for absolute beginners but i would like to add additional speeds and rhythm timings so the user can have some control over their experience


**Week 11**

I have found that its too difficult to get the micro bit to react to individual dibbles and i have been having touble with restarting the rhythm after an error. So because of this im starting to think i should treat it as more of a time based challenge than a dribble counter.

I have made a number of changes to the code to work in line with my new direction. Goal of my new project to is to achieve 10 consectuive dribbles and use this goal as a training machanism.   

![OnShakeStart](./Images/OnShakeStart.png)

This code will now show a tick and play a melody after 10 consecutive dribbles. I have added a clear screen and a reset to make starting the excersise again more seemless. I have made the rhythm window larger to increase the likelyhood of a successful dribble.

![OnShakeEnd](./Images/OnShakeEnd.png)

Ive also added a melody to unsucessful dribbles. I wanted this melody to be shorter than the sucessful melody so it wouldnt discourage users to much. I found it was quite frustrating to keep hearing the tone after consecutive unsuccessful dribbles and this was creating a less enjoyable experience.

**Week 12**

<video width="320" height="240" controls>
  <source src="./Images/DribbleTest.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

This is the execution of the previous code. It works as intended and i believe could be a useful piece of training equipment.

![CompletedCode](./Images/CompletedCode.png)
This is the completed code that i will be using for the final product. 

**week 13**
I have begun working on the video segment for the assignment. My initial idea for the video is to create a advertisement that you might see for childrens toys. The first software i started with was the adobe express video editor. I used a template to create the title page and added some of my own photos of the micro bit and a basketball to help to the audience associate my idea with basketball. I also used adobe express to remove the background of the basketball to make it sit in the picture in a more aesthically pleasing way  

![TitlePage](./Images/TitlePage.png)

I gathered a number of video clips that show me demonstrating how the device might be used by audiences. My plan is to create a couple quick snippet clips  that transistion quickly in the video to keep audiences engaged and entertained throughout. I think it is important to show how it responds to the user and how it has been designed for anyone to be able to use. 

![BasketBall](./Images/BasketBall.png) 

The clips im trying to create will show what happens when you succeed and fail. How the user might wear it and how to put it on. then showing the how its intended purpose as a training assisstant. And then a i final shot of how it looks by itself and when the user it wearing it.

![VidCap](./Images/VidCap.png) 

I used powerpoint to create the opening and closing credits scenes

![PresentedBy](./Images/PresentedBy.png) 
![Credits](./Images/Credits.png) 

The music used throughout was created by me using real instruments and recorded on my phone, uploaded to my computer and pieced together using a software called OBS studio.

I think the device could benefit from added features such as total dribble count tracking instead of ccounting to 10 and restarting along with other feedback loop features such as vibrations in the micro bit and potentially even custom audio tunes for success and failures. This prototype as it is now still has its place in the basketball scene in my opinion and could be improved to be a valuable piece for those that are looking for technology assissted practise mechanisms 



