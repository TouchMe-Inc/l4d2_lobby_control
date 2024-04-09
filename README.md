# About lobby_control
The plugin allows you to delete the lobby and restore it.

In order for the server to participate in the search for games, but have all the benefits of a remote lobby, you must use the following parameters:
```
sb_all_bot_game "0"                           // Disables reading the server.cfg file before creating a lobby sv_allow_lobby_connect_only 1.
sv_allow_lobby_connect_only "1"               // If set to 1, players may only join this server from matchmaking lobby, may not connect directly.
sm_cvar sm_auto_lobby_remove "1"
```
