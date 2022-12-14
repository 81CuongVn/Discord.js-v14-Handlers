<h1 align="center">Hi I'm Shree</h1>

<img align="center" src="https://discord.c99.nl/widget/theme-1/606099560854585365.png" alt="Discord"/> 
<p align="left"> <img src="https://komarev.com/ghpvc/?username=sh3ee&label=Profile%20views&color=0e75b6&style=flat" alt="kabirsingh2004" /> </p>

# Discord.js-v14-Handlers Template

`Hello, this repository represents the basic template to get started with a Discord Bot in Discord.JS v14. You can clone or fork this repository and start making changes if you want.`

#

## Requirements:
* Node.JS version ```16.9.0``` or higher (Recommended latest ```LTS version of NodeJS```, install it from [here](https://nodejs.org/en/))
* Discord.JS v14 (Install it from [here](https://www.npmjs.com/package/discord.js/v/14.0.3))

## How to start the bot?
If you already have created your Discord Bot Application, please skip to this part.

## Now How to Make application?

⚙ **Setting up a bot application**

Creating a Bot Account
In order to work with the library and the Discord API in general, we must first create a Discord Bot account.

**Creating a Bot account is a pretty straightforward process.**
#
`1.` Go [this site](https://discord.com/developers/applications) and click on **New Application**, and just name it whatever you want.

#
`2.` Navigate to the application page

#
`3.` Click on the “New Application” button.

![Setup the Bot like this](https://cdn.discordapp.com/attachments/952449038890975233/1010076684042653726/unknown.png "Discord Developers Portal")

#
`4.` Give the application a name and click “Create”.


![Setup the Bot like this](https://cdn.discordapp.com/attachments/952449038890975233/1010076726296055868/unknown.png "Discord Developers Portal")

#
`5.` Create a Bot User by navigating to the “Bot” tab and clicking “Add Bot”.
⚪ Click “Yes, do it!” to continue.
![Setup the Bot like this](https://cdn.discordapp.com/attachments/952449038890975233/1010076866293534791/unknown.png "Discord Developers Portal")

#
`6.` Make sure that Public Bot is ticked if you want others to invite your bot.
⚪ You should also make sure that Require OAuth2 Code Grant is unchecked unless you are developing a service that needs it. 
If you’re unsure, then leave it unchecked.
![Setup the Bot like this](https://cdn.discordapp.com/attachments/952449038890975233/1010076896790331452/unknown.png "Discord Developers Portal")

`7.` After the creation of the application, head over to the menu **Tab**, and push the buttons on the right side for everything except, *REQUIRES OAUTH2 CODE GRANT* this option. You can enable the *MESSAGE INTENT* also if you want. An example image is shown below,

![Setup the Bot like this](https://cdn.discordapp.com/attachments/952449038890975233/1010078228196630558/unknown.png "Discord Developers Portal")

#
`8.` Go to the **OAuth2** menu, and head over to the sub-menu called **URL Generator**. In the scopes, please check on *Bot* & *applications.commands*. Underneath inside the last box, choose your permissions and copy the URL that is generated below.

#
`9.` **Paste the url in another tab and invite the bot to your server.**

#
`10.` **After inviting the bot, open this project in your IDE, and write `npm i` in the Console/Shell and hit enter. For VS Code users, hit `Ctrl + J` to open up the terminal and then run this command. This will install all the required packages!**

#
`11.` Now, go back to your **Discord Developers Portal** and go to the menu **Bot**. Here click on *Reset Token* & copy this token.

#
`12.` Go to the file *.env* and replace the token with `BOT_TOKEN`. The final one should look like this,
`DISCORD_TOKEN = ewtgwsry.784ny03574yvn952784yup092y3u41.4ttw4ty4wy9`

#
`13.` **Now go to your server and create a logs channel if you don't have and copy it's ID. If you don't know how to copy ID of an element in Discord** [follow this](https://support.discord.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID-)

#
`14.` Go again to the `.env` file and replace that ID with `LOGS_CHANNEL`. The final one should look like this,
`LOGS = 89814879844897`

#
`15`. Go to your console, write `node .` and hit enter. If you've done everything correctly, the bot should be turned on now!

#

## How to add my own file?
* For any type of commands, please head over to the folder, **Commands** and create another folder inside it. **DO NOT ADD A JS FILE INSIDE COMMANDS FOLDER**. It should be, *Commands > Information > ping.js*. So, we've the main folder, then a category folder and then the `js` file.
* For any type of events, please head over to the folder, **Events** and follow the procedure of adding Commands.
