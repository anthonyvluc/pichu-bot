---
layout: default
title: PichuBot - A Discord Bot
---


# PROJECT GOALS

![PichuBot Image](pichubot.png)

The [Asian American Association](https://www3.nd.edu/~aaa/) community at the University of Notre Dame looks to create a welcoming environment for all of its members, those who are 0 - 100% Asian. AAA is an umbrella club of many smaller cultural student associations with a more narrowed focus. Through [Discord](https://discordapp.com/), the club hopes to provide a common platform to connect its undergraduate members, retain communication with alumni, and spread information about AAA and ND events on campus.  

In order to maintain the Discord, [PichuBot](https://github.com/anthonyvluc/PichuBot) is a Discord Bot that helps manage the AAA Discord Server. PichuBot supports the community with various commands and automation to better engage the community and support the execution of the AAA Board. Explore the server to dive into the AAA Family today!


# INSTALLATION

PichuBot currently does not support ```pip install```-ations.  

After setting up a Python3 environment, cloning the repository, and acquiring the bot token, a user can run
```cmd
./start_bot.sh
```
to deploy the bot and test features. Testing is done on the ```#test-dev``` text channel on AAA Discord.  


# CONTRIBUTING
Members of **Team PichuBot** may freely ```git clone``` the repository to then add functionality to the bot. The bot token can be received from any team leads of the project. The current team leads are: ```aluc, dluc, and mwang6```.  

Open source contributing can be done via the following steps:  
  - Fork a new repository of PichuBot
  - Create a new Discord server for testing
  - Make a personal bot token for testing
  - Test changes and make a PR onto the master branch  

Commands are called via an exclamation mark such as, `!echo "Hello, Asian American Association"`. New command can be created with the 
```python
@commands.command(pass_context=True)
```
decorator and then added to the `/commands` directory as a new file.   

The project follows PEP8 standards and every PR will be automatically tested through `pep8speaks` for valid formatting.
