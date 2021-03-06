# EpicWelcome
This plugin allows you to customize your join messages (titles, actionbar, annoucing new player and more)  
Supports PlaceholderAPI  
This plugin has been only tested on 1.16

## Configuration
```yaml
# EpicWelcome by xNeox (http://github.com/xxneox/EpicWelcome)
# You can use PlaceholderAPI placeholders in every message!
# https://github.com/PlaceholderAPI/PlaceholderAPI/wiki/Placeholders

join-title:
  enabled: true
  time:
    fade-in: 20 # 20 ticks = 1 second
    stay: 60
    fade-out: 20
  new-players:
    title: "&aWelcome &ato &eYourServer&a!"
    subtitle: "&7Remember to read &c/rules &7and have fun!"
  existing-players:
    title: "&7Welcome back %player_name%!"
    subtitle: "&aYou are playing on &eYourServer&a!"

join-actionbar:
  enabled: true
  new-players: "&aEnjoy your stay!"
  existing-players: "&aWelcome back!"

join-motd:
  enabled: true
  message: |
    &7Welcome &e%player% &7on &eYourServer!
    &7Have fun!

annouce-first-join:
  enabled: true
  message: "&aWelcome to &eYourServer&a, %player_name%, you are our &b#%server_unique_joins% player!"

custom-join-message:
  enabled: true
  message: "&8(&a+&8) &a%player_name% &7has joined the server."

custom-quit-message:
  enabled: true
  message: "&8(&c-&8) &c%player_name% &7has left the server."
```

## Preview
![](https://i.imgur.com/38ytGSm.png)
