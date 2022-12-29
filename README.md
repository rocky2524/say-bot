# say-bot

```
client.on('message', message => {
    if (message.content.startsWith( `${prefix}say`)) {
        if (message.author.bot) return;
        const SayMessage = message.content.slice(5).trim();
        message.channel.send(SayMessage)
        message.delete()
    }   
});
```
