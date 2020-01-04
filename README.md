# WannaPlugins
A assemble of Minecraft Plugins for 1.15.1.

> Italiano
Questo plugin aggiunge molti comandi per migliorare l'esperienza di gioco da parte degli amministratori e degli utenti in se.
Continene queste funzionalita:
  WannaAd e' un comando che permette di mandare un avviso a tutto il server, molto invasivo. Utile se bisogna avvisare di un evento, avvenimento importante.
  WannaFly e' un comando molto semplice che permette a chi ne avra' il permesso, di volare.
  WannaBeGod e' un comando che permette di diventare invincibili in sopravvivenza. Se combinata con la vanish e' perfetta per scovare qualche malandrino che cerca di hackerare!
  WannaVanish e' un comando che consente di diventare invisibile a tutti i giocatori.
  WannaFreeze e' un comando che permette di oscurare la vista di un giocatore, fermarlo permanentemente fino a che non si riesegue il comando, cosi anche se il furbetto esce dal server, gli sara' impossibile fuggire, e rimarra' per sempre immobile. 
  ChatCraft e' invece un comando che consente ai giocatori di chattare tra loro privatamente. Un prossimo aggiornamento consentera' di avere un log delle chat!
Il plugin e' anche ricco di listener, modifica il messaggio di morte, di entrata e di uscita del giocatore, rendendolo piu semplice e meno invasivo.
Contiene anche un EasterEgg, quello di Herobrine: fara' prendere un bello spavento alle persone, se fatto nel momento giusto!

> English
This plugin adds many commands to improve the gaming experience for administrators and users alike.
Continue these features:
  WannaAd is a command that allows you to send a warning to the whole server, very invasive. Useful if you need to notify of an event, an important event.
  WannaFly is a very simple command that allows those who have permission to fly.
  WannaBeGod is a command that allows you to become invincible in survival. If combined with the vanish it is perfect for finding some marauders trying to hack!
  WannaVanish is a command that allows you to become invisible to all players.
  WannaFreeze is a command that allows you to obscure a player's view, stop him permanently until the command is re-run, so even if the sly man leaves the server, it will be impossible for him to escape, and will remain forever immobile.
  ChatCraft is instead a command that allows players to chat with each other privately. A future update will allow you to have a chat log!
The plugin is also full of listeners, it modifies the player's death, entry and exit message, making it simpler and less invasive.
It also contains an EasterEgg, that of Herobrine: it will make people frighten, if done at the right time!

> Chinese
该插件添加了许多命令，以改善管理员和用户的游戏体验。
继续执行以下功能：
  WannaAd是一个命令，它使您可以向整个服务器发送警告，这非常具有侵入性。如果您需要通知事件（重要事件），则很有用。
  WannaFly是一个非常简单的命令，它允许那些拥有飞行权限的人使用。
  WannaBeGod是一个使您在生存中立于不败之地的命令。如果再加上消失，它非常适合寻找一些试图入侵的掠夺者！
  WannaVanish是一个使您对所有玩家不可见的命令。
  WannaFreeze是一个命令，它使您可以遮挡玩家的视线，使其永久停下来，直到重新执行该命令为止，因此，即使狡猾的人离开服务器，他也将无法逃脱，并且永远保持静止。
  相反，ChatCraft是允许玩家私下聊天的命令。将来的更新将使您拥有聊天记录！
该插件还充满了听众，它修改了播放器的死亡，进入和退出消息，使其更简单且侵入性更小。
它还包含一个Herobrine的EasterEgg：如果在正确的时间完成，它将使人们感到恐惧！

Traduction provided by Google Translate.
```
Plugin.yml
name: WannaPlugins
version: ${project.version}
main: me.franxpari.wannaplugins.WannaPlugins
api-version: 1.13
authors: [franxpari]
description: This plugin make the cummunication between players better.
commands:
  wannawarn:
    permission: wannaplugins.warn
    description: Warn a player
    aliases:
      - warn
      - ww
      - wannaw
      - wwarn
  wannafreeze:
    permission: wannaplugins.freeze
    description: Freeze a player
    aliases:
      - freeze
      - wfreeze
      - wf
  wannaad:
    permission: wannaplugins.ad
    description: Send an Advertisement
    aliases:
      - ad
      - wad
      - wannaa
      - wa
   chatcraft:
    description: Chat with other players
    aliases:
      - cc
      - chatc
      - ccraft
      - cchat
      - chat
      - wchat
  wannavanish:
    permission: wannaplugins.vanish
    aliases:
      - v
      - vanish
 wannafly:
    permission: wannaplugins.fly
    aliases:
      - fly
      - wannafly
      - wfly
 wannabegod:
    permission: wannaplugins.god
    aliases:
      - god
      - wannagod
  wannaherobrine:
    permission: wannaplugins.herobrine
    aliases:
      - herobrine
```
