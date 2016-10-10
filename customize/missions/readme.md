#Customize

Missions can be customized.

Missions are XML files.

There are editor with GUI for this:
http://www.cattail.nu/artemis_mission_wizard/
https://artemis.forumchitchat.com/file?id=2905854

This runs fine in WINE.

###To run custom missions
In the Artemis install folder, there's a subfolder called 'Dat'.  Inside that is another folder called 'Missions'.
From [Mission scripting docs](http://artemiswiki.pbworks.com/w/page/51088806/Mission%20Scripting):
Inside the Missions folder, each mission needs to have its own unique folder. Each mission folder name must start with 'MISS_'. Inside a mission folder must be 1 XML file.  It must share the same exact name as the folder it's inside, except for the .xml suffix.  This file will contain all the commands that make the mission happen.  There may be other files in the same folder.  As a general rule, any sound, video, or image files that the mission uses must be in the same folder as the XML file that references it.
