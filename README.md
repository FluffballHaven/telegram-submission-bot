# telegram-submission-bot

## Prepare
* Install Python and run `pip install python-telegram-bot==11.1.0`
* Create 1 Bot, 1 Group and 1 Public Channel

## Configuration
Open `config.json` and configure
```
{
    "Admin": 0, //Administrator user ID (usually 8-9 digits)
    "Token": "", //Bot's Token
    "Group_ID": 0, //No need to fill in
    "Publish_Channel_ID": "" //Channel ID (e.g. @channel)
}
```
After running the bot, enter `/setgroup` in the review group

## Run
```
python main.py
```

## Use
### Contribution
![Screenshot](https://github.com/Netrvin/telegram-submission-bot/raw/master/Readme_Img/Screenshot1.jpg)

Send the message to the robot, choose whether to keep the source of the message, and then complete the submission (if you forward another person’s message, you cannot choose not to keep the source of the message)
Acceptable submission types:
* Text
* Picture
* Audio/Voice
* Video
* File

### Review
![Screenshot](https://github.com/Netrvin/telegram-submission-bot/raw/master/Readme_Img/Screenshot2.jpg)

All users in the review group, click to adopt to complete the review
Reply to the manuscript itself (not the manuscript details) in the group, and comment on it while using it

## Todo (Features)
-[x] Comment manuscript
-[x] Forwarding others’ messages is forbidden to be anonymous and avoid copyright issues
-[x] Notify contributors after adopting the manuscript
-[x] Add contributor/reviewer internal link to manuscript details
-[x] Publish manuscript anonymously
-[] Contribution statistics
- [ ] multi-language
