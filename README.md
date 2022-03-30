# IAAR
Basic design of a new class of highly agile(target area:HUMANOID) robots that I plan to build.
## AIM
To design  analog based robots which provides a huge advantage over conventional robots in terms of agility and easiness of calibration.
## CONCEPT
My Idea is to combine ancient mechanics with modern precision to create a robot that would give us added advantage in terms of agility.
The idea is simple : We replicate the actions of bone joints by using a combination of an electromagnet and a magnet which moves an axle and a resizable latch.
This setup is highly raw and not accurate , which might be the reason that this technology is used today, But I managed to come up with a hack to address this issue.
The trick is simple: we add a simple screw system in the latch tightener. Such that, the tightening and loosening of the screw changes the friction between the latch and the part that holds the latch.
This will help us to calibrate the joints to the highest precision.
## FURTHER EXPLANATION WITH DIAGRAM
### TOP
![IMG_20220329_185705](https://user-images.githubusercontent.com/88607869/160638796-cc00ebdf-3183-4948-8494-226a0494a999.jpg)
### SIDE
![IMG_20220329_185647](https://user-images.githubusercontent.com/88607869/160638725-0c64b075-3d09-4799-88ba-3d5aa6ebabc5.jpg)
<br> The two big squares are pieces which represent the two bones in the muscle joints of the human body.
<br> The goal here is to create a mechanism to move the first bone in reference to the second bone.
<br> To do this we use a latch system and an axle attached to a magnet. 
<br> One of the sides of and the other is connected a magnet which is suspended in the middle of an electromagnet in the second bone
<br> The latch axle is connected to the middle of the main axil.
<br> When electricity is passed through the electromagnet in the second bone a magnetic field is produced. Which pushes and pulls the magnet and the main axil attached to it. This results in the movement of the first bone with the latch axil as the pivot point.
![IMG_20220330_201936](https://user-images.githubusercontent.com/88607869/160865939-f14d9671-23f3-4847-a936-8f9dc4d42a09.jpg)
The main axle moves bi directionally as the middle of the latch axil as the pivot point.This will in turn move the first bone in reference to the second bone. But this setup is really raw and not precise. That's where the use of a resizable latch comes in.
<br> The latch tightener is a bit of an elastic system where a screw is inserted and when the screw is tightened the circumference of the tightener increases and it bukdges into the walls of the latch holder. This will increase the friction between the two and bring changes into the movement of the main axle.
![IMG_20220330_201910](https://user-images.githubusercontent.com/88607869/160865959-a1ed95ab-5e30-4ced-b1c6-9b47f65d644a.jpg)
Lets say we have to move the bone in the below direction (note -ve values shows backward direction)
<br><b>  4    -2    6    -6</b>
<br>Whose corresponding analogue signal will have the below maximum voltages.
<br><b>  2    -1    3    -3</b>
<br>But in our system we pass this signal through an amplifier which amplifies the previous signal into this new signal.
<br><b>  4    -2    6    -6</b>
<br>which we will give as an input to the electromagnet and  is supposed to give out the following rotations.
<br><b>  8    -4    12   -12</b>
<br>But due to the internal friction that already exists in the system it will give out a rotation of 
<br><b>  8x   -4x   12x  -12x</b> Where <b> x </b> is a number between one and one by two.
<br>So on the thought that the movements of the bones will give out rotations which is a real value amplification of the required signal , we can go ahead with building the rest of the parts. That is if you are building a finger , we build this setup and we do the rest of the artsy stuff. That is the stuff which will make this piece of machine look like an actual finger. We do this in such a way that we leave a small gap to access the screw.
<br>After doing all of these setup , we check the system once again. That is we give the input signal and see the retation and see how much it warries from the required rotations.
<br>Soon after this we adjust the screw so that the actual rotations match the required rotation and hence calibrating the system.
<br>The system once calibrated do not need to be calibrated again.
## ADVANTAGES
(while compared to current systems)
<br>More precise.
<br>Better agility.
<br>Easy calibration even after prosthetics and props are added.
<br>Long lasting.
<br>More economical


    
