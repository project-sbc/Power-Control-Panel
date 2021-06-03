# Power-Control-Panel
This software allows easy change of TDP on windows handheld devices. Features include: configurable profiles with charger vs battery values and xinput TDP change capability.

YouTube video of software in action: https://youtu.be/JwvPWb7sDqk


If you would like to donate you can at:
https://ko-fi.com/project_sbc

HTTPS://paypal.me/projectsbc



Troubleshooting:
App randomly closes - if you used a prior version and recently downloaded a newer release, you need to delete the config file. I have updated the config file a few times. If you don't delete the old config file it won't have the expected changes I've made.
You can find it under users - your username - appdata - local - power_control_app and delete all files and sub folders in there.

Computer crashes when changing TDP - next time you open the software it will alert you it crashed and take you to the settings tab. Adjust the RW Delay value to a high value like 1500 and try it again. This sets the delay reading and writing to the registry. Some devices can handle 200 ms, others are sensitive and need over 1000 ms.

This program is provided as is, for personal use only. By using it you accept any risks and responsibilities associated with its use. 

