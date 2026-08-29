# **measure-one**
### A Caliper? A PCB? NO! IT IS A PCB CALIPER!

Measure-One is a caliper that is made entirely from PCBs. 


Measure-One can measure in both centimeters and inches. And it can measure anything up to 30 cm (~ 11.8 inches).


A render of measure-one in blender:

<img width="2048" height="1080" alt="Measure-One_Final" src="https://github.com/user-attachments/assets/6f6fd83a-5b41-4ac9-a3a2-e7748dbfae7a" />

___

## The Reason and the Inspiration for This Project

I first had the idea to make this project when I saw JBlitzar's (btz) project "measure-one". He made an pcb ruler and I asked to myself that if a ruler that is made from PCB looks that cool how would I caliper look? Also at the time that I started this project I was looking to get an caliper so it lined up perfectly :] At the end I ended up with a project like this. Altough the process had some problems I had fun making this project.


I also got the inspiration for measure-one's render from JBlitzar. I want to thank him A LOT. If you liked this project you might like his project too.
___

I made 2 version of the caliper PCB's. One with instructions and one without. I added these instructions cause some people may have problems putting together this caliper which has a total of 23 different piece designs. You can find how the instructions work in the next part.
___

## How to Understand the Instructions

I already stated how to use the instructions in one of my devlogs. Here is that part of that devlog:

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

___

## Getting It for Yourself / Manufacturing

There is a total of 23 different pieces designs but when taking the 2 version (with instructions and without instructions) there are 46 different PCBs. All of the gerber files of these PCBs can be found in `Manufacturing` folder. The ones with instructions have `"_W_I"` at the end of their name. 

There are also the panelized PCB's gerbers. I made these gerbers my stitching up the other ones in the same group. But they have different number of designs in each panel. This part becomes very important when ordering it from a manufacturer. There are the different design counts of the panelized versions:

* Measure_One_Main_Body_Panelized / Measure_One_Main_Body_Panelized_W_I    **=**    **7**

* Measure_Slider_Body_Panelized / Measure_Slider_Body_Panelized_W_I    **=**   **8**

* Measure_Slider_Pointer_Body_Panelized / Measure_Slider_Pointer_Body_Panelized_W_I    **=**   **8**
___
You can also find the KiCad design files for these PCBs in the `Kicad` folder.
___

## Same Photos Of this Project

<img width="1457" height="787" alt="image" src="https://github.com/user-attachments/assets/949fad6d-4ecf-4591-8f72-4f7175b1ee78" />
<img width="228" height="390" alt="image" src="https://github.com/user-attachments/assets/241ac1c6-1c2f-47ff-bb30-22f1936db098" /><img width="282" height="365" alt="image" src="https://github.com/user-attachments/assets/a98dff8a-7c08-4527-8786-53abd198c635" />

<img width="866" height="551" alt="image" src="https://github.com/user-attachments/assets/2ee72714-48a2-4f67-9042-20b0804b89c6" />
<img width="1391" height="143" alt="image" src="https://github.com/user-attachments/assets/9af7bd4a-b5db-4aee-b836-3e43fa9677af" />
<img width="1377" height="775" alt="image" src="https://github.com/user-attachments/assets/37c8385a-d4db-4b21-bd94-a7cbe37db320" />
___
### BOM (Bill of Materials)
When I looked get these PCBs from JLCPCB it was nearly $120 + shipping. And that is probably what you are going to get when you try to order one yourself. But because I am in Türkiye and the taxes are quite strict I will get it from my local resellers and It will cost a lot more than the JLCPCBs international amount.

*Yet To Be Updated*

___
## License

This project is licensed under the **CC BY-NC-SA 4.0 License**. 

You may modify and redistribute this project under the terms of the **CC BY-NC-SA 4.0**, visit https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.txt for the license.
