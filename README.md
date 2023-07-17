
### **<p align="center">Bombparty bot</p>**


<p align="center"><strong>Automated Bombparty game bot</strong><br>Win every game while AFK with this automated bot</p>

<div align="center">
  <a href="https://skillicons.dev">
   <img src="https://skillicons.dev/icons?i=python,selenium" />
  </a>
</div>



# BombParty-bot

BombParty is an online game at [jklm.fun](https://jklm.fun) where players have to provide a word that contains the given syllable before the bomb explodes. By using Selenium and several language dictionaries, this program is able to fetch data from the game, compute it, and type back an answer into the game automatically. It has been coded so that the answer is written as humanly as possible, simulating human typing and thinking.

Note: The bot misspells words from time to time. This is not a bug, it's a feature :) (We want to avoid suspicion from other players at all costs)

![game gif](https://user-images.githubusercontent.com/95043218/225719743-3de852ef-29e4-4f04-ad2c-3fb9fdd96568.gif)

Even though the game can be played in multiple languages, the bot can be configured to play Spanish and English only.

## Requirements

- Selenium: Used to automate navigator. It helps fetching syllable data, and typing the word back to the game when it has been computed.
- Navigator driver: For this project I have used Chromium's driver version 111. If your Chrome version does not match this project's driver version, I recommend [downloading the driver](https://chromedriver.chromium.org/downloads) of your current version.

## How to use

1. Download zip file and extract in the desired location
2. Execute main.py
3. Console will prompt the user to input necessary data to join online lobby
4. Relax and enjoy the show

## Known issues

- If bot fails to provide a word before the time runs out, it will crash and stop the program. Game itself and the rest of players are not affected.

## Disclaimer

This has been made with the aim of getting used to web scraping and other web automation tasks with Python. This is a cheat and may get you banned.
