# ONLY TRANSLATE STUFF `"quotes"`, and `'apostrophies'`

```py
async def pp_size(ctx):
        '''Mesures ya dick and tells you the size'''
        channel = client.get_channel(899378836968439878)
        size = random.randint(1, 500)
        print(f'{ctx.author} got {size} in {ctx.guild} server')
        if size == 152:
            yes=random.randint(ppsize.mx, ppsize.rare)
            if yes == ppsize.rare:
                embed = discord.Embed(title = f"{ctx.author} your pp size is...", description = ("501 inches, wait something ain't right here"), color = 0x5867f2)
                print(ctx.author, "GOT 501 inches!!")
                await ctx.response.send_message(embed = embed)
                await channel.send(f'ATTENTION @everyone, user <@{ctx.author.id}> got the RAREST dick size, 501 inches is impossible but they still got it, congrats! ')
                f = open("ppsize.scp079", "a")
                f.write(f'{ctx.author} =>\t\t')
                f.write('501!\n')
                f.close()
            else:
                embed = discord.Embed(title = f"{ctx.author} your pp size is...", description = ("500 inches"), color = 0x5867f2)
                await ctx.response.send_message(embed = embed)
                f = open("ppsize.scp079", "a")
                f.write(f'{ctx.author} =>\t\t')
                f.write(f'500\n')
                f.close()

        elif size == 335:
            rare=random.randint(1, 500)
            if rare == 470:
                embed = discord.Embed(title = f"{ctx.author} your pp size is...", description = ("hold up, wait a minute, we're having an error... your pp size is 502 somehow?"))
                await ctx.response.send_message(f"yo <@&910068859573256212> look at this...",embed = embed)
                print(ctx.author, "GOT 502 inches!!")
                f = open("ppsize.scp079", "a")
                f.write(f'{ctx.author} =>\t\t')
                f.write('502?\n')
                f.close()
            else:
                embed = discord.Embed(title = f"{ctx.author} your pp size is...", description = (f"{rare} inches"))
                await ctx.response.send_message(embed = embed)
                f = open("ppsize.scp079", "a")
                f.write(f'{ctx.author} =>\t\t')
                f.write(f'{size}\n')
                f.close()
        else:
            embed = discord.Embed(title = f"{ctx.author} your pp size is...", description = (f"{size} inches"), color = 0x5867f2)
            await ctx.response.send_message(embed = embed)
            f = open("ppsize.scp079", "a")
            f.write(f'{ctx.author} =>\t\t')
            f.write(f'{size}\n')
            f.close()
```
