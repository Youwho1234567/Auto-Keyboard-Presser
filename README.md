# Auto-Keyboard-Presser




Hey thanks for checking out my github this software is 100% free and you can modify/change it all you want as long as you share this github with people you know.Please read the whole readme as it explains the software in great detail

How to download 


Firstly download the AHK this is the software that runs the code
http://bit.ly/DownloadAHK

Secondly create a txt file and change the file format to ahk to do this click rename and change .txt to .ahk 

Thirdly right click the new document and click open with notepad once notepad is open paste this into the empty notepad 

```
Pause on

loop
{
ControlSend,,  {w down}, Minecraft* 1.16.3 - Multiplayer
sleep 800
ControlSend,,  {w up}, Minecraft* 1.16.3 - Multiplayer
sleep 2000
}

f6::Pause
```






Let me explain what you see here where it says loop its just saying loop anything in the curly brackets.
ControlSend W down is just saying hold down W in the tab titledMinecraft* 1.16.3 - Multiplayer.
Sleep is saying  how long you want it to run so in this instance we want W to be held down for 800 ms.
Then on the next line there is another ControlSend but this time it says W up which means stop holding down W in the tab titled Minecraft* 1.16.3 - Multiplayer for 2 seconds.
Then f6::Pause is just the hotkey  you want to trigger it with 

If you want it to be trigged with f4 Change it to this.

f4::pause

If you want to make it so you have to hit certain keys to trigger it for example u and f4 you would replace it to.

U & f4::Pause

If you wanted it to hold down a diffrent key you would change it to

ControlSend,,  {a down}, Minecraft* 1.16.3 - Multiplayer
ControlSend,,  {w up}, Minecraft* 1.16.3 - Multiplayer

If you wanted to change it so it only clicks a key remove the brackets and the down so it looks like this 

ControlSend,,  a, Minecraft* 1.16.3 - Multiplayer

If you want to change it so it clicks in a diffrent tab then Minecraft* 1.16.3 - Multiplayer change it so it looks like this 

ControlSend,,  a, Insert tab name here





**KNOWN BUGS**

Sometimes while the script is running keys like Crtl, Alt, Tab and  Shfit
will not work.Other keys may not work also

Sometimes after stoping script it will continue to run

I will not fix any of these bugs unless this gets popular also if this software get popular ill do a youtube video on how to install it.Please let me know what you think, any more bugs you find or if something in this readme didnt make sense by opening a issue or by contacting me via discord Youwho1234567#1605 Have a wonderfull rest of the day

Youwho1234567 


