----------
# This Is A Protected Bot! If You Fork Without Permission Your Bot will Ban Automatically👋

## For Using This Bot You Need To Subscribe My YouTube Channel.Than Join My Whatsapp group And Send Me Prove I will Give You Access Code.
## I'm [NAHIDUL ISLAM-BOT] Also Know As NAHIDUL ISLAM NAIM                   Facebook Link 🔗        (https://www.facebook.com/virtual.abbu.nobita) 👋

# 📰 Talking about Information
<img align="right" width=200px alt="PNG" src="https://i.pinimg.com/originals/a0/10/21/a010215b786ada4176ae237b5b154310.gif" />

-   ⚜️ My name is 𝐍𝐀𝐇𝐈𝐃𝐔𝐋 𝐈𝐒𝐋𝐀𝐌 𝐍𝐀𝐈𝐌.
-   ❤️‍🔥 𝟏𝟏/𝐎𝐂𝐓/𝟐𝟎𝟎𝟕
-   💬 My nickname is 𝐍𝐀𝐇𝐈𝐃𝐔𝐋 𝐈𝐒𝐋𝐀𝐌-𝐁𝐎𝐓 (𝐍𝐈𝐁)
-   💬 I'm Single.💜
-   💓 Relationship: Single 
-   🍁 Profile: [Facebook](https://www.facebook.com/virtual.abbu.nobita)
-   🍀 Describe About Myself: I'm Full Time Busy Person. I've Continue My Studies. Besides work I write scripts in JavaScript To improve performance of the bot. If you're using my Bot. Thank you for using Nahidul-bot Version 2 
<hr>

# 📖 Top Langs
![](https://imgur.com/a/HkuD0bH)


# 🤝🏻 Connect with Me
wp:/+8801796457292

### <br>   ❖ DEPLOY_WORKFLOWS ❖
```
name: Node.js CI

on:
  push:
    branches: [main]
  pull_request:
    branches: [main]

jobs:
  build:
    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]
        # See supported Node.js release schedule at https://nodejs.org/en/about/releases/

    steps:
    # Step to check out the repository code
    - uses: actions/checkout@v2

    # Step to set up the specified Node.js version
    - name: Use Node.js ${{ matrix.node-version }}
      uses: actions/setup-node@v2
      with:
        node-version: ${{ matrix.node-version }}

    # Step to install dependencies
    - name: Install dependencies
      run: npm install

    # Step to run the bot with the correct port
    - name: Start the bot
      env:
        PORT: 8080
      run: npm start
```

[![FORK nahidul islam naim (https://github.com/NNAIM01/Nobita-)
