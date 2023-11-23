---
description: 'Version: 1.5.3.17'
---

# 🇨🇳 Chinese

{% hint style="success" %}
Translated by: **jhqwqmc (Discord: jhqwqmc)**\
File translated: **AdminGUI.json, particuleConfig.json, Config.json, Scoreboard.json**\
**Plugin version: 1.5.3.17**
{% endhint %}

_Download the files and rename them as their original names (AdminGUI.json, particuleConfig.json, Config.json, Scoreboard.json)_

{% file src="../.gitbook/assets/AdminGUI_Chinese.json" %}
AdminGUI.json
{% endfile %}

{% file src="../.gitbook/assets/particleConfig_Chinese.json" %}
particleConfig.json
{% endfile %}

{% file src="../.gitbook/assets/Config_Chinese.json" %}
Config.json
{% endfile %}

{% file src="../.gitbook/assets/Scoreboard_Chinese.json" %}
Scoreboard.json
{% endfile %}

{% hint style="success" %}
Translated by: **C-095#1669**\
File translated: **Config.json**\
**Plugin version: 0.7.1-BETA**
{% endhint %}

```
{
  "PREFIX": "&f鞘翅竞速 &c>> &f",
  "auto_add_prefix": true,
  "SQL_LOCATION": "/database",
  "SQL_STATS_INTERVAL": 10000,
  "SQL_USE_CUSTOM_SQL": false,
  "SQL_CUSTOM_SQL_HOST": "",
  "SQL_CUSTOM_SQL_PORT": "",
  "SQL_CUSTOM_SQL_DATABASE": "",
  "SQL_CUSTOM_SQL_USER": "",
  "SQL_CUSTOM_SQL_PASSWORD": "",
  "SQL_CUSTOM_SQL_TYPE": "mysql",
  "max_info_per_page": 10,
  "TimerStart": 30,
  "TimerStart_host": 10,
  "TimerStartFull": 15,
  "LineHelper": true,
  "AutoTP_Spec_Distance": 75,
  "TimerRound": 15,
  "ParticleRatio": 4,
  "Max_maps_per_games": 4,
  "Max_alert_host": 3,
  "PERMISSION_MESSAGE": "&c你没有使用此命令的权限",
  "RankingMaxPlayers": 8,
  "NEXT_CHECKPOINT_PARTICLE": "END_ROD",
  "ITEM_1CP_BACK": "&c上一个检查点",
  "ITEM_2CP_BACK": "&c2 回到检查点",
  "ITEM_RESTART": "&c重新开始",
  "MAP_DIFICULTY": true,
  "MAP_DIFFICULTY_DEFAULT": 3,
  "MAP_DIFFICULTY_MAX": 5,
  "MAP_DIFFICULTY_SYMBOL": "✮",
  "MAP_DIFFICULTY_SYMBOL_ACTIVECOLOR": "&e",
  "MAP_DIFFICULTY_SYMBOL_ACTIVECOLOR_MAX": "&c",
  "MAP_DIFFICULTY_SYMBOL_MAX": true,
  "MAP_DIFFICULTY_SYMBOL_ACTIVECOLOR_LAST": "&6",
  "MAP_DIFFICULTY_SYMBOL_COLOR": "&7",
  "MAP_DIFFICULTY_MESSAGE": "&7地图难度: {DIFFICULTY}",
  "SQL_SAVE_HOST_STATS": false,
  "ITEM_DNF": "&c弃赛",
  "ITEM_BED": "&c离开游戏",
  "ITEM_SPEC": "&a进入观看模式",
  "ALERT_HOST": "&6{PLAYER} &a开启了一次鞘翅竞速 &7(点此加入游戏)",
  "ACTIONBAR_TIME": "&7剩余时间: &c{TIME}",
  "MSG_PAGE": "&7页数 &c{PAGE} &7/ &c{MAX_PAGE}",
  "MSG_ENDMAP": "&6{PLAYER} &7-> &c{ARG}",
  "MSG_GAMEFULL": "&c这场游戏已经满人了",
  "MSG_GAMESTARTED": "&c这场游戏已经开始了",
  "LOCATIONNOTDEFINED": "&cThis location isn't defined !",
  "MSG_ERHOST_LISTGAMES": "&a游戏列表 &7&o(hover): ",
  "MSG_ERMAP_LISTMAPS": "&a地图列表 &7&o(hover): ",
  "MSG_ERMAP_LISTMAPS_MAPSFORMAT": "&c>> &f{MAP_NAME} ",
  "MSG_ERMAP_LISTGAMES_GAMESFORMAT": "&c>> &f{GAME_NAME} ",
  "MSG_ERMAP_LISTCHECKPOINT": "&a检查点列表 &7&o(hover): ",
  "DEFAULT": "&6默认",
  "NONE": "&6无",
  "MSG_ERMAP_LISTCHECKPOINT_CHECKPOINTFORMAT": "&f#{CHECKPOINT_ID_ORDER} &c>> &f({X},{Y},{Z}) &7&o(点此传送)",
  "MSG_ERMAP_LISTEND": "&a终点列表 &7&o(hover): ",
  "MSG_ERMAP_LISTEND_ENDFORMAT": "&f#{END_ID_ORDER} &c>> &f({X},{Y},{Z}) &7&o(点此传送)",
  "YES": "&a是",
  "NO": "&c否",
  "CHECK": "&a✓",
  "CROSS": "&cx",
  "MSG_STATE_WAITING": "&a等待中",
  "MSG_STATE_STARTING": "&6开始中",
  "MSG_STATE_STARTED": "&c已经开始",
  "MSG_NOGAMETOLEAVE": "&c你现在不需要离开，因为你现在不在一场游戏中",
  "MSG_GAMENOTEXIST": "&c此游戏不存在",
  "MSG_NOTYOURHOST": "&c你不是这一场游戏的发起人",
  "MSG_TIMERSTART": "&a计时器已启动",
  "MSG_TIMERCANCEL": "&c计时器被取消",
  "MSG_HOST_NOTEXIST": "&c找不到您的主机",
  "MSG_LEAVEYOURGAME": "&c你已经在一场游戏里了",
  "MSG_MAPCREATING": "&a创建地图中...",
  "MSG_MAPNAMEEXIST": "&c这个地图的名字已经存在了",
  "MSG_GAMENAME_EXIST": "&c这个游戏的名字已经存在了",
  "MSG_HOST_CREATING": "&a正在创建主机...",
  "MSG_CHECKPOINT_VERIFIED": "&f检查点已通过! ({CHECKPOINT_PASSED} / {CHECKPOINT_MAX})",
  "MSG_GAME_PLAYERJOIN": "&6{PLAYER_NAME} &f加入了鞘翅竞赛 ! &7&o({PLAYER_SIZE} / {MAX_PLAYER})",
  "MSG_GAME_PLAYERJOIN_PLAYERNEEDEDLEFT": " &c(还需要 {PLAYER_NEEDED} 个玩家)",
  "MSG_GAME_PLAYERLEAVE": "&6{PLAYER_NAME} &f退出了鞘翅竞赛 ! &7&o({PLAYER_SIZE} / {MAX_PLAYER})",
  "MSG_GAME_NOTENOUGHPLAYERS": "&c计时器取消，没有足够的玩家",
  "MSG_MAP_NOTAVAILABLE": "&c此地图不可用 !",
  "MSG_MAP_NOTAVAILABLE2": "&c{MAP} 不可用 !",
  "MSG_MAPNOTFOUND2": "&c找不到 {ARG}",
  "MSG_ALERT": "&c你已经发送了太多的游戏公告",
  "PARTICLE_LIST": "&7粒子列表 (点击激活): ",
  "PARTICLE_LIST_ITEMS": " &7{item}",
  "PARTICLE_LIST_ITEMS_HOVER": "&7{item}: 点击激活",
  "PARTICLE_LIST_NOTFOUND": "&c没有找到这个类型的粒子效果",
  "PERSONAL_BEST": " &6&k&llol &6&l个人最佳成绩&k&llol",
  "PERMISSION_ER_PLAY": "elytraracing.play",
  "ER_PLAY_GAME": "&c没有找到游戏!",
  "USAGE_ER_HELP": [
    "&f关于 &c'er' &f命令的帮助:",
    "&c/er join <game_name> &f-> 加入一场游戏",
    "&c/er leave &f-> 离开一场游戏",
    "&c/er play &f-> 加入一场游戏"
  ],
  "USAGE_ER_JOIN": "&c使用: /er join <game_name>",
  "USAGE_ER_LEAVE": "&c使用: /er leave",
  "USAGE_ER_STATS": "&c使用: /er stats",
  "USAGE_ERHOST_CREATE": "&c使用: /erhost create <game_name> <max_players> <maps>",
  "MSG_STEP_TIMER": {
    "0": "你的游戏正在开始中...",
    "1": "你的游戏将在 &f1 &f秒后启动",
    "2": "你的游戏将在 &a2 &f秒后启动",
    "3": "你的游戏将在 &23 &f秒后启动",
    "4": "你的游戏将在 &64 &f秒后启动",
    "5": "你的游戏将在 &c5 &f秒后启动",
    "10": "你的游戏将在 &c10 &f秒后启动",
    "30": "你的游戏将在 &c30 &f秒后启动"
  },
  "MSG_STEPROUND_TIMER": {
    "0": "下一个回合正在开始中...",
    "1": "下一个回合将在 &f1 &f秒后启动",
    "2": "下一个回合将在 &a2 &f秒后启动",
    "3": "下一个回合将在 &23 &f秒后启动",
    "4": "下一个回合将在 &64 &f秒后启动",
    "5": "下一个回合将在 &c5 &f秒后启动",
    "15": "下一个回合将在 &c15 &f秒后启动"
  },
  "MSG_STEP_TIMER_MAPSTART_TITLE": {
    "0": "&c>>  出发  <<",
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
  "COMMAND_EXECUTION_PER_RANK_IN_HOST": false,
  "COMMAND_EXECUTION_PER_RANK_GRANDPRIX": {
    "-1": "[CONSOLE]/give {SELF_PLAYER} minecraft:cookie {SCORE}",
    "0": "[PLAYER]/tell {SELF_PLAYER} you executed a command"
  },
  "COMMAND_EXECUTION_PER_RANK_RACEMODE": {
    "-1": "[CONSOLE]/give {SELF_PLAYER} minecraft:cookie 5",
    "0": "[PLAYER]/tell {SELF_PLAYER} you executed a command"
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
  "DNF_POINT": -1,
  "MSG_PRE_RANK": "&7\n排名:\n",
  "MSG_PRE_SCORE": "&7\n分数榜:\n",
  "MSG_YOURRANK": "&7你在此地图的排名: &c{RANK}",
  "MSG_YOURSCORE": "&7你的总排名是: &c{RANK} &7分数是 &c{SCORE}",
  "MSG_ARG_RANK_TIME_DNF": "&c弃赛",
  "MSG_ARG_RANK_TIME_TIME": "&c{TIME}",
  "TELEPORTING": "&7传送中...",
  "TIMEFORMAT": "{MINUTES}分 {SECONDS}.{MILLISECONDS}秒",
  "TIMEFORMAT_WM": "{MINUTES}分 {SECONDS}秒",
  "USAGE_ERMAP_CREATE": "&c用法: /ermap create <地图名称>",
  "ERMAP_MAP_DELETE": "&cThe map will be deleted after a reload/restart",
  "USAGE_ERMAP_SHOW": "&c用法: /ermap map <地图名称> show <on/off>",
  "USAGE_ERMAP_ENABLE": "&c用法: /ermap map <地图名称> enable <on/off>",
  "USAGE_ERMAP_SETDIFFICULTY": "&c用法: /ermap map <地图名称> setdifficulty <difficulty>",
  "MSG_MAPNOTFOUND": "&c这一张地图无法被找到",
  "MSG_SAVE_SUCCESSFUL": "&fChanges have been &asucessfully &fsaved",
  "MSG_SHOW_ON": "&a启用 ...",
  "MSG_SHOW_OFF": "&c禁用 ...",
  "MSG_CHECKPOINT_NOTFOUND": "&c没有找到检查点",
  "MSG_END_NOTFOUND": "&c没有找到终点",
  "ID_ORDER_ARG": "&c<id_order> 必须是一个整数",
  "ID_ORDER_TARGET_ARG": "&c<id_order_target> 必须是一个整数",
  "DEGREES_ARG": "&c<degrees> 必须是一个整数",
  "MULTIPLIER_ARG": "&c<multiplier> 必须是一个小数",
  "SIZE_ARG": "&c<size> 必须是一个整数",
  "AMOUNT_ARG": "&c<amount> 必须是一个整数",
  "SECONDS_ARG": "&c<seconds> 必须是一个介于 0 到 59之间的整数",
  "MINUTES_ARG": "&c<minutes> 必须是一个大于 0 的整数",
  "MAX_PLAYER_ARG": "&c<max_players> 必须是一个大于 0 的整数",
  "PAGE_ARG": "&c<page> 必须是一个大于 0 的整数",
  "SPECTATORMODE": "&a你进入了观众模式 &7(点击这里或者使用 '/er quitspec' 命令离开)",
  "AVAILABLE_MAPS": "&a可用地图: {MAPS}",
  "USAGE_PODIUM_SETLOCATION": "&c/ermap map <map_name> podium setlocation <placement (1, 2 ..)>",
  "USAGE_PODIUM": "&c/ermap map <map_name> podium <on/off/setlocation>",
  "USAGE_INSERTCHECKPOINT": "&c/ermap map <map_name> insertcheckpoint <id_order_wanted>",
  "USAGE_REMOVEEND": "&c/ermap map <map_name> removeend <id_order>",
  "USAGE_REMOVECHECKPOINT": "&c/ermap map <map_name> removecheckpoint <id_order>",
  "USAGE_SETTIMEMAX": "&c/ermap map <map_name> settimemax <minutes> <seconds>",
  "SIGN_RELOAD_SEC": 10,
  "USAGE_ERGAMES_SET": "&cUsage: /ergames set <autogame_name> <on/off>",
  "USAGE_ERGAMES_SETQUEUE": "&cUsage: /ergames setqueue <queue_name> <on/off>",
  "ERGAMES_LIST": "&6List of autogames: {AUTOGAMES}",
  "ERGAMES_ENABLED_PREFIX": "&a",
  "ERGAMES_DISABLED_PREFIX": "&c",
  "ERGAMES_LIST_SEPERATION_PREFIX": "&7",
  "ERGAMES_NOTFOUND": "&c找不到这个自动游戏",
  "ERGAMES_ALREADYGAME": "&c你无法启用这个自动游戏，因为已经有了一个相同名字的游戏了",
  "TABLIST_GRANDPRIX": true,
  "TABLIST_RANK_SCORE_TITLE": "&7得分榜 \n",
  "TABLIST_RANK_SCORE_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "TABLIST_GRANDPRIX_PERSONAL_PERSONAL": "&6此地图上的个人统计数据:",
  "TABLIST_GRANDPRIX_PERSONAL_TIME": "&9个人最佳时间: &c{TIME}",
  "TABLIST_GRANDPRIX_PERSONAL_RANK": "&9你的排名: &c{RANK}",
  "TABLIST_GRANDPRIX_PERSONAL_WINRATE": "&9你的胜率: &c{WINRATE} %",
  "HOLOGRAMS_UPDATEINTERVAL": 60000,
  "HOLOGRAMS_LINESPACE": 0.29,
  "HOLOGRAMS_RANK_LIMIT": 15.0,
  "HOLOGRAMS_RANK_SCORE_TITLE": "&6&l高分榜",
  "HOLOGRAMS_RANK_SCORE_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_RANK_WON_RACEMODE_TITLE": "&6&l胜率榜",
  "HOLOGRAMS_RANK_WON_RACEMODE_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_RANK_WON_GRANDPRIX_TITLE": "&6&l大奖赛排行",
  "HOLOGRAMS_RANK_WON_GRANDPRIX_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_RANK_MAP_TITLE": "&6&l最速榜 {MAP}",
  "HOLOGRAMS_RANK_MAP_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_PERSONAL_MAPS_TITLE": "&6&l此地图上的个人统计数据",
  "HOLOGRAMS_PERSONAL_MAPS_SPECIFIC": "&6{MAP_NAME} &7: &c{PLAYER_TIME} &7(#{PLAYER_RANK}) (胜率: {WINRATE}%)",
  "HOLOGRAMS_PERSONAL_MAPS_MAX": 10,
  "TELEPORT_SOLVER": false,
  "PODIUM_FIREWORKS": true,
  "PODIUM_FIREWORK_NUMBER": 10,
  "END_TIME": 30,
  "SEPERATE_GAMES_HIDE_PLAYERS": true,
  "CUSTOM_AND_SEPARATED_CHAT": false,
  "CUSTOM_CHAT_FORMAT": "&6{PLAYER} &f>> {MESSAGE}",
  "MSG_LISTMAPS_INFO": [
    "&a>> {MAP_NAME}",
    " ",
    "&f>> &7有效性: {VALID}",
    "&f>> &7是否启动: {ENABLED}",
    " ",
    "&f>> &7检查点: &c{CHECKPOINTS}",
    "&f>> &7终点: &c{ENDS}",
    "&f>> &7大厅位置: &c{LOBBY}",
    "&f>> &7开始位置: &c{START}",
    "&f>> &7结束位置: &c{END}",
    "&f>> &7领奖台: &c{PODIUM}",
    " ",
    "&f>> &7最大时间: &c{TIME}",
    "&f>> &7难度: &c{DIFFICULTY}",
    " "
  ],
  "USAGE_ERHOST_HELP": [
    "&f关于 &c'erhost' &f命令的帮助:",
    "&c/erhost create <game_name> <max_players> <maps> &f-> 创建一个游戏 &7(每张地图必须用 ',' 隔开)",
    "&c/erhost alert &f-> 发送一条游戏公告让其他玩家加入你的游戏",
    "&c/erhost listmaps &f-> 列出有效的地图",
    "&c/erhost start &f-> 开始游戏",
    "&c/erhost stoptimer &f-> 停止倒计时",
    "&c/erhost list &f-> 游戏列表"
  ],
  "STATES": {
    "STARTING": "&6进行中",
    "STARTED": "&c游戏中",
    "WAITING": "&a等待中",
    "FINISHED": "&7结束"
  },
  "SIGN_FORMAT_ONEQUEUE_ONEGAME": [
    "&f[鞘翅竞速]",
    "&6{MAP}",
    "{STATE}",
    "&c{PLAYERS}/{MAX_PLAYERS}"
  ],
  "SIGN_FORMAT": [
    "&f[鞘翅竞速]",
    "&6{MAP}",
    "&c{PLAYERS}/{MAX_PLAYERS}",
    "&7点击加入"
  ],
  "SIGN_FORMAT_DISABLED": [
    "&f[鞘翅竞速]",
    " ",
    "&4关闭",
    " "
  ],
  "MSG_LISTCHECKPOINT_INFO": [
    " ",
    "&f>> &7ID: {ID_ORDER}",
    " ",
    "&f>> &7x: &c{X}",
    "&f>> &7y: &c{Y}",
    "&f>> &7z: &c{Z}",
    "&f>> &7世界: &c{WORLD}",
    " ",
    "&f>> &7半径: &c{RADIUS}",
    "&f>> &7粒子数量: &c{PARTICLE_AMOUNT}",
    "&f>> &7加速倍数: &c{BOOST_MULTIPLIER}",
    "&f>> &7",
    "&f>> &7粒子类型: &c{PARTICLE_TYPE}",
    "&f>> &7被连接到: &c{LINK}"
  ],
  "MSG_LISTGAMES_INFO": [
    "&a>> {GAME_NAME}",
    " ",
    "&f>> &7玩家数: &c{PLAYER_SIZE}",
    "&f>> &7最少玩家数: &c{MIN_PLAYER}",
    "&f>> &7最大玩家数: &c{MAX_PLAYER}",
    " ",
    "&f>> &7统计: &c{GAME_STATE}"
  ],
  "MSG_LISTEND_INFO": [
    " ",
    "&f>> &7ID: {ID_ORDER}",
    " ",
    "&f>> &7x: &c{X}",
    "&f>> &7y: &c{Y}",
    "&f>> &7z: &c{Z}",
    "&f>> &7世界: &c{WORLD}",
    " ",
    "&f>> &7半径: &c{RADIUS}",
    "&f>> &7粒子数量: &c{PARTICLE_AMOUNT}",
    "&f>> &7",
    "&f>> &7粒子类型: &c{PARTICLE_TYPE}"
  ],
  "USAGE_ERMAP_HELP_HELP": [
    "&f关于 &c'ermap' &f命令的帮助",
    "&c/ermap help MapSystem &f-> 地图系统帮助",
    "&c/ermap help CheckpointSystem &f-> 检查点系统帮助",
    "&c/ermap help EndSystem &f-> 终点系统帮助"
  ],
  "USAGE_ERGAMES_HELP": [
    "&f关于 &c'ergames' &f命令的帮助",
    "&c/ergames add &f-> Add a blank map in the configuration file",
    "&7The configuration must be done in the file: plugins/ElytraRacing/Autogames.json"
  ],
  "ERSTATS_MAP": "&6&l地图上的个人统计信息",
  "ERSTATS_MAP_EACH": "&6>> {MAP_NAME} &9: {PLAYER_TIME} &9(#{PLAYER_RANK}) \n&6> &9(胜率: {WINRATE}%)",
  "USAGE_ERSTATS_SHOW": [
    "&6&l个人统计: {USERNAME}",
    "&7比赛: &c{PLAYER_GAME_PLAYED_RACEMODE} ",
    "&7比赛获胜: &c{PLAYER_GAME_WON_RACEMODE} &9(#{RANK_WON_RACEMODE}) &7({POURCENTAGE_WINRATE_RACEMODE}%)",
    "&7大奖赛: &c{PLAYER_GAME_PLAYED_GRANDPRIX} ",
    "&7大奖赛获胜: &c{PLAYER_GAME_WON_GRANDPRIX} &9(#{RANK_WON_GRANDPRIX}) &7({POURCENTAGE_WINRATE_GRANDPRIX}%)",
    "&7分数: &c{SCORE_TOTAL} &9(#{RANK_SCORE_TOTAL})",
    "&6最喜欢的地图: &6{FAVORITE_MAP} &7&o(胜率: {FAVORITE_MAP_WINRATE}%)",
    "[HOVERMESSAGE_MAP_STATS]&9地图上的个人统计信息 &7&o(将鼠标放在此处)"
  ],
  "HOLOGRAMS_PERSONALSTATS": [
    "&6&l个人统计:",
    "&7游戏场数: &c{PLAYER_GAME_PLAYED_RACEMODE} ",
    "&7游戏胜场: &c{PLAYER_GAME_WON_RACEMODE} &9(#{RANK_WON_RACEMODE}) &7({POURCENTAGE_WINRATE_RACEMODE}%)",
    "&7大奖赛场数: &c{PLAYER_GAME_PLAYED_GRANDPRIX} ",
    "&7大奖赛胜场: &c{PLAYER_GAME_WON_GRANDPRIX} &9(#{RANK_WON_GRANDPRIX}) &7({POURCENTAGE_WINRATE_GRANDPRIX}%)",
    "&7分数: &c{SCORE_TOTAL} &9(#{RANK_SCORE_TOTAL})",
    "&6最喜欢的地图: &6{FAVORITE_MAP} &7&o(winrate: {FAVORITE_MAP_WINRATE}%)"
  ],
  "USAGE_ERMAP_HELP_MAP": [
    "&f关于'ermap'命令中 'map' 的帮助(地图)",
    "&c/ermap list &f-> 地图列表",
    "&c/ermap create <name> &f-> 创建一张地图",
    "&c/ermap map <map_name> setlocationlobby &f-> 在你的地图中设置大厅位置",
    "&c/ermap map <map_name> setlocationstart &f-> 在你的地图中设置起点",
    "&c/ermap map <map_name> setlocationend &f-> 在你的地图中设置终点",
    "&c/ermap map <map_name> tplobby &f-> 传送到你的地图的大厅",
    "&c/ermap map <map_name> tpstart &f-> 传送到你的地图的起点",
    "&c/ermap map <map_name> tpend &f-> 传送到你的地图的终点",
    "&c/ermap map <map_name> settimemax <minutes> <seconds> &f-> 设置此地图的最大完赛时间",
    "&c/ermap map <map_name> show <on/off> &f-> 显示或者隐藏地图(检查点，终点)",
    "&c/ermap map <map_name> enable <on/off> &f-> 开启或关闭你的地图",
    "&c/ermap map <map_name> podium <on/off> &f-> 开启或关闭你的地图的领奖台",
    "&c/ermap map <map_name> podium setlocation <placement (1, 2 ..)> &f-> 设置你的地图的领奖台位置",
    "&c/ermap map <map_name> setdifficulty <difficulty> &f-> 设置地图的难度"
  ],
  "USAGE_ERMAP_HELP_CHECKPOINT": [
    "&f关于'ermap'命令中 'checkpoint' 的帮助(检查点)",
    "&c/ermap map <map_name> listcheckpoint &f-> 展示你的地图上的检查点列表(show id_orders)",
    "&c/ermap map <map_name> listcheckpoint <page> &f-> 展示你的地图上的检查点列表 (show id_orders)",
    "&c/ermap map <map_name> addcheckpoint &f-> 在你的地图上添加一个检查点",
    "&c/ermap map <map_name> insertcheckpoint <id_order_wanted> &f-> 在你输入的检查点ID插入一个新的检查点",
    "&c/ermap map <map_name> removecheckpoint <id_order> &f-> 在你的地图上删除一个检查点",
    " ",
    "&c/ermap map <map_name> checkpoint <id_order> tp &f-> 传送到你的检查点",
    "&c/ermap map <map_name> checkpoint <id_order> setXrotation <degrees> &f-> 在X轴上旋转检查点",
    "&c/ermap map <map_name> checkpoint <id_order> setYrotation <degrees> &f-> 在Y轴上旋转检查点",
    "&c/ermap map <map_name> checkpoint <id_order> setZrotation <degrees> &f-> 在Z轴上旋转检查点",
    "&c/ermap map <map_name> checkpoint <id_order> setboostmultiplier <Multiplier> &f-> 设置检查点的加速器",
    "&c/ermap map <map_name> checkpoint <id_order> setlocation &f-> 设置检查点的位置",
    "&c/ermap map <map_name> checkpoint <id_order> setsize <size> &f-> 设置检查点的尺寸",
    "&c/ermap map <map_name> checkpoint <id_order> setparticleamount <amount> &f-> 设置检查点的粒子数量",
    "&c/ermap map <map_name> checkpoint <id_order> linkto <id_order_target> &f-> 连接到另一个检查点 (链接与检查点本身无关，而是与检查点本身有关。)",
    "&c/ermap map <map_name> checkpoint <id_order> removelinkto <id_order_target>&f-> 删除两个检查点之间的链接",
    "&c/ermap map <map_name> checkpoint <id_order> setparticle &f-> 设置检查点的粒子类型",
    "&c/ermap map <map_name> checkpoint <id_order> setparticleifnext &f-> 设置下一个检查点的粒子类型"
  ],
  "USAGE_ERMAP_HELP_END": [
    "&f关于'ermap'命令中 'end' 的帮助(终点)",
    "&c/ermap map <map_name> listend &f-> 展示你地图上的终点列表 (show id_orders)",
    "&c/ermap map <map_name> listend <page> &f-> 展示你地图上的终点列表 (show id_orders)",
    "&c/ermap map <map_name> addend &f-> 在你的地图上增加终点",
    "&c/ermap map <map_name> removeend <id_order> &f-> 从你的地图上删除一个终点",
    " ",
    "&c/ermap map <map_name> end <id_order> tp &f-> 传送到你地图上的终点",
    "&c/ermap map <map_name> end <id_order> setXrotation <degrees> &f-> 在X轴上旋转终点",
    "&c/ermap map <map_name> end <id_order> setYrotation <degrees> &f-> 在Y轴上旋转终点",
    "&c/ermap map <map_name> end <id_order> setZrotation <degrees> &f-> 在Z轴上旋转终点",
    "&c/ermap map <map_name> end <id_order> setsize <size> &f-> 设置终点的尺寸",
    "&c/ermap map <map_name> end <id_order> setparticleamount <amount> &f-> 设置终点的粒子数量",
    "&c/ermap map <map_name> end <id_order> setparticle &f-> 设置终点的粒子类型",
    "&c/ermap map <map_name> end <id_order> setparticleifnext &f-> 设置下一个终点的粒子类型"
  ]
}
```

