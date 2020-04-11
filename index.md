# Lock Bot Certified Server Templates
All documentation on this page is subject to version 2 and will not apply to version 1.18. All documentation is subject to change. Here you will find how to setup our Staff certified server layouts, you will only find certified templates on this GitHub page or the LockBot website!

# Bot Links:
- **[LockBot V2 Invite Link](https://discordapp.com/oauth2/authorize?client_id=422082687310888971&permissions=0&scope=bot)**
- **[Discord Server Invite](https://discord.gg/9t2csSh)**
- **[LockBot Website](https://support.lockbot.network/)**

# Server Templates:

LockBot is providing certified Discord server templates to ensure that our users get the most out of our bot without the hassle of having to redo your whole server just so you can get the bot to work, below you can see a list of available templates. ***Also, these templates are made to work with Lock Bot but if you just want the template be my guest, use it!***

| Server Templates | Link |
| ------ | ------ |
| LockBot Simple V1 | https://discord.new/a4TvV2KZAn2n |

```sh
To request another template please view the LockBot Main Server and contact @Soocle#5944!
```

# Server Setup:
Since all layouts have been extensively tested and are all with the same permission layouts, these are the most effcient ways to use the `m-mode` command and the most efficient ways to unlock the server with `m-unlock`.

### Method #1:
> Run the command and unlock **all** public chat channels with `.m-unlock 2 [category name]`

> **DO NOT** use the category unlock on any other categories.

> To unlock the normal information category:
-  Right click the Information Category
- Go to Edit Category
- Permissions
- Scroll to the `@everyone` role and allow Read Text Channels and See Voice Channels

And that's it! You have successfully unlocked your server without the hassle of having to mess with so many role permissions! Once you unlock your channels you can then delete the `#maintenance-mode` channel at the top of your channel list

### Method #2: 
Since you have already been in the `m-mode` state and the server is locked, you can unlock the whole server if you don't mind people seeing any of the staff channels by:

> Run the command `.m-unlock 1` to unlock your whole server

> To relock the Normal Information Category:
-  Right click the Information Category
- Go to Edit Category
- Permissions
- Scroll to the `@everyone` role and Deny the Send Messages permissions

> To relock the Logs Category
-  Right click the Server Logs Category
- Go to Edit Category
- Permissions
- Scroll to the `@everyone` role and Deny the Send Messages permissions

> To relock the Staff Channels Category
-  Right click the Staff Channels Category
- Go to Edit Category
- Permissions
- Scroll to the `@everyone` role and deny the Read Text Channels and See Voice Channels permission.


## PLEASE NOTE THAT THESE ARE THE RECOMMENDED METHODS TO UNLOCK YOUR SERVER TO AVOID CONFUSION!
