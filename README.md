# transcript extractor

Yet another Telegram Voice Recognition bot but using [vosk](https://github.com/alphacep/vosk-api) and supports 20+ languages.

## Environment Variables

- `API_ID` - Get this from [my.telegram.org](https://my.telegram.org/auth).
- `API_HASH` - Get this from [my.telegram.org](https://my.telegram.org/auth).
- `BOT_TOKEN` - Get this from [@BotFather](https://t.me/BotFather).
- `SEND_AS` - transcript sending format (TXT or PDF).
- `LANGUAGE_CODE` - vosk supported language(code), see supported languages [here](https://github.com/alphacep/vosk-api).
- `MODEL_DOWNLOAD_URL` - language model download link. ( see available models [here](https://alphacephei.com/vosk/models) )


## Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/samadii/Transcript-Extractor-Bot)


## Local Deploying

1. Make sure you have [FFmpeg](www.ffmpeg.org).

2. Clone the repo
   ```
   git clone https://github.com/samadii/Transcript-Extractor-Bot
   ```

3. Enter the directory
   ```
   cd Transcript-Extractor-Bot
   ```
  
4. Install all requirements using pip.
   ```
   pip3 install -r requirements.txt
   ```

5. Run the file
   ```
   python3 main.py
   ```

### Devs: 
- [@samadii](https://github.com/samadii)
