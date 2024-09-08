---
title: Minecraft server manager
---
# VPN tunnel options
## [Hamachi](https://www.vpn.net/)
- 5 users limit on one channel </br>
![[minecraft-server-manager.png]]</br>
- **always** some issues 

## [Zerotier](https://www.zerotier.com/)
- limit of 100 users
- It is far more reliable and easy to manage.
- ==How to use zerotier WIP==

## [Playit.gg](https://playit.gg/)
- anyone could connect
- it was needed only on the host computer
- perfect
- ==How to use zerotier playit.gg WIP==
# Current setup
![[minecraft-server-manager 2024-09-08 11.03.31.excalidraw.png]]

## Running on the host computer
- [My fork of crafty discord bot](https://github.com/Floxicek/crafty_discord_bot) that can power off windows computer after server stops
	- [crafty controller](https://craftycontrol.com/)
- zerotier and playit (it is overkill i know)

## Running on the Rpi
https://github.com/Floxicek/remote-computer-start-discord-bot - sends the magic packet to the computer to wake it up