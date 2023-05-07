# magma-forge-client-setup
Incase you would like to read the source instructions, read here: https://github.com/superzanti/ServerSync/wiki/Quick-start

For a video process refer to this video: 

Download files here: https://1drv.ms/u/s!AvzEsnT6yIJovCCK1rqAXiIG4meB?e=bmydUt

After, click on "run server sync.bat" so it is highlighted and then right click it. A dialogue box will appear and you need to click edit.

You will see "C:\Program Files\Java\jdk1.8.0_202\bin\java.exe" -jar serversync-4.1.0.jar.

Copy C:\Program Files\Java\jdk1.8.0_202\bin\java.exe and paste that into your file explorer window.

If the path is correct then you are fine to create a shortcut for "Run Server Synce.bat" and put it on your desktop.

If the path is invalid then you will need to check for where the install path is. Go to your c drve and check program files (NOT X86) and look for a folder called java.

Once you find that folder click on it and then look for the java version 202, after click on the bin and then copy the path.

GO onto the bat file from ealier and replace C:\Program Files\Java\jdk1.8.0_202\bin\ with the path you have. MAKE SURE TO PUT java.exe after bin\

Then go to your minecraft directory, search %appdata% in your file explorer and look for .minecraft.

Drag the server sync file and run server sync file in the .minecraft folder.

Once done, click on the "Run Server Sync.bat" and enter the server ip and port 25565 in their respective areas.

Thats it, whenever you want to play the server run the bat file and press sync and then launch minecraft and connect to the server.
