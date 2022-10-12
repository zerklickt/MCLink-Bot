# MCLink-Bot
A Discord bot to crosslink your Discord server with your minecraft server

This bot was created to allow chatting between a Discord Server and a Minecraft Server.
Users can write in a specified text channel on Discord and have their messages broadcasted to everyone on a Minecraft Server. If you are a player on that Minecraft Server, type /dc <your Message> to respond.
  
  Get it here!
  [Downloads](https://github.com/zerklickt/MCLink-Bot/releases)

## How to use
1. Download jar file and place it in your plugins folder
2. Run the server at least once to create a plugin folder with a config.yml in it
3. Create a new Discord Application. I'm afraid I can't setup one Application for every single bot, but since Discord offers creating applications yourself (for free), this should be a minor issue. I won't go into detail on how to create such an application (there are SEVERAL tutorials on the internet and Discord offers a guide by themselves)
However, once you've created a new application, create a new bot user and copy the bot token, you'll need it later inside your config.yml. **Don't ever give this bot token to anyone else!** Everyone who's in possession of that token can control your bot by remote. **If you think the token has been leaked, generate a new one**
4. It's time to invite your bot to your Discord Server! To do that, open the following URL in your browser and replace "YOUR_CLIENT_ID" with the Client ID of the bot you've just created 
https://discord.com/oauth2/authorize?client_id=INSERT_CLIENT_ID_HERE&scope=bot&permissions=67595328 
You may be wondering why the bot requires quite a few permissions, and that's justified. Being sceptical is nowadays key to browse the web safely. The reason is that I added some more permissions thinking of features that will be implemented in the future. If any of these features required a permission the bot hadn't been granted yet, you'd have to re-invite the bot to your server. This is something that might become annoying if you had to do this several times because of every single new feature, which is why I bundled it all into a one-time-job. If you feel uncomfortable by granting all the permissions, you can disable them individually. However, depending on which permission you disabled, this might lead to the bot malfunctioning. If that's the case, re-inviting the bot with more permissions should do the job.
5. After you created the application and copied the token, head to the plugin.yml file and replace the "token" placeholder with your personal token.
6. Almost done! You need to specify the text channel which will be used for cross-platform chatting. To do that, right-click the corresponding text channel and click "Copy ID" (if this option is not being displayed to you, you might need to turn on developer mode in Discord's settings). Replace the placeholder with the ID and save the config.
7. Reload the server - Done!


### List of current features:
- Sending messages from Discord to Minecraft and vice versa
- Retrieve a list of players being online by typing "-whoison" in Discord

### List of upcoming features:
- Chatting using Discord's private textchannels to allow individual conversations
- Player stats

If you are missing any features, feel free to write me an Email :)

## What's left to say?
Thank you for using my bot! For now I won't be sharing the source code, but if you wish to get it, just write me an Email :) You may also reverse-engineer it, I honestly don't really care. I just want to give the possibility of linking Minecraft with Discord to everyone out there, which is why I don't insist in you following any strict copyright guidelines.
