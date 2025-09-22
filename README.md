Audio feature brief
You might notice "Float dB", this feature can bring you to the opus limit (over discord limit) very easily and just raises your total audio baseline by a fair margine
You might notice "Noise Injection", this feature essentially adds a constant to the pcm values to raise their volume without interfereing with the float stream at all, this method CAN reach the opus limit but its likely not going to match a [-32768, 32767] perfect stream

What node is this targeted to? 
This is targeted to shauns voice modules to keep everything compatible

How do I compile this
Easy way to obtain from GitHub: to compile and use this, go to the GitHub page linked to this giant message, then the green button that says "Code", click it and then press "Open with Visual Studio" on the dropdown menu, follow the dialogue, once you reach Visual Studio, press "Clone" in the bottom right of the smaller menu
Fixing errors: This step is important, you may notice that everything is displaying errors, go to just below top of Visual Studio, find a text box called "Debug", click it, then select "Release", this step is very important and issues regarding errors will be ignored
Compiling: Find where it says Solution 'ExampleHook' (2 of 2 projects) at the top of the screen, right click this, then select "Build Solution", nothing should error, once its done compiling, right click again on the same solution bar and go down on the meny and select "Open Folder in File Explorer", then open the "x64" folder, then "Release", then run "Injector.exe"

THIS SHIT IS IMPORTANT 
1. to prove a point this hook uses 2 offsets total from discord voice node and is as clear as every single other hook
waste a week finding 50 of them for fun though

2. important to know is this is for shauns voice modules not discord voice patcher's so this is more for yelling china and ice 40 times per day, make sure you are using his modules I attached them to the repository just in case you didnt have them you can just download them off of it

3. make sure you close discord before running the injector so it actually loads with discord

AND FOR ANY OTHER INFORMATION 
DISCORD - nox.staytrue
