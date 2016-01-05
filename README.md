# Annotation-Webapp
This is botanical label making software used to annotate specimens for use in herbaria. 
This software is ready to use with zebra gx430t label printer. 
It is possible to use this with other printers but different driver compatibiilities will need to be encoded for.

Directions for primary installation as follows:  	revision date 11/23/2015 DJA

Note: a few things are still being worked out: we are working on a method to make room for longer species 
names and to automatically refresh after the label is printed.

This web application was designed to make annotation labels for vascular plant specimens. 
There are two options: it can run by scanning QR codes with a Honeywell barcode scanner 
(designed for the New England Thematic Collections Network NSF-funded digitization grant), 
or by simply entering (or cutting and pasting) the species name into a blank box. 
The Zebra printer we are using is the GX430t with a thermal transfer process (NOT direct thermal). 
We are printing onto archival 1” tall by 3” wide labels purchased from Watson Label Products and a wax/resin ribbon.

The current code runs on windows machines only using Firefox.
Current webapp access point: http://www.uvm.edu/~pringle

Set up the printer with the computer (some of this needs to be done for each individual user):

Install Zebra drivers & Configure print setting:	
1.	Make sure printer is off.
2.	Plug the USB port from the Zebra printer into windows computer. Turn printer on. This should launch the zebra drivers application and setup wizard.
3.	In the event that USB port does not launch promptly, visit 
https://www.zebra.com/us/en/support-downloads/eula.-227178c9720c025483893483886ea54032da4ba1a754ef88faaff03fffc08a71d3935761544249a30fd1eff8d2004c654dc33e5a2077f40a53215bcf57d79ada5e744b82b6e1c7b.html and follow software download instructions.
4.	**Change printing preferences to reflect dimension of labels. Note: the label field is 2”*3” despite printing 1”*3” labels.
a.	Windows folderDevices and Printers
b.	Right click on ZDesigner GX430t icon.
c.	Printing Preferences
d.	Choose stocks tabNew
e.	Settings are as follows
i.	Speed: 2
ii.	Darkness: 26
iii.	Orientation: Portrait
iv.	Format: Inch
v.	Size: Width-3; H-2
vi.	Unprintable area all 0
vii.	Name this preference, “LABEL”; Press Apply. This can now be referenced for fast and easy printing without reentering specifications.

Install Windows drivers (has to be done for each user):
1.	Visit https://qz.io/ and follow instructions for download.
2.	QZ Tray needs to be downloaded and turned on. 
3.	Set QZ Tray to “Automatically start” on your Windows machine.
a.	Click the “show hidden icons” triangle on the task bar (lower right corner of screen).
b.	Left click the QZ Tray icon.
c.	Left click “Automatically start”
d.	This should only have to be set once on each machine FOR EACH USER.

Create a shortcut for your desktop (*not a necessary step-just a time saver):
1.	 Make Firefox your default browser. 
2.	Highlight the entire entry in your browsers address bar or this link: http://www.uvm.edu/~pringle
3.	Right click link and select Copy. 
4.	On your Desktop right click an empty area, move the cursor over 'New' and then select 'Shortcut'. 
5.	Right click in the box, select Paste and click Next.
6.	Rename the shortcut or easy access to the annotation web app. 

Configure Page Setup in Firefox:
1.	With Firefox open, right click in the border at the very top of the open window. 
2.	Select Menu Bar.
3.	Select File, Page setup.
4.	In Format and Options, make sure “Shrink to fit page width” is not selected; orientation “portrait”
5.	In Margins and Headers/Footers, set all four margin values to zero.
6.	Press ok


Run the program to print labels:

After you have done all of the setup steps above for your login on a computer, launching the program should require nothing more than clicking the link for the short cut and plugging in your Zebra printer and your Honeywell barcode reader, if applicable.  
1.	Sign into user interface 
a.	Username: pringle
b.	Password: DigiHerb
2.	Access software
a.	uvm.edu/~pringle
b.	or shortcut on desktop
3.	Ensure that the predetermined printing preference stock is selected.
4.	After you have printed the label and are ready to generate a new label, press the refresh button in your browser.


Program is made to work with 1”*3” oriented label stock. Make sure stock and ribbon are loaded correctly according to Zebra specifications. Press the feed button to calibrate alignment. You are now ready to make annotations! 

