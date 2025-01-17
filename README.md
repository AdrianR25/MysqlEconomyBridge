### MySQL Economy Bridge Bukkit/Spigot Minecraft Plugin

**About** | *Sync your local economy system using Vault on a MySQL Database, to share the economy accounts across more servers. Usefull for game hubs.*

**About Fork** | *The purpose of this fork is to update the plugin to 1.17.1, as well as fixing the old JDBC driver class being used*

**How does it work?** | *It usses the login and disconnect events to sync the economy.*
- If you have an local economy account with money on it when you disconnect/leave the server it will upload your money to the mysql database.
- When you join a server it will check the database for your account and move the money to the local economy on the server you just joined.

**Features :**
* Mysql Database
* Online and Offline UUID support
* Light

**Dependency** | To install it on you need a Spigot server with Vault and any economy system installed. And a mysql database server.

> To compile it you need Spigot 1.17.1 and Vault.

![GitHub Logo](http://www.spigotmc.org/data/resource_icons/6/6174.jpg?1429384324) **Download the plugin over Spigot (original plugin, not this fork):**
#### [Download](http://www.spigotmc.org/resources/mysql-economy-bridge.6174/)
