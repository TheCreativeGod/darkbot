# darkbot

[![Build Status](https://travis-ci.org/darkaqua/darkbot.svg?branch=master)](https://travis-ci.org/darkaqua/darkbot)
[![Discord Status](https://discordapp.com/api/guilds/244102569729720321/widget.png)](http://darkaqua.net)

API de discord usada para el proyecto en node.js usando la libreria [discord.js](https://discord.js.org/#/docs/main/master/general/welcome)

Si quieres colaborar en el proyecto unete a nuestro [discord](http://darkaqua.net)

Reescrito por [mcmacker4](https://github.com/mcmacker4)<br>
Versión antigua [aquí](https://github.com/darkaqua/darkbot_old)

###Ejemplo de config.json<br>
```json
{
    "token": "<token aqui>",
    "webhook_secret": "<password del webhook>",
    "prefix": "!"
}
```

###Recomendaciones para programar

####No usar

- ``require('./Main')`` 
- ``var``, en su lugar ``const`` o ``let``

####Evitar usar

- ``function a(){}``, en su lugar ``const a = () => {}`` o ``a: () => {}``