# Astro Sprnt - MIPS Assembly

This is the final project regarding the CSC212 (Computer Architecture) course taken in SP25 at NDU - Louaize.
Applied in this final project, are concepts of arithmetic logic operaions, Bitmap display, and sound output.<br/><br/>
**Main Features:**<br/>
🚀 Shoot-em up space invaders themed.<br/>
🕹️ Navigating a main menu, controls explanation!<br/>
👾 Random enemy spawning!<br/>
☄️ Score the highest!

##  How It's Made: 

▫️**Tech used:** MIPS<br/>
▫️**Dependencies:** MARS (MIPS Assembly Runtime Simulator) which can be found [here](https://dpetersanderson.github.io/).<br/><br/>

⚠️**BitMap display Settings:**<br/>
▫️Unit Width in Pixels: 1<br/>
▫️Unit Height in Pixels: 1<br/>
▫️Display Width in Pixels: 512<br/>
▫️Display Height in Pixels: 512<br/>
▫️Base Address for Display: 0x10010000<br/><br/>

Make sure to open the Bitmap display, the Keyboard and Display MMIO simulator, and connect them both to MIPS (both can be found under the Tools section) before proceeding, and setting up the bitmap to the correct settings which can be found above.<br/><br/>
▫️When first running, the user is presented with 3 options, all of which they can navigate freely using **[1,2,3]** and select using **[SPACE]**. The user is also able to see the currently selected option using the white selector ball.<br/>
<img width="256" alt="main_menu" src="https://github.com/user-attachments/assets/83af9de1-699b-4bf5-8c03-df3c51910656" /><img width="16" alt="dividor" src="https://github.com/user-attachments/assets/9349b32a-9ff9-459b-b4ef-9a15d2bcd1cc" />
<img width="256" alt="credits" src="https://github.com/user-attachments/assets/1837675b-4889-49fb-87dd-f2c350510c47" /><img width="16" alt="dividor" src="https://github.com/user-attachments/assets/46fcf58d-ccf4-4194-b043-9fb7b7e584bd" />
<img width="256" alt="controls" src="https://github.com/user-attachments/assets/a015ecbd-3209-4bc4-a327-3ec27a2b952b" /><br/><br/>
 
▫️Once the user starts the game, they are met with the above controls explanation screen. Upon proceeding, the player ship is rendered along with the health bar, as such the user is allowed 3 "hearts" or "hits" before the game ends.<br/>

