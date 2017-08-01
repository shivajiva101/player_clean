# player_clean
Minetest mod - cleans players of specified items and resets privileges.

Adds the commands:

/clear <player_name> -- for use after a player joins.

/pcwl {add|remove} <player_name> -- add/remove player to the whitelist, use /pcwl to see the list

Adds the privilege: pcadmin -- allows use of /clean and /pcwl commands

Add pclean.on_join & pclean.reset_privs to minetest.conf to
override the defaults, valid options are true or false.
