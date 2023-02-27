# admin-map-Rust-

**Displays all connected players on the map for admins.**

Pretty straightforward but ill explain the basics.  

Every 5 seconds it loops through the list of connected players and outputs them as little markers on the map. Made this to help out with teamer issues, admins can now check their maps to see if players are grouped up together and can keep track of groups easier. 

Additionally there is a right click to teleport function built in. Admins can right click anywhere on the map and teleport there instantly. This function is found on line 115-123. If you don't want to include it then comment it out or remove it. 

Use case : 

"/amap on" to turn on the admin map. 
"/amap off" to turn off the admin map. 

Configure line 71 to adjust the usergroups that should have access to the map. 

Teleporting occurs when the marker is placed down and then removed. This means you need to double right click on the map to be teleported. Helps to solve accidental tp's. 


**( This plugin is currently untested and I would really appreciate it if someone could test it for me. )**

Report any issues. 

Contact me for anything else. 

