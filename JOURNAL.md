# 3 August 2026 
I researched about how to make an custom caliper, PCB manufaturing and how to make this project durable so that it can actually be a useable piece.

After my researched I learned a few things: 

To make an caliper you need a few pieces;

▪  A main body,

▪  A slider,

▪  And a pointer thingy that is going to be attached to the slider. (This is actually a custom piece that is not necessary. But I find it to look better like this.) 

I also found out that PCBs are not really things that are very durable. This creates a *big* problem. The problem is when they aren't very durable they can just snap at the root and make it unusable. I plan to solve this problem by making the 2 main body and 2 slider parts that can fit together to make double the durability. I am not really sure if this will work but I think it's my only choice. 
___
I also did some sketches. I will later design the PCBs according to these sketches.

<img width="1457" height="787" alt="image" src="https://github.com/user-attachments/assets/d8e3d45b-383d-435f-9de9-bac51d6eb120" />

As I said there is 3 main parts of the caliper.
___
Also I am looking into integrating some useful parts like templates for circles, arcs and angles.
___
Also **thanks a lot** to JBlitzar (btz)'s project measure-zero to give me the idea for this project. I also talked to him and he said I can use the naming scheme. I also wanter to make a reference to his project because they are very alike. I will give the link to his projects github and forge page so you can look to it too!

https://github.com/JBlitzar/measure-zero

https://forge.hackclub.com/projects/972
___
Time Spent: 1 Hour

I was able to lapse 30 minutes of sketching but I couldn't lapsed the 30 minutes of research process.


___
# 5 August - 6 August 2026 
I made a CAD design in Autodesk Fusion. I luckily modeled it, cause I found out that my original design is so fragile to be usable. 

I made a new plan and design to solve this issue.
My new design again consists of 3 main parts. But they are not 1 piece per part as the previous one.
Now each part uses a few different pieces. These pieces will fit together to make an 3D object just like a 3D puzzle. This design will be way more durable and way more usable.

<img width="1237" height="657" alt="image" src="https://github.com/user-attachments/assets/8b39800e-5ec3-415d-b858-9f8805e38dbc" />
<img width="323" height="521" alt="image" src="https://github.com/user-attachments/assets/bae87c46-d1c5-4216-b6c9-5bbf3f869cd1" />
<img width="228" height="390" alt="image" src="https://github.com/user-attachments/assets/468d2135-7b98-42db-8cd3-b8bd2a7f2aa3" />


I didn't yet designed the puzzle joints. But I plan onworking on the joints this week.
___
I also want to modify the main body so it can be used as a container for templates and rulers.
___
Time Spent: 2 Hours
___
# 8 August - 10 August 2026
I designed the puzzle piece sets in CAD. I will use these designs to visualize my project and to plan the outlines of the PCBs. I gave the holes 0.2 mm of clearance to be more reliable.

These are some photos of the designs:

<img width="892" height="547" alt="image" src="https://github.com/user-attachments/assets/d58cab18-517f-4031-a036-8105d4cc680c" />
<img width="262" height="405" alt="image" src="https://github.com/user-attachments/assets/2906867f-a89a-41cb-ae77-6058b12fc634" />
<img width="282" height="365" alt="image" src="https://github.com/user-attachments/assets/30f4cfcf-17fb-40a8-a0ce-d08a8b3ea65a" />
<img width="866" height="551" alt="image" src="https://github.com/user-attachments/assets/1fb26f34-249b-4928-93d9-3e96ee8a55fa" />

There are a total of 22 **unique** pieces. But the total piece count is 32 pieces.
I know that this is a lot of different PCBs. But I couldn't figure out any other way to make it sturdier than the original 3 piece plan. 
___
Time Spent: 4 Hours 45 Minutes
___
# 17 August - 19 August 2026
I was gone for a few days.

Last 2 days I worked on getting the required shapes of the PCBs from my CAD design to KiCad. I used something called DXF files that I just learned few days ago. Apparently they are very useful when you need to do something like this :) 

After this one done. I only have a few things left to do to finish this project. The silkscreen and the build.
<img width="297" height="852" alt="image" src="https://github.com/user-attachments/assets/4dbce524-1afd-4053-8170-1347aabaad48" />
<img width="263" height="343" alt="image" src="https://github.com/user-attachments/assets/e3b5c00b-95af-4fa8-b5ba-c765ec0cf49e" />
<img width="287" height="334" alt="image" src="https://github.com/user-attachments/assets/192edb41-3f54-4e1b-bc39-ac1b7e801a24" />
<img width="333" height="313" alt="image" src="https://github.com/user-attachments/assets/4d4a6192-9052-431b-8b65-5e8114b546fa" />

___

Time Spent: 1 Hour
___
# 19 August - 22 August 2026
I sketched the "measuring lines" for the main function of the project, I don't know what they are called but I will refer them like this. My plan was normally only 30 cm but I added the lines for measuring in inches to make it universal. I also used the Minecraft font for the numbers, because it is one of my favourites.

I also thought that the puzzle might be a bit hard for some because of that I did 2 different sets of pieces. They are exactly same dimensions **but** one is 
with instructions, I will meniotn how it will work later this devlog, and the other one is without any instruction.

Instructions have 3 different symbol types;

1. Letters inside a rectangle

   This symbol type consists of three symbols, `M_B`, `S`, and `S_P`. These symbols indicates which piece set the PCB is from. Each corresponds to a piece set:

   1. `M_B` → Main Body
   2. `S` → Slider
   3. `S_P` → Slider Pointer

2. Letters inside a circle

   This symbol type is used to indicate which piece of the set each PCB belongs to. For example if the symbol is a A inside a cirle, the PCB is the piece A in it's set, if it is a B inside a circle it is the piece B and so on... Also these symbols are generally right beeside the type 1 symbols that indicate the set. This makes it easier to know which sets which part the PCB is.

3. Only letters

   This symbols type is the most used one. They indicate which part will be connected to the nearest side or the nearest slot. These symbols only show the letter of the piece that is gonna be connected not the group. But keep in mind that the indicated piece is in the same group as the PCB. As I said it usually shows what is gonna be connected to the **nearest** part, but sometimes there isn't enough available space so they get squeezed to the same collumn and it is impossible to know which side it is for. I solved this by using small arrows to indicate the side they are for. 


I want to mention that all of these symbols are on the **silkscreen** layer of the PCB.
I also added "_W_I" at the end of these PCB files to indicate that it is with instructions

These are the photos of all of the silkscreen symbols/sketches: 

Type 1 (In a rectangle):

<img width="759" height="189" alt="image" src="https://github.com/user-attachments/assets/0d85ecfa-9706-4d38-8984-fae76d028ee6" />


Type 2 (In a circle):

<img width="681" height="357" alt="image" src="https://github.com/user-attachments/assets/2d26647c-aaad-4b02-84e9-83f8972c9d99" />


Type 3 (Only letters):

<img width="598" height="258" alt="image" src="https://github.com/user-attachments/assets/d0bff1cf-19d2-4bd3-accf-87d9485503cf" />


Also arrows are like this:

<img width="607" height="88" alt="image" src="https://github.com/user-attachments/assets/4a19cce2-3a11-433e-8e7a-d84e22a5e0a5" />


And finally the measuring lines:

<img width="1391" height="143" alt="image" src="https://github.com/user-attachments/assets/6ce6e81a-ffe6-4f75-a9c8-727f95dfe920" />

___
After this done I only have 3 things left to do. 3D render for the forge page, uploading the gerber files to the github repo and writing a readme file.
I think I can do these in less than 1 week.
___
Time Spent: 4 Hours 20 Minutes
___
# 23 August - 24 August 2026
 **Cover image everybooodyyy!**
I designed the cover image in blender. After a bit of material prep, light work and post processing (compositing) it was done.
These took me more than 1 hour, like 2 hours but I only lapsed 1 hour and 10 minutes of it so that is my time spent.

These are some photos of my setup:

<img width="1377" height="775" alt="image" src="https://github.com/user-attachments/assets/4984f39a-3330-45fc-8200-6780ab3ada7e" />

<img width="1147" height="697" alt="image" src="https://github.com/user-attachments/assets/bbbe4079-795e-4829-b57e-87c73bf5a411" />

And these are some of the material and compositing photos:

<img width="692" height="456" alt="image" src="https://github.com/user-attachments/assets/129a9a2b-ba20-4e69-90bc-848198446040" />

<img width="695" height="363" alt="image" src="https://github.com/user-attachments/assets/a15fb4e9-0088-4e79-a95a-800db8b67c05" />

<img width="668" height="257" alt="image" src="https://github.com/user-attachments/assets/6536e42c-19d1-484c-b7b3-e6268ef9e1bc" />


I wanted to make this render look like an minimalist ad with studio lightning. I think I achieved that as much as possible with my level of experience (Beginner).
Also I waited 1+ hours for rendering time in the Cycles render engine. I did a few round of rendering and tuned it a bit each time. And this is the final render which is going to be my cover image:

<img width="2048" height="1080" alt="Measure-One_Final" src="https://github.com/user-attachments/assets/b24054a3-0546-4e3a-9555-b3a1fce0497f" />

___
This project is nearly done. Only remaining thing to do is editing the github repo. And I am looking to finish that in the next 2 days. 
___
Time Spent: 1 Hour 10 Minutes
___
# August 26 - August 27 2026
I made a panelized pcb for every piece category. (Main_Body, Slider, Slider_Pointer, Main_Body_W_I, Slider_W_I, Slider_Pointer_W_I)
And I extracted all of the gerber files from (23+3)*2 = ***52*** different PCB designs.

These took a ***TON*** of time. I redid the panels nearly 2 times each and tested the gerber files if they work.

I am going to add these files to github next day with the other things that I have to do in my repo.

A photo of one of the panelized PCBs:
<img width="792" height="366" alt="image" src="https://github.com/user-attachments/assets/af78bec6-4521-4012-b275-a1292e8828ff" />

___
Time Spent: 2 Hours 43 Minutes
___
