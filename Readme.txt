Command & Conquer™: Yuri's Revenge™

LATE BREAKING NEWS FROM THE FRONT

Copyright 2001 Electronic Arts Inc. All rights reserved.
Westwood Studios™ is an Electronic Arts™ brand.


Version #:  1.000
August 30th, 2001


For latest news and updates visit WWW.WESTWOOD.COM



 - - TOP SECRET - -	

Commander:

Welcome back!  Thank you for extending your tour of duty.  Your outstanding 
service is greatly appreciated by the High Command and people all over the 
World.  Due to the chaotic disruptions caused by Yuri's psychic technologies, 
the following information must be kept classified until you are ready for 
action.  Review the following bulletin from Command Headquarters with great 
care. Commit it to memory, so you can be decisive and victorious out on the 
battlefield!

Good Luck.

--President Michael Dugan




GENERAL CHANGES & FEATURE UPDATES


General:
-  In the Game Option screen, the Game Resolution setting only sets the in-
   game (battlefield) resolution.  The game shell screen resolution is locked 
   at 800 by 600 pixels.
 
-  With the Short Game selected, Yuri's Slave Miner is excluded from the 
   winning condition.

-  Now all players can see the infantry pips of any fortifiable civilian 
   building, regardless of which player garrisons it.

-  When a unit is mind controlled, all players will see the initial mind-control 
   line from the controller to its victim.

-  The T (unit-type select) and P (all-unit select) hot-keys will automatically 
   exclude units inside of a Tank Bunker.

-  In Red Alert 2, sometimes a game would not end if the last remaining unit 
   were in a mind-controlled vehicle.  Now, if this should happen, the unit 
   inside will be automatically killed, and the ex-owner of the captured unit 
   will be declared the loser.

-  Tab-flash-for-readiness has been updated.  The following features will 
   only flash the tab for a bit to inform the player when fully charged: Spy 
   Plane, Force Shield, Psychic Reveal.

-  If playing behind a firewall, the preview maps do not get transmitted to 
   other players.


Units & Structures:
-  Magnetron can only levitate vehicles, not infantry.

-  The Brute is not allowed inside of an IFV.  However, the Brute is allowed 
   inside other transports, but only as a passenger.

-  The Hero units (Tanya, Boris, and Yuri Prime) are not allowed to use their 
   special attack from within the Battle Fortress.

-  Kirov spinning every time it acquires an order/target is now fixed.

-  Setting waypoints for planes from within the radar map has been disabled.

-  Floating Disc will auto target and shoot any base defenses that are 
   powered (i.e. Prism Tower and Tesla Coil).  However, the Floating Disc 
   will not auto target and shoot any base defenses that are not powered 
   (i.e. Pillbox and Sentry Gun).

-  Psychic Dominator permanently "captures" its victims rather than just 
   mind controls them for a short duration.  Once a unit has been psychic 
   dominated (purple halo on the unit), it can never be mind controlled again.

-  Yuri Prime and Yuri Clone's psychic blast do not harm friendly units.

-  Cloning Vats allow the player to make a second Hero unit (Tanya, Boris, 
   and Yuri Prime).


Multiplay:

-  In the Westwood Online Quick Match and Quick Co-op games, the Super 
   Weapons setting is always on, and the Crates setting is always to off.

-  In Team Alliance game mode, you must set your teams at the start.  Once 
   the battle has started, you are not allowed to switch alliance.

-  In Land Rush game mode, the Yuri player begins with a few Attack Dogs 
   among his starting units.

-  In Skirmish: Battle mode, all AI players start out on the same team fighting 
   against the human player.



Other:

-  Known problems with the Cirrus Logic 5464 video card:
-  Systems with this device may experience the following problems: low 
   frame rate, slow movie playback, and audio distortion.

-  Known problems with USB sound devices:
-  There seems to be some sort of conflict with USB sound devices.  If 
   using these devices, the game may load with no audio.  Examples of 
   such devices: the Altec Lansing ADA70 USB Speakers, Microsoft 
   Digital Sound System 80 USB.

-  Known problems with Ensoniq SoundScape and OPTI 82C 931:
-  Systems with this device may experience the following problems: 
   some random audio stuttering and popping in game and movies.

-  Information from the previous Readme files still applies.  Please review 
   the archive section below for additional information.




README ARCHIVE SECTION



Command & Conquer: Red Alert 2™

LATE BREAKING NEWS FROM THE FRONT

Copyright 2000 Electronic Arts Inc. All rights reserved.
Westwood StudiosTM is an Electronic ArtsTM brand.

Patch 1.006

May 25th, 2001

For latest news and updates visit WWW.WESTWOOD.COM


-----------------------------------TOP SECRET----------------------------------

Commander:

Thanks for your continued participation in the war effort. We have been able to 
make some modifications to your tactical display that should improve your 
experiences on the battlefield.

Good Luck.

--President Michael Dugan

--------------------------------------------------------------------------------


GENERAL CHANGES 


Fixes:
-  Chrono IFV no longer loses its target when selecting a target further than 
   his firing range. Now it moves within attack range and fires without losing 
   focus at any moment.
-  Modified official maps are not transferred over Internet games. 
-  If a player disconnects 3 times in one game for durations more than 25 
   seconds each, the game will finish and be awarded to the non-
   disconnector at the 3rd time.  
-  If walls or other buildings block the Soviet Barracks exit, no unit is built 
   even if the user has a Cloning Vat. The cost is refunded to the player. 
-  No other infantry units other than those with explosives can blow up 
   buildings when joining to a Tanya command waypoint.


WESTWOOD ONLINE CHANGES OR FEATURE ADDITIONS

New Features
-  NAT (Network Address Translation) and Firewall support (Notice: See 
   Firewall & NAT Support later on this document)

Fixes
-  In 4 player Internet games,  Red Alert 2TM now behaves correctly and 
   continues the match with the remaining players when the host loses 
   connection.
-  The game now behaves correctly by continuing 4 player Internet games 
   when the host gets disconnected from his ISP but is able to reconnect in 
   time.
-  In-game chat,  whenever the user types a message longer than a screen 
   width the text is transmitted and displayed properly.



FIREWALL AND NAT SUPPORT

 Red Alert 2TM now automatically supports firewalls and network address 
translating (NAT) while playing on Westwood Online.

Note: in this document the term "firewall" is used to refer to both firewall and 
"network address translation" products.

The following hardware/software was used in testing:

Hardware:
Linksys BEFSR11 / BEFSR14
Netgear RT311 / RT314
DLink DI-701 / DI-702
SonicWall Tele / Soho2

Software:
Windows 98 ICS (Internet Connection Sharing)
Sygate Home Networking 4.0
NAT32 Plus 1.4 (build 1-16-01)

Even if your firewall was not listed, it is likely that it will work with this 
patch. Many firewalls have the same behavior.  




Automatic Firewall/NAT support

Red Alert 2TMnow automatically supports the above firewalls out of the box, 
with no need to configure esoteric settings on the firewalls, such as port 
forwarding, triggers, static mapping or any of the other complicated settings
that might otherwise be needed.

Support is complete and transparent, including the following features:

1.  Supports hosting or joining any game when behind a firewall.
2.  Supports multiple players behind the same firewall; if you have more than 
    one system on a home LAN sharing a cable modem, DSL or other 
    connection you can now play against each other or against other players 
    on the  Internet.

Now when a game is launched on Westwood Online, you will see a "Connecting 
To Other Players" dialogue box.  Here you will be able to see your connectivity 
to the other players in the game.  If any player cannot establish a connection 
with another, the game will not launch.  A message will appear explaining who is 
having difficulty connecting.

It is necessary on some firewalls to wait for packets to be received from other 
players before trying to connect.  If your firewall has this behavior, you will 
need to enable "Send Delay" in the network options.  From the main menu, select 
"Options" then "Network".  Using this setting may cause connection problems 
with other players if used unnecessarily.  Please refer to your firewall 
documentation to see how your firewall operates. (note: Netgear firewalls model 
numbers RT311 & RT314 were found to require this setting during our testing)

Note to firewall manufacturers: if your firewall products are not among the 
tested firewalls we'd love to hear from you! Contact  gameresearch@westwood.com 
in Westwood Studios   


Manual Firewall/NAT support

In addition to the automatic firewall support features listed above, we have 
included an advanced setting for advanced users that can be used if all else 
fails. 
From the main menu, select "Options" then "Network". Under the "Internet 
Firewall Settings" section you'll see a "port number" option, which can be used 
to instruct  Red Alert 2TMto always use the port specified here. You should use a 
port number between 1024 and 65535. Every computer that you want to play the 
game on should be given a different port number if they are all behind the same 
firewall. To return to the automatic mode, remove the port number from 
the "port number" edit box.

If you specify a port for Red Alert 2TM to use then you will have to manually 
configure your firewall with static IP and port forwarding to route packets to 
the correct computer. Each firewalls configuration method is different so consult 
your firewalls documentation for instructions on how to do this. You will 
probably have to assign a static IP to each computer connecting to the firewall 
otherwise the static forwarding rules may not work after restarting a computer 
or firewall.


Dual Network Cards in Windows 98

A Windows 98 client can only have one gateway at a time. This means that if you 
are running  Red Alert 2TM in a Windows 98 machine that has 2 or more   network 
cards you will need to get sure that the traffic is going through the right one. 
The best way to do this is disabling all network cards except the one who 
gives you the connectivity to the Internet/LAN. Otherwise you can have 
connectivity problems when running Red Alert 2TM. 


FINALALERT 2™ SUPORT AND TIPS

FinalAlert 2TM is a mission editor for Red Alert 2TM.  It can be downloaded from 
www.westwood.com free of charge.  Westwood Studios and the original 
FinalAlert developer have been hard at work adding and improving functionality.  
Here are some of the items we've been working on.

-  Framework mode is now included.

-  Allows raising and lowering of tile placement heights.

-  Randomizes land tiles within the editor to improve open area aesthetics in 
   the map.  

-  Fixes bugs for raising/lowering terrain.  FinalAlert 2™ used to create map 
   holes that are very difficult to detect and fix.  Framework mode helps with 
   this a great deal also.

-  Includes an indication of current terrain height.
	
-  Includes an indication of current ore/gem count on map.
	
-  Includes Uninstall.
	
-  Increased time allowed on Westwood Online to transfer maps between 
   players.  Now up to 3 minutes.  
	
-  Only allows FinalAlert 2 ™ map sharing in non-tourney games.
	
-  Allows sharing of map names.

-  Includes random tree placement tool.

-  Optimizes the FinalAlert 2 ™ map load times, especially when there are 
   lots of custom maps in the game folder.

-  Red Alert 2TM will not add starting spots to a FinalAlert 2 ™ map if it has 2 
   or more predefined starting spots.

-  Red Alert 2TM now can now use maps created with FinalAlert 2 ™ in all 
   game modes.

-  Allows map names to appear when using FinalAlert 2 ™ (User created) 
   maps.

Please note:  When a custom made map is transferred to a guest player, it will 
not become available in the map listing until Red Alert 2TM is restarted.  
Therefore, if more than one game is going to be set on a custom map, it is 
recommended that the guest(s) quit the game after the first match (once the map 
has been transferred).  Otherwise the map will be transferred every time a new 
game is started.




Command & Conquer™: Red Alert 2™

LATE BREAKING NEWS FROM THE FRONT

Copyright 2000 Electronic Arts Inc. All rights reserved.
Westwood Studios™ is an Electronic Arts™ brand.


September 23, 2000

For latest news and updates visit WWW.WESTWOOD.COM


 - - TOP SECRET - -	

Commander:

Thank you, for joining up. Your service will not go unrecognized. Please take 
care to read the following bulletin from Command Headquarters so that you are 
fully briefed on the current situation. Due to battlefield conditions, certain 
information must be kept classified until you are ready for action.

Good Luck.

--President Michael Dugan


1.	WINDOWS 95/98/NT/Millenium

1.1.	Microsoft DirectX
1.2.	Microsoft Office Toolbar
1.3.	Windows NT 4.0
1.4.	Windows ME 

2.	TROUBLE SHOOTING

2.1.	Known Video Card Issues
2.2.	Known Sound Card Issues
2.3.	Known Direct X Issues
2.4.	Gateway Computer Users
2.5.	Virtual Memory Settings
2.6.	Known RealPlayer Issues
2.7.	AutoPlay
2.8.	16 bit CD-ROM drivers
2.9.	CD-Changers and Multi-Drivers
2.10.	Choppy movie performance
2.11.	Power Saving Mode
2.12.	Periodic Slowdown
2.13.	Game Updates and Patches
2.14.	Connection Speed Slider
2.15.	Dual Network Cards and IPX Issues:
2.16.	Firewall Issues
2.17.	Network Address Translation (NAT) Games:

3.	GAMEPLAY INFO & UPDATES

3.1.	Engineers
3.2.	Rankings for Ladders and Tournaments over Westwood Online
3.3.	Quick Match over Westwood Online


1.	WINDOWS 95/98/NT/Millenium

	1.1. Microsoft DirectX:

Command & Conquer: Red Alert 2 is a Microsoft DirectX application. 
Version 7.0 of Microsoft DirectX is included on the CD and you have the 
option to install it when Command & Conquer: Red Alert 2 is installed.

Under some early versions of Windows 95, DirectX 7.0 cannot be installed 
directly from the Command & Conquer: Red Alert 2 installer. If this occurs, 
please run DXSetup.exe located on the CD in the DXSetup folder.
 
All Microsoft DirectX drivers are located in the DXSetup folder off of the 
root of the CD. To reinstall the Microsoft DirectX drivers go into the 
DXSetup folder and run DXSetup.exe. You can explore the CD by 
choosing the "Explore the CD" option in the AutoPlay title screen. If you 
have difficulty running Windows 95/98 after these new Microsoft DirectX 
drivers have been installed, please contact your local Microsoft subsidiary, 
or write:

	Microsoft Customer Sales and Service,
		One Microsoft Way,
	Redmond, WA 98052-6399, USA

		USA telephone: 1-800-426-9400
	International telephone: ++1-206-882-8080

	1.2. Microsoft Office Toolbar:

If you make use of this feature of Microsoft Office and it appears over the 
game screen when playing Command & Conquer: Red Alert 2 you will 
have to disable the Office Toolbar before playing.

	1.3. Windows NT 4.0:

Command & Conquer: Red Alert 2 requires Service Pack 3 or later 
versions to be installed in order to work with Windows NT 4.0. Please 
contact your computer manufacturer if you need to get Service Pack 3.

1.4. Windows ME:

Windows ME DirectX appears to have hardware conflicts with some 2mb 
video cards. The cards may work well with Windows ME itself, and even 
other games, but with Red Alert 2 you may experience black screen 
lockups when loading the game. The problem may be corrected by 
updating the video card driver to Windows ME compatible drivers, 
updating your version of DirectX, or upgrading to a 4mb card or higher.


2.	TROUBLE SHOOTING

	2.1. Known Video Card Issues:

Video monitor settings may need to be adjusted after installing the 
Microsoft DirectX video drivers. If you screen distorts, or is shifted 
horizontally or vertically, you can return it to normal by adjusting the 
controls on your monitor. 

Most video display problems can be corrected by installing the latest 
drivers for your particular card. Please consult your video card 
documentation for details on how to get the latest drivers for your card. 

If you are using the Microsoft Theme Pack and have selected a custom 
cursor, video corruption can occur. For best results, please use default 
cursors while playing Command & Conquer: Red Alert 2.

Users with integrated Intel 3D graphic cards (2MB AGP) may experience 
refresh problems at high resolutions (above 640x480). In order to fix this 
problem, modify the [VIDEO] section of the RA2.INI file located in the RA2 
root directory to include: 

VideoBackBuffer=no

(This also includes any users with low end video cards, experiencing any 
trails or refresh problems at any resolution)

2.2. Known Sound Card Issues:

Old SoundBlaster AWE 64 and AWE 32 sound card drivers can cause 
skipping and repeating sound that may cause your computer to run 
Command & Conquer: Red Alert 2 much slower than normal. If you have 
one of these sound cards and are experiencing these symptoms, please 
contact your card manufacturer for latest drivers.

Audio may stutter on certain systems running Windows NT. To correct this 
problem you must install the latest audio driver for your sound card.

Most sound card problems can be corrected by installing the latest drivers 
for your particular card. Please consult your sound card documentation for 
details on how to get the latest drivers.

If you are using USB speakers, do not turn off the speakers during 
gameplay. Doing so may cause your system to become unstable and 
even crash.

2.3. Known DirectX Issues:

If another application is using the sound card while trying to install or run 
the game, a "DXSound Error" will appear. If this error occurs, please close 
all applications and run the install or game again.

2.4. Gateway Computer Users:

If you are using a Gateway computer with "Gateway GoBack" software by 
WildFile running in the background, you may experience lockups in Red 
Alert 2. GoBack is loaded in the Windows system tray (by the clock) and 
represented by two yellow arrows. To close out GoBack, right click on the 
double yellow arrows in the system tray, and select close. It is 
recommended that you close all programs running in the background 
before starting Red Alert 2.

	2.5. Virtual Memory Settings:

Command & Conquer: Red Alert 2 may need to use more RAM than is 
present on your system. Windows 95/98 automatically takes care of this 
by using what is known as "Virtual Memory" - which uses space on your 
hard disk to simulate the memory it needs and swaps data back and forth 
from your hard disk as required. Windows 95/98 allows you to manually 
set the amount of hard drive space it uses for Virtual Memory: WE 
HIGHLY RECOMMEND THAT YOU DO NOT DO THIS! To let Windows 
95/98 manage the Virtual Memory, go to the Windows 95/98 start menu, 
select 'settings\control panel', then double-click 'system', click 
'performance\file\system\virtual memory' and then select 'Let Windows 
manage my virtual memory settings (recommended).'

2.6. Known RealPlayer Issues:

RealPlayer seems to have a conflict with the movie player used in Red 
Alert 2. With RealPlayer's "Start Center" feature enabled (which seems to 
keep RealPlayer resident in some form) we have found stability issues 
when exiting Red Alert 2 as it goes to the desktop.

	2.7. AutoPlay:

If your CD does not AutoPlay when inserted in the drive, you may have 
this feature disabled. To Enable AutoPlay, right click on 'My Computer' 
and select 'Properties' then 'Device Manager'. Select your CD-ROM drive 
and click 'Properties'. Select 'Settings' and check the 'Auto insert 
notification' box.

	2.8. 16 bit CD-ROM drivers:

Command & Conquer: Red Alert 2 may fail to start if there is a 16 bit CD-
ROM driver loaded from the AUTOEXEC.BAT or CONFIG.SYS. If you 
have references to MSCDEX or equivalent drivers then try removing them 
from your autoexec.bat and config.sys files. Windows 95/98 does not 
generally need these drivers to work and in most cases will actually 
perform better without them.

	2.9. CD-Changers and Multi-Drivers:

Command & Conquer: Red Alert 2 does not support multiple CD-ROM 
drives or CD-changers and assumes that you only have one CD-ROM 
drive. If you have more than one CD-ROM drive, you should insert the 
Command & Conquer: Red Alert 2 CD in the first CD drive letter. For 
example, if you have CD drives E:, F: and G:, your Command & Conquer: 
Red Alert 2 CD should be inserted into the E: drive.

	2.10. Choppy movie performance:

If you find that the movie performance is choppy or jerky, try reducing the 
Windows 95/98 CD caching by going to the Start/Settings/Control Panel 
and double-clicking the System applet. In the System Properties dialog, 
click the Performance tab and then click the File System button. From the 
File System Properties dialog, click the CD-ROM tab and note the 
Supplemental Cache Size setting (so that you can reset the cache size if 
need be). Now set the Supplemental Cache Size to Small. This should 
have a marked effect on movie performance.

You can also try adjusting your detail settings in the Options Menu. Low 
Detail will remove effects like water wakes behind ships, smoke and effect 
lines. Red Alert 2 will also dynamically remove animations in certain 
situations on low spec machines to ensure a high quality game 
performance.

	2.11. Power Saving Modes:

It is possible that your computer loses connection to your ISP due to long 
periods of inactivity. Sometimes this is caused by the sleep mode in your 
"Power Saving" options. This can cause problems during game play or 
when connected to Westwood Online. To avoid any problems please 
disable your screen saver or power-saving modes when running the 
game.
	
2.12. Periodic Slowdowns:

If periodic slowdowns occur while playing Command & Conquer: Red Alert 
2 and the CD is not being accessed please insure that there are no other 
applications running during your game session. This includes anti-virus 
software.

2.13. Game Updates and Patches:
		
Command & Conquer: Red Alert 2 contains an auto-updating feature. 
Updated versions of the game will be announced to you when playing 
Command & Conquer: Red Alert 2 on Westwood Online. When an 
updated version of the game is available you will be able to receive it and 
automatically have it installed, if you wish. If you do not intend to play 
Command & Conquer: Red Alert 2 on Westwood Online then please 
check www.westwood.com for update information.

2.14. Connection Speed Slider:

Red Alert 2 has a game-latency tolerance setting in the Game Options 
screen that allows players to increase the tolerance of network latency on 
laggy connections for Internet gaming. To adjust, move the slider to the 
appropriate setting. For example, if you are connecting over a modem, the 
best setting for you would be "Normal" or "Poor". If you are connecting 
over a broadband connection (Cable Modem or DSL), move the slider to 
"Fast". This attempts to match your system with your connection for peak 
performance. Moving the slider from Poor or Normal to Fast can have an 
adverse effect on game performance.

2.15. Dual Network Cards and IPX Issues: 

If you have two network cards in your computer and both have the IPX 
protocol bound to them, you can use the "Network Options" to choose the 
card which you'd like to use. Note: on some Windows 95 and 98 systems 
and in some configurations, Red Alert 2 can't see your second network 
card. A workaround to this problem is to disable your primary card in 
Windows device manager and reboot. Red Alert 2 should successfully see 
and utilize your second network card. Please refer to your Windows 
documentation for more information on how to disable your primary 
network card.

2.16.  Firewall Issues:

If you are playing Red Alert 2 behind a firewall and wish to host a game, 
you must open the following ports:  Port 1234, 1235, 1236, 1237.  These 
ports use the UDP protocol.  If you do not know how to configure your 
firewall consult your firewall documentation or contact your system 
administrator or Internet Provider.

2.17.  Network Address Translation (NAT) Games:

If your network is using Network Address Translation, two or more users 
behind the NAT'd firewall will be unable to play in the same game.  They 
will, however, be able to play in different games.






3.	GAMEPLAY INFO & UPDATES

	3.1. Engineers:

Engineers (and Engineers in IFVs) can be placed in Guard mode, like any 
other unit. When in guard mode, engineers automatically heal any nearby 
player owned structures that are damaged into the red or capture nearby 
enemy buildings.


3.2.	 Rankings for Ladders and Tournaments over Westwood 
Online:

Westwood offers many opportunities for players to test their mettle against 
the best players in the world. Check out Westwood.com for the latest 
breaking news. Rankings for Ladders and Tournaments in Red Alert to are 
defaulted to "Short Games"

3.3.	 Quick Match over Westwood Online:

Red Alert 2 offers players an easy way to meet players on the battlefield. 
Simply try the "Quick Match" selection in Westwood Online. This option 
will try to match players of similar ranking, similar ping times (Internet 
connection latency to other players), location and system specs.




