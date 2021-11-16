# What this does
https://www.gog.com/game/eye_divine_cybermancy

The Good Old Games release of E.Y.E Divine Cybermancy disabled the Online and Lan multiplayer options of the game. The Online mode uses steams servers, however Lan connections work fine without steam.

All of the multiplayer options still exist in the game, the menu buttons for them just got hidden or disabled. 

The modified files in this repo restore the hidden options in the create server menu dialog, and revert the menu button's name from 'SECONDARY MISSIONS [SOLO]' to 'Create Server'

The 'SECONDARY MISSIONS [SOLO]' label is only renamed for english localization

<hr>

Original GoG version Menu:

![image](https://user-images.githubusercontent.com/2367440/141922617-aa359770-3f2f-4509-b647-b10ac5b59954.png)

Updated Menu:

![image](https://user-images.githubusercontent.com/2367440/141922662-2406c33d-0a00-4859-a91f-850d6eae2e9d.png)


# Installation

Download or clone this repo to your computer

![image](https://user-images.githubusercontent.com/2367440/141928847-1a9e4061-f6f6-4ec6-b8aa-8facecced34c.png)


Copy the EYE folder into your E.Y.E. install directory, and replace the files when prompted.


# Creating / Joining a server

When you next open the game, you should see the Create Server button with dropdowns to select gametype, as well as set Lan Only which will default to Yes.

Set your host settings as desired and hit start.

<hr>

To join a local server, open the console with '~' and enter

    connect <host-ip>

where host-ip is the local ip of the host machine (typically something like 192.168.x.x)


# TODO

I want to try and add a gui button for connecting to an IP, but I'm not sure if that will be possible with just resource file modifications

