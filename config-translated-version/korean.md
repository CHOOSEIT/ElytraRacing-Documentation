# 🇰🇷 Korean

{% hint style="success" %}
Translated by: **대표#9143**

**Server IP: d-na.kr (1.19.2 or latest)**

\
**Plugin version: 1.5.1**
{% endhint %}

<details>

<summary>Config.json</summary>

```
}
  "DOCUMENTATION_LINK": "https://chooseit.io/elytraracing",
  "PREFIX": "&f하늘레이싱 &c>> &f",
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
  "ER_TRAIN_MAP_NOTFOUND": "&c이 맵으로는 트레이닝이 불가능 합니다.",
  "ER_TRAIN_CHOOSE_MAP_GUI_TITLE": "맵 선택",
  "SIGN_RELOAD_SEC": 3,
  "TELEPORT_SOLVER": false,
  "UNLOCK_DISTANCE": 100,
  "UNLOCK_OBJECT": "&f오브젝트 잠금 해제",
  "LOCK_OBJECT": "&f연결되었습니다.",
  "LOCK_ITEMS_GIVE": "&f아이템을 주었습니다.",
  "LOCK_OBJECT_NEAR_NOTFOUND": "&c주변에 아무것도 없습니다.",
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
  "REPLAY_FORMAT_16MAXCHAR": "&7{MINUTES}분 {SECONDS}.{MILLISECONDS}초",
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
  "MAP_DIFFICULTY_MESSAGE": "&7레이싱 난이도: {DIFFICULTY}",
  "DNF_POINT": -1,
  "TABLIST_GRANDPRIX": true,
  "COMMANDS_WHITELIST": false,
  "COMMANDS_WHITELIST_COMMANDS": [
    "msg",
    "rl",
    "reload"
  ],
  "COMMANDS_WHITELIST_BYPASS_PERMISSION": "elytraracing.wlcommands.bypass",
  "COMMANDS_MESSAGE": "&c해당 명령어는 사용하실 수 없습니다.",
  "SPECTATOR_ITEM": true,
  "STATIC_ITEMS": true,
  "RankingMaxPlayers": 8,
  "PODIUM_FIREWORKS": true,
  "PODIUM_FIREWORK_NUMBER": 10,
  "END_TIME": 30,
  "DISABLE_ELYTRA": false,
  "COMMAND_EXECUTION_PER_RANK_IN_HOST": false,
  "COMMAND_EXECUTION_PER_RANK_GRANDPRIX": {
    "-1": "[CONSOLE]/minecraft:give {SELF_PLAYER} minecraft:cookie {SCORE} §%§[PLAYER]/tell {SELF_PLAYER} 명령어를 실행하였습니다.",
    "0": "[CONSOLE]/tell {SELF_PLAYER} 명령어를 실행하였습니다."
  },
  "COMMAND_EXECUTION_PER_RANK_RACEMODE": {
    "-1": "[CONSOLE]/minecraft:give {SELF_PLAYER} minecraft:cookie 5 §%§[PLAYER]/tell {SELF_PLAYER} 명령어를 실행하였습니다.",
    "0": "[CONSOLE]/tell {SELF_PLAYER} 명령어를 실행하였습니다."
  },
  "PERMISSION_MESSAGE": "&c해당 명령어는 사용하실 수 없습니다.",
  "PERMISSION_MESSAGE_HOST": "&c해당 게임에 참가하실 수 없습니다.",
  "MSG_NUMBER_LAP": "&e바퀴수: {LAPS}",
  "HOLOGRAM_NOT_FOUND": "&c홀로그램을 찾을 수 없습니다.",
  "ITEM_1CP_BACK": "&c이전 체크포인트로 이동",
  "ITEM_1CP_BACK_MATERIAL": null,
  "ITEM_1CP_BACK_SLOT": 0,
  "ITEM_2CP_BACK": "&c두번째 이전 체크포인트로 이동",
  "ITEM_2CP_BACK_MATERIAL": null,
  "ITEM_2CP_BACK_SLOT": 1,
  "ITEM_RESTART": "&c재시작하기",
  "ITEM_RESTART_MATERIAL": null,
  "ITEM_RESTART_SLOT": 4,
  "ITEM_DNF": "&c포기",
  "ITEM_DNF_MATERIAL": null,
  "ITEM_DNF_SLOT": 8,
  "ITEM_BED": "&c게임 나가기",
  "ITEM_BED_MATERIAL": null,
  "ITEM_BED_SLOT": 8,
  "ITEM_SPEC": "&a관찰자 모드",
  "ITEM_SPEC_MATERIAL": null,
  "ITEM_SPEC_SLOT": 4,
  "ITEM_CUSTOM": "&a관찰자 모드",
  "ITEM_CUSTOM_MATERIAL": "AIR:-1",
  "ITEM_CUSTOM_SLOT": 3,
  "ITEM_HOST": "&a방 설정",
  "ITEM_HOST_MATERIAL": null,
  "ITEM_HOST_SLOT": 4,
  "ITEM_PARTICLE": "&a파티클 선택",
  "ITEM_PARTICLE_MATERIAL": null,
  "ITEM_PARTICLE_SLOT": 2,
  "ITEM_FIREWORK_SLOT": 2,
  "ITEM_PAPERMAPINFO_SLOT": 4,
  "ITEM_PAPERMAPINFO_MATERIAL": null,
  "ITEM_HOSTSEPARATION_TITLE": "&f맵 선택",
  "ITEM_HOSTSEPARATION_DESCRIPTION": "&a⬇  ⬇  ⬇  ⬇  ⬇  ⬇",
  "ITEM_HOSTSEPARATION_MATERIAL": null,
  "ITEM_HOSTMAP_TITLE_SELECTED": "&a{MAP_NAME}",
  "ITEM_HOSTMAP_TITLE_NOTSELECTED": "&f{MAP_NAME}",
  "ITEM_HOSTMAP_MATERIAL_SELECTED": null,
  "ITEM_HOSTMAP_MATERIAL_NOTSELECTED": null,
  "HOSTMAP_CREATOR_INVENTORY_TITLE": "방 만들기",
  "ALERT_HOST": "&6{PLAYER} &a호스트가 게임을 시작했습니다. &7(클릭해서 입장하기)",
  "ERROR_MESSAGE": "&c프로세스중에 오류가 발생했습니다.",
  "ACTIONBAR_TIME": "&7남은 시간: &c{TIME}",
  "MSG_PAGE": "&7페이지 &c{PAGE} &7/ &c{MAX_PAGE}",
  "MSG_ENDMAP": "&6{PLAYER} &7-> &c{ARG}",
  "MSG_GAMEFULL": "&c이 방에는 더이상 입장하실 수 없습니다.",
  "MSG_GAMESTARTED": "&c이 방은 이미 게임을 시작하였습니다.",
  "LOCATIONNOTDEFINED": "&c이 장소는 정의되지 않았습니다!",
  "MSG_ERHOST_LISTGAMES": "&a방 목록 &7&o(마우스 올리기): ",
  "MSG_ERMAP_LISTGAMES_GAMESFORMAT": "&c>> &f{GAME_NAME} ",
  "MSG_ERMAP_LISTCHECKPOINT": "&a체크포인트 목록 &7&o(마우스 올리기): ",
  "DEFAULT": "&6기본",
  "NONE": "&6없음",
  "NOBODY": "아무도 없음",
  "MSG_ERMAP_LISTCHECKPOINT_CHECKPOINTFORMAT": "&f#{CHECKPOINT_ID_ORDER} &c>> &f({X},{Y},{Z}) &7&o(클릭해서 이동하기)",
  "MSG_ERMAP_LISTEND": "&aList of ends &7&o(hover): ",
  "MSG_ERMAP_LISTEND_ENDFORMAT": "&f#{END_ID_ORDER} &c>> &f({X},{Y},{Z}) &7&o(클릭해서 이동하기)",
  "YES": "&a네",
  "NO": "&c아니오",
  "CHECK": "&a✓",
  "CROSS": "&cx",
  "MSG_STATE_WAITING": "&a기다리는중",
  "MSG_STATE_STARTING": "&6시작하는중",
  "MSG_STATE_STARTED": "&c시작함",
  "MSG_SPEC_JOINING": "&7관찰자 모드로 입장하는중...",
  "PERM_SPECGAME": "elytraracing.specgame",
  "MSG_NOGAMETOLEAVE": "&c아직 게임에 참여중이지 않습니다.",
  "MSG_GAMENOTEXIST": "&c이 방은 존재하지 않습니다.",
  "MSG_NOTYOURHOST": "&c이 방의 호스트가 아닙니다.",
  "MSG_TIMERSTART": "&a타이머 시작",
  "MSG_TIMERCANCEL": "&c타이머 취소",
  "MSG_HOST_NOTEXIST": "&c이 방의 호스트를 찾을 수 없습니다.",
  "MSG_LEAVEYOURGAME": "&c이미 이 방에 참여중입니다.",
  "MSG_GAMENOTOPEN": "&c열리지 않았습니다.",
  "MSG_MAPCREATING": "&a맵 만드는중...",
  "MSG_MAPNAMEEXIST": "&c해당 맵 이름은 이미 존재합니다.",
  "MSG_GAMENAME_EXIST": "&c해당 방 이름은 이미 존재합니다.",
  "MSG_HOST_CREATING": "&a방 만드는중...",
  "MSG_CHECKPOINT_VERIFIED": "&f체크포인트를 지났습니다! ({CHECKPOINT_PASSED} / {CHECKPOINT_MAX})",
  "MSG_LAP_VERIFIED": "&e완주 완료! ({LAP_PASSED} / {LAP_MAX})",
  "MSG_GAME_PLAYERJOIN": "&6{PLAYER_NAME} &f레이스에 참여하였습니다! &7&o({PLAYER_SIZE} / {MAX_PLAYER})",
  "MSG_GAME_PLAYERJOIN_PLAYERNEEDEDLEFT": " &c({PLAYER_NEEDED} 명이 더 필요합니다.)",
  "MSG_GAME_PLAYERLEAVE": "&6{PLAYER_NAME} &f레이스에서 퇴장하셨습니다! &7&o({PLAYER_SIZE} / {MAX_PLAYER})",
  "MSG_GAME_NOTENOUGHPLAYERS": "&c플레이어가 충분하지 않아 타이머가 취소되었습니다.",
  "PLAYER_NOTFOUND": "&c플레이어를 찾을 수 없습니다.",
  "ERHOST_PLAYER_NOTFOUND": "&c해당 플레이어는 당신의 방에 참여중이지 않습니다.",
  "MSG_MAP_NOTAVAILABLE": "&c이 맵은 사용하실 수 없습니다!",
  "MSG_MAP_NOTAVAILABLE2": "&c{MAP}맵은 사용하실 수 없습니다.",
  "MSG_MAPNOTFOUND2": "&c{ARG}맵을 찾을 수 없습니다.",
  "MSG_ALERT": "&c이미 충분한 알림을 보냈습니다.",
  "PARTICLE_LIST": "&7파티클 목록 (클릭해서 활성화): ",
  "PARTICLE_LIST_ITEMS": " &7{item}",
  "PARTICLE_LIST_ITEMS_HOVER": "&7{item}: 클릭해서 활성화",
  "PARTICLE_LIST_NOTFOUND": "&c이 파티클 타입은 찾을 수 없습니다.",
  "GRANDPRIX": "그랑프리",
  "RACEMODE": "레이스",
  "PERSONAL_BEST": " &6&k&llol &6&l개인 최고기록&k&llol",
  "TIME_NOT_FOUND": " - ",
  "RANK_NOT_FOUND": "-",
  "ER_PLAY_GAME": "&c게임을 찾을 수 없습니다!",
  "MSG_STEP_TIMER": {
    "0": "게임 시작중...",
    "1": "&f1 &f초후에 게임이 시작됩니다.",
    "2": "&a2 &f초후에 게임이 시작됩니다.",
    "3": "&23 &f초후에 게임이 시작됩니다.",
    "4": "&64 &f초후에 게임이 시작됩니다.",
    "5": "&c5 &f초후에 게임이 시작됩니다.",
    "10": "&c10 &f초후에 게임이 시작됩니다.",
    "30": "&c30 &f초후에 게임이 시작됩니다."
  },
  "MSG_STEPROUND_TIMER": {
    "0": "다음 라운드 시작중...",
    "1": "&f1 &f초후에 다음 라운드가 시작됩니다.",
    "2": "&a2 &f초후에 다음 라운드가 시작됩니다.",
    "3": "&23 &f초후에 다음 라운드가 시작됩니다.",
    "4": "&64 &f초후에 다음 라운드가 시작됩니다.",
    "5": "&c5 &f초후에 다음 라운드가 시작됩니다.",
    "15": "&c15 &f초후에 다음 라운드가 시작됩니다."
  },
  "MSG_STEP_TIMER_MAPSTART_TITLE": {
    "0": "&c>>  시작  <<",
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
  "MSG_PRE_RANK": "&7\n랭킹:\n",
  "MSG_PRE_SCORE": "&7\n스코어보드:\n",
  "MSG_YOURRANK": "&7이 맵에서의 당신의 랭킹: &c{RANK}",
  "MSG_YOURSCORE": "&7전체 랭킹: &c{RANK} &7, &c{SCORE} &7점",
  "MSG_ARG_RANK_TIME_DNF": "&c포기",
  "MSG_ARG_RANK_TIME_TIME": "&c{TIME}",
  "TELEPORTING": "&7이동중...",
  "TIMEFORMAT": "{MINUTES}분 {SECONDS}.{MILLISECONDS}초",
  "TIMEFORMAT_WM": "{MINUTES}분 {SECONDS}초",
  "PLACEHOLDER_NOTFOUND_PLAYER": "없음",
  "PLACEHOLDER_DEFAULT_NUMBER": "0",
  "PLACEHOLDER_DEFAULT_TEXT": "",
  "PLACEHOLDER_DEFAULT_RANKING": "-",
  "ERMAP_MAP_DELETE": "&c리로드 이후에 맵이 삭제될 예정입니다.",
  "MSG_MAPNOTFOUND": "&c해당 맵을 찾을 수 없습니다.",
  "MSG_SAVE_SUCCESSFUL": "&f변경사항이 저장되었습니다.",
  "MSG_FILE_RELOAD": "&f파일이 리로드 되었습니다.",
  "MSG_SHOW_ON": "&a활성화중...",
  "MSG_SHOW_OFF": "&c비활성화중...",
  "MSG_CHECKPOINT_NOTFOUND": "&c해당 체크포인트를 찾을 수 없습니다.",
  "MSG_END_NOTFOUND": "&c해당 종료지점을 찾을 수 없습니다.",
  "ID_ORDER_ARG": "&c[id_order] 숫자로만 적어주세요.",
  "ID_ORDER_TARGET_ARG": "&c[id_order_target] 숫자로만 적어주세요.",
  "DEGREES_ARG": "&c[rotation] 숫자로만 적어주세요.",
  "MULTIPLIER_ARG": "&c[amount] 소수점으로만 적어주세요.",
  "SIZE_ARG": "&c[size] 소수점으로만 적어주세요.",
  "AMOUNT_ARG": "&c[amount] 숫자로만 적어주세요.",
  "SECONDS_ARG": "&c[seconds] 0부터 59사이의 숫자로만 적어주세요.",
  "MINUTES_ARG": "&c[minutes] 0보다 큰 숫자로만 적어주세요.",
  "MAX_PLAYER_ARG": "&c[slots] 0보다 큰 숫자로만 적어주세요.",
  "PAGE_ARG": "&c[page] 0보다 큰 숫자로만 적어주세요.",
  "ERCONFIG_SETITEM_ID_NOT_FOUND": "&c[id_item] 을(를)찾을 수 없습니다.",
  "ERCONFIG_SETITEM_ITEM_NOT_FOUND": "&c손에 아이템을 쥐고 다시 실행해 주세요.",
  "SPEC_PERM": null,
  "SPEC_PERM_MESSAGE": "&c권한이 없습니다.",
  "HOST_GAMENOTOPEN": "&c게임이 열리지 않았습니다.",
  "SPECTATORMODE": "&a관찰자 모드로 들어가기 &7(클릭해서 나가거나 '/er quitspec'을 쳐주세요)",
  "STUCKSPECTATOR": "&a'/er near'를 치시면 주변 플레이어에게 이동합니다.",
  "AVAILABLE_MAPS": "&a사용가능한 맵: {MAPS}",
  "ERGAMES_LIST": "&6오토게임 목록: {AUTOGAMES}",
  "ERGAMES_ENABLED_PREFIX": "&a",
  "ERGAMES_DISABLED_PREFIX": "&c",
  "ERGAMES_LIST_SEPERATION_PREFIX": "&7",
  "ERGAMES_NOTFOUND": "&c해당 오토게임을 찾을 수 없습니다.",
  "ERGAMES_ALREADYGAME": "&c중복된 방 이름입니다.",
  "TABLIST_RANK_SCORE_TITLE": "&7스코어보드",
  "TABLIST_RANK_SCORE_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "TABLIST_GRANDPRIX_PERSONAL_PERSONAL": "&6이 맵에서의 개인 기록:",
  "TABLIST_GRANDPRIX_PERSONAL_TIME": "&9최고 개인 기록: &c{TIME}",
  "TABLIST_GRANDPRIX_PERSONAL_RANK": "&9랭킹: &c{RANK}",
  "TABLIST_GRANDPRIX_PERSONAL_WINRATE": "&9승률: &c{WINRATE} %",
  "HOLOGRAMS_RANK_SCORE_TITLE": "&6&l상위 15명 최고기록(최고점수)",
  "HOLOGRAMS_RANK_SCORE_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "-2": "&9{RANK} &7- &9-------- &7- &c0",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_RANK_WON_RACEMODE_TITLE": "&6&l상위 15명 최고기록(승리 횟수)",
  "HOLOGRAMS_RANK_WON_RACEMODE_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "-2": "&9{RANK} &7- &9-------- &7- &c0",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_RANK_WON_GRANDPRIX_TITLE": "&6&l상위 15명 최고기록(그랑프리 승리 횟수)",
  "HOLOGRAMS_RANK_WON_GRANDPRIX_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "-2": "&9{RANK} &7- &9-------- &7- &c0",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_RANK_MAP_TITLE": "&6&l{MAP}맵에서의 상위 15명 최고기록",
  "HOLOGRAMS_RANK_MAP_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "-2": "&9{RANK} &7- &9-------- &7- &c0",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_PERSONAL_MAPS_TITLE": "&6&l이 맵의 개인 기록",
  "HOLOGRAMS_PERSONAL_MAPS_SPECIFIC": "&6{MAP_NAME} &7: &c{PLAYER_TIME} &7(#{PLAYER_RANK}) (승률: {WINRATE}%)",
  "HOST_MAPCHOOSER_CHANGEPAGE": "클릭해서 페이지 변경하기",
  "DNF_INSTANT_QUIT": false,
  "MSG_LISTMAPS_INFO": [
    "&a>> {MAP_NAME}",
    " ",
    "&f>> &7유효: {VALID}",
    "&f>> &7활성: {ENABLED}",
    " ",
    "&f>> &7체크포인트: &c{CHECKPOINTS}",
    "&f>> &7종료 지점: &c{ENDS}",
    "&f>> &7로비 위치: &c{LOBBY}",
    "&f>> &7시작 위치: &c{START}",
    "&f>> &7종료 지점: &c{END}",
    "&f>> &7지휘대: &c{PODIUM}",
    " ",
    "&f>> &7최대 시간: &c{TIME}",
    "&f>> &7난이도: &c{DIFFICULTY}",
    " "
  ],
  "HOST_TITLE_PERM": "&7권한: &c{PERMISSION}",
  "HOST_DESC_PERM": [
    " ",
    "&f/erhost setperm &c[permission/none]",
    "&f이 게임에서 권한을 설정합니다.",
    " "
  ],
  "HOST_TITLE_ALERT": "&a알림",
  "HOST_DESC_ALERT": [
    " ",
    "&f이 게임을 채팅으로 홍보합니다.",
    " "
  ],
  "HOST_TITLE_START": "&a시작",
  "HOST_DESC_START": [
    " ",
    "&f클릭해서 게임을 시작합니다.",
    " "
  ],
  "HOST_TITLE_END": "&c카운트 다운 취소",
  "HOST_DESC_END": [
    " ",
    "&f클릭해서 카운트 다운을 취소합니다.",
    " "
  ],
  "HOST_TITLE_SLOTS": "&c최대 유저",
  "HOST_DESC_SLOTS": [
    " ",
    "&f최대 유저: &c{SLOTS}",
    " ",
    "&7좌클릭: +1 (+ 쉬프트: +10)",
    "&7우클릭: -1 (+ 쉬프트: -10)",
    " "
  ],
  "HOST_TITLE_OPEN": "&f방 상태: &a오픈",
  "HOST_TITLE_CLOSED": "&f방 상태: &c닫힘",
  "HOSTCREATOR_CREATE_TITLE": "&a방 만들기",
  "HOSTCREATOR_CREATE_DESCRIPTION": [
    " ",
    "&f방 제목: &c{NAME}",
    " ",
    "&f최대 유저: &c{SLOTS}",
    "&f맵 개수: &c{MAP_NUMBER}",
    "&f모드: &c{MODE}",
    " "
  ],
  "HOSTCREATOR_MAPS_TITLE": "&f맵 개수: &c{MAP_NUMBER}",
  "HOSTCREATOR_MAPS_DESCRIPTION": "&f{ORDER}. {MAP_NAME}",
  "HOSTCREATOR_MAXPLAYERS_TITLE": "&f최대 유저: {SLOTS}",
  "HOST_MAXPLAYERS_SLOTS": [
    " ",
    "&f최대 유저: &c{SLOTS}",
    " ",
    "&7좌클릭: +1 (+ 쉬프트: +10)",
    "&7우클릭: -1 (+ 쉬프트: -10)",
    " "
  ],
  "STATES": {
    "STARTING": "&6시작하는중",
    "STARTED": "&c게임 진행중",
    "WAITING": "&a기다리는중",
    "FINISHED": "&7완주중"
  },
  "SIGN_FORMAT_ONEQUEUE_ONEGAME": [
    "&f[하늘레이싱]",
    "&6{MAP}",
    "{STATE}",
    "&c{PLAYERS}/{MAX_PLAYERS}"
  ],
  "SIGN_FORMAT": [
    "&f[하늘레이싱]",
    "&6{MAP}",
    "&c{PLAYERS}/{MAX_PLAYERS}",
    "&7Click to join"
  ],
  "SIGN_FORMAT_DISABLED": [
    "&f[하늘레이싱]",
    " ",
    "&4비활성화",
    " "
  ],
  "MSG_LISTCHECKPOINT_INFO": [
    " ",
    "&f>> &7ID: {ID_ORDER}",
    " ",
    "&f>> &7x: &c{X}",
    "&f>> &7y: &c{Y}",
    "&f>> &7z: &c{Z}",
    "&f>> &7세계: &c{WORLD}",
    " ",
    "&f>> &7반경: &c{RADIUS}",
    "&f>> &7파티클 수: &c{PARTICLE_AMOUNT}",
    "&f>> &7부스트 수: &c{BOOST_MULTIPLIER}",
    "&f>> &7",
    "&f>> &7파티클 타입: &c{PARTICLE_TYPE}",
    "&f>> &7다음과 연결됨: &c{LINK}"
  ],
  "MSG_LISTGAMES_INFO": [
    "&a>> {GAME_NAME}",
    " ",
    "&f>> &7플레이어: &c{PLAYER_SIZE}",
    "&f>> &7최소 플레이어: &c{MIN_PLAYER}",
    "&f>> &7최대 플레이어: &c{MAX_PLAYER}",
    " ",
    "&f>> &7상태: &c{GAME_STATE}"
  ],
  "MSG_LISTEND_INFO": [
    " ",
    "&f>> &7ID: {ID_ORDER}",
    " ",
    "&f>> &7x: &c{X}",
    "&f>> &7y: &c{Y}",
    "&f>> &7z: &c{Z}",
    "&f>> &7세계: &c{WORLD}",
    " ",
    "&f>> &7반경: &c{RADIUS}",
    "&f>> &7파티클 수: &c{PARTICLE_AMOUNT}",
    "&f>> &7",
    "&f>> &7파티클 타입: &c{PARTICLE_TYPE}",
    null
  ],
  "ERSTATS_MAP": "&6&l이 맵의 개인 통계",
  "ERSTATS_MAP_EACH": "&6>> {MAP_NAME} &9: {PLAYER_TIME} &9(#{PLAYER_RANK}) \n&6> &9(승률: {WINRATE}%)",
  "CHANGEPAGE": "&7클릭해서 페이지 바꾸기",
  "CHANGEPAGERIGHT": "&9➡",
  "CHANGEPAGELEFT": "&c⬅",
  "ERTRAIN_MAP_INFO": [
    "&f완주 시간: &6{PLAYER_TIME}",
    "&f랭킹: &6#{PLAYER_RANK}",
    "&f승률: &6{WINRATE}%",
    " "
  ],
  "ERTRAIN_MAP_INFO_PLUS": [
    "",
    "&7난이도: {DIFFICULTY}",
    "&7바퀴수: &c{LAPS}",
    "",
    "&7클릭해서 이 맵 선택하기"
  ],
  "ERTRAIN_MAP_INFO_TITLE": "&f{MAP_NAME}",
  "FORCE_KICK_VERSION_BELOW_19": true,
  "PLAYER_VERSION_BELOW_19": "&c이 게임을 플레이할 수 있는 올바른 버전이 없습니다.",
  "USAGE_ERSTATS_SHOW": [
    "&6&l개인 통계: {USERNAME}",
    "&7플레이한 레이스: &c{PLAYER_GAME_PLAYED_RACEMODE} ",
    "&7레이스 승리: &c{PLAYER_GAME_WON_RACEMODE} &9(#{RANK_WON_RACEMODE}) &7({PERCENTAGE_WINRATE_RACEMODE}%)",
    "&7플레이한 그랑프리: &c{PLAYER_GAME_PLAYED_GRANDPRIX} ",
    "&7승리한 그랑프리: &c{PLAYER_GAME_WON_GRANDPRIX} &9(#{RANK_WON_GRANDPRIX}) &7({PERCENTAGE_WINRATE_GRANDPRIX}%)",
    "&7점수: &c{SCORE_TOTAL} &9(#{RANK_SCORE_TOTAL})",
    "&6즐겨찾는 맵: &6{FAVORITE_MAP} &7&o(승률: {FAVORITE_MAP_WINRATE}%)",
    "[HOVERMESSAGE_MAP_STATS]&9이 맵의 개인 통계 &7&o(마우스 올리기)"
  ],
  "HOLOGRAMS_PERSONALSTATS": [
    "&6&l개인 통계:",
    "&7플레이한 레이스: &c{PLAYER_GAME_PLAYED_RACEMODE} ",
    "&7레이스 승리: &c{PLAYER_GAME_WON_RACEMODE} &9(#{RANK_WON_RACEMODE}) &7({PERCENTAGE_WINRATE_RACEMODE}%)",
    "&7플레이한 그랑프리: &c{PLAYER_GAME_PLAYED_GRANDPRIX} ",
    "&7승리한 그랑프리: &c{PLAYER_GAME_WON_GRANDPRIX} &9(#{RANK_WON_GRANDPRIX}) &7({PERCENTAGE_WINRATE_GRANDPRIX}%)",
    "&7점수: &c{SCORE_TOTAL} &9(#{RANK_SCORE_TOTAL})",
    "&6즐겨찾는 맵: &6{FAVORITE_MAP} &7&o(승률: {FAVORITE_MAP_WINRATE}%)"
  ],
  "MAP_INGAME_INFO_MENU_TITLE": "&f맵 정보",
  "MAP_INGAME_INFO_DESCRIPTION": [
    "&f{ORDER}. {MAP_NAME}",
    "&f-> 상태: {PLAYER_TIME},#{PLAYER_RANK} ({PLAYER_WINRATE}%)"
  ],
  "NOTENOUGH_MAP_HOSTCREATOR": "&c방을 만들려면 최소 1개의 맵이 필요합니다.",
  "ONEGAME": false,
  "ONEGAME_AUTOJOINGAME": "",
  "ONEGAME_KICK_AFTER_GAME": true,
  "ONEGAME_LOBBYSERVER": "",
  "ONEGAME_REMOVEJOINQUITMESSAGES": true,
  "ONEGAME_MOTD_USE": false,
  "ONEGAME_MOTD": [
    "&f>> 하늘레이싱: {STATE} &7[-] 맵: &6{MAP}",
    "§f>> &7플레이중: §c{PLAYING} &7[-] 모드: {MODE_INFORMATION}"
  ],
  "ONEGAME_MOTD_RACEMODE_INFORMATION": "&a레이스 모드",
  "ONEGAME_MOTD_GRANDPRIX_INFORMATION": "&a그랑프리 &f{ROUND}/{ROUND_MAX}",
  "ONEGAME_MOTD_CHANGE_MAX_PLAYERS": true,
  "CHALLENGE_MAXGAME": false,
  "CHALLENGE_MAXGAME_PER_PLAYER": 10,
  "CHALLENGE_MAXGAME_COMPLETION_COMMAND": "[CONSOLE]/give {SELF_PLAYER} minecraft:cookie §%§[PLAYER]/tell {SELF_PLAYER} 명령어를 실행하였습니다.",
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

</details>

<details>

<summary>Scoreboard.json</summary>

```
{
  "Enable": false,
  "TickReloadInterval": 20,
  "link": "chooseit.io/er",
  "RaceMode": {
    "perState": {
      "FINISHED": {
        "title": "하늘레이싱",
        "lines": [
          "",
          "&e1등 - {RANK_PLAYER_1}",
          "&72등 - {RANK_PLAYER_2}",
          "&63등 - {RANK_PLAYER_3}",
          "순위: {SELF_RANK_PLAYER}",
          "",
          "{LINK}"
        ]
      },
      "WAITING": {
        "title": "하늘레이싱",
        "lines": [
          "",
          "&f플레이어: {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&f맵: {CURRENT_MAP}",
          "&f모드: &aRace",
          "",
          "&c{NEEDED_PLAYER}명의 플레이어가 필요합니다.",
          "",
          "{LINK}"
        ]
      },
      "HOST_FINISHED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&e1등 - {RANK_PLAYER_1}",
          "&72등 - {RANK_PLAYER_2}",
          "&63등 - {RANK_PLAYER_3}",
          "순위: {SELF_RANK_PLAYER}",
          "",
          "{LINK}"
        ]
      },
      "SPECTATOR": {
        "title": "하늘레이싱",
        "lines": [
          "",
          "남은 시간: &c{TIME_LEFT}",
          "&f플레이어: {CURRENT_PLAYER}/{MAX_PLAYER}",
          "",
          "&e1등 - {RACE_RANK_PLAYER_1}",
          "&72등 - {RACE_RANK_PLAYER_2}",
          "&63등 - {RACE_RANK_PLAYER_3}",
          "&f4등 - {RACE_RANK_PLAYER_4}",
          "&f5등 - {RACE_RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "HOST_STARTED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "남은 시간: &c{TIME_LEFT}",
          "&f플레이어: {CURRENT_PLAYER}/{MAX_PLAYER}",
          "",
          "&e1등 - {RACE_RANK_PLAYER_1}",
          "&72등 - {RACE_RANK_PLAYER_2}",
          "&63등 - {RACE_RANK_PLAYER_3}",
          "순위: {SELF_RACE_RANK_PLAYER}",
          "",
          "체크포인트: &6{SELF_CPS}/{MAX_CPS}",
          "바퀴수: &6{SELF_LAPS}/{MAX_LAPS}",
          "",
          "{LINK}"
        ]
      },
      "STARTED": {
        "title": "하늘레이싱",
        "lines": [
          "",
          "남은 시간: &c{TIME_LEFT}",
          "&f플레이어: {CURRENT_PLAYER}/{MAX_PLAYER}",
          "",
          "&e1등 - {RACE_RANK_PLAYER_1}",
          "&72등 - {RACE_RANK_PLAYER_2}",
          "&63등 - {RACE_RANK_PLAYER_3}",
          "순위: {SELF_RACE_RANK_PLAYER}",
          "",
          "체크포인트: &6{SELF_CPS}/{MAX_CPS}",
          "바퀴수: &6{SELF_LAPS}/{MAX_LAPS}",
          "",
          "{LINK}"
        ]
      },
      "HOST_SPECTATOR": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "남은 시간: &c{TIME_LEFT}",
          "&f플레이어: {CURRENT_PLAYER}/{MAX_PLAYER}",
          "",
          "&e1등 - {RACE_RANK_PLAYER_1}",
          "&72등 - {RACE_RANK_PLAYER_2}",
          "&63등 - {RACE_RANK_PLAYER_3}",
          "&f4등 - {RACE_RANK_PLAYER_4}",
          "&f5등 - {RACE_RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "HOST_WAITING": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&f플레이어: {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&f맵: {CURRENT_MAP}",
          "&f모드: &a레이스",
          "",
          "호스트: {HOST}",
          "",
          "{LINK}"
        ]
      },
      "HOST_STARTING": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&f플레이어: {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&f맵: {CURRENT_MAP}",
          "&f모드: &aRace",
          "",
          "호스트: {HOST}",
          "&c{STARTING_COUNTDOWN}초 후에 시작됩니다.",
          "",
          "{LINK}"
        ]
      },
      "SPECTATOR_FINISHED": {
        "title": "하늘레이싱",
        "lines": [
          "",
          "&e1등 - {RANK_PLAYER_1}",
          "&72등 - {RANK_PLAYER_2}",
          "&63등 - {RANK_PLAYER_3}",
          "&f4등 - {RANK_PLAYER_4}",
          "&f5등 - {RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "STARTING": {
        "title": "하늘레이싱",
        "lines": [
          "",
          "&f플레이어: {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&f맵: {CURRENT_MAP}",
          "&f모드: &aRace",
          "",
          "&c{STARTING_COUNTDOWN}초 후에 시작됩니다.",
          "",
          "{LINK}"
        ]
      },
      "HOST_SPECTATOR_FINISHED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&e1등 - {RANK_PLAYER_1}",
          "&72등 - {RANK_PLAYER_2}",
          "&63등 - {RANK_PLAYER_3}",
          "&f4등 - {RANK_PLAYER_4}",
          "&f5등 - {RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      }
    }
  },
  "GrandPrix": {
    "perState": {
      "FINISHED": {
        "title": "하늘레이싱",
        "lines": [
          "",
          "&e1등 - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72등 - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63등 - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "순위: {SELF_RANK_PLAYER}",
          "점수: {SELF_RANK_PLAYER_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "HOST_BETWEENROUND": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "다음 맵: {CURRENT_MAP}",
          "{CURRENT_MAP_DIFFICULTY}",
          "&6PB: {SELF_MAP_PB}",
          "",
          "&e1등 - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72등 - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63등 - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "순위: {SELF_RANK_PLAYER}",
          "점수: {SELF_RANK_PLAYER_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "HOST_STARTED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "남은 시간: &c{TIME_LEFT}",
          "&f플레이어: {CURRENT_PLAYER}/{MAX_PLAYER}",
          "라운드: {CURRENT_ROUND}/{MAX_ROUND}",
          "",
          "&e1등 - {RACE_RANK_PLAYER_1}",
          "&72등 - {RACE_RANK_PLAYER_2}",
          "&63등 - {RACE_RANK_PLAYER_3}",
          "순위: {SELF_RACE_RANK_PLAYER}",
          "",
          "체크포인트: &6{SELF_CPS}/{MAX_CPS}",
          "바퀴수: &6{SELF_LAPS}/{MAX_LAPS}",
          "",
          "{LINK}"
        ]
      },
      "HOST_SPECTATOR_BETWEENROUND": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "다음 맵: {CURRENT_MAP}",
          "{CURRENT_MAP_DIFFICULTY}",
          "&6PB: {SELF_MAP_PB}",
          "",
          "&e1등 - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72등 - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63등 - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "&f4등 - {RANK_PLAYER_4} - {RANK_PLAYER_4_SCORE}",
          "&f5등 - {RANK_PLAYER_5} - {RANK_PLAYER_5_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "HOST_SPECTATOR": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "남은 시간: &c{TIME_LEFT}",
          "&f플레이어: {CURRENT_PLAYER}/{MAX_PLAYER}",
          "라운드: {CURRENT_ROUND}/{MAX_ROUND}",
          "",
          "&e1등 - {RACE_RANK_PLAYER_1}",
          "&72등 - {RACE_RANK_PLAYER_2}",
          "&63등 - {RACE_RANK_PLAYER_3}",
          "&f4등 - {RACE_RANK_PLAYER_4}",
          "&f5등 - {RACE_RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "SPECTATOR_FINISHED": {
        "title": "하늘레이싱",
        "lines": [
          "",
          "&e1등 - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72등 - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63등 - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "&f4등 - {RANK_PLAYER_4} - {RANK_PLAYER_4_SCORE}",
          "&f5등 - {RANK_PLAYER_5} - {RANK_PLAYER_5_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "STARTING": {
        "title": "하늘레이싱",
        "lines": [
          "",
          "&f플레이어: {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&f맵: {CURRENT_MAP}",
          "&f모드: &aGrandPrix",
          "라운드: 1/{MAX_ROUND}",
          "",
          "&c{STARTING_COUNTDOWN}초 후에 시작됩니다.",
          "",
          "{LINK}"
        ]
      },
      "BETWEENROUND": {
        "title": "하늘레이싱",
        "lines": [
          "",
          "다음 맵: {CURRENT_MAP}",
          "{CURRENT_MAP_DIFFICULTY}",
          "&6PB: {SELF_MAP_PB}",
          "",
          "&e1등 - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72등 - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63등 - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "순위: {SELF_RANK_PLAYER}",
          "점수: {SELF_RANK_PLAYER_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "WAITING": {
        "title": "하늘레이싱",
        "lines": [
          "",
          "&f플레이어: {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&f맵: {CURRENT_MAP}",
          "&f모드: &aGrandPrix",
          "라운드: 1/{MAX_ROUND}",
          "",
          "&c{NEEDED_PLAYER}명의 플레이어가 필요합니다.",
          "",
          "{LINK}"
        ]
      },
      "HOST_FINISHED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&e1등 - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72등 - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63등 - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "순위: {SELF_RANK_PLAYER}",
          "점수: {SELF_RANK_PLAYER_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "SPECTATOR": {
        "title": "하늘레이싱",
        "lines": [
          "",
          "남은 시간: &c{TIME_LEFT}",
          "&f플레이어: {CURRENT_PLAYER}/{MAX_PLAYER}",
          "라운드: {CURRENT_ROUND}/{MAX_ROUND}",
          "",
          "&e1등 - {RACE_RANK_PLAYER_1}",
          "&72등 - {RACE_RANK_PLAYER_2}",
          "&63등 - {RACE_RANK_PLAYER_3}",
          "&f4등 - {RACE_RANK_PLAYER_4}",
          "&f5등 - {RACE_RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "SPECTATOR_BETWEENROUND": {
        "title": "하늘레이싱",
        "lines": [
          "",
          "다음 맵: {CURRENT_MAP}",
          "{CURRENT_MAP_DIFFICULTY}",
          "&6PB: {SELF_MAP_PB}",
          "",
          "&e1등 - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72등 - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63등 - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "&f4등 - {RANK_PLAYER_4} - {RANK_PLAYER_4_SCORE}",
          "&f5등 - {RANK_PLAYER_5} - {RANK_PLAYER_5_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "STARTED": {
        "title": "하늘레이싱",
        "lines": [
          "",
          "남은 시간: &c{TIME_LEFT}",
          "&f플레이어: {CURRENT_PLAYER}/{MAX_PLAYER}",
          "라운드: {CURRENT_ROUND}/{MAX_ROUND}",
          "",
          "&e1등 - {RACE_RANK_PLAYER_1}",
          "&72등 - {RACE_RANK_PLAYER_2}",
          "&63등 - {RACE_RANK_PLAYER_3}",
          "순위: {SELF_RACE_RANK_PLAYER}",
          "",
          "체크포인트: &6{SELF_CPS}/{MAX_CPS}",
          "바퀴수: &6{SELF_LAPS}/{MAX_LAPS}",
          "",
          "{LINK}"
        ]
      },
      "HOST_WAITING": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&f플레이어: {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&f맵: {CURRENT_MAP}",
          "&f모드: &aGrandPrix",
          "라운드: 1/{MAX_ROUND}",
          "",
          "호스트: {HOST}",
          "",
          "{LINK}"
        ]
      },
      "HOST_STARTING": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&f플레이어: {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&f맵: {CURRENT_MAP}",
          "&f모드: &aGrandPrix",
          "라운드: 1/{MAX_ROUND}",
          "",
          "호스트: {HOST}",
          "&c{STARTING_COUNTDOWN}초 후에 시작됩니다.",
          "",
          "{LINK}"
        ]
      },
      "HOST_SPECTATOR_FINISHED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&e1등 - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72등 - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63등 - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "&f4등 - {RANK_PLAYER_4} - {RANK_PLAYER_4_SCORE}",
          "&f5등 - {RANK_PLAYER_5} - {RANK_PLAYER_5_SCORE}",
          "",
          "{LINK}"
        ]
      }
    }
  },
  "Training": {
    "perState": {
      "TRAINING": {
        "title": "하늘레이싱",
        "lines": [
          "",
          "&6PB: {SELF_MAP_PB}",
          "&f순위: {SELF_MAP_RANK}",
          "",
          "기록: {MAP_WR_PLAYER}",
          "&6시간: &c{MAP_WR_TIME}",
          "",
          "남은 시간: &c{TIME_LEFT}",
          "&f난이도: {CURRENT_MAP_DIFFICULTY}",
          "체크포인트: &6{SELF_CPS}/{MAX_CPS}",
          "바퀴수: &6{SELF_LAPS}/{MAX_LAPS}",
          "",
          "{LINK}"
        ]
      }
    }
  }
}
```

</details>
