# Dude, where are my tools?
This addon is a little helper that remembers where you put your unbreakable tools and put that info on your login screen to find them at a quick glance.

<img width="301" height="326" alt="image" src="https://github.com/user-attachments/assets/beb957d9-8666-4db5-88ca-84bc6c62b137" />


### Data initialization
It is not possible to read each character's equipment while on the login screen. The addon will learn which characters have which tools while running.

If you want, you can speed up discovery by addin an API key in the addon settings. Mind that it may take a while depending on response time and availability of the GW2 API.
**Adding an API key is entirely optional. You can initialize the addon completely by just logging into each alt once.**

**Note for multi-account users:** you can add as many keys as you want. The addon tries to read the equipment data for each of your characters of the account
currently logged into. If a key does not have the permissions to read that data (i.e. key of a different account) the request will fail and the next key will be used
for the next attempt.

### Display
- on login screen, characters with unbreakable tools will have the type of tool printed on the character slot
- when hovering the tooltip will display which tools that character has by name
- you can bind a hotkey to toggle a panel with the info in the addon settings

*Note: characters that have no data loaded yet or no tools equipped may show up with an error message in the panel.*

# Disclaimer
The addon accesses data and functions by Guild Wars 2 using information in memory. As such it has to remain closed source.
All sources have been reviewed by Raidcore.gg and are found to be in accordance with the [Raidcore.gg Addon Policy](https://discord.com/channels/410828272679518241/1259477034959114341/1259544667670712382).

The ArenaNet [Terms of Service](https://www.arena.net/en/legal) and [Third Party Programs Policy](https://help.guildwars2.com/hc/en-us/articles/360013625034-Policy-Third-Party-Programs) apply in their current version.
