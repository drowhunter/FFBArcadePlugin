***FFB Arcade Plugin***

Version 1.7c

Brought to you by Boomslangnz, Ducon2016, Spazzy & pinkimo.

This is a plugin to provide Force Feedback and Rumble to various arcade games.


***REQUIREMENTS***

- Requires Visual Runtime Files https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/

- GUI Requires Visual Runtime 2019 and has to be in same folder with metroframework.dll & SDL2.dll


***HOW TO USE***

Launch FFBPluginGUI.exe & Go to Setup Help Section. 

For more advanced information read below


***Advanced information***

-Alternative FFB is for certain wheels such as Thrustmaster wheels or PWM2M2 etc where rotation always goes only 1 direction, enable this to fix if your wheel does this

-MinForce is the lowest force the wheel strength will be, if AlternativeFFB is enabled, use AlternativeFFB MinForce instead.

-MaxForce is the maximum force the wheel strength will be, if AlternativeFFB is enabled, use AlternativeFFB MaxForce instead.

-Feedback length is how long the force feedback effect will last for

-Enable Rumble is to enable or disable Rumble for controllers

-Reverse Rumble is to swap the motors around if it rumbles opposite to how you want

-PowerMode is to raise the strength of low values to increase strength feel on certain games

-Some games such as Road Fighters 3D have input support. Go to Input section and enable Input Support and set up axis/buttons


*** OUTPUT SUPPORT ***

(For MAME)

- Create a ini file on root of MAME folder called Mame.ini and place inside it and save
#
# OSD OUTPUT OPTIONS
#
output                    windows

- Ensure either MAME32.dll or MAME64.dll is with FFB Plugin files in MAME folder depending on 32bit or 64bit MAME

(For SUPERMODEL EMULATOR)

- If you wish to use FFB Plugin over Supermodel's FFB then disable Supermodel's FFB.

- When you launch game, ensure you have command -outputs=win for FFB Plugin to recieve Output Values etc

- Ensure either MAME32.dll or MAME64.dll is with FFB Plugin files in Supermodel folder depending on 32bit or 64bit Supermodel


***CREDITS***

- Reaver from Teknoparrot . Huge thanks to Reaver for supplying code necessary for some games & general force feedback,
extremely generous.

- Jackchen for his Daytona Championship USA FFB work at beginning of year.

- seam for always testing and helping

- Howard Castro for help on game FFB code. Always helpful and a big reason this plugin was ever made

- Mame team

- SailorSat for finding the offsets etc required for Daytona USA Multiplayer AI hack

- Nuexzz for finding offset required for Daytona Panoramic Force Hack

- POOTERMAN for making logo on GUI

- headkaze for making MAMEInterOp SDK

- Everyone who helps and gives back to this awesome scene. Thanks for everything!


***SUPPORTED GAMES***

-Alien 3
-Alien Extermination
-Afterburner II
-Afterburner Climax
-Batman (2013)
-Beast Busters
-Battle Gear 4 Tuned (Japan version v2.07)
-California Speed
-Chase Bombers
-ChaseHQ 2
-Cisco Heat
-Crusn'USA
-Crusn' World
-Daytona USA
-Daytona USA 2 - Power Edition
-Daytona USA 2 - Battle on the Edge
-Daytona Championship USA 
-Dirt Devils
-Dirty Drivin
-Emergency Call Ambulance
-F-1 Grand Prix Star
-F-1 Grand Prix Star II
-Ford Racing
-Ghoul Panic
-Golden Gun
-GRID
-GTI Club Supermini Festa
-Gun Buster
-House of the dead 4
-Hyperdrive
-Indy 500
-Initial D Zero
-Initial D 4
-Initial D 4 Japan
-Initial D 5
-Initial D 6
-Initial D 7
-Initial D 8
-KO Drive
-Laser Ghost
-LeMans 24
-Let's Go Island
-Let's Go Island 3D
-Machstorm
-Mario Kart GP DX
-Mechanized Attack
-Nascar Racing
-OffRoad Challenge
-Operation Thunderbolt
-Operation Wolf
-Outrun
-Outrun 2 Special Tours Deluxe
-Outrunners
-Over Rev
-Point Blank 2
-Pokken Tournament
-Power Drift
-Rail Chase
-Rambo
-Rave Racer TURN ON FEEDBACK STEERING IN GAME SETTINGS OR YOU WILL NOT RECIEVE FORCE FEEDBACK!
(will ONLY work on either Mame Binary 32 or 64 bit or MameUI64 for Mame version 0.199 or 0.206 on OLDMame Plugin)
-Revolution X
-Road Fighters 3D
-San Francisco Rush
-San Francisco Rush The Rock
-San Francisco Rush 2049
-Scud Race
-Scud Race Plus
-Sega Touring Car Championship
-Sega Racing Classic
-Sega Rally Championship
-Sega Rally 2
-Sega Rally 3
-Super GT 24h
-SnoCross
-Sonic & Sega All Stars Racing
-Space gun
-Terminator 2
-Transformers: Human Alliance
-Turbo Outrun
-Turkey Shoot
-Under Fire
-Vapor TRX
-Virtua Racing
-Wacky Races
-Wangan Midnight Maximum Tune 5
-Le Mans 24