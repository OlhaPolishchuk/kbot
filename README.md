# Kbot
## Description

[Kbot](https://t.me/po_kbot) is a functional Telegram bot that can process messages from users and respond to them. This bot is made with Golang using [Cobra CLI](https://github.com/spf13/cobra) and [Telebot.v3](gopkg.in/telebot.v3) frameworks.

Link: [t.me/po_kbot](https://t.me/po_kbot)

## Installation

1. Clone this repository.
2. Open the project in your environment.
3. Generate a Telegram token with [BotFather](t.me/BotFather).
4. Assign the value of the received token to the environment variable TELE_TOKEN
```bash
read -s TELE_TOKEN
export TELE_TOKEN
```
5. Build the project. Replace square brackets with your repository address and the version of the app. 
```bash
go build -ldflags "-X="github.com/[your`s repository]/cmd.appVersion=[current app version]
```
6. Run the project using the "start" command.
```bash
./kbot start
```


## Usage

Enter **/start hello** in Kbot and it will return "Hello I'm Kbot [current app version]".
