<p align="center">
    <a href="https://github.com/venombolteop/pyrolink">
        <img src="https://raw.githubusercontent.com/pylogram/artwork/main/artwork/pyrolink-logo.png" alt="Pyrolink" width="128">
    </a>
    <br>
    <b>Telegram MTProto API Framework for Python</b>
    <br>
    <a href="https://t.me/pylogram">
        Homepage
    </a>
    •
    <a href="https://t.me/pylogram">
        Documentation
    </a>
    •
    <a href="https://t.me/pylogram">
        Releases
    </a>
    •
    <a href="https://t.me/pylogram">
        News
    </a>
</p>

## Pyrolink

> [!NOTE]
> The project is now maintained or supported. Thanks for appreciating it.

> Elegant, modern and asynchronous Telegram MTProto API framework in Python for users and bots

``` python
from pyrogram import Client, filters

app = Client("my_account")


@app.on_message(filters.private)
async def hello(client, message):
    await message.reply("Hello from Pyrogram!")


app.run()
```

**Pyrolink** is a modern, elegant and asynchronous [MTProto API](https://docs.pyrogram.org/topics/mtproto-vs-botapi)
framework. It enables you to easily interact with the main Telegram API through a user account (custom client) or a bot
identity (bot API alternative) using Python.

### Key Features

- **Ready**: Install Pyrolink with pip and start building your applications right away.
- **Easy**: Makes the Telegram API simple and intuitive, while still allowing advanced usages.
- **Elegant**: Low-level details are abstracted and re-presented in a more convenient way.
- **Fast**: Boosted up by [TeleCrypto](https://github.com/venombolteop/telecrypto), a high-performance cryptography library written in C.  
- **Type-hinted**: Types and methods are all type-hinted, enabling excellent editor support.
- **Async**: Fully asynchronous (also usable synchronously if wanted, for convenience).
- **Powerful**: Full access to Telegram's API to execute any official client action and more.

### Installing

``` bash
pip3 install pyrolink
```

### Resources

- Check out the docs at https://t.me/pylogram to learn more about Pyrolink, get started right
away and discover more in-depth material for building your client applications.
- Join the official channel at https://t.me/pylogram and stay tuned for news, updates and announcements.
