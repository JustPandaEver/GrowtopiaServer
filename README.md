# Growtopia Server v1.0 ![Build Status](https://media.discordapp.net/attachments/1103007816471552050/1103007929449336836/68747470733a2f2f63692e6170707665796f722e636f6d2f6170692f70726f6a656374732f7374617475732f6769746875622f47726f77746f7069614e6f6f62732f47726f77746f706961536572766572.png)
Better/Faster Version of GrowtopiaNoobs's GrowtopiaServer Project. (**The First Growtopia Private Server with ENet**)
- This Project Is Owned By Algonix, RockiCodes is my old account.

This project has been compiled with Visual Studio 2022 and 2019 or other compilers weren't been tested.

This project has been published under GNU AFFERO GPL license, so you need to **publish the whole source code and citate the orginal authors name, even if you are using your server as service**!

# **TODO list:**
- [X] ENet Functions For Connectivity (using ENet C++ Library)
- [X] Item Serializing (support for new v15)
- [X] Readable and Easy to Use/Understand
- [X] Premium World Lock System (Used to purchase ingame goods)
- [X] Discord Webhook Code (discord_webhook.h)
- [X] World Lock Algorithm (Wl, Dl, BGL, etc)
- [ ] Tile Algorithm (Sl, Bl, Hl, Builder Lock)
- [X] Event Pool (found in event_pool.h [used for delaying actions])

If you want to support the development of this project, make sure you contribute to this repo!

# Make Sure To Check Out My Youtube Channel: (JenZip GT)
- https://www.youtube.com/channel/UCBpSmvDyThHz7obkqivKTLA

# Updates:
- WinHTTP, added winhttp.h for webhook messages using winhttp by microsoft
- Added ItemDat v15 Support
- Switched to x64, by changing enet.lib to enet64.lib and changed input directories
