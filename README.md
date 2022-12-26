A Simple Discord Self Embed
===========================
This is a simple self embed package that can be used to embed messages in a Discord server as a user.

### Install
> ``` bash
> pip install selfembed-discord
> ```

### Example
> ```python
> import discord_selfembed
> 
> embed = discord_selfembed.Embed("selfembed-discord", 
>   description="A way for selfbots to send embeds.", 
>   colour="36393F", 
>   url="https://github.com/AmeLooksSus/selfembed-discord"
> )
> embed.set_image("https://1.gravatar.com/avatar/6e5071e57508447a6e3a440944ead000")
> embed.set_author("AmeLooksSus")
> 
> url = embed.generate_url(hide_url=True)
> print(url)
> ```

### Limitations

 It prolly doesn't work, cus I'm a beginner?
 
