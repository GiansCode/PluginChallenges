# PluginChallenges
Kick start your Bukkit development career with these simple challenges!

1. **Environment Setup**
   1. Create a Maven Project, and implement the Bukkit API for the latest Minecraft version
   1. Setup the debugger in your IDE to easily test/debug your plugins
1. **First Command**
   1. Create a plugin that, when a player executes */hello*, it sends them a message back saying hi
1. **Command Arguments**
   1. Create a plugin that, when a player executes */heal*, it fills their health
   1. Add an additional command, */feed*, that fills their hunger bar
   1. Create a command argument, */heal|feed [player]*, that heals/feeds the specified player if they are online
1. **Broadcasting Messages**
   1. Create a plugin that, when a player executes */fakejoin [player]*, it broadcasts a message saying the specified player joined
   1. Add an additional command */fakeleave [player]*, that loops through all online players, and sends them a message saying the specified player left
1. **Event Handling**
   1. Create a plugin that, when a player joins the server, it sends them a Title and Subtitle saying "Welcome to", "My server"
   1. Add a feature where if they right click any Block, it tells them what block they have right clicked; formatted nicely
1. **Configuration**
   1. Expand upon the right click a Block plugin, but, make it only message them if they click a block specified in the configuration file
1. **Permissions**
   1. Expand upon the right click a Block plugin, but, make it only message them if they have the *"notify.block"* permission
