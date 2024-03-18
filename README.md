<div align="center">
  <br />
  <p>
    <a href="https://discord.js.org"><img src="https://discord.js.org/static/logo.svg" width="546" alt="discord.js" /></a>
  </p>
  <br />
  <p>
    <a href="https://discord.gg/bRCvFy9"><img src="https://discordapp.com/api/guilds/222078108977594368/embed.png" alt="Discord server" /></a>
    <a href="https://www.npmjs.com/package/discord.js"><img src="https://img.shields.io/npm/v/discord.js.svg?maxAge=3600" alt="NPM version" /></a>
    <a href="https://www.npmjs.com/package/discord.js"><img src="https://img.shields.io/npm/dt/discord.js.svg?maxAge=3600" alt="NPM downloads" /></a>
    <a href="https://travis-ci.org/hydrabolt/discord.js"><img src="https://travis-ci.org/hydrabolt/discord.js.svg" alt="Build status" /></a>
    
  </p>
  <p>
    <a href="https://nodei.co/npm/discord.js/"><img src="https://nodei.co/npm/discord.js.png?downloads=true&stars=true" alt="NPM info" /></a>
  </p>
</div>

## About
discord.js is a powerful [node.js](https://nodejs.org) module that allows you to interact with the
[Discord API](https://discordapp.com/developers/docs/intro) very easily.

- Object-oriented
- Predictable abstractions
- Performant
- 100% coverage of the Discord API

## Installation
**Node.js 6.0.0 or newer is required.**  
Ignore any warnings about unmet peer dependencies, as they're all optional.

Write code in Git-Bash / terminal: `npm install discord.js`  

## Example usage
```js
const Discord = require('discord.js');
const client = new Discord.Client();

client.on('ready', () => {
  console.log('I am ready!');
});

client.on('message', message => {
  if (message.content === 'ping') {
    message.reply('pong');
  }
});

client.login('your token');
```

## My Discord_Bot Working
"My Discord bot serves as a convenient tool for calculating Air Quality Index (AQI) values for cities specified by users. By simply entering the name of a city, users can receive comprehensive data on AQI levels, including information such as pollutant concentrations and health implications. Furthermore, the bot provides tailored health advice based on the AQI value, offering insights into how current air quality may impact well-being. This feature enhances user awareness of environmental conditions and promotes healthier lifestyle choices in response to varying air quality levels."

# Working ScreenShot

<img src = "https://github.com/dhruvsaboo1805/Discord_Bot/assets/104023753/25850212-6353-4c10-90ad-0df9f406595d"></img>

## Links
* [Website](https://discord.js.org/) ([source](https://github.com/hydrabolt/discord.js-site))
* [Documentation](https://discord.js.org/#/docs)
* [Discord.js server](https://discord.gg/bRCvFy9)
* [Discord API server](https://discord.gg/rV4BwdK)
* [GitHub](https://github.com/dhruvsaboo1805/Discord_Bot.git)
* [NPM](https://www.npmjs.com/package/discord.js)
* [Related libraries](https://discordapi.com/unofficial/libs.html) (see also [discord-rpc](https://www.npmjs.com/package/discord-rpc))

## Help
If you don't understand something in the documentation, you are experiencing problems, or you just need a gentle
nudge in the right direction, please don't hesitate to join our official [Discord.js Server](https://discord.gg/bRCvFy9).
