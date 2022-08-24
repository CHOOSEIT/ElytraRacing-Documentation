---
description: From 1.5.1
---

# 👁 Default Config Files

{% hint style="success" %}
If you want other languages look at this page:
{% endhint %}

{% content-ref url="broken-reference" %}
[Broken link](broken-reference)
{% endcontent-ref %}





<details>

<summary>Config.json</summary>

{% code title="" lineNumbers="true" %}
```json
{
  "DOCUMENTATION_LINK": "https://chooseit.io/elytraracing",
  "PREFIX": "&fElytraRacing &c>> &f",
  "RELOADINTERVALOBJECTS": 10,
  "auto_add_prefix": true,
  "max_info_per_page": 10,
  "ParticleRatio": 4,
  "ER_SHOW_TRAIN": true,
  "ER_SHOW_PLAY": true,
  "PERMISSION_SIGN": "elytraracing.sign",
  "PERMISSION_ER_PLAY": "elytraracing.play",
  "PERMISSION_ER_TRAIN": "elytraracing.train",
  "ER_TRAIN_MAPS": [],
  "ER_TRAIN_ENABLE": true,
  "ER_TRAIN_ENABLED": "&c",
  "ER_TRAIN_MAP_NOTFOUND": "&cThis map is not eligible for training",
  "ER_TRAIN_CHOOSE_MAP_GUI_TITLE": "Choose a map",
  "SIGN_RELOAD_SEC": 3,
  "TELEPORT_SOLVER": false,
  "UNLOCK_DISTANCE": 100,
  "UNLOCK_OBJECT": "&fUnlocked object",
  "LOCK_OBJECT": "&fLinked this object with you &asuccessfully",
  "LOCK_ITEMS_GIVE": "&fItems have been &asuccessfully &fgiven",
  "LOCK_OBJECT_NEAR_NOTFOUND": "&cNo object have been found near you",
  "ITEM_DEFAULT_PRECISION_LOC": 0.25,
  "ITEM_DEFAULT_PRECISION_DEGREE": 2.5,
  "SEPERATE_GAMES_HIDE_PLAYERS": true,
  "CUSTOM_AND_SEPARATED_CHAT": false,
  "CUSTOM_CHAT_FORMAT": "&6{PLAYER} &f>> {MESSAGE}",
  "PARTICLE_VIEW_DISTANCE": 250,
  "HOLOGRAMS_UPDATEINTERVAL": 60000,
  "HOLOGRAMS_LINESPACE": 0.29,
  "HOLOGRAMS_RANK_LIMIT": 15,
  "HOLOGRAMS_FAKE_LINES": false,
  "HOLOGRAMS_PERSONAL_MAPS_MAX": 10,
  "HOLOGRAMS_0_SHOW": true,
  "HOLOGRAMS_RANK_DUPLICATION": true,
  "REPLAY_FORMAT_16MAXCHAR": "&7{MINUTES}m {SECONDS}.{MILLISECONDS}s",
  "SQL_LOCATION": "/database",
  "SQL_STATS_INTERVAL": 10000,
  "SQL_USE_CUSTOM_SQL": false,
  "SQL_CUSTOM_SQL_HOST": "",
  "SQL_CUSTOM_SQL_PORT": "",
  "SQL_CUSTOM_SQL_DATABASE": "",
  "SQL_CUSTOM_SQL_USER": "",
  "SQL_CUSTOM_SQL_PASSWORD": "",
  "SQL_CUSTOM_SQL_TYPE": "mysql",
  "SQL_SAVE_HOST_STATS": true,
  "TimerStart": 30,
  "TimerStart_host": 10,
  "Max_maps_per_games": 4,
  "Max_alert_host": 3,
  "GUI_MAPTESTING_MAXPLAYER": 10,
  "GUI_MAPTESTING_PERMISSION": null,
  "AutoTP_Spec_Distance": 75,
  "TP_ON_HIT": true,
  "LineHelper": true,
  "NEXT_CHECKPOINT_PARTICLE": "END_ROD",
  "CHECKPOINT_TELEPORT_MIDDLE": false,
  "ELYTRA_MODELDATA": -1,
  "TimerRound": 15,
  "MAP_DIFICULTY": true,
  "MAP_DIFFICULTY_DEFAULT": 3,
  "MAP_DIFFICULTY_MAX": 5,
  "MAP_DIFFICULTY_SYMBOL": "✮",
  "MAP_DIFFICULTY_SYMBOL_ACTIVECOLOR": "&e",
  "MAP_DIFFICULTY_SYMBOL_ACTIVECOLOR_MAX": "&c",
  "MAP_DIFFICULTY_SYMBOL_MAX": true,
  "MAP_DIFFICULTY_SYMBOL_ACTIVECOLOR_LAST": "&6",
  "MAP_DIFFICULTY_SYMBOL_COLOR": "&7",
  "MAP_DIFFICULTY_MESSAGE": "&7Map difficulty: {DIFFICULTY}",
  "DNF_POINT": -1,
  "TABLIST_GRANDPRIX": true,
  "COMMANDS_WHITELIST": false,
  "COMMANDS_WHITELIST_COMMANDS": [
    "msg",
    "rl",
    "reload"
  ],
  "COMMANDS_WHITELIST_BYPASS_PERMISSION": "elytraracing.wlcommands.bypass",
  "COMMANDS_MESSAGE": "&cYou can't perform this command here !",
  "SPECTATOR_ITEM": true,
  "STATIC_ITEMS": true,
  "RankingMaxPlayers": 8,
  "PODIUM_FIREWORKS": true,
  "PODIUM_FIREWORK_NUMBER": 10,
  "END_TIME": 30,
  "DISABLE_ELYTRA": false,
  "COMMAND_EXECUTION_PER_RANK_IN_HOST": false,
  "COMMAND_EXECUTION_PER_RANK_GRANDPRIX": {
    "-1": "[CONSOLE]/give {SELF_PLAYER} minecraft:cookie {SCORE} §%§[PLAYER]/tell {SELF_PLAYER} you executed a command",
    "0": "[PLAYER]/tell {SELF_PLAYER} you executed a command"
  },
  "COMMAND_EXECUTION_PER_RANK_RACEMODE": {
    "-1": "[CONSOLE]/give {SELF_PLAYER} minecraft:cookie 5 §%§[PLAYER]/tell {SELF_PLAYER} you executed a command",
    "0": "[PLAYER]/tell {SELF_PLAYER} you executed a command"
  },
  "PERMISSION_MESSAGE": "&cYou are not allowed to perform this command",
  "PERMISSION_MESSAGE_HOST": "&cYou are not allowed to join this game",
  "MSG_NUMBER_LAP": "&eNumber of lap(s): {LAPS}",
  "HOLOGRAM_NOT_FOUND": "&cThis hologram can't be found.",
  "ITEM_1CP_BACK": "&cPrevious checkpoint",
  "ITEM_1CP_BACK_MATERIAL": null,
  "ITEM_1CP_BACK_SLOT": 0,
  "ITEM_2CP_BACK": "&c2 checkpoints back",
  "ITEM_2CP_BACK_MATERIAL": null,
  "ITEM_2CP_BACK_SLOT": 1,
  "ITEM_RESTART": "&cRESTART",
  "ITEM_RESTART_MATERIAL": null,
  "ITEM_RESTART_SLOT": 4,
  "ITEM_DNF": "&cDNF",
  "ITEM_DNF_MATERIAL": null,
  "ITEM_DNF_SLOT": 8,
  "ITEM_BED": "&cLeave game",
  "ITEM_BED_MATERIAL": null,
  "ITEM_BED_SLOT": 8,
  "ITEM_SPEC": "&aJoin spec mode",
  "ITEM_SPEC_MATERIAL": null,
  "ITEM_SPEC_SLOT": 4,
  "ITEM_CUSTOM": "&aJoin spec mode",
  "ITEM_CUSTOM_MATERIAL": null,
  "ITEM_CUSTOM_SLOT": 3,
  "ITEM_HOST": "&aHost Configuration",
  "ITEM_HOST_MATERIAL": null,
  "ITEM_HOST_SLOT": 4,
  "ITEM_PARTICLE": "&aParticle Selector",
  "ITEM_PARTICLE_MATERIAL": null,
  "ITEM_PARTICLE_SLOT": 2,
  "ITEM_FIREWORK_SLOT": 2,
  "ITEM_PAPERMAPINFO_SLOT": 4,
  "ITEM_PAPERMAPINFO_MATERIAL": null,
  "ITEM_HOSTSEPARATION_TITLE": "&fMap Selection",
  "ITEM_HOSTSEPARATION_DESCRIPTION": "&a⬇  ⬇  ⬇  ⬇  ⬇  ⬇",
  "ITEM_HOSTSEPARATION_MATERIAL": null,
  "ITEM_HOSTMAP_TITLE_SELECTED": "&a{MAP_NAME}",
  "ITEM_HOSTMAP_TITLE_NOTSELECTED": "&f{MAP_NAME}",
  "ITEM_HOSTMAP_MATERIAL_SELECTED": null,
  "ITEM_HOSTMAP_MATERIAL_NOTSELECTED": null,
  "HOSTMAP_CREATOR_INVENTORY_TITLE": "Host creator",
  "ALERT_HOST": "&6{PLAYER} &ajust started to host &7(Click here to join)",
  "ERROR_MESSAGE": "&cAn error was encounter during process",
  "ACTIONBAR_TIME": "&7Time left: &c{TIME}",
  "MSG_PAGE": "&7Page &c{PAGE} &7of &c{MAX_PAGE}",
  "MSG_ENDMAP": "&6{PLAYER} &7-> &c{ARG}",
  "MSG_GAMEFULL": "&cThis game is already full",
  "MSG_GAMESTARTED": "&cThis game is already started",
  "LOCATIONNOTDEFINED": "&cThis location isn't defined !",
  "MSG_ERHOST_LISTGAMES": "&aList of games &7&o(hover): ",
  "MSG_ERMAP_LISTGAMES_GAMESFORMAT": "&c>> &f{GAME_NAME} ",
  "MSG_ERMAP_LISTCHECKPOINT": "&aList of checkpoints &7&o(hover): ",
  "DEFAULT": "&6DEFAULT",
  "NONE": "&6NONE",
  "NOBODY": "Nobody",
  "MSG_ERMAP_LISTCHECKPOINT_CHECKPOINTFORMAT": "&f#{CHECKPOINT_ID_ORDER} &c>> &f({X},{Y},{Z}) &7&o(Click to teleport)",
  "MSG_ERMAP_LISTEND": "&aList of ends &7&o(hover): ",
  "MSG_ERMAP_LISTEND_ENDFORMAT": "&f#{END_ID_ORDER} &c>> &f({X},{Y},{Z}) &7&o(Click to teleport)",
  "YES": "&aYes",
  "NO": "&cNo",
  "CHECK": "&a✓",
  "CROSS": "&cx",
  "MSG_STATE_WAITING": "&aWaiting",
  "MSG_STATE_STARTING": "&6Starting",
  "MSG_STATE_STARTED": "&cStarted",
  "MSG_SPEC_JOINING": "&7Joining the game as spectator...",
  "PERM_SPECGAME": "elytraracing.specgame",
  "MSG_NOGAMETOLEAVE": "&cNo need to leave, you're not in a game yet",
  "MSG_GAMENOTEXIST": "&cThis game does not exist",
  "MSG_NOTYOURHOST": "&cYou aren't the host of this game",
  "MSG_TIMERSTART": "&aTimer started",
  "MSG_TIMERCANCEL": "&cTimer cancelled",
  "MSG_HOST_NOTEXIST": "&cYour host can't be found",
  "MSG_LEAVEYOURGAME": "&cYou are already in a game",
  "MSG_GAMENOTOPEN": "&cThis is not open",
  "MSG_MAPCREATING": "&aCreating map...",
  "MSG_MAPNAMEEXIST": "&cThis map name already exists",
  "MSG_GAMENAME_EXIST": "&cThis game name already exists",
  "MSG_HOST_CREATING": "&aCreating host...",
  "MSG_CHECKPOINT_VERIFIED": "&fCheckpoint passed ! ({CHECKPOINT_PASSED} / {CHECKPOINT_MAX})",
  "MSG_LAP_VERIFIED": "&eLap completed ! ({LAP_PASSED} / {LAP_MAX})",
  "MSG_GAME_PLAYERJOIN": "&6{PLAYER_NAME} &fjoined the race ! &7&o({PLAYER_SIZE} / {MAX_PLAYER})",
  "MSG_GAME_PLAYERJOIN_PLAYERNEEDEDLEFT": " &c({PLAYER_NEEDED} left needed)",
  "MSG_GAME_PLAYERLEAVE": "&6{PLAYER_NAME} &fleft the race ! &7&o({PLAYER_SIZE} / {MAX_PLAYER})",
  "MSG_GAME_NOTENOUGHPLAYERS": "&cTimer cancelled, not enough players",
  "PLAYER_NOTFOUND": "&cPlayer not found.",
  "ERHOST_PLAYER_NOTFOUND": "&cThis player is not in your game.",
  "MSG_MAP_NOTAVAILABLE": "&cThis map is not available !",
  "MSG_MAP_NOTAVAILABLE2": "&c{MAP} isn't available !",
  "MSG_MAPNOTFOUND2": "&c{ARG} can't be found",
  "MSG_ALERT": "&cYou already sent too many alerts",
  "PARTICLE_LIST": "&7Particle list (Click to activate): ",
  "PARTICLE_LIST_ITEMS": " &7{item}",
  "PARTICLE_LIST_ITEMS_HOVER": "&7{item}: Click to activate",
  "PARTICLE_LIST_NOTFOUND": "&cThis particle type can't be found",
  "GRANDPRIX": "Grandprix",
  "RACEMODE": "Race",
  "PERSONAL_BEST": " &6&k&llol &6&lPersonal Best&k&llol",
  "TIME_NOT_FOUND": " - ",
  "RANK_NOT_FOUND": "-",
  "ER_PLAY_GAME": "&cNo game have been found !",
  "MSG_STEP_TIMER": {
    "0": "Your game is starting...",
    "1": "Your game is starting in &f1 &fsecond",
    "2": "Your game is starting in &a2 &fseconds",
    "3": "Your game is starting in &23 &fseconds",
    "4": "Your game is starting in &64 &fseconds",
    "5": "Your game is starting in &c5 &fseconds",
    "10": "Your game is starting in &c10 &fseconds",
    "30": "Your game is starting in &c30 &fseconds"
  },
  "MSG_STEPROUND_TIMER": {
    "0": "Next round is starting...",
    "1": "Next round is starting in &f1 &fsecond",
    "2": "Next round is starting in &a2 &fseconds",
    "3": "Next round is starting in &23 &fseconds",
    "4": "Next round is starting in &64 &fseconds",
    "5": "Next round is starting in &c5 &fseconds",
    "15": "Next round is starting in &c15 &fseconds"
  },
  "MSG_STEP_TIMER_MAPSTART_TITLE": {
    "0": "&c>>  GO  <<",
    "1": "&e1",
    "2": "&62",
    "3": "&c3"
  },
  "MSG_STEP_TIMER_MAPSTART_SUBTITLE": {
    "0": "",
    "1": "",
    "2": "",
    "3": ""
  },
  "MSG_PER_RANK_TIME": {
    "1": "&e{RANKING}&f: &e{PLAYER} &f>> {ARG_RANK_TIME}",
    "2": "&a{RANKING}&f: &a{PLAYER} &f>> {ARG_RANK_TIME}",
    "3": "&2{RANKING}&f: &2{PLAYER} &f>> {ARG_RANK_TIME}",
    "4": "&6{RANKING}&f: &6{PLAYER} &f>> {ARG_RANK_TIME}",
    "5": "&c{RANKING}&f: &f{PLAYER} &f>> {ARG_RANK_TIME}",
    "6": "&c{RANKING}&f: &f{PLAYER} &f>> {ARG_RANK_TIME}",
    "7": "&c{RANKING}&f: &f{PLAYER} &f>> {ARG_RANK_TIME}",
    "8": "&c{RANKING}&f: &f{PLAYER} &f>> {ARG_RANK_TIME}"
  },
  "MSG_PER_RANK_SCORE": {
    "1": "&e{RANKING}&f: &e{PLAYER} &f>> {SCORE}",
    "2": "&a{RANKING}&f: &a{PLAYER} &f>> {SCORE}",
    "3": "&2{RANKING}&f: &2{PLAYER} &f>> {SCORE}",
    "4": "&6{RANKING}&f: &6{PLAYER} &f>> {SCORE}",
    "5": "&c{RANKING}&f: &f{PLAYER} &f>> {SCORE}",
    "6": "&c{RANKING}&f: &f{PLAYER} &f>> {SCORE}",
    "7": "&c{RANKING}&f: &f{PLAYER} &f>> {SCORE}",
    "8": "&c{RANKING}&f: &f{PLAYER} &f>> {SCORE}"
  },
  "SCORING_PER_RANK": {
    "1": 15,
    "2": 12,
    "3": 10,
    "4": 9,
    "5": 8,
    "6": 7,
    "7": 6,
    "8": 5,
    "9": 4,
    "10": 3,
    "11": 2,
    "12": 1
  },
  "MSG_PRE_RANK": "&7\nRanking:\n",
  "MSG_PRE_SCORE": "&7\nScoreboard:\n",
  "MSG_YOURRANK": "&7Your rank on this map: &c{RANK}",
  "MSG_YOURSCORE": "&7Your overall rank is: &c{RANK} &7with &c{SCORE} &7points",
  "MSG_ARG_RANK_TIME_DNF": "&cDNF",
  "MSG_ARG_RANK_TIME_TIME": "&c{TIME}",
  "TELEPORTING": "&7Teleporting...",
  "TIMEFORMAT": "{MINUTES}m {SECONDS}.{MILLISECONDS}s",
  "TIMEFORMAT_WM": "{MINUTES}m {SECONDS}s",
  "PLACEHOLDER_NOTFOUND_PLAYER": "None",
  "PLACEHOLDER_DEFAULT_NUMBER": "0",
  "PLACEHOLDER_DEFAULT_TEXT": "",
  "PLACEHOLDER_DEFAULT_RANKING": "-",
  "ERMAP_MAP_DELETE": "&cThe map will be deleted after a reload/restart",
  "MSG_MAPNOTFOUND": "&cThis map can't be found",
  "MSG_SAVE_SUCCESSFUL": "&fChanges have been &asucessfully &fsaved",
  "MSG_FILE_RELOAD": "&fFile(s) have been &asucessfully &freloaded.",
  "MSG_SHOW_ON": "&aEnabling ...",
  "MSG_SHOW_OFF": "&cDisabling ...",
  "MSG_CHECKPOINT_NOTFOUND": "&cThis checkpoint can't be found",
  "MSG_END_NOTFOUND": "&cThis end can't be found",
  "ID_ORDER_ARG": "&c[id_order] must be an integer",
  "ID_ORDER_TARGET_ARG": "&c[id_order_target] must be an integer",
  "DEGREES_ARG": "&c[rotation] must be an integer",
  "MULTIPLIER_ARG": "&c[amount] must be a float",
  "SIZE_ARG": "&c[size] must be a float",
  "AMOUNT_ARG": "&c[amount] must be an integer",
  "SECONDS_ARG": "&c[seconds] must be an integer between 0 and 59",
  "MINUTES_ARG": "&c[minutes] must be an integer greater than 0",
  "MAX_PLAYER_ARG": "&c[slots] must be an integer greater than 0",
  "PAGE_ARG": "&c[page] must be an integer greater than 0",
  "ERCONFIG_SETITEM_ID_NOT_FOUND": "&cThis [id_item] can't be found",
  "ERCONFIG_SETITEM_ITEM_NOT_FOUND": "&cThe item in your hand can not be found",
  "SPEC_PERM": null,
  "SPEC_PERM_MESSAGE": "&cYou don't have permission to spectate a game.",
  "HOST_GAMENOTOPEN": "&cYour game is not open",
  "SPECTATORMODE": "&aYou have entered in spectator mode &7(Click here to leave or type '/er quitspec')",
  "STUCKSPECTATOR": "&aUse /er near §fto teleport to the nearest player",
  "AVAILABLE_MAPS": "&aAvailable maps: {MAPS}",
  "ERGAMES_LIST": "&6List of autogames: {AUTOGAMES}",
  "ERGAMES_ENABLED_PREFIX": "&a",
  "ERGAMES_DISABLED_PREFIX": "&c",
  "ERGAMES_LIST_SEPERATION_PREFIX": "&7",
  "ERGAMES_NOTFOUND": "&cThis autogame can't be found",
  "ERGAMES_ALREADYGAME": "&cYou can't enable this autogame because there is already a game with the same name",
  "TABLIST_RANK_SCORE_TITLE": "&7Scoreboard",
  "TABLIST_RANK_SCORE_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "TABLIST_GRANDPRIX_PERSONAL_PERSONAL": "&6Personal stats on this map:",
  "TABLIST_GRANDPRIX_PERSONAL_TIME": "&9Best personal time: &c{TIME}",
  "TABLIST_GRANDPRIX_PERSONAL_RANK": "&9Your rank: &c{RANK}",
  "TABLIST_GRANDPRIX_PERSONAL_WINRATE": "&9Your winrate: &c{WINRATE} %",
  "HOLOGRAMS_RANK_SCORE_TITLE": "&6&lTop 15 Highest scores",
  "HOLOGRAMS_RANK_SCORE_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "-2": "&9{RANK} &7- &9-------- &7- &c0",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_RANK_WON_RACEMODE_TITLE": "&6&lTop 15 Highest races won",
  "HOLOGRAMS_RANK_WON_RACEMODE_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "-2": "&9{RANK} &7- &9-------- &7- &c0",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_RANK_WON_GRANDPRIX_TITLE": "&6&lTop 15 Highest grandprix won",
  "HOLOGRAMS_RANK_WON_GRANDPRIX_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "-2": "&9{RANK} &7- &9-------- &7- &c0",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_RANK_MAP_TITLE": "&6&lTop 15 Best times on {MAP}",
  "HOLOGRAMS_RANK_MAP_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "-2": "&9{RANK} &7- &9-------- &7- &c0",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_PERSONAL_MAPS_TITLE": "&6&lPersonal stats on maps",
  "HOLOGRAMS_PERSONAL_MAPS_SPECIFIC": "&6{MAP_NAME} &7: &c{PLAYER_TIME} &7(#{PLAYER_RANK}) (winrate: {WINRATE}%)",
  "HOST_MAPCHOOSER_CHANGEPAGE": "Click here to change page",
  "DNF_INSTANT_QUIT": false,
  "MSG_LISTMAPS_INFO": [
    "&a>> {MAP_NAME}",
    " ",
    "&f>> &7Valid: {VALID}",
    "&f>> &7Enabled: {ENABLED}",
    " ",
    "&f>> &7Checkpoints: &c{CHECKPOINTS}",
    "&f>> &7Ends: &c{ENDS}",
    "&f>> &7Lobby location: &c{LOBBY}",
    "&f>> &7Start location: &c{START}",
    "&f>> &7End location: &c{END}",
    "&f>> &7Podium: &c{PODIUM}",
    " ",
    "&f>> &7Time max.: &c{TIME}",
    "&f>> &7Difficulty: &c{DIFFICULTY}",
    " "
  ],
  "HOST_TITLE_PERM": "&7Permission: &c{PERMISSION}",
  "HOST_DESC_PERM": [
    " ",
    "&f/erhost setperm &c[permission/none]",
    "&fTo define the permission to join your game.",
    " "
  ],
  "HOST_TITLE_ALERT": "&aAlert",
  "HOST_DESC_ALERT": [
    " ",
    "&fClick here to broadcast an invitation to join your game",
    " "
  ],
  "HOST_TITLE_START": "&aStart",
  "HOST_DESC_START": [
    " ",
    "&fClick here to start the game",
    " "
  ],
  "HOST_TITLE_END": "&cCancel countdown",
  "HOST_DESC_END": [
    " ",
    "&fClick here to stop the countdown",
    " "
  ],
  "HOST_TITLE_SLOTS": "&cSlots",
  "HOST_DESC_SLOTS": [
    " ",
    "&fNumber of slots: &c{SLOTS}",
    " ",
    "&7Left click: +1 (+ Shift: +10)",
    "&7Right click: -1 (+ Shift: -10)",
    " "
  ],
  "HOST_TITLE_OPEN": "&fYour host is currently: &aOpen",
  "HOST_TITLE_CLOSED": "&fYour host is currently: &cClosed",
  "HOSTCREATOR_CREATE_TITLE": "&aCreate the host",
  "HOSTCREATOR_CREATE_DESCRIPTION": [
    " ",
    "&fName: &c{NAME}",
    " ",
    "&fNumber of slots: &c{SLOTS}",
    "&fNumber of maps: &c{MAP_NUMBER}",
    "&fMode: &c{MODE}",
    " "
  ],
  "HOSTCREATOR_MAPS_TITLE": "&fNumber of maps: &c{MAP_NUMBER}",
  "HOSTCREATOR_MAPS_DESCRIPTION": "&f{ORDER}. {MAP_NAME}",
  "HOSTCREATOR_MAXPLAYERS_TITLE": "&fSlots: {SLOTS}",
  "HOST_MAXPLAYERS_SLOTS": [
    " ",
    "&fNumber of slots: &c{SLOTS}",
    " ",
    "&7Left click: +1 (+ Shift: +10)",
    "&7Right click: -1 (+ Shift: -10)",
    " "
  ],
  "STATES": {
    "STARTING": "&6Starting",
    "STARTED": "&cIngame",
    "WAITING": "&aWaiting",
    "FINISHED": "&7Finishing"
  },
  "SIGN_FORMAT_ONEQUEUE_ONEGAME": [
    "&f[ElytraRacing]",
    "&6{MAP}",
    "{STATE}",
    "&c{PLAYERS}/{MAX_PLAYERS}"
  ],
  "SIGN_FORMAT": [
    "&f[ElytraRacing]",
    "&6{MAP}",
    "&c{PLAYERS}/{MAX_PLAYERS}",
    "&7Click to join"
  ],
  "SIGN_FORMAT_DISABLED": [
    "&f[ElytraRacing]",
    " ",
    "&4DISABLED",
    " "
  ],
  "MSG_LISTCHECKPOINT_INFO": [
    " ",
    "&f>> &7ID: {ID_ORDER}",
    " ",
    "&f>> &7x: &c{X}",
    "&f>> &7y: &c{Y}",
    "&f>> &7z: &c{Z}",
    "&f>> &7World: &c{WORLD}",
    " ",
    "&f>> &7Radius: &c{RADIUS}",
    "&f>> &7Particle amount: &c{PARTICLE_AMOUNT}",
    "&f>> &7Boost multiplier: &c{BOOST_MULTIPLIER}",
    "&f>> &7",
    "&f>> &7Particle type: &c{PARTICLE_TYPE}",
    "&f>> &7Linked to: &c{LINK}"
  ],
  "MSG_LISTGAMES_INFO": [
    "&a>> {GAME_NAME}",
    " ",
    "&f>> &7Players: &c{PLAYER_SIZE}",
    "&f>> &7min. players: &c{MIN_PLAYER}",
    "&f>> &7max. players: &c{MAX_PLAYER}",
    " ",
    "&f>> &7State: &c{GAME_STATE}"
  ],
  "MSG_LISTEND_INFO": [
    " ",
    "&f>> &7ID: {ID_ORDER}",
    " ",
    "&f>> &7x: &c{X}",
    "&f>> &7y: &c{Y}",
    "&f>> &7z: &c{Z}",
    "&f>> &7World: &c{WORLD}",
    " ",
    "&f>> &7Radius: &c{RADIUS}",
    "&f>> &7Particle amount: &c{PARTICLE_AMOUNT}",
    "&f>> &7",
    "&f>> &7Particle type: &c{PARTICLE_TYPE}"
  ],
  "ERSTATS_MAP": "&6&lPersonal stats on maps",
  "ERSTATS_MAP_EACH": "&6>> {MAP_NAME} &9: {PLAYER_TIME} &9(#{PLAYER_RANK}) \n&6> &9(winrate: {WINRATE}%)",
  "CHANGEPAGE": "&7Click here to change page",
  "CHANGEPAGERIGHT": "&9➡",
  "CHANGEPAGELEFT": "&c⬅",
  "ERTRAIN_MAP_INFO": [
    "&fYour time: &6{PLAYER_TIME}",
    "&fYour rank: &6#{PLAYER_RANK}",
    "&fYour winrate: &6{WINRATE}%",
    " "
  ],
  "ERTRAIN_MAP_INFO_PLUS": [
    "",
    "&7Difficulty: {DIFFICULTY}",
    "&7Lap(s): &c{LAPS}",
    "",
    "&7Click here to select this map"
  ],
  "ERTRAIN_MAP_INFO_TITLE": "&f{MAP_NAME}",
  "FORCE_KICK_VERSION_BELOW_19": true,
  "PLAYER_VERSION_BELOW_19": "&cYou don't have the right version to play this game",
  "USAGE_ERSTATS_SHOW": [
    "&6&lPersonal stats: {USERNAME}",
    "&7Races played: &c{PLAYER_GAME_PLAYED_RACEMODE} ",
    "&7Races won: &c{PLAYER_GAME_WON_RACEMODE} &9(#{RANK_WON_RACEMODE}) &7({PERCENTAGE_WINRATE_RACEMODE}%)",
    "&7Grandprix played: &c{PLAYER_GAME_PLAYED_GRANDPRIX} ",
    "&7Grandprix won: &c{PLAYER_GAME_WON_GRANDPRIX} &9(#{RANK_WON_GRANDPRIX}) &7({PERCENTAGE_WINRATE_GRANDPRIX}%)",
    "&7Score: &c{SCORE_TOTAL} &9(#{RANK_SCORE_TOTAL})",
    "&6Favorite map: &6{FAVORITE_MAP} &7&o(winrate: {FAVORITE_MAP_WINRATE}%)",
    "[HOVERMESSAGE_MAP_STATS]&9Personal stats on maps &7&o(hover)"
  ],
  "HOLOGRAMS_PERSONALSTATS": [
    "&6&lPersonal stats:",
    "&7Races played: &c{PLAYER_GAME_PLAYED_RACEMODE} ",
    "&7Races won: &c{PLAYER_GAME_WON_RACEMODE} &9(#{RANK_WON_RACEMODE}) &7({PERCENTAGE_WINRATE_RACEMODE}%)",
    "&7Grandprix played: &c{PLAYER_GAME_PLAYED_GRANDPRIX} ",
    "&7Grandprix won: &c{PLAYER_GAME_WON_GRANDPRIX} &9(#{RANK_WON_GRANDPRIX}) &7({PERCENTAGE_WINRATE_GRANDPRIX}%)",
    "&7Score: &c{SCORE_TOTAL} &9(#{RANK_SCORE_TOTAL})",
    "&6Favorite map: &6{FAVORITE_MAP} &7&o(winrate: {FAVORITE_MAP_WINRATE}%)"
  ],
  "MAP_INGAME_INFO_MENU_TITLE": "&fMaps information",
  "MAP_INGAME_INFO_DESCRIPTION": [
    "&f{ORDER}. {MAP_NAME}",
    "&f-> Your stats: {PLAYER_TIME},#{PLAYER_RANK} ({PLAYER_WINRATE}%)"
  ],
  "NOTENOUGH_MAP_HOSTCREATOR": "&cYou need at least 1 map to create a host",
  "ONEGAME": false,
  "ONEGAME_AUTOJOINGAME": "",
  "ONEGAME_KICK_AFTER_GAME": true,
  "ONEGAME_LOBBYSERVER": "",
  "ONEGAME_REMOVEJOINQUITMESSAGES": true,
  "ONEGAME_MOTD_USE": false,
  "ONEGAME_MOTD": [
    "&f>> ElytraRacing: {STATE} &7[-] Map: &6{MAP}",
    "§f>> &7Playing: §c{PLAYING} &7[-] Mode: {MODE_INFORMATION}"
  ],
  "ONEGAME_MOTD_RACEMODE_INFORMATION": "&aRacemode",
  "ONEGAME_MOTD_GRANDPRIX_INFORMATION": "&aGrandPrix &f{ROUND}/{ROUND_MAX}",
  "ONEGAME_MOTD_CHANGE_MAX_PLAYERS": true,
  "CHALLENGE_MAXGAME": false,
  "CHALLENGE_MAXGAME_PER_PLAYER": 10,
  "CHALLENGE_MAXGAME_COMPLETION_COMMAND": "[CONSOLE]/give {SELF_PLAYER} minecraft:cookie §%§[PLAYER]/tell {SELF_PLAYER} you executed a command",
  "PLAY_SOUND": true,
  "SOUND_START_3": "",
  "SOUND_START_3_VOLUME": 1.0,
  "SOUND_START_3_PITCH": 1.0,
  "SOUND_START_2": "",
  "SOUND_START_2_VOLUME": 1.0,
  "SOUND_START_2_PITCH": 1.0,
  "SOUND_START_1": "",
  "SOUND_START_1_VOLUME": 1.0,
  "SOUND_START_1_PITCH": 1.0,
  "SOUND_START_START": "",
  "SOUND_START_START_VOLUME": 1.0,
  "SOUND_START_START_PITCH": 1.0,
  "SOUND_CHECKPOINT_PASSED": null,
  "SOUND_CHECKPOINT_PASSED_VOLUME": 1.0,
  "SOUND_CHECKPOINT_PASSED_PITCH": 1.0,
  "SOUND_END_PASSED": null,
  "SOUND_END_PASSED_VOLUME": 1.0,
  "SOUND_END_PASSED_PITCH": 1.0,
  "SOUND_ADDITIONAL_OBJECT_PASSED": null,
  "SOUND_ADDITIONAL_OBJECT_PASSED_VOLUME": 1.0,
  "SOUND_ADDITIONAL_OBJECT_PASSED_PITCH": 1.0,
  "SOUND_FIREWORKS_VOLUME": 1.0,
  "SOUND_FIREWORKS_PITCH": 1.0,
  "WIN_RACEMODE_WITHOUT_FINISHING": true,
  "CONSOLE_USERNAME": "server",
  "RENDER_DISTANCE_CP": false,
  "RENDER_DISTANCE_CP_VALUE": 2,
  "HOOK_PARTIES_ENABLE": true
}
```
{% endcode %}



</details>

<details>

<summary>AdminGUI.json</summary>

{% code lineNumbers="true" %}
```json
{
  "world": "World",
  "id": "ID",
  "map": "Map",
  "type": "Type",
  "normal": "normal",
  "ifnext": "ifnext",
  "name": "Name",
  "linkto": "Linkto",
  "rotations": "Rotations",
  "shape": "Shape",
  "radius": "Radius",
  "valid": "Valid",
  "enabled": "Enabled",
  "checkpoints": "Checkpoint(s)",
  "ends": "End(s)",
  "aos": "Additional object(s)",
  "locations": "Locations",
  "start": "Start",
  "end": "End",
  "lobby": "Lobby",
  "boostMultiplier": "Boost multiplier",
  "fireworks": "Firework(s)",
  "cpangle": "Checkpoint angle",
  "laps": "Lap(s)",
  "lap": "lap",
  "lapMapLong": "Here you can modify the number of laps on this map",
  "thereisare": "There is/are",
  "inMapCp": "checkpoint(s) in the map",
  "inMapEnd": "end(s) in the map",
  "inMapAo": "additional object(s) in the map",
  "clickModificationCp": "Click to modify a checkpoint",
  "clickModificationEnd": "Click to modify an end",
  "clickModificationAo": "Click to modify an additional object",
  "currentDifficulty": "Current map difficulty",
  "clickDifficulty": "Click here to modify the difficulty",
  "respawnCpAngle": "Checkpoint respawn angle",
  "respawnCpAngleL1": "Click modify the angle used for the map",
  "respawnCpAngleL2": "Information:",
  "PLAYER": "PLAYER",
  "respawnCpAngleL3": "- Use the angle that the player had when he entered the checkpoint",
  "NEXT_CHECKPOINT": "NEXT_CHECKPOINT",
  "Experimental": "Experimental",
  "respawnCpAngleL4": "- Create an angle to redirect the player toward the next checkpoint",
  "respawnCpAngleL5": "This feature is only working with maps that contains §c§l1 end and no linked checkpoints",
  "clickHereDefine": "Click here to define",
  "defaultParticleCP": "default particle for checkpoints",
  "defaultParticleEnd": "default particle for ends",
  "defaultParticleAO": "default particle for additional objects",
  "mapAvailableTraining": "Map available for training",
  "clickmapAvailableTraining": "Click here to add or remove this map of the training set",
  "dbUUID": "Database UUID",
  "clickDB": "Click here to clear saved informations in the database",
  "podiumConfiguration": "Podium configuration",
  "qPodium": "Is the podium system is activated for this map ?",
  "qPodiumL1": "Command to add a new location for the podium:",
  "qPodiumL2": "/ermap map [map] podium setlocation <placement... 1, 2, 3..>",
  "qPodiumL3": "Command to teleport a location of the podium:",
  "qPodiumL4": "/ermap map [map] podium tp <placement... 1, 2, 3..>",
  "startHost": "Start an host",
  "createHostMap": "Click here to create an host using this map",
  "maxtimepossible": "Max. time possible",
  "difficulty": "Difficulty",
  "podium": "Podium",
  "particles": "Particles",
  "changeName": "Change name",
  "confirm": "Confirm",
  "cancel": "Cancel",
  "currentLaps": "Current lap(s)",
  "currentMaxTime": "Current max. time",
  "currentMaxTimeModification": "Here you can modify the maximum possible time on the map",
  "minute": "minute",
  "divideMinutes": "Divise by 2 current minutes",
  "doubleMinutes": "Double current minutes",
  "firework": "firework",
  "divideFirework": "Divise by 2 current fireworks",
  "doubleFirework": "Double current fireworks",
  "second": "second",
  "divideSeconds": "Divise by 2 current seconds",
  "doubleSeconds": "Double current seconds",
  "changeHologramName": "Change name of the hologram",
  "cmdChangeHologramName": "/erconfig holograms setname [current_name] [new_name]",
  "changeMap": "Change map",
  "changeHologramMap": "Change map associated to the hologram",
  "cmdChangeHologramMap": "/erconfig holograms setmap [hologram] [map]",
  "localisation": "Localisation",
  "leftTeleported": "Left click to be teleported",
  "clickTeleported": "Click to be teleported",
  "shiftclickDefineLocation": "Shift click to define this location",
  "rightTeleported": "Right click to be teleported",
  "leftConfigure": "Left click to configure",
  "rightChangeLocation": "Right click to change location",
  "rightDefineLocation": "Right click to define location",
  "refreshDisplay": "Refresh display",
  "clickRefreshElement": "Click here to refresh displayed elements on the hologram",
  "delete": "Delete",
  "personalMaps": "Personal maps",
  "clickCreateNewHolograms": "Click here to create a new hologram of this type",
  "personalStats": "Personal stats",
  "rankscore": "Rank score",
  "rankmap": "Rank map",
  "rankmapL1": "You have to define a map for this hologram.",
  "rankmapL2": "/erconfig holograms setmap [hologram] [map]",
  "rankwonr": "Rank won racemode",
  "rankwong": "Rank won grandprix",
  "deleteHologram": "Click here to delete this hologram",
  "currentParticle": "Current particle",
  "currentParticleLongMap": "Here you can see the current particle set for this map",
  "clickChangeParticle": "Click here to change the particle",
  "currentFireworkAmountMap": "Here you can modify the number of fireworks on the map",
  "clickChangePage": "Click here to change page",
  "particleAmount": "Particle amount",
  "information": "Information",
  "clickDefineParticleObject": "Click here to define the particle of the object",
  "currentLocation": "Current location",
  "currentParticleAmount": "Current particle amount",
  "particleAmountLong": "Here you can modify the particle amount displayed",
  "currentFireworksAmount": "Current firework amount",
  "fireworksAmountLong": "Here you can modify the number of firework given by this object",
  "leftclick": "Left click",
  "shiftleftclick": "Shift left click",
  "rightclick": "Right click",
  "shiftrightclick": "Shift right click",
  "currentRadius": "Current radius",
  "radiusmodification": "Here you can modify the radius",
  "helpMessage": "Help message",
  "helpMessageL1": "Click here to display the list of commands for ",
  "helpMessageL2": "this object that will automatically complete arguments",
  "helpMessageL2Map": "this map that will automatically complete arguments",
  "currentBoostMultiplier": "Current boost multiplier",
  "boostMultiplierModification": "Here you can modify the boost multiplier applied to the player",
  "closeMenu": "Click here to close this menu",
  "linkWithYou": "Link this object with you",
  "linkModificationL1": "Click here to link this object with you and be able to modify it.",
  "linkModificationL2": "With this link you will be able",
  "linkModificationL3": "to modify this object using items",
  "linkModificationL4": "Left click to link the object.",
  "linkModificationL5": "Right click to get items",
  "linkModificationL6": "If you are too far from the object it will",
  "linkModificationL7": "automatically unlock you.",
  "clickDelete": "CLick here to delete this object.",
  "informationConfirmationDeleteAO": "Delete an additional object",
  "informationConfirmationDeleteCP": "Delete a checkpoint",
  "informationConfirmationDeleteEND": "Delete an end",
  "createNew": "Create a new",
  "clickCreateNew": "Click here to create a new",
  "clickCreateNewCP": "checkpoint at your location",
  "clickCreateNewAO": "additional object at your location",
  "clickCreateNewEnd": "end at your location",
  "isLocationLobby": "Is lobby location is defined ?",
  "isLocationStart": "Is start location is defined ?",
  "isLocationEnd": "Is end location is defined ?",
  "locationLobby": "Lobby location",
  "locationStart": "Start location",
  "locationEnd": "End location",
  "specAndWalls": "Spec and walls",
  "qspecAndWalls": "Spec can pass through walls ?",
  "clickChangeValue": "Click here to change the value",
  "showMap": "Show map",
  "clickShowMap": "Click here to show/hide this map",
  "currentParticleSet": "Here you can see the current particle set",
  "pageHologramPage": "Hologram configuration",
  "pageAOCP": "List of additional objects",
  "pageAOP": "Additional object configuration",
  "pageConfirmationDeleteObject": "Confirmation of deletion",
  "pageCPCP": "List of checkpoints",
  "pageCPP": "Checkpoint configuration",
  "pageECP": "List of ends",
  "pageEP": "End configuration",
  "pageHCP": "List of holograms",
  "pageMCP": "List of maps",
  "pageMS": "Map settings:"
}
```
{% endcode %}



</details>

<details>

<summary>Autogames.json</summary>

{% code lineNumbers="true" %}
```json
{
  "DEFAULT_QUEUE": "play",
  "ENABLED_QUEUES": [
    "play"
  ],
  "DISABLED_QUEUES": [],
  "autoGamesList": [
    {
      "name": "default",
      "maps": [
        "",
        "",
        ""
      ],
      "minplayers": 2,
      "maxplayers": 10,
      "mapnumber": 1,
      "randomMapSorting": true,
      "enabled": true,
      "queue": "play",
      "permission": null
    }
  ]
}
```
{% endcode %}

</details>

<details>

<summary>Holograms.json</summary>

{% code lineNumbers="true" %}
```json
{
  "Holograms": [
    {
      "x": 0.0,
      "y": 0.0,
      "z": 0.0,
      "world": "<worldname>",
      "hologram_type": "PERSONAL_STATS",
      "option_map": null,
      "name": "c8a6e8"
    },
    {
      "x": 0.0,
      "y": 0.0,
      "z": 0.0,
      "world": "<worldname>",
      "hologram_type": "RANK_MAP",
      "option_map": "<map_name>",
      "name": "054ddb"
    },
    {
      "x": 0.0,
      "y": 0.0,
      "z": 0.0,
      "world": "<worldname>",
      "hologram_type": "RANK_MAP",
      "option_map": "<map_name>",
      "name": "187281"
    },
    {
      "x": 0.0,
      "y": 0.0,
      "z": 0.0,
      "world": "<worldname>",
      "hologram_type": "RANK_SCORE",
      "option_map": null,
      "name": "71a540"
    },
    {
      "x": 0.0,
      "y": 0.0,
      "z": 0.0,
      "world": "<worldname>",
      "hologram_type": "RANK_WON_GRANDPRIX",
      "option_map": null,
      "name": "f5b125"
    },
    {
      "x": 0.0,
      "y": 0.0,
      "z": 0.0,
      "world": "<worldname>",
      "hologram_type": "RANK_WON_RACEMODE",
      "option_map": "<map_name>",
      "name": "ee64d4"
    },
    {
      "x": 0.0,
      "y": 0.0,
      "z": 0.0,
      "world": "<worldname>",
      "hologram_type": "PERSONAL_MAPS",
      "option_map": "null",
      "name": "a99845"
    }
  ]
}
```
{% endcode %}

</details>

<details>

<summary>Scoreboard.json</summary>

{% code lineNumbers="true" %}
```json
{
  "Enable": false,
  "TickReloadInterval": 20,
  "link": "chooseit.io/er",
  "RaceMode": {
    "perState": {
      "HOST_WAITING": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&fPlayer(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fMap: {CURRENT_MAP}",
          "&fMode: &aRace",
          "",
          "Host: {HOST}",
          "",
          "{LINK}"
        ]
      },
      "HOST_FINISHED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&e1st - {RANK_PLAYER_1}",
          "&72nd - {RANK_PLAYER_2}",
          "&63rd - {RANK_PLAYER_3}",
          "Your rank: {SELF_RANK_PLAYER}",
          "",
          "{LINK}"
        ]
      },
      "STARTED": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "Time left: &c{TIME_LEFT}",
          "&fPlayer(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "",
          "&e1st - {RACE_RANK_PLAYER_1}",
          "&72nd - {RACE_RANK_PLAYER_2}",
          "&63rd - {RACE_RANK_PLAYER_3}",
          "Your rank: {SELF_RACE_RANK_PLAYER}",
          "",
          "Checkpoints: &6{SELF_CPS}/{MAX_CPS}",
          "Laps: &6{SELF_LAPS}/{MAX_LAPS}",
          "",
          "{LINK}"
        ]
      },
      "HOST_SPECTATOR": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "Time left: &c{TIME_LEFT}",
          "&fPlayer(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "",
          "&e1st - {RACE_RANK_PLAYER_1}",
          "&72nd - {RACE_RANK_PLAYER_2}",
          "&63rd - {RACE_RANK_PLAYER_3}",
          "&f4th - {RACE_RANK_PLAYER_4}",
          "&f5th - {RACE_RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "SPECTATOR": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "Time left: &c{TIME_LEFT}",
          "&fPlayer(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "",
          "&e1st - {RACE_RANK_PLAYER_1}",
          "&72nd - {RACE_RANK_PLAYER_2}",
          "&63rd - {RACE_RANK_PLAYER_3}",
          "&f4th - {RACE_RANK_PLAYER_4}",
          "&f5th - {RACE_RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "HOST_STARTING": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&fPlayer(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fMap: {CURRENT_MAP}",
          "&fMode: &aRace",
          "",
          "Host: {HOST}",
          "&cStarting in {STARTING_COUNTDOWN} second(s)",
          "",
          "{LINK}"
        ]
      },
      "FINISHED": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&e1st - {RANK_PLAYER_1}",
          "&72nd - {RANK_PLAYER_2}",
          "&63rd - {RANK_PLAYER_3}",
          "Your rank: {SELF_RANK_PLAYER}",
          "",
          "{LINK}"
        ]
      },
      "HOST_STARTED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "Time left: &c{TIME_LEFT}",
          "&fPlayer(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "",
          "&e1st - {RACE_RANK_PLAYER_1}",
          "&72nd - {RACE_RANK_PLAYER_2}",
          "&63rd - {RACE_RANK_PLAYER_3}",
          "Your rank: {SELF_RACE_RANK_PLAYER}",
          "",
          "Checkpoints: &6{SELF_CPS}/{MAX_CPS}",
          "Laps: &6{SELF_LAPS}/{MAX_LAPS}",
          "",
          "{LINK}"
        ]
      },
      "SPECTATOR_FINISHED": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&e1st - {RANK_PLAYER_1}",
          "&72nd - {RANK_PLAYER_2}",
          "&63rd - {RANK_PLAYER_3}",
          "&f4th - {RANK_PLAYER_4}",
          "&f5th - {RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "STARTING": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&fPlayer(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fMap: {CURRENT_MAP}",
          "&fMode: &aRace",
          "",
          "&cStarting in {STARTING_COUNTDOWN} second(s)",
          "",
          "{LINK}"
        ]
      },
      "WAITING": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&fPlayer(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fMap: {CURRENT_MAP}",
          "&fMode: &aRace",
          "",
          "&cNeed {NEEDED_PLAYER} player(s) to start",
          "",
          "{LINK}"
        ]
      },
      "HOST_SPECTATOR_FINISHED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&e1st - {RANK_PLAYER_1}",
          "&72nd - {RANK_PLAYER_2}",
          "&63rd - {RANK_PLAYER_3}",
          "&f4th - {RANK_PLAYER_4}",
          "&f5th - {RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      }
    }
  },
  "GrandPrix": {
    "perState": {
      "HOST_WAITING": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&fPlayer(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fMap: {CURRENT_MAP}",
          "&fMode: &aGrandPrix",
          "Round: 1/{MAX_ROUND}",
          "",
          "Host: {HOST}",
          "",
          "{LINK}"
        ]
      },
      "HOST_BETWEENROUND": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "Next map: {CURRENT_MAP}",
          "{CURRENT_MAP_DIFFICULTY}",
          "&6PB: {SELF_MAP_PB}",
          "",
          "&e1st - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72nd - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63rd - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "Your rank: {SELF_RANK_PLAYER}",
          "Your score: {SELF_RANK_PLAYER_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "HOST_SPECTATOR": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "Time left: &c{TIME_LEFT}",
          "&fPlayer(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "Round: {CURRENT_ROUND}/{MAX_ROUND}",
          "",
          "&e1st - {RACE_RANK_PLAYER_1}",
          "&72nd - {RACE_RANK_PLAYER_2}",
          "&63rd - {RACE_RANK_PLAYER_3}",
          "&f4th - {RACE_RANK_PLAYER_4}",
          "&f5th - {RACE_RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "HOST_STARTING": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&fPlayer(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fMap: {CURRENT_MAP}",
          "&fMode: &aGrandPrix",
          "Round: 1/{MAX_ROUND}",
          "",
          "Host: {HOST}",
          "&cStarting in {STARTING_COUNTDOWN} second(s)",
          "",
          "{LINK}"
        ]
      },
      "HOST_STARTED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "Time left: &c{TIME_LEFT}",
          "&fPlayer(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "Round: {CURRENT_ROUND}/{MAX_ROUND}",
          "",
          "&e1st - {RACE_RANK_PLAYER_1}",
          "&72nd - {RACE_RANK_PLAYER_2}",
          "&63rd - {RACE_RANK_PLAYER_3}",
          "Your rank: {SELF_RACE_RANK_PLAYER}",
          "",
          "Checkpoints: &6{SELF_CPS}/{MAX_CPS}",
          "Laps: &6{SELF_LAPS}/{MAX_LAPS}",
          "",
          "{LINK}"
        ]
      },
      "SPECTATOR_FINISHED": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&e1st - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72nd - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63rd - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "&f4th - {RANK_PLAYER_4} - {RANK_PLAYER_4_SCORE}",
          "&f5th - {RANK_PLAYER_5} - {RANK_PLAYER_5_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "STARTING": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&fPlayer(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fMap: {CURRENT_MAP}",
          "&fMode: &aGrandPrix",
          "Round: 1/{MAX_ROUND}",
          "",
          "&cStarting in {STARTING_COUNTDOWN} second(s)",
          "",
          "{LINK}"
        ]
      },
      "BETWEENROUND": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "Next map: {CURRENT_MAP}",
          "{CURRENT_MAP_DIFFICULTY}",
          "&6PB: {SELF_MAP_PB}",
          "",
          "&e1st - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72nd - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63rd - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "Your rank: {SELF_RANK_PLAYER}",
          "Your score: {SELF_RANK_PLAYER_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "HOST_SPECTATOR_BETWEENROUND": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "Next map: {CURRENT_MAP}",
          "{CURRENT_MAP_DIFFICULTY}",
          "&6PB: {SELF_MAP_PB}",
          "",
          "&e1st - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72nd - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63rd - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "&f4th - {RANK_PLAYER_4} - {RANK_PLAYER_4_SCORE}",
          "&f5th - {RANK_PLAYER_5} - {RANK_PLAYER_5_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "HOST_FINISHED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&e1st - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72nd - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63rd - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "Your rank: {SELF_RANK_PLAYER}",
          "Your score: {SELF_RANK_PLAYER_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "SPECTATOR_BETWEENROUND": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "Next map: {CURRENT_MAP}",
          "{CURRENT_MAP_DIFFICULTY}",
          "&6PB: {SELF_MAP_PB}",
          "",
          "&e1st - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72nd - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63rd - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "&f4th - {RANK_PLAYER_4} - {RANK_PLAYER_4_SCORE}",
          "&f5th - {RANK_PLAYER_5} - {RANK_PLAYER_5_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "STARTED": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "Time left: &c{TIME_LEFT}",
          "&fPlayer(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "Round: {CURRENT_ROUND}/{MAX_ROUND}",
          "",
          "&e1st - {RACE_RANK_PLAYER_1}",
          "&72nd - {RACE_RANK_PLAYER_2}",
          "&63rd - {RACE_RANK_PLAYER_3}",
          "Your rank: {SELF_RACE_RANK_PLAYER}",
          "",
          "Checkpoints: &6{SELF_CPS}/{MAX_CPS}",
          "Laps: &6{SELF_LAPS}/{MAX_LAPS}",
          "",
          "{LINK}"
        ]
      },
      "SPECTATOR": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "Time left: &c{TIME_LEFT}",
          "&fPlayer(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "Round: {CURRENT_ROUND}/{MAX_ROUND}",
          "",
          "&e1st - {RACE_RANK_PLAYER_1}",
          "&72nd - {RACE_RANK_PLAYER_2}",
          "&63rd - {RACE_RANK_PLAYER_3}",
          "&f4th - {RACE_RANK_PLAYER_4}",
          "&f5th - {RACE_RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "FINISHED": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&e1st - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72nd - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63rd - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "Your rank: {SELF_RANK_PLAYER}",
          "Your score: {SELF_RANK_PLAYER_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "WAITING": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&fPlayer(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fMap: {CURRENT_MAP}",
          "&fMode: &aGrandPrix",
          "Round: 1/{MAX_ROUND}",
          "",
          "&cNeed {NEEDED_PLAYER} player(s) to start",
          "",
          "{LINK}"
        ]
      },
      "HOST_SPECTATOR_FINISHED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&e1st - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72nd - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63rd - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "&f4th - {RANK_PLAYER_4} - {RANK_PLAYER_4_SCORE}",
          "&f5th - {RANK_PLAYER_5} - {RANK_PLAYER_5_SCORE}",
          "",
          "{LINK}"
        ]
      }
    }
  },
  "Training": {
    "perState": {
      "TRAINING": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&6PB: {SELF_MAP_PB}",
          "&fRank: {SELF_MAP_RANK}",
          "",
          "WR holder: {MAP_WR_PLAYER}",
          "&6Time: &c{MAP_WR_TIME}",
          "",
          "Time left: &c{TIME_LEFT}",
          "&fDifficulty: {CURRENT_MAP_DIFFICULTY}",
          "Checkpoints: &6{SELF_CPS}/{MAX_CPS}",
          "Laps: &6{SELF_LAPS}/{MAX_LAPS}",
          "",
          "{LINK}"
        ]
      }
    }
  }
}
```
{% endcode %}

</details>

<details>

<summary>particles/particleConfig.json</summary>

{% code lineNumbers="true" %}
```json
{
  "ENABLE": false,
  "INTERVAL_PERSONAL_PARTICLE_REFRESH": 1,
  "GUI_PARTICLE_TITLE": "Particle Selector",
  "GUI_ITEM_PARTICLE_TITLE": "&f{PARTICLE_NAME}",
  "GUI_ITEM_PARTICLE_TITLE_SELECTED": "&a{PARTICLE_NAME}",
  "GUI_NO_PARTICLE": "None",
  "GUI_DISABLE_OTHERS_PARTICLES_UNSELECTED": "&fDisable others particles",
  "GUI_DISABLE_OTHERS_PARTICLES_SELECTED": "&fDisable others particles",
  "GUI_DISABLE_OTHERS_PARTICLES_LORE_SELECTED": "&f-> Currently: &a✓",
  "GUI_DISABLE_OTHERS_PARTICLES_LORE_UNSELECTED": "&f-> Currently: &c❌",
  "MSG_SAVE_SUCCESSFUL": "&fChanges have been &asucessfully &fsaved",
  "GUI_CLICKCHANGE": "Click here to change page",
  "GUI_ENCHANT_SELECTED": true,
  "particles": [
    {
      "name": "GreenCircle",
      "enable": true,
      "particle": "TOTEM",
      "item": "PAPER",
      "shapeParticle": [
        {
          "key": "SHAPE_CIRCLE",
          "option": "7;1"
        },
        {
          "key": "MASK_PLAYERFOLLOW",
          "option": ""
        }
      ],
      "colorCreator": null
    },
    {
      "name": "RotatingRainbowCircle",
      "enable": true,
      "particle": "REDSTONE",
      "item": "PAPER",
      "shapeParticle": [
        {
          "key": "SHAPE_CIRCLE",
          "option": "7;1"
        },
        {
          "key": "MASK_Z_ROTATION",
          "option": "10000;true"
        },
        {
          "key": "MASK_PLAYERFOLLOW",
          "option": ""
        }
      ],
      "colorCreator": [
        {
          "key": "RAINBOW",
          "option": "15000;true"
        }
      ]
    },
    {
      "name": "RainbowPoint",
      "enable": true,
      "particle": "REDSTONE",
      "item": "PAPER",
      "shapeParticle": [
        {
          "key": "SHAPE_POINT",
          "option": ""
        }
      ],
      "colorCreator": [
        {
          "key": "RAINBOW",
          "option": "15000;true"
        }
      ]
    },
    {
      "name": "RedPoint",
      "enable": true,
      "particle": "REDSTONE",
      "item": "PAPER",
      "shapeParticle": [
        {
          "key": "SHAPE_POINT",
          "option": ""
        }
      ],
      "colorCreator": [
        {
          "key": "CONSTANT",
          "option": "255;0;0"
        }
      ]
    },
    {
      "name": "HorizontalWave",
      "enable": true,
      "particle": "REDSTONE",
      "item": "PAPER",
      "shapeParticle": [
        {
          "key": "SHAPE_CIRCLE",
          "option": "7;0.75"
        },
        {
          "key": "MASK_X_ROTATION",
          "option": "7000;true"
        },
        {
          "key": "MASK_PLAYERFOLLOW",
          "option": ""
        }
      ],
      "colorCreator": [
        {
          "key": "CONSTANT",
          "option": "0;153;255"
        }
      ]
    },
    {
      "name": "VerticalWavingPoint",
      "enable": true,
      "particle": "REDSTONE",
      "item": "PAPER",
      "shapeParticle": [
        {
          "key": "SHAPE_CIRCLE",
          "option": "1;0.75"
        },
        {
          "key": "MASK_Y_ROTATION",
          "option": "1000;true"
        },
        {
          "key": "MASK_PLAYERFOLLOW",
          "option": ""
        }
      ],
      "colorCreator": [
        {
          "key": "CONSTANT",
          "option": "0;153;255"
        }
      ]
    },
    {
      "name": "RainbowTube",
      "enable": true,
      "particle": "REDSTONE",
      "item": "PAPER",
      "shapeParticle": [
        {
          "key": "SHAPE_CIRCLE",
          "option": "20;0.66"
        },
        {
          "key": "MASK_PLAYERFOLLOW",
          "option": ""
        }
      ],
      "colorCreator": [
        {
          "key": "RAINBOW",
          "option": "10000;true"
        }
      ]
    }
  ]
}
```
{% endcode %}

</details>
