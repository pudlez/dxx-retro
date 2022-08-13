                         __________
__________/ D2X-Rebirth /


http://www.dxx-rebirth.com


0. Introduction:
================

   D2X-Rebirth is based on a late D2X-CVS Source, coded and released by Bradley Bell and his team.
   I spend much time to improve the Sourcecode, tried to fix bugs in there and added some improvements.
   It is the goal of DXX-Rebirth to keep these games alive and the result is a very stable version of
   the Descent ][ port - called D2X-Rebirth.
   I hope you enjoy the game as you did when you played it the first time.
   If you have something to say about my release, feel free to contact me at zico [at] dxx-rebirth [dot] com


1. Features:
============

   DXX-Rebirth has every little feature you already may know from the DOS Version of Descent and much more.

   For example:
   * Plays Descent and Descent 2 and all their AddOns and third-party levels.
   * DXX-Rebirth runs on your favourite Operating System. We officially support Linux (and other *NIX), Mac OS (9/X) and Windows (2000, XP, Vista, 7). Still the code can be compiled on many other systems as well.
   * OpenGL provides a fast and smooth rendering - even on low-end systems.
   * Optionally you can enbale several effects like Transparency, Colored lighting, Texture Filtering, FSAA, etc.
   * Thanks to SDL, a wide palette of Joysticks are supported. Also you can use more Joysticks, buttons and axes than you can ever operate in your state of evolution.
   * If you prefer steering your Pyro with a mouse, you will not have the problem that the movement becomes slow in high game speed.
   * Joystick, Keyboard and Mouse can be used simultaneously.
   * The games can display all resolutions and aspects supported by your Monitor, including an option for VSync.
   * Besides MIDI and CD-Audio (Redbook), you can play your own custom Music from your Harddrive or a separate AddOn.
   * Both games can utilize special AddOn packs to replace or expand the original game content.
   * Multiplayer via UDP protocol provides a fast and easy-to-use LAN and Online action. This includes reliable communication causing less glitches due to lost packages.
   * Multiplayer via IPX protocol lets you play against players still using the MS-DOS version of the game.
   * The ingame Demo-recording system has been improved. Demos are less glitchy and smaller while still still being backwards-compatible to earlier versions of the games.
   * Higher game speed will not cause glitches such as unacceptable fast homing projectiles, incredible high damage caused by several collisions or Fusion cannon, etc.
   * Player files, Savegames, Demos and Missions from DOS-Versions of the games can freely be used in DXX-Rebirth and vice versa.
   * Even more ...


2 Installation:
===============

2.1 Needed files:
=================

   Since D2X-Rebirth is a Sourceport of the Descent2-Engine you will need the Game-Content data files to run
   the game. You don't own the full game, yet?
   Just visit GOOD OLD GAMES via:
   http://www.gog.com/en/gamecard/descent_1_descent_2/pp/fc074d501302eb2b93e2554793fcaf50b3bf7291
   and download it for a very low price! DRM-FREE!

   Following files are needed to run the game:
   descent2.ham
   descent2.hog
   descent2.s11
   descent2.s22
   alien1.pig
   alien2.pig
   fire.pig
   groupa.pig
   ice.pig
   water.pig
   intro-h.mvl and/or intro-l.mvl
   other-h.mvl and/or other-l.mvl
   robots-h.mvl and/or robots-l.mvl

   With the PC version, these files - except the Movies (*.mvl) - are archived in the file
   'descent2.sow' on the Descent2 CD-Rom.
   This is an ARJ-archive and can be extracted with an adapted archiver like ‘unarj’ or by installing the
   game on a Windows/DOS system.

   Of course you can also use the Interactive Demo game content with D2X-Rebirth which you can find here:
   http://www.dxx-rebirth.com/game-content/

2.2 Where to put these files:
=============================

    Copy the files described above to the D2X-Rebirth-directory - where the d2x-rebirth executable is located.

2.3 Optional files:
===================

   D2X-Rebirth is expandable. You can add additional content to the game.

   Vertigo series AddOn
   --------------------
   Can be added by copying the files
   d2x-h.mvl and/or d2x-l.mvl, hoard.ham to your game-directory/Sharepath and
   d2x.hog, d2x.mn2 to 'missions/' subdirectory.
   All these files should be located on the ‘Vertigo Series’ CD-Rom

   Missions:
   ---------
   Those can be found on several websites. Add them to the game by copying them to subdirectory
   ‘missions/’. They can also go in subdirectories of 'missions/', unlike with the original version.
   A good place to find additional mission might be the Descent mission Database:
   http://www.dxx-rebirth.com/descent-mission-database/

   Custom Music (MP3, OGG, FLAC, etc.):
   -----------------------------------
   Custom Music can be played via the CUSTOM MUSIC options by specifying it in the Sound Options menu.
   Please note that all custom music has to be in 44Khz format. Supported formats depend on the capabilities of SDL_mixer.

   AddOn Packs:
   ------------
   Custom AddOn packs will expand the game in many differnt ways. These are usually provided as ZIP or 7Z and can easily
   be installed by putting them to where your game content resides (OS-dependent - see above).
   NO EXTRACTION OR ADDITIONAL CONFIGURATION NEEDED.
   You can find all official AddOns here:
   http://www.dxx-rebirth.com/addons/

2.4 Run the game:
=================

   Simply double-click the d2x-rebirth executable.
   Also check out d2x.ini for setting up additional command-line options you may like.


3. Multiplayer:
===============

   D2X-Rebirth supports Multiplayer over (obsoleted) IPX and UDP/IP.
   Please note that UDP/IP generally supports more features of D2X-Rebirth and uses Packet Loss Prevention while
   IPX is mainly meant to play together with non-D2X-Rebirth games.
   Using UDP/IP works over LAN and Internet. By default, each game communicates over UDP-Port 42424. This can be
   changed via the menus while creating a game and manually join a game, command-line argument or D2X.INI. To
   successfully host a game online, make sure UDP-Port 42424 (or otherwise if specified correctly) is opened on
   your Router/Firewall. Clients do not need to open any ports.
   The game also supports IPv6 if built in while compiling and should be backwards compatible to IPv4 builds
   as good as possible.


4. Legal stuff:
===============

   See COPYING.txt


5. Contact:
===========

   http://www.dxx-rebirth.com/
   zico [at] dxx-rebirth [dot] com
