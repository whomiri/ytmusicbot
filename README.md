# Telegram Music Botu / Development

Desteklenenler: YouTube/SoundCloud/Mixcloud

## Emrler 🛠
- `/ping` - Botun ping deyerini olcer / Emrler Arttirilir

## HEROKU DESTEKLENIR 

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/whomiri/ytmusicbot)

## El ile deploy

```
# Telegram API Key
# alin: https://my.telegram.org/apps
export API_ID="1234567"
export API_HASH="0123456789abcdef0123456789abcdef"

# Telegram Bot Token
# get from https://t.me/BotFather
export BOT_TOKEN="123456:ABC-DEF1234ghIkl-zyx57W2v1u123ew11"

# DAXIL EDIN / USERNAME VE GRUP ID,
# BOSLUQ ILE AYRILMALIDIRLAR KI DUZGUN SPLIT EDILE BILSIN
export MUSIC_CHATS="-100123456789 username"

# install ffmpeg
apt install ffmpeg

virtualenv venv
venv/bin/pip install -U -r requirements.txt
venv/bin/python music.py
```
