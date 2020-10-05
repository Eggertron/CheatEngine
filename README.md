# CheatEngine
A Collection of CheatEngine Tables that I created or downloaded and used.
Tables that I did not create, I do not modify.
# Links to other repositories
https://github.com/Hexorg/CheatEngineTables
# Hide CE from Detection
These steps are [originally found here](https://www.unknowncheats.me/forum/grand-theft-auto-v/357234-request-undetected-cheat-engine-gta-5-rage-mp.html). 
 First, create a copy of the `cheatengine-x86_64.exe` binary file, name it whatever you want (we will call it `unknown.exe` in this example). Next, use [Resource Hacker](http://www.angusj.com/resourcehacker/) to open `unknown.exe` and change some information inside `Version Info` -> `1:0`. Change CompanyName and FileDescription to `unknown.exe` and press F5 to compile followed by CTRL+S to save the file.
Next we will open `unknown.exe` and click on the `Memory View` box. In the `Memroy View` window to go `Tools` -> `Lua Engine`. Paste in the following lines into the `Lua Engine` window
```
getApplication().Title="unknown"
getMainForm().Caption="unknown"
```
and press the `Execute` button. Now you are ready to hack your games.
