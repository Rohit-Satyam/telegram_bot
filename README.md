# How to configure Telegram bot
1. Install Telegram-send using conda: `conda install -c conda-forge telegram-send`
2. Once installed you have to configure it. But before that install the telegram on your phone and generate an API token for the same on your phone.
3. **Step 1.** Find telegram bot named "@botfarther", he will help you with creating and managing your bot![enter image description here](https://www.siteguarding.com/images/telegram_1.png)

4. **Step 2.** Print “/help” and you will see all possible commands that the botfather can operate.![enter image description here](https://www.siteguarding.com/images/telegram_2.png)
5. To create a new bot type “/newbot” or click on it.![enter image description here](https://www.siteguarding.com/images/telegram_3.png)
6. I wanted to create a bot for my WGS work so i chose name: **wgs_task_update**. This will be the name used for the group on telegram that will revceive messages from your system
7. I chose username **Rohit_wgs_bot**
8. It will provide you a message containing the API token whoch you can copy and save in your email.
9. Now coming back to your linux system, type the following command: `telegram-send --configure`
10. It will ask for API token. Simply copy paste it. Something like shown below![enter image description here](https://www.linux-magazine.com/var/linux_magazin/storage/images/media/linux-magazine-eng-us/images/telegram-send/675315-1-eng-US/telegram-send_reference.png) 
11. It will then give you a password which you need to go to type in **wgs_task_update** in your phone. Tada!! your bot is set now to send notifications on your telegram.

