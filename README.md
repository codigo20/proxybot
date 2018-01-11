# proxy-bot
Proxy es un bot Discord de registros de reportes basado en [Discord.js](https://discord.js.org/#/docs/main/stable/general/welcome), podrás generar un reporte a un usuario por spamer raiders links, entre otros tambien listar el historial de ello y mas funciones como log de ban, remove ban, banslist  y de ingreso de usuarios.

#### SERVIDOR SOPORTE DISCORD
<p align="center">
  <a href="https://discord.gg/VxwER6t"><img src="https://discordapp.com/api/guilds/312846399731662850/widget.png?style=banner2" alt="Discord server"></a>
</p>

#### INSTALACION Y CONFIGURACION
Este bot usa node.js  para ejecutarse. Por favor, consulte https://nodejs.org/es/ e instale la versión recomendara v8.x.
Una vez que tenga el node instalado, Descargar el archivo .zip y descomprimelo en tu escritorio.

<p align="center">
    <img src="https://i.imgur.com/EkRunBv.png" alt="img">
</p>

Abrir la carpeta descargada del bot, abrir el archivo `config.json` y edite los datos del archivo.

    {
    "token":"TOKENBOT",
    "prefix":"!!y",
    "idbot": "IDBOT",
    "idcanalverificados":"IDCANAL",
    "idcanalreportes":"IDCANAL",
    "rolname":"NOMBRE-ROL"
    
    }

"token" : "Para obtener un token debes crear tu app de discord API, [Crear una app discord](http://www.craterdev.com/documentacion-mybot/guia/cuenta-app-bot.html) y copiar el token de tu bot ".

"prefix" : " Aqui debes ingresar un prefix para tu bot. Ejm `!!, -, +, ?, !!y`."

"idbot" : "Copiar el ID de tu bot creado anteriormente."

"idcanalverificados" : "Copiar el ID del canal donde se mostrara los reportes verificados, ACEPTADOS o RECHAZADOS."

"idcanalreportes" : "Copiar el ID del canal donde se mostraran los reportes generados para ser verificados."

"rolname" : "Nombre del rol, quienes tendran acceso a verificar los reportes generados. Ejm: `verificadores, admin, staff`".
(el rol debe estar creado primero en su servidor)



