# Power-Control-Panel

Download the latest version 0.1.7 here: https://github.com/project-sbc/Power-Control-Panel/releases


This software allows easy change of TDP on windows handheld devices. 
Features include: 
-configurable profiles with charger vs battery values
-xinput TDP change capability (hold LB RB and a dpad direction)
-assign an exe to a profile to auto start when exe opens
-auto startup at logon to system tray 
-touch friendly interface, keyboard (mostly) not required

Supported CPUs are limited to intel such as tiger lake, ice lake, kaby lake
AMD support coming soon!!!!

Devices this is great for:
GPD win 3
Gpd win max
Gpd win 2
One netbook 1gx/pro
One netbook one mix 3/4
One netbook one x player


YouTube video of software in action: https://youtu.be/JwvPWb7sDqk


If you would like to donate you can at:
https://ko-fi.com/project_sbc

https://www.paypal.com/donate?business=NQFQSSJBTTYY4&currency_code=USD



Troubleshooting:
1. App randomly closes - if you used a prior version and recently downloaded a newer release, you need to delete the config file. I have updated the config file a few times. If you don't delete the old config file it won't have the expected changes I've made.
You can find it under users - your username - appdata - local - power_control_app and delete all files and sub folders in there.

2. Computer crashes when changing TDP - next time you open the software it will alert you it crashed and take you to the settings tab. Adjust the RW Delay value to a high value like 1500 and try it again. This sets the delay reading and writing to the registry. Some devices can handle 200 ms, others are sensitive and need over 1000 ms.

3. Values don't save when I reopen the program - same thing as 1, delete the config file!

This program is provided as is, for personal use only. By using it you accept any risks and responsibilities associated with its use. 

