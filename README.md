# touhou_bot
It's a hard-coded bot for Touhou. This version works with PCB. State 1 Easy today, LNNN Tomorrow!

Install the packages from requirements.txt

Open Touhou PCB with vpatch on a 1920x1080 monitor in windowed mode with Width = 960 Height = 720 configured in vpatch

Arrange your windows like I have them in the screenshot.png file and keep running the second cell and adjusting until the window is centered on the play area. There is a character image saved and included (reimu_fast.pckl) but if the bot can't detect reimu because of a screen size difference (or if you want to use a different character or play a different Touhou, you can use the second cell to center the character (I use a 5x8 rectangle of character, I recommend using that) and saving the character array as a .pckl. The fifth cell can help by showing where the bot thinks the character might be, and you can run the function of the sixth cell with move_mouse=True many times while playing to watch the mouse track the character. Then run everything up to the last cell.

When you run the bot in the last cell, you want the Touhou game already started, then switch back to the Jupyter window (should pause the game) and start the last cell. You then have 5 seconds to click back to the Touhou window before it starts. Typical performance is to make it to the first boss but die there. 

You can manually bomb or hold shift to focus (can slightly mess up character detection) to help it out and get a lot further, but it's hard to predict when it will run into a bullet. It has a lot of blind spots because of the incredibly simple decision algorithm, but it can still make some very impressive dodges is you watch it long enough.

V1: https://youtu.be/qO1IGUIP4Ro
V2: https://youtu.be/Ck31KrDU9Is

If you can't get it to work or want help with modifying it (after making an effort first) or you make an improvement and want to let me know, my discord is @abrickwalll
