# NeoForge-Server
Mi servidor de Minecraft con mods, utilizando Neoforge y Ngrok o Playit.gg

![](/Demo%20assets/full-enderfox.png)  
  
## Mods  
- Chat Heads | By dzwdz
- Traveler's Backpack | By Tiviacz1337
- Towns and Towers | By Biban_Auriu
- Cristel Lib | By Cristelknight _(Dependencia)_  
  
### Mods del lado del cliente nada más
- ~~Skin Layers 3D | By tr7zw _(Opcional)_~~
- CustomSkinLoader | By xfl03 _(Opcional)_

## Comandos útiles

| Comando                  | Descripción                                      |
|--------------------------|--------------------------------------------------|
| `sudo java -jar neoforge-21.4.124-installer.jar --install-server` | Instala o hace una update del Minecraft Server. (Para hacer el update necesitaras descargar el nuevo .jar neoforge installer y luego ejecutar este comando) (Recomendable una copia de seguridad del server antes de hacer update de versión)   |
| `ngrok tcp 25565`        | Expone el puerto 25565 (tcp) y crea un link de Ngrok, el cual compartiras a los jugadores para que se puedan unir. |
| `playit`                 | Expone el puerto 25565 (tcp) y crea un link de Playit.gg, el cual compartiras a los jugadores para que se puedan unir.   |
| `./run.sh`               | Corre el Minecraft Server (port 25565). |