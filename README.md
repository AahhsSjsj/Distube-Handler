<p align="center">Distube Handler ♥️ </p>

# **Hola Mi Gente Aqui Estamos Un Codigo De Distube Handler :D**

## **Primero Requisitos:**

- **[Distube](https://www.npmjs.com/package/distube)**
- **[Discord.js V13](https://www.npmjs.com/package/discord.js)**
- **[@discordjs/voice](https://github.com/discordjs/voice)**
- **[FFmpeg](https://github.com/discordjs/opus)**
- **[@discordjs/opus](https://github.com/discordjs/opus)**
- **[sodium](https://www.npmjs.com/package/libsodium-wrappers) or [libsodium-wrappers](https://www.npmjs.com/package/libsodium-wrappers)**
- **[python](https://www.python.org/) (Opcional: para que [youtube-dl](https://youtube-dl.org/) admita más de 700+ sitios.)**

## **Ahora El Codigo Handler**

### **Para Los que tienen handler en el index.js:**

### **Primer Paso:**

**Crear Un Nueva Carpeta llamada `Validation`:**

<div align="left"><img src="https://i.imgur.com/BnarL93.gif">

### **Segundo Paso:**

**Crear Un Archivo llamado: `DistubeE.js`:**

<div align="left"><img src="https://i.imgur.com/AwfQVO1.gif">

**De Ahi Escribir Este Texto En Ese Archivo! (C&P):**

```js
module.exports = {
  DistubeE: [
    "addList",
    "addSong",
    "deleteQueue",
    "disconnect",
    "empty",
    "error",
    "finish",
    "finishSong",
    "initQueue",
    "noRelated",
    "playSong",
    "searchCancel",
    "searchDone",
    "searchInvalidAnswer",
    "searchNoResult",
    "searchResult",
  ],
};
```

### **Tercer Paso:**

**Despues De Eso Vayan A Su Index.js escriban primero este texto:**

<div align="left"><img src="https://media.discordapp.net/attachments/912187186017882132/921240809850929232/unknown.png?width=666&height=459">

### **Cuarto Paso:**

**Despues De Lo Otro Deben Crear la Carpeta llamada: `DEvents`:**

<div align="left"><img src="https://i.imgur.com/xHoBDEt.gif">

**Despues de eso crean una subcarpeta y adentro un archivo.js con cualquier nombre:**

<div align="left"><img src="https://i.imgur.com/Li8EiSN.gif">

**Asi Ya Estaria Listo | Codigo Handler:**

```js
const { MessageEmbed, Client } = require("discord.js");
const { Queue, Song } = require("distube");

module.exports = {
  name: "",
  /**
   * @param {DEFINICION} title
   * @param {DEFINICION} title
   */
  run: async () => {},
};
```

### **Para Los que tienen una carpeta llamada `handlers`:**

### **Primer Paso:**

**Crear Un Nueva Carpeta llamada `Validation`:**

<div align="left"><img src="https://i.imgur.com/BnarL93.gif">

### **Segundo Paso:**

**Crear Un Archivo llamado: `DistubeE.js`:**

<div align="left"><img src="https://i.imgur.com/AwfQVO1.gif">

**De Ahi Escribir Este Texto En Ese Archivo! (C&P):**

```js
module.exports = {
  DistubeE: [
    "addList",
    "addSong",
    "deleteQueue",
    "disconnect",
    "empty",
    "error",
    "finish",
    "finishSong",
    "initQueue",
    "noRelated",
    "playSong",
    "searchCancel",
    "searchDone",
    "searchInvalidAnswer",
    "searchNoResult",
    "searchResult",
  ],
};
```

### **Tercer Paso:**

**Despues De Eso Vayan A Su carpeta `handlers` crean un archivo llamado `HandlerD`:**

<div align="left"><img src="https://i.imgur.com/cZtUXa5.gif">

**Y Ponen Este Codigo En Ese Archivo:**

<div align="left"><img src="https://i.imgur.com/X2GLfrB.png">

### **Cuarto Paso:**

**Despues De Lo Otro Deben Crear la Carpeta llamada: `DEvents`:**

<div align="left"><img src="https://i.imgur.com/xHoBDEt.gif">

**Despues de eso crean una subcarpeta y adentro un archivo.js con cualquier nombre:**

<div align="left"><img src="https://i.imgur.com/Li8EiSN.gif">

**Asi Ya Estaria Listo | Codigo Handler:**

```js
const { MessageEmbed, Client } = require("discord.js");
const { Queue, Song } = require("distube");

module.exports = {
  name: "",
  /**
   * @param {DEFINICION} title
   * @param {DEFINICION} title
   */
  run: async () => {},
};
```

# **🔗Links**

- [Web De Discord.js](https://discord.js.org/#/)
- [Documentation Discord.js](https://discord.js.org/#/docs/main/stable/general/welcome)
- [Github](https://github.com/AahhsSjsj)
- [Node.js v16](https://nodejs.org/es/download/current/)
- [Visual Studio Code](https://code.visualstudio.com/download)
- [Discord Server Diurnos](discord.gg/eRpGsqwzDZ)

```txt

                  __  _____         _____                        _____ ______
                 / / |  __ \       / ____|                      |  __ \___  /
   __ _  __ _   / /__| |__) |_ __ | |  __ ___  __ ___      _____| |  | | / /
  / _` |/ _` | / / _ \  _  /| '_ \| | |_ / __|/ _` \ \ /\ / /_  / |  | |/ /
 | (_| | (_| |/ /  __/ | \ \| |_) | |__| \__ \ (_| |\ V  V / / /| |__| / /__
  \__, |\__, /_/ \___|_|  \_\ .__/ \_____|___/\__, | \_/\_/ /___|_____/_____|
   __/ | __/ |              | |                  | |
  |___/ |___/               |_|                  |_|

```

### **🔗 Links De La Paginas Para Ejecutar El Proyecto**

- [Heroku](https://heroku.com)
- [Replit](https://replit.com)
- [Glitch](https://glitch.com)
- [Logearte En Glitch](https://glitch.com/signup)
- [Logearte En Replit](https://replit.com/login)
- [Logearte En Heroku](https://id.heroku.com/login)
- [Registrate En Glitch](https://glitch.com/signin)
- [Registrate En Replit](https://replit.com/signup)
- [Registrate En Heroku](https://signup.heroku.com)

### **🔗 Links Discord.js:**

- [Website](https://discord.js.org/) ([source](https://github.com/discordjs/website))
- [Documentation](https://discord.js.org/#/docs/main/master/general/welcome)
- [Guia](https://discordjs.guide/) ([source](https://github.com/discordjs/guide))
- Ver también el [Guía de actualización](https://discordjs.guide/additional-info/changes-in-v13.html), incluidos los elementos Ya actualizados y eliminados de la biblioteca.
- [Discord.js Discord server](https://discord.gg/djs)
- [Discord API Discord server](https://discord.gg/discord-api)
- [GitHub](https://github.com/discordjs/discord.js)
- [NPM](https://www.npmjs.com/package/discord.js)
- [Bibliotecas relacionadas](https://discord.com/developers/docs/topics/community-resources#libraries)

### **🔗 Links Distube:**

#### **Documentation**

**Lea las definiciones, propiedades y detalles de eventos de DisTube en el [Documentation page](https://distube.js.org/).**

#### **Example Bot**

- [DisTube Bot](https://skick.xyz/DisTube) - **Un robot de música con controlador de reacción, filtros, modo DJ, lista de reproducción personalizada del usuario y votación.**
- [DisTube Example](https://github.com/distubejs/example) - **Bot de ejemplo con un controlador de comandos simple.**
- [DisTube Guide](https://distube.js.org/guide) - **Cómo construir un bot de musica desde cero.**

## **Dependencies**

- [node-ytdl-core](https://github.com/fent/node-ytdl-core): **YouTube scraper ([DisTube Fork](https://github.com/distubejs/node-ytdl-core))**
- [node-ytsr](https://github.com/TimeForANinja/node-ytsr): **YouTube search scraper ([DisTube Fork](https://github.com/distubejs/ytsr))**
- [node-ytpl](https://github.com/TimeForANinja/node-ytpl): **YouTube playlist resolver ([DisTube Fork](https://github.com/distubejs/ytpl))**
- [youtube-dl-exec](https://github.com/microlinkhq/youtube-dl-exec): **[`youtube-dl`](https://youtube-dl.org/) wrapper**
