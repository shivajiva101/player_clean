# Player Clean

Cleans players of specified items and resets privileges.

## Commands

* `/clear <player_name>` -- for use after a player joins.

* `/pcwl (<add | remove>) <player_name>` add/remove player to/from the whitelist, use /pcwl to see the list

## Privileges

* `pcadmin` allows use of `/clean` and `/pcwl` commands.

## Functions

This mod adds `pclean.on_join` & `pclean.reset_privs` to `minetest.conf` to
override the defaults.  
Valid options are true or false.

**Note:** Owner is automatically exempt from being cleaned!
