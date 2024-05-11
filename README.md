<div align="center">
  <a href="https://github.com/knockstick/knos-authbot">
    <img src="https://media.discordapp.net/attachments/872388362160455693/1231498864926916649/logo.png?ex=66372db1&is=6624b8b1&hm=bbecdf5c8bd5af7632622b82586a98bf19dd5975a82e3733f6488cee94bed7ef&=&format=webp&quality=lossless" alt="Logo" style="width: 60%; height: 60%;">
  </a>
  
  <h2 align="center">Kno's AuthBot</h2>
  <p align="center">
    Simple Discord Bot that uses OAuth2 to verify members and pull them back to the server.
  </p>
</div>

---

<b>[🇷🇺 README на русском](https://github.com/knockstick/knos-authbot/blob/main/README-ru.md/)</b>

### 🍕 Features

- Sends logs to a Discord channel
- Unlimited member pulling
- Slash commands
- Customization options
- Download and upload user database
- Supports multiple OAuth2 scopes
- Automatically updates access tokens
- Pull by country
- **100%** without CAPTCHA!
---

### 💻 Installation

- `Python 3.9+` required
1. Download the repository *(if you haven't already)*
2. Create an application at the <b>[Discord Developer Portal](https://discord.com/developers)</b> and **enable all intents**
3. Edit the [config.json](https://github.com/knockstick/knos-authbot/blob/main/config.json) file and configure the HTML page in [templates folder](https://github.com/knockstick/knos-authbot/blob/main/templates)
4. Install the requirements using `pip3 install -r requirements.txt`
5. Start the bot with `python3 bot.py`

- Done! Type `/verify-embed` in your admin guild to send your verification embed to a channel.
---

### 📸 Screenshots
<img src="https://media.discordapp.net/attachments/1230859548659683413/1238070355717918780/oauth2scr.png?ex=663df25f&is=663ca0df&hm=ce07709135fdbd96fafe7b89fad95991f8c70734a306a132eb0a5d19dec6d815&=&format=webp&quality=lossless&width=635&height=762" style="width: 40%; height: 40%;" alt="An image showing a new verified user">
<img src="https://media.discordapp.net/attachments/1230859548659683413/1231503389200879626/image.png?ex=663731e8&is=6624bce8&hm=11ffedfb0a9ea384fa86e97ce77004f5570f8186332ece0835fea755ab225b5d&=&format=webp&quality=lossless" style="width: 40%; height: 40%;" alt="An image showing /pull command">
<img src="https://media.discordapp.net/attachments/1230404669130412086/1235831050832183376/image.png?ex=6635ccdb&is=66347b5b&hm=3907bdd81fceabf96823da83ff67f2af9e308888ebff5e902148f2a2841a4cd1&=&format=webp&quality=lossless" style="width: 40%; height: 40%;" alt="An image showing /pull command results">
<img src="https://media.discordapp.net/attachments/1230859548659683413/1231547521395064832/image.png?ex=66375b02&is=6624e602&hm=bdbe0bf15e6545222e5052682ade6ee541a0d7b49475d6ecd51c44b112a21d45&=&format=webp&quality=lossless" style="width: 40%; height: 40%;" alt="The UI of the program">

---

### ❗ Disclaimer

This github repo is for **EDUCATIONAL PURPOSES ONLY.** I am not responsible for your actions.

---

### 🌟 Having troubles?
If you have an error or a problem, feel free to [start a new issue!](https://github.com/knockstick/knos-authbot/issues/new)

**OR: join my [discord server](https://discord.gg/ph85kayeuH)**

Don't forget to leave a **star!**

---
### 📰 Changelog

```diff
v 1.2.1 ⋮ 11.05.2024
+ Minor bug fixes with the new /usercheck command
+ New scope: connections: Display your user connections (like YouTube, Steam) in the log message

v1.2 ⋮ 09.05.2024
+ New command: /usercheck to remove unauthorized users and refresh access tokens
+ You can now pull by country
+ IP, access token and country are now stored in data.json
! Thanks to my Discord server members for this great ideas

v1.1 ⋮ 02.05.2024
+ Added `amount` argument to /pull command
+ You can now specify multiple guilds and verify roles in config.json
+ Better /pull stats
+ Now showing state and server name in the log
+ Login URL in /verify-embed now has a state
- Removed `log_on_end` argument from /pull command

v1.0 ⋮ 21.04.2024
! Initial release
```

---

<p align="center">
  <img src="https://img.shields.io/github/stars/knockstick/knos-authbot.svg?style=for-the-badge&labelColor=black&color=f429ff&logo=IOTA"/>
  <img src="https://img.shields.io/github/languages/top/knockstick/knos-authbot.svg?style=for-the-badge&labelColor=black&color=f429ff&logo=python"/>
</p>

---
