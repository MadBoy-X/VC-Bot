# Tesla MusicBot [ Pytgcalls ]

Telegram VoiceChat Bot To Play Music With Pytgcalls From Various Sources In Your Group.


https://user-images.githubusercontent.com/73926361/126453534-7712ed8b-5dfe-48c2-9178-472981a41967.mp4


### Account requirements
- A Telegram account to use as the music bot, **You cannot use regular bot accounts, as they cannot join voice chats. *It must be a user account.***
- API_ID and API_HASH for that account.
- The account must be an admin of the chat, with _Manage Voice Chats_ and _Delete Messages_ permissions.

---
---
---

## Deploying

* Heroku:

#### Generate String session [IMPORTANT]
- Get it by running [This Repl](https://replit.com/@madboy482/Pyrogram-Session) 

or 

- Run this file [sessiongen.py](https://raw.githubusercontent.com/MadBoy-X/MusicBot/MusicBot/sessiongen.py) locally.

Then you will get a session string, copy it, then press heroku deploy button.

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?button-url=https%3A%2F%2Fgithub.com%2FMadBoy-X%2FMusicBot&template=https%3A%2F%2Fgithub.com%2FMadBoy-X%2FMusicBot)

Now use these [Commands](https://github.com/MadBoy-X/MusicBot/blob/MusicBot/README.md#commands), to play music.

---

* Local machine/VPS:
  
`git clone https://github.com/MadBoy-X/MusicBot`   
`pip install -r requirements.txt`   
`apt-get install ffmpeg`   
`touch .env && nano .env`, fill in the vars as in [.env.sample](./.env.sample)   
`python bot.py`  

---
---
---

## Commands:   
- `{PREFIX}on` - Check if the (user)bot is online. [DEFAULT »» `!on`]
- `{PREFIX}help` - Help message. [DEFAULT »» `!help`]
- `{PREFIX}stream` - Either give a youtube URL or reply to a telegram file to play it. [DEFAULT »» `!stream`]  
- `{PREFIX}pause` - Pause the stream. [DEFAULT »» `!pause`]
- `{PREFIX}resume` - Yes, resume. [DEFAULT »» `!resume`]  

---
---
---

## Note
- If you want any help you can ask [Here](https://t.me/TeslaRobo_Chat)

---
---
---

# Credits 📍
## • MADBOY   »»  <a href="https://github.com/madboy482" alt="MadBoy"> <img src="https://img.shields.io/badge/MADBOY-30302f?logo=github" /></a> {DEV}
## • PRANAV   »»  <a href="https://github.com/Pranav18262" alt="Pranav"> <img src="https://img.shields.io/badge/PRANAV-625D5D?logo=github" /></a> {DEV}

---
---

## Special Thanks to :
- [VC_Bot](https://github.com/xditya/VCBot)
- [pytgcalls](https://github.com/pytgcalls/pytgcalls)   
- [pytgcalls-wrapper](https://github.com/callsmusic/pytgcalls-wrapper)   
- [Pyrogram](https://github.com/pyrogram/pyrogram) 
