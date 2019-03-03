# GameOfDrones
Repository for CAD models, datasheets and pics taken while making quadcopter.
![quad image](https://github.com/BitsRobocon/GameOfDrones/blob/master/IMG-20190303-WA0007.jpg)

Our drone is a quadcopter. We started making the quadcopter around mid september. It uses a flight controller Naze32 rev6 full version as its brain.  The function of the flight controller is to give electronic signals to the Electronic Speed Controllers (Simonk 30A) which in turn provide voltage across the Brushless DC motor (A2212 1400kv). Drone uses a 3 cell orange lipo 5200mah as its power source. All the Electronic Speed Controllers are connected in parallel across the battery via a Power Distribution Board (pdb). We are using propellers of size 8 inch and 4.5 inch pitch. Drone’s body is made up of 2 aluminium pipes and a face plate in order to mount Electronics on top of it. Chassis weighs about 335gm without electronics. Aluminium 1.5 cm strips of 3 mm thickness are bent and used as landing gear because it is required that on landing the landing gear must absorb most of the impact reaction. 


Drone chassis
The drone is manually controlled via a transmitter receiver pair (FSi6X and FSiaB10) which has 10 channels used to control quadcopter motors and other modes offered by the flight controller during flight. 

The competition we are going for this December (Operation Rahat) requires a QR code scanning and a package drop mechanism. We are using Raspberrypi 3B+ with picamera to do QR code scanning and a simple servo-hinge mechanism to deal with dropping mechanism.


 Our Final Drone
For drone videos and to know about our other projects 

FOLLOW OUR WORK ON
Facebook
Github
Youtube
Google+
LinkedIn
WordPress
Thank you for reading !!!

Share this post
Click to share on Facebook (Opens in new window)Click to share on Google+ (Opens in new window)Click to share on LinkedIn (Opens in new window)Click to share on WhatsApp (Opens in new window)Click to email this to a friend (Opens in new window)More

 Nitin Vinayak Agrawal  Quadcopter for Operation Rahat Leave a comment  November 26, 2018  1 MinuteEdit "More about our Drone…"
Problems associated with Automatic bot
As you know we are participating in the IIT Bombay techfest competition International Robotics Challenge  , we are required to make an Automatic Bot which should be capable of solving a maze and performing a set of tasks such as QR code scanning and color sensing. So our approch in solving the challenge is that we are using a raspberrypi side by side with an Arduino nano. Basically arduino nano being a microcontroller is given the task to continously run the magnetometer and provide the absolute orientation of the bot to the raspberrypi. Raspberrypi being a microprocessor uses the information provided by the arduino to compute its next movement in realtime. The automatic bot is using PID control mechanism to correct errors during the locomotion. Raspberrypi also has a picamera which is capable of taking  5 MP images for QR code scanning. We are still trying with color sensor for the color identification, else we would use the picamera with python image processing library to identify the colors.

Our IRC team has been stuck with the problem of proper locomotion since 3 months now. The situation is like this – any two consecutive walls in the maze has a distance of 30 cm between them and our bot is 14 cm in width including the wheels, therefore the error while locomotion as detected by the ultrasound sensor is quite large. Therefore the bot applies a large amount of correction and tries to follow a zigzag path causing undesired positions of bot in maze and sometimes collides with maze walls.

Currently in order to solve the problem we are thinking of improving our chassis by increasing its size hence decreasing the amount of error and the correction applied. Assuming this would work, here is the pic of our new chassis from a previous project.


Thank you for reading.

Share this post
Click to share on Facebook (Opens in new window)Click to share on Google+ (Opens in new window)Click to share on LinkedIn (Opens in new window)Click to share on WhatsApp (Opens in new window)Click to email this to a friend (Opens in new window)More

 Nitin Vinayak Agrawal  International Robotics Challenge Leave a comment  November 23, 2018  1 MinuteEdit "Problems associated with Automatic bot"
We broke our first propeller…
Our drone was flying great without any major damage eventhough it had experienced  multiple crashing until today, while hovering at a level above the ground one of the motors started making an odd sound. So we thought that it must be the connection between the motor and the propeller, but on inspection we found that the propeller had a tight connection. We started our flight tests again, ignoring the odd noise from the third motor. This time drone started to wobble in midair and fell with high speed onto the ground with one of the four motors taking the head on impact with the ground, thus splitting the propeller into two parts.

img_20181120_163306

Later on we found the reason for crash to be a loose screw on the base plate of the motor which was supposedly the reason for unpleasant sound caused by collisions between the base plate and aluminium plate of the drone body. We don’t have any extra 8 inch propeller therefore we will have to wait for atleast a couple of days till new propellers arrive.

For more drone pictures check out our drone gallery

Thanks for reading.

 

 

Share this post
Click to share on Facebook (Opens in new window)Click to share on Google+ (Opens in new window)Click to share on LinkedIn (Opens in new )Click to share on WhatsApp (Opens in new window)Click to email this to a friend (Opens in new window)More




Also check out our other projects–

Website:https://teamroboconbitspilani.github.io/ 
Blog:https://teamroboconbitspilani.home.blog/ 
Github:https://github.com/BitsRobocon 
Facebook:https://www.facebook.com/bitspilanirobocon 
LinkedIn:https://www.linkedin.com/company/team-robocon-bits-pilani/ 
GooglePlus:https://plus.google.com/106004069810406041106 
Instagram:https://www.instagram.com/teamroboconbitspilani/

If you want to know more about our project email us at: bitsrobocon@gmail.com
