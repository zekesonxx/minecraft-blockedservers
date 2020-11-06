# Minecraft blockedservers Scraper
Minecraft pulls down a list of blocked servers from the Mojang API before connecting to a server, and checks the sha1 hash of the server you're connecting to against the blockedservers list.

This repository checks the blockedservers list every 6 hours, and updates it if any of it changes.

* Source: https://sessionserver.mojang.com/blockedservers
* More Info: https://wiki.vg/Mojang_API#Blocked_Servers
* Inspired By: https://simonwillison.net/2020/Oct/9/git-scraping/
