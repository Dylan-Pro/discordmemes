# Discord Memes

Discord-Memes es un modulo para hacer memes en tu bot de discord, tiene images español, videos español, videos ingles, e imagenes ingles!

# Instalación

```npm install discord-memes```

# Uso

```js
const memes = require("discord-memes"); //requerir el paquete
console.log(memes.imagenesEspañol()) //retorna imagenes en español
```

# Ejemplo
```js
const memes = require('discord-memes');
const Discord = require('discord.js');
const client = new Discord.Client();

client.on('ready', () => {
    console.log('Listo!')
});

client.on('message', (message) => {
    if (message.content == 'meme') {
        message.channel.send(memes.imagenesEspañol())
    }
});

client.login('token');
```

# Métodos

`memes.imagenesEspañol()` retorna imagenes de memes en español

`memes.imagenesIngles()` retorna imagenes de memes en ingles

`memes.videosEspañol()` retorna videos de memes en español

`memes.videosIngles()` retorna videos de memes en ingles

# Github

[Github](https://github.com/Dylan-Pro/DiscordMemes)
