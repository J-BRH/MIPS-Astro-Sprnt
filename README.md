# Astro Sprnt - MIPS Assembly

This is the final project regarding the CSC312 (Computer Architecture) course taken in SP25 at NDU - Louaize.
Applied in this final project, are concepts of arithmetic logic operations, Bitmap display, and sound output.<br/><br/>
**Main Features:**<br/>
🚀 Shoot-em up space invaders themed.<br/>
🕹️ Navigating a main menu, controls explanation!<br/>
👾 Random enemy spawning!<br/>
⭐ 2 player skins to chose from!<br/>
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
▫️Moreover, a spawn grid is set in place, allowing enemies to spawn on top, and bullets on the bottom. Each "tick" updates the enemies and bullet positions, detects for collisions, and cleans up explosions.<br/>
▫️Another point to keep in mind, is that the user's movements are the "tick" running the game. If no movement is detected, the game does not spawn enemies, does not move bullets, and does not check for collisions or out of bounds enemies and bullets.<br/>
<img width="256" alt="gameplay" src="https://github.com/user-attachments/assets/b63d5c45-e2d6-4a9d-8a60-f7b3bd3a0e0c" /><img width="16" alt="dividor" src="https://github.com/user-attachments/assets/9349b32a-9ff9-459b-b4ef-9a15d2bcd1cc" />
<img width="256" alt="gameplay2" src="https://github.com/user-attachments/assets/0ff05686-908b-479d-885b-efdea51f1639" /><img width="16" alt="dividor" src="https://github.com/user-attachments/assets/9349b32a-9ff9-459b-b4ef-9a15d2bcd1cc" />
<img width="256" alt="grid" src="https://github.com/user-attachments/assets/cbe8e5d7-2dd6-4813-a3f7-3e9e2261d7b8" /><br/><br/>
▫️The player is also able to change their ships' skin by going to the options menu and selecting their preferred choice.<br/>
▫️Finally, when the player recieves a total of 3 hits to their life, the game ends, displaying the user's score in form of stars from 1 to 5. 1 being a minimum of 0-2 enemies killed, going all the way to 10 for 5 stars.<br/><br/>
<img width="256" alt="game_over" src="https://github.com/user-attachments/assets/70b8b0cc-1a43-4b98-a7de-17ab91ae7e0e" /><img width="16" alt="dividor" src="https://github.com/user-attachments/assets/9349b32a-9ff9-459b-b4ef-9a15d2bcd1cc" />
<img width="256" alt="skin_changer" src="https://github.com/user-attachments/assets/01c80b78-bd65-4640-b9c1-27cbf5bc7d2c" /><img width="16" alt="dividor" src="https://github.com/user-attachments/assets/9349b32a-9ff9-459b-b4ef-9a15d2bcd1cc" /><img width="256" alt="other_char" src="https://github.com/user-attachments/assets/44a962b8-8b4b-4d00-9839-e7244f5a66b9" /><br/><br/>
📼 Video Showcase: https://youtu.be/mFEvedBVJ_k
