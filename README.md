<h1 align="center">⚡ SP Clone ⚡<br></h1> 

<br />

<p align="center">CloneBot is a telegram bot that allows you to copy folder/team drive to team drives. One of the main advantage of this bot is that you can host it to Heroku for free.<p/>

<!-- > ## A simple bot to copy and duplicate team drives -->
<p align="center">
  <img src="https://i.imgur.com/QkxmCOp.png" />
</p>

<br />

#### ✅ Advantages
- Use server side copy
- Bypass the 750Gb a day limit thanks to Service accounts
- Duplicate team drive
- Copy public folders & files to team drives
- [Host it to heroku](https://github.com/MsGsuite/CloneBot_Heroku)

#### ❌ Drawbacks
- Does not support files upload (only copy)
- You cannot copy the data to My Drive

Note : there are hidden features, check at the source code of the bot to find them 🙃
<br/><br/>

### ⚠ You need [service accounts (sa)](https://telegra.ph/How-to-create-and-use-service-accounts-sa-03-31) to use the bot
<br/><br/>

## ⚛️ Deploying on Heroku

 [🎬 Click me for the video tutorial](https://drive.google.com/file/d/1HniSEGUOptbZmHVXuOPULnzpyBBhgw3l/view?usp=sharing)
 
1. Click on the button below :
<p><a href="https://dashboard.heroku.com/new?button-url=https%3A%2F%2Fgithub.com%2F&template=https://github.com/SpMedia23/SP-Clone-Bot/"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" alt="Deploy to Heroku" /></a></p>


2. Fill the following values : 

> gclone_para_override = leave this blank is you don't know how to use it
>
> group_ids = your telegram group ID (leave it blank if you don't want to add one). To get your group id, go to @MissRose_bot and type /id
>
> telegram_token = go to @BotFather and send /newbot to get one
>
> user_ids = Your user id (go to @MissRose_bot and type /id to get your id) - If you want to authorize multiple users, add a comma between each ID (ex: 150654065,5897065)

3. Click on Deploy app...
4. When it's over, go to : https://dashboard.heroku.com/apps/YOURAPPNAME/resources (replace YOURAPPNAME by your appname 🙃)
5. Then click on the ✏ and check $0.00 option and click on confirm.
6. Now you can start your bot !
<br/><br/>
<br/><br/>

## 📱 Run the bot on your phone using termux

--> https://telegra.ph/Clone-Bot-Termux-04-30
<br/><br/>

## 💠 Host the bot on your computer

1. Download the repo : https://github.com/MsGsuite/CloneBot/archive/refs/heads/master.zip
2. Open the config.ini file (inside the telegram_gcloner folder) and fill the following values :


> path_to_gclone =./gclone  ⚠ Don't touch this
>
> telegram_token = go to @BotFather and send /newbot to get one
>
> user_ids = -1 = Your user id (go to @MissRose_bot and type /id to get your id) - If you want to authorize multiple users, add a comma between each ID (ex: 150654065,5897065)
> 
> group_ids = your telegram group ID (leave it blank if you don't want to add one). To get your group id, go to @MissRose_bot and type /id
> 
> gclone_para_override = leave this empty if you don't know how to use it

3. Install [python](https://www.python.org/downloads/)
4. open CMD and cd to the folder containing the bot
5. run `pip install -r requirements.txt`
6. cd to the telegram_gcloner folder and run : `py telegram_gcloner.py`
7. Start your bot and you can copy your data !
<br/><br/>


## 📢 Follow us:
- Team drive generator : https://td.msgsuite.workers.dev/
- Telegram channel : https://t.me/MsGsuite
- Telegram chat : https://t.me/MsGsuiteChat

## ❤️ Credits & thanks :
- [wrenfairbank](https://github.com/wrenfairbank/telegram_gcloner) for the original python script
- [smartass08](https://github.com/smartass08/telegram_gcloner) to adapt the scrip to heroku
- [anymeofu](https://github.com/anymeofu/CloneBot) for making the Direct Heroku deployable Version
- Zero-The-Kamisama to making me discover this amazing bot and the detailed instructions
- [zorgof](https://t.me/zorgof) for the termux script

<h1 align="center"> Thank You msgsuite <br></h1> 
