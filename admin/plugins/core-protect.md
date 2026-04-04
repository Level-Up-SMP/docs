# Core Protect

[Official CoreProtect Documentation](https://docs.coreprotect.net/)

Core Protect is a block logging plugin that allows us to track what happens in the world and who is responsible for what changes. It also gives us the unique ability to "rollback" or undo certain actions at various times and places throughout the server.

## Inspection Tool

The inspection tool is one of the quickest and fastest ways to check for block and container interaction.

Run the command `/co inspect` to enable the inspection tool.

Then right click on the block/door/container/etc to check the transaction log.

Run the same `/co inspect` command to disable the tool.

## Lookup Command

The lookup command is mostly useful when you would like to look at a particular player's activity.

The lookup parameters are as follows: `u:<user> t:<time> r:<radius> a:<action> i:<include> e:<exclude>`

To view all of the actions for a player in the last 5 minutes, you can run `/co lookup u:USERNAME time:5m`

If you would like to view all of the action of a player within a 5 block radius of where you are standing, you can run `/co lookup u:USERNAME r:5`

All parameters can be defined, but please ensure you are entering them correctly.

## Rollback Command

The rollback command is especially useful for undoing mistakes.

In most cases, you'll run it with a combination of `time` and `radius` parameters.

To rollback all blocks that were changed in the last 2 minutes and within a 10 block radius, you would run the command `/co rollback t:2m r:10`
