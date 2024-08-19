# AI content creator

## General info

a bot made in python which basically generates automated videos according to niche which user choose.

## Technologies used

- for voice generating: elevenlabs
- for getting ideas and scripts for voiceovers: chatgpt(openai api)
- for getting stock videos for background: pexels api
- for transcribing voice over: openai whisper

## Features

- making requests directly to chatgpt to get ideas and then script for whole video
- auto gaining videos using pexels api
- generating voice-over using elevenlabs
- combining them into video using moviepy
- making transcription and subtitles using openai's faster-whisper
- karaoke styled subtitles
-Auto Upload to Youtube Using Selenium and playwright.
todo

- maybe some bugfixing

## Installation

first you need to install [imagemagick](https://www.imagemagick.org/)

```
$ cd openai-python-content-creator-main
$ pip install -r requirements.txt
$ py ./main.py
```
