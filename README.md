# Community-Bridge 1.11

The original community bridge plugin for Minecraft, developed back in 2012 and based off work by Chiller.

This code was the last build before I stopped working on the plugin, I've put it up here just for archival purposes.

-----

As I have closed my Forums I needed a way to still track users and publish information on my site so I have added a new feature that allows the creation of database records for users. This is a work in progress and there will be some updates in the coming days as I finalise it but I have posted the new version so you can try it out if you like. There is only one new line in the config called "create-players" which is either TRUE or FALSE. If set to true then it will insert a record into the USERS table for the players when they connect. This does not support multi-table systems yet I am working on that.

First thing is first, credit goes to Chiller for the base to which this plugin is based off. His work with ForumBridge was what inspired me to update and add to his already great plugin. So in essence this is a continuation of Chiller's ForumBridge plugin, I have added some new features and cleaned up a few small bugs. I have also added some basic statistics tracking and the ability to set requirements to play on the server. There are a whole slew of features available in this release and more to come in time. So the reason its not ForumBridge is because its more of a CommunityBridge in my opinion as its not limited to using just forums as a base point for access control.​

# Change Log

Version 1.11:
- Fixed a bug where it would not set players offline on disconnect when using single table or multi-table with key.
- Creates users properly now
Version 1.10:
- Added a new feature to create database records for new players this currently only supports single tables and is a work in progress.
Version 1.07:
- Added secondary timer option to remind unregistered users more frequently to register (Requested by Ablac)
- Compatable with 1.2.5-R4
Version 1.05:
- Fixed some broken Commands
- Plugin disables itself when there is a SQL query problem
- Better SQL Connection checks before queries
Version 1.04:
- Fixed Permission Names
- Updated Commands
Version 1.02:
- Fixed bPermissions
Version 1.01:
- Added comments to default config.yml
- Fixed missing value from config.yml
Version 1: Initial Release
