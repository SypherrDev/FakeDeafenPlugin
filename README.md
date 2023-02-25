
# FakeDeafenPlugin

This is a [BetterDiscord](https://betterdiscord.app/) plugin that allows you to fake being deafened.






## Usage
    1. Deafen in discord.
    2. Enable the plugin in your plugins tab.
    3. Undeafen, you'll now be able to hear, while others will see you as deafened.
    
    To undo everything, you can simply disable the plugin and reset by deafen/undeafening.


## Information

A lot of the versions found online require you to restart your Discord for you to be able to join different voice channels or perform any other actions, which is crazy because it's a one-liner to reset the overwritten method.

```js
WebSocket.prototype.send = WebSocket.prototype.original;
```


## Credits

 - [Abbe](https://github.com/abbe/discord-fake-deafen) (original console code)
