# NoEncryption
NoEncryption is a very simple plugin designed that removes the signature from player messages. This means that your players won't be chat reported!  
This fork only exists to be on the SaveMinecraft GitHub account. It will be as updated as <a href="https://github.com/Doclic/NoEncryption">Doclic/NoEncryption</a> and will have the same releases.  
If you want to create an issue or pull request, create on the original repo.  
I won't check issues here.  
  
<b>This plugin won't allow banned players to join.</b>

## Installation
Simply add the jar to the plugins directory!  
When updating the plugin, your players need to disconnect for the changes to work.  

## Usage
The plugin is always on. Your players should never get reported.  
  
If when loading the plugin, you receive this error message: "Failed to setup NoEncryption's compatibility!", this means that your Minecraft version isn't compatible with the plugin.  
I'll update the plugin every time a new Minecraft version releases.

## Why this works
Since 1.19, chat messages are digitally signed. This means that your messages have a number attached with them that proves your are the one that wrote it. It works similarly to a real life signature, except that it's way more secure.  
This plugin removes this signature from your messages, so Microsoft will have no way to know that you didn't lie to the system when issuing a report.
