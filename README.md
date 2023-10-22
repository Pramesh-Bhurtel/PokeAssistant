⚠️| Added better troubleshooters in PokéAssistant `v3.8.9`. The bot will auto-update!
:--- | :---

# PokéAssistant

**[Free]** Amazing Pokétwo Assistant that identifies Pokémons from Pokétwo spawns, pings a role if a legendary spawns and pins them, pings you if your Shiny Hunt Pokémon spawns and other features like Quest Ping! Every features are automated.

__**This bot is `not` against Discord TOS**__

## Information
PokéAssistant is a bot aimed to help Pokétwo players. It will tell you what Pokémon it is whenever Pokétwo spawns one along with many other features. As such, you no longer have to rack your brains or even search Google. Sometimes, you may just miss a rare Pokémon like this.
## License
There is no license for PokéAssistant. This ensures you are not allowed to redistribute or change the code.
## Features
### Read [this](https://github.com/TrashUwU/PokeAssistant#extra-features) if your bot is working and you want to install more features.
- Harmless and Beginner-Friendly
- Works on your own bot
- Anti-Sniper
- Fast and light
- Can be hosted 24/7 on cloud or on PC
- Auto-updates code
- Uses AI to identify Pokémons
- 85% Accuracy because of small dataset, how much do you expect from free REPLIT?
- Returns 1-3 Pokémons as prediction
- Pins good spawns
- DMs you, if your Shiny Hunt Pokémon spawns
- Pings other members in your server, if their Shiny Hunt Pokémon spawns
- Pings a specific role when rare Pokémons spawn
- Returns prediction containing 3 Pokémon images and names, if there are many results
- No ads **(Premium)**
- Faster Prediction **(Premium)**
- Decreased Rate Limit **(Premium)**
- Rare Pokémon Lock **(Premium)**
- Automated Who's-That-Pokémon feature **(Premium)**
- Pings for Quest (If one spawns from given Region) **(Premium)**
- Remove `prefix!join` message and reaction **(Premium)**
- Custom Embed Design **(Exotic)**



## Extra Features
> These features are disabled/enabled by default. Follow the setup-instructions to toggle them.

| **Name**      | **Description** | **Setup**   |
| :---:        |    :---:   | :---: |
| **🔍 Quick Find**      | The bot will identify the Pokémon if it finds a spawn in any Channel or Server.       | From https://replit.com/repls, open your bot Repl, go to `Secrets (Environment Variables)` open `CHANNEL` secret. Now clear the channel ID(s) in value section and paste `000`. Click `Save`. Wait for it to restart after 30 minutes.  |
| **🏓 Role Ping**   | The bot will ping a specific role if an Ultra Beast, Alolan, Galarian, Legendary or Mythical Pokémon Spawns. `Quick Find` feature should be enabled for better performance. | From https://replit.com/repls, open your bot Repl, go to `Secrets (Environment Variables)` create a Secret with Key `ROLE` and Value will be the Role name or ID which will be pinged if a rare pokémon spawns.  Click `Save`. Stop the code and run agian or wait for it to automatically restart after 1-12 hours. |
| **💪 Mass Ping**   | Made for Mass Shiny Hunt Tag. People who have `Sh POKEMONNAME` in server-nickname will get pinged if any `POKEMONNAME` spawns.  `Quick Find` feature should be enabled for better performance.   | From https://replit.com/repls, open your bot Repl, go to `Secrets (Environment Variables)` create a Secret with Key `PING` and Value will be `True`. To restrict SH Ping to SH only channels, create a Secret with Key `SCH` and Value will be the Channel ID(s) of SH channels (Separate with `,`). To disable, delete the secret called `PING` or set the value to `False`. Stop the code and run agian or wait for it to automatically restart after 1-12 hours. |
| **❌ Non Explicit**   | The bot will not ping for `Mass Ping`, `Role Ping` and `Quest Ping` feature if it's confidence is low. | From https://replit.com/repls, open your bot Repl, go to `Secrets (Environment Variables)` create a Secret with Key `EXPLICIT` and Value will be `False`. To disable, delete the secret called `EXPLICIT` or set the value to `True`. Stop the code and run agian or wait for it to automatically restart after 1-12 hours. |
| **🏹 Poké Hunt**   | The bot will DM the owner if a given Pokémon Spawns.  `Quick Find` feature should be enabled for better performance.   | From https://replit.com/repls, open your bot Repl, go to `Secrets (Environment Variables)` create a Secret with Key `HUNT` and Value will be a Pokémon name. Owner will get pinged if that Pokémon spawns, useful for Shiny Hunt. Click `Save`. Stop the code and run agian or wait for it to automatically restart after 1-12 hours.  |
| **🚫 Anti Snipe**   | The bot will warn snipers if they are caught. (Snipers catch Pokémons but do not help Pokémons spawn by sending messages) `Quick Find` feature should be enabled for better performance. | From https://replit.com/repls, open your bot Repl, go to `Secrets (Environment Variables)` create a Secret with Key `SNIPE` and Value will be `True`. Click `Save`. To disable, delete the secret called `SNIPE` or set the value to `False`. Stop the code and run agian or wait for it to automatically restart after 1-12 hours. |
| **📌 Auto Pin**   | The bot will pin Ultra Beast, Alolan, Galarian, Legendary or Mythical spawns. `Quick Find` feature should be enabled for better performance. | From https://replit.com/repls, open your bot Repl, go to `Secrets (Environment Variables)` create a Secret with Key `PIN` and Value will be `True`. Click `Save`. To disable, delete the secret called `PIN` or set the value to `False`. Stop the code and run agian or wait for it to automatically restart after 1-12 hours. |
| **🎈 Custom Prefix**   | The prefix of the bot will be changed. | From https://replit.com/repls, open your bot Repl, go to `Secrets (Environment Variables)` create a Secret with Key `PREFIX` and Value will be two letters. Example: `pk`, commands will look like `pk!join`. Click `Save`. To disable, delete the secret called `PIN` or set the value to `False`. Stop the code and run agian or wait for it to automatically restart after 1-12 hours. |
| **🧠 Hint Identifier**   | The bot will retrieve the Pokémon name from Hint. Type hint command in Pokétwo and the bot will respond. | From https://replit.com/repls, open your bot Repl, go to `Secrets (Environment Variables)` create a Secret with Key `HINT` and Value will be `True`. Click `Save`. To disable, delete the secret called `HINT` or set the value to `False`. Stop the code and run agian or wait for it to automatically restart after 1-12 hours. |
| **🔪 Anti SH/Quest Steal**   | Mutes the user if they are caught stealing SH/Quest. And unmutes after 60 minutes + Restores all roles. | Mention your bot for help, and use the `<prefix>punish` command. |
| **🧩 Quest Ping**   | **Premium Feature**, the name describes everything. | Mention your bot for help, and use the `<prefix>quest` command. |
| **❓ Who's-That-Pokémon** | **Premium Feature**, send a spawn image in a given channel, the bot will say the name. | Mention your bot for help, and use the `<prefix>who` command. |

## FAQs
### Is it harmful?
The bot is not against Discord TOS. But do not show your bot token to others.
### How do I restart the bot?
Type `prefix!reboot` to reboot your bot! Ping your bot to see the prefix.