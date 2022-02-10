# MinecraftTelegramBot
Minecraft Telegram Bot

### Package to Install
`pip install python-telegram-bot`

### Used Modules Description
+ Updater: This will contain the API key we got from BotFather to specify in which bot we are adding functionalities to using our python code.
+ Update: This will invoke every time a bot receives an update i.e. message or command and will send the user a message.
+ CallbackContext: We will not use its functionality directly in our code but when we will be adding the dispatcher it is required (and it will work internally)
+ CommandHandler: This Handler class is used to handle any command sent by the user to the bot, a command always starts with “/” i.e “/start”,”/help” etc.
+ MessageHandler: This Handler class is used to handle any normal message sent by the user to the bot,
+ FIlters: This will filter normal text, commands, images, etc from a sent message.
