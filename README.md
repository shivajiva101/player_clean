# Player Clean

Cleans specified items and resets privileges of player.

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

## Requirements

- default (included in [minetest_game](https://github.com/minetest/minetest_game))
- MT/MTG 5.0.0+.
