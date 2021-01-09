# Discord Memes

Discord-Memes es un modulo para hacer memes en tu bot de discord, tiene images español, videos español, de todo español, y putin!

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

`memes.videosEspañol()` retorna videos de memes en español

`memes.deTodoEspañol()` retorna de todo (videos e imagenes) en español

`memes.putin()` retorna videos de putin caminando en diferentes versiones

# Links

[**Discord server**](https://discord.gg/sRuTH454aB)
