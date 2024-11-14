# Kizmeow-Telegram-Discord-Bot
A bot that forwards Telegram messages to Discord via webhook. Kizmeow does not require any Discord or Telegram permissions, nor does it require adding any bots to Telegram group, the only thing required is the Discord webhook url.

The bot is under development, it only forward text messages and images currently. 

What's the difference between Kizmeow and other existing bots?
-----------------

|                                                                   | Kizmeow | Other Bots |
|-------------------------------------------------------------------|:-------:|:----------:|
|Not required to add Discord Bot to your Discord server             |   ✔    |     ❌     |
|Not required to add Telegram Bot to your Telegram group            |   ✔    |     ❌     |
|Discord webhook not required                                       |   ❌   |    ✔❌    |
|Forward message from public Telegram channel which you don't own it|   ✔    |     ❌    |
|Forward message from private Telegram channel                      |   ❌   |     ✔     |
|Forward message from private/public Telegram group                 |   ❌   |     ✔❌  |
|GUI and CLI supported                                              |   ✔    |    ✔❌   |
|Discord embed supported                                            |   ✔    |    ✔❌   |


Usage
-----------------

1. Click [here](https://github.com/Xeift/Kizmeow-Telegram-Discord-Bot/archive/refs/heads/main.zip) to download zip first.

If you don't want to download any file on your precious computer, you can run CLI on cloud first.

[Click me](https://replit.com/@xeiftc/Kizmeow-Telegram-Discord-Bot#main.py) to run CLI on Replit.

2. Run CLI,

There are two interface, GUI and CLI.

You can choose one you desire. If you're not familiar with Python, I suggest you use GUI.

The window on the left side is CLI, the right one is GUI.

![image](https://user-images.githubusercontent.com/80938768/196021293-f8741207-a46c-4902-b4aa-b3f03fe467e5.png)

Whether you choose GUI or CLI, we need to obtain below data first:

|       Name                           | Description | Required | Example |
|--------------------------------------|-------------|----------|---------|
| Discord webhook URL                  |The Discord webhook you got in Discord channel|    ✔    | https://discord.com/api/webhooks/953518959309783100/nv0byOn-![image](https://github.com/user-attachments/assets/70694575-c8e8-44c8-a37c-641803b80a49)
xwMmRfHV6lasGbkhmNX0DvQyUAMJcoRbZJeHrpIpVKdB9bjJk962BddJRq8C |
| Telegram public announcement channel |The link of the public Telegram announcement channel. Public group, private group, private channel will not work|    ✔    | https://t.me/dsafdsfa3243 |
| Embed color                          |        |    ✔    | 0xe8006f |
| Embed hyperlink setting              |        |    ❌    | 1 |
| Keyword filter option                |        |    ❌    | 1 |
| Keyword filter bank                 |        |    ❌    | hello |
| Check message every n sec            |        |    ✔    | 20 |
| Content text                         |        |    ❌    | This message is forward from Telegram |

The gif table below shows the steps to get these parameters.

|               Parameter Name               |                                 How to get the parameter?                                 |
|--------------------------------------------|-------------------------------------------------------------------------------------------|
|             Discord webhook URL            | ![image](https://github.com/user-attachments/assets/9798b6ea-9be7-40b5-8169-87e3445d1c8d) |
|    Telegram public announcement channel    | ![image](https://github.com/user-attachments/assets/98f40aad-471c-42bf-b2c6-038fcc639e77) |
|                Embed color                 | ![image](https://github.com/user-attachments/assets/d072d6d9-22e1-412d-8278-7a6676e7feb0) |

Right click on the Discord server you want to forward message to.

Select `Server Settings` → `Intergrations`

![image](https://user-images.githubusercontent.com/80938768/196020310-9080efb6-cf40-4480-9286-9423b8d02482.png)

Click `New Webhhok` to create a new webhook.

Click `Copy Webhook URL` and paste the URL on notepad, Google Docs or any text editor, we will need it later.

![image](https://user-images.githubusercontent.com/80938768/196020693-faa13f8c-7c24-46dc-936f-e0dadb8b046a.png)

#### *TG Channel Link*

Click the title of the announcement channel, copy the link `https://t.me/?????`.

![image](https://user-images.githubusercontent.com/80938768/221586315-c9d93d38-fd34-4aa9-a649-928cd028153f.png)


#### *Embed Color*

Google "color picker" and choose the color you like, copy its HEX value and change "#" to "0x".

![image](https://user-images.githubusercontent.com/80938768/196021711-9626ec37-e4da-4dd9-9485-7d6dfefe2ef9.png)

Finally, we got all data we need.

#### *GUI*

1. Open `GUI` folder
2. Run GUI.exe
3. Enter data, click start bot

Video Tutorial: https://www.youtube.com/watch?v=YuWAM28t8nc

#### *CLI*

1. Open `CLI` folder
2. Install python and packages in requirements.txt
3. Run CLI
4. Enter data, it will start automatically

Note
-----------------

TTK theme I use for GUI: [Azure theme for ttk](https://github.com/rdbende/Azure-ttk-theme)

A nice tool I use for convert .py to .exe : [Auto PY to EXE](https://github.com/brentvollebregt/auto-py-to-exe)

Code by @xeft. If you have any question, feel free to DM me on Discord or open an issue.

Kizmeow icon illustrate by [Kiyue](https://instagram.com/sweetdays_gun_gun?igshid=YmMyMTA2M2Y=)
![image](https://user-images.githubusercontent.com/80938768/196019602-f4ac2896-cdaa-4028-acdb-53b8a0a60d43.png)

It's recommand to use CLI since I have no time to update GUI, functions of GUI are not up to date. 😶

FAQ
-----------------

<details>
<summary>Do I need to keep my computer on if I want to make this script running 7/24?</summary>
Yes.
</details>
