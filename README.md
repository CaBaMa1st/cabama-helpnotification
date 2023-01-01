### Preview

- Vista previa | Preview : [image/imagen](https://cdn.discordapp.com/attachments/1048580529370435675/1059199527611023431/image.png)
- Responsive

### Desc
- HelpNotification for Fivem

### Requirements | Requerimientos

- Añadir 3 lineas de codigo al es_extended/client/functions.lua reemplazando su correspondiente ESX.ShowHelpNotification

    ESX.ShowHelpNotification = function(text)
        return exports["cabama-help"]:showHelp(text)
    end
