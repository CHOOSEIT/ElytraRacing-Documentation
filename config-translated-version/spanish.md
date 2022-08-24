# 🇪🇸 Spanish

{% hint style="warning" %}
Files translated using Deepl.com

The goal of this translation is not to have the perfect on but to have a version that will help you to start to configure the plugin in the language you want

If you see bad translations please send me a message on discord
{% endhint %}

{% hint style="warning" %}
Archivos traducidos con Deepl.com&#x20;

El objetivo de esta traducción no es tener el perfecto en pero para tener una versión que le ayudará a empezar a configurar el plugin en el idioma que desee&#x20;

Si ves malas traducciones por favor envíame un mensaje en discordia
{% endhint %}

<details>

<summary>Config.json</summary>

```
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
  "ER_TRAIN_MAP_NOTFOUND": "&cEste mapa no es elegible para la formación",
  "ER_TRAIN_CHOOSE_MAP_GUI_TITLE": "Elija un mapa",
  "SIGN_RELOAD_SEC": 3,
  "TELEPORT_SOLVER": false,
  "UNLOCK_DISTANCE": 100,
  "UNLOCK_OBJECT": "&fObjeto desbloqueado",
  "LOCK_OBJECT": "&fVinculado este objeto con usted &asucede",
  "LOCK_ITEMS_GIVE": "&fVinculado este objeto con usted &asucede",
  "LOCK_OBJECT_NEAR_NOTFOUND": "&cNo se ha encontrado ningún objeto cerca de usted",
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
  "MAP_DIFFICULTY_MESSAGE": "&7Dificultad del mapa: {DIFFICULTY}",
  "DNF_POINT": -1,
  "TABLIST_GRANDPRIX": true,
  "COMMANDS_WHITELIST": false,
  "COMMANDS_WHITELIST_COMMANDS": [
    "msg",
    "rl",
    "reload"
  ],
  "COMMANDS_WHITELIST_BYPASS_PERMISSION": "elytraracing.wlcommands.bypass",
  "COMMANDS_MESSAGE": "&c¡No se puede realizar este comando aquí !",
  "SPECTATOR_ITEM": true,
  "STATIC_ITEMS": true,
  "RankingMaxPlayers": 8,
  "PODIUM_FIREWORKS": true,
  "PODIUM_FIREWORK_NUMBER": 10,
  "END_TIME": 30,
  "DISABLE_ELYTRA": false,
  "COMMAND_EXECUTION_PER_RANK_IN_HOST": false,
  "COMMAND_EXECUTION_PER_RANK_GRANDPRIX": {
    "-1": "[CONSOLE]/give {SELF_PLAYER} minecraft:cookie {SCORE} §%§[PLAYER]/tell {SELF_PLAYER} has ejecutado un comando",
    "0": "[PLAYER]/tell {SELF_PLAYER} has ejecutado un comando"
  },
  "COMMAND_EXECUTION_PER_RANK_RACEMODE": {
    "-1": "[CONSOLE]/give {SELF_PLAYER} minecraft:cookie 5 §%§[PLAYER]/tell {SELF_PLAYER} has ejecutado un comando",
    "0": "[PLAYER]/tell {SELF_PLAYER} has ejecutado un comando"
  },
  "PERMISSION_MESSAGE": "&cNo está permitido realizar este comando",
  "PERMISSION_MESSAGE_HOST": "&cNo está permitido unirse a este juego",
  "MSG_NUMBER_LAP": "&eNúmero de vueltas: {LAPS}",
  "HOLOGRAM_NOT_FOUND": "&cEste holograma no puede ser encontrado.",
  "ITEM_1CP_BACK": "&cPunto de control anterior",
  "ITEM_1CP_BACK_MATERIAL": null,
  "ITEM_1CP_BACK_SLOT": 0,
  "ITEM_2CP_BACK": "&c2 puntos de control atrás",
  "ITEM_2CP_BACK_MATERIAL": null,
  "ITEM_2CP_BACK_SLOT": 1,
  "ITEM_RESTART": "&cREINICIAR",
  "ITEM_RESTART_MATERIAL": null,
  "ITEM_RESTART_SLOT": 4,
  "ITEM_DNF": "&cNHT",
  "ITEM_DNF_MATERIAL": null,
  "ITEM_DNF_SLOT": 8,
  "ITEM_BED": "&cDeja el juego",
  "ITEM_BED_MATERIAL": null,
  "ITEM_BED_SLOT": 8,
  "ITEM_SPEC": "&aUnirse al modo de especificación",
  "ITEM_SPEC_MATERIAL": null,
  "ITEM_SPEC_SLOT": 4,
  "ITEM_CUSTOM": "&aUnirse al modo de especificación",
  "ITEM_CUSTOM_MATERIAL": null,
  "ITEM_CUSTOM_SLOT": 3,
  "ITEM_HOST": "&aConfiguración del host",
  "ITEM_HOST_MATERIAL": null,
  "ITEM_HOST_SLOT": 4,
  "ITEM_PARTICLE": "&aSelector de partículas",
  "ITEM_PARTICLE_MATERIAL": null,
  "ITEM_PARTICLE_SLOT": 2,
  "ITEM_FIREWORK_SLOT": 2,
  "ITEM_PAPERMAPINFO_SLOT": 4,
  "ITEM_PAPERMAPINFO_MATERIAL": null,
  "ITEM_HOSTSEPARATION_TITLE": "&fSelección de mapas",
  "ITEM_HOSTSEPARATION_DESCRIPTION": "&a⬇  ⬇  ⬇  ⬇  ⬇  ⬇",
  "ITEM_HOSTSEPARATION_MATERIAL": null,
  "ITEM_HOSTMAP_TITLE_SELECTED": "&a{MAP_NAME}",
  "ITEM_HOSTMAP_TITLE_NOTSELECTED": "&f{MAP_NAME}",
  "ITEM_HOSTMAP_MATERIAL_SELECTED": null,
  "ITEM_HOSTMAP_MATERIAL_NOTSELECTED": null,
  "HOSTMAP_CREATOR_INVENTORY_TITLE": "Creador del anfitrión",
  "ALERT_HOST": "&6{PLAYER} &aacaba de empezar a acoger &7(Haga clic aquí para unirse)",
  "ERROR_MESSAGE": "&cSe ha encontrado un error durante el proceso",
  "ACTIONBAR_TIME": "&7Tiempo restante: &c{TIME}",
  "MSG_PAGE": "&7Página &c{PAGE} &7de &c{MAX_PAGE}",
  "MSG_ENDMAP": "&6{PLAYER} &7-> &c{ARG}",
  "MSG_GAMEFULL": "&cEste juego ya está lleno",
  "MSG_GAMESTARTED": "&cEste juego ya ha comenzado",
  "LOCATIONNOTDEFINED": "&c¡Esta ubicación no está definida!",
  "MSG_ERHOST_LISTGAMES": "&aLista de juegos &7&o(hover): ",
  "MSG_ERMAP_LISTGAMES_GAMESFORMAT": "&c>> &f{GAME_NAME} ",
  "MSG_ERMAP_LISTCHECKPOINT": "&aLista de puntos de control &7&o(hover): ",
  "DEFAULT": "&6DEFAULT",
  "NONE": "&6NINGUNO",
  "NOBODY": "Nadie",
  "MSG_ERMAP_LISTCHECKPOINT_CHECKPOINTFORMAT": "&f#{CHECKPOINT_ID_ORDER} &c>> &f({X},{Y},{Z}) &7&o(Haz clic para teletransportarte)",
  "MSG_ERMAP_LISTEND": "&aLista de finales &7&o(hover): ",
  "MSG_ERMAP_LISTEND_ENDFORMAT": "&f#{END_ID_ORDER} &c>> &f({X},{Y},{Z}) &7&o(Click to Haz clic para teletransportarte)",
  "YES": "&aSí",
  "NO": "&cNo",
  "CHECK": "&a✓",
  "CROSS": "&cx",
  "MSG_STATE_WAITING": "&aEsperando",
  "MSG_STATE_STARTING": "&6Comienza",
  "MSG_STATE_STARTED": "&cComenzó",
  "MSG_SPEC_JOINING": "&7Unirse al juego como espectador...",
  "PERM_SPECGAME": "elytraracing.specgame",
  "MSG_NOGAMETOLEAVE": "&cNo es necesario que te vayas, aún no estás en un juego",
  "MSG_GAMENOTEXIST": "&cEste juego no existe",
  "MSG_NOTYOURHOST": "&cNo eres el anfitrión de este juego",
  "MSG_TIMERSTART": "&aTemporizador iniciado",
  "MSG_TIMERCANCEL": "&cTemporizador cancelado",
  "MSG_HOST_NOTEXIST": "&cNo se puede encontrar a su anfitrión",
  "MSG_LEAVEYOURGAME": "&cYa estás en un juego",
  "MSG_GAMENOTOPEN": "&cEsto no está abierto",
  "MSG_MAPCREATING": "&aCrear un mapa...",
  "MSG_MAPNAMEEXIST": "&cEste nombre de mapa ya existe",
  "MSG_GAMENAME_EXIST": "&cEste nombre de juego ya existe",
  "MSG_HOST_CREATING": "&aEste nombre de juego ya existe",
  "MSG_CHECKPOINT_VERIFIED": "&fPunto de control superado. ({CHECKPOINT_PASSED} / {CHECKPOINT_MAX})",
  "MSG_LAP_VERIFIED": "&eVuelta completada. ({LAP_PASSED} / {LAP_MAX})",
  "MSG_GAME_PLAYERJOIN": "&6¡{PLAYER_NAME} &fse unió a la carrera ! &7&o({PLAYER_SIZE} / {MAX_PLAYER})",
  "MSG_GAME_PLAYERJOIN_PLAYERNEEDEDLEFT": " &c({PLAYER_NEEDED} se necesita la izquierda)",
  "MSG_GAME_PLAYERLEAVE": "&6¡{PLAYER_NAME} &fabandonó la carrera! &7&o({PLAYER_SIZE} / {MAX_PLAYER})",
  "MSG_GAME_NOTENOUGHPLAYERS": "&cTemporizador cancelado, no hay suficientes jugadores",
  "PLAYER_NOTFOUND": "&cJugador no encontrado.",
  "ERHOST_PLAYER_NOTFOUND": "&cEste jugador no está en su juego.",
  "MSG_MAP_NOTAVAILABLE": "&cEste mapa no está disponible.",
  "MSG_MAP_NOTAVAILABLE2": "&c{MAP} ¡no está disponible!",
  "MSG_MAPNOTFOUND2": "&c{ARG} no se puede encontrar",
  "MSG_ALERT": "&cYa has enviado demasiadas alertas",
  "PARTICLE_LIST": "&7Lista de partículas (Haga clic para activar): ",
  "PARTICLE_LIST_ITEMS": " &7{item}",
  "PARTICLE_LIST_ITEMS_HOVER": "&7{item}: Haga clic para activar",
  "PARTICLE_LIST_NOTFOUND": "&cEste tipo de partícula no se puede encontrar",
  "GRANDPRIX": "Grandprix",
  "RACEMODE": "Race",
  "PERSONAL_BEST": " &6&k&llol &6&lMejor marca personal&k&llol",
  "TIME_NOT_FOUND": " - ",
  "RANK_NOT_FOUND": "-",
  "ER_PLAY_GAME": "&cNo se ha encontrado ningún juego.",
  "MSG_STEP_TIMER": {
    "0": "Su juego está comenzando...",
    "1": "Su juego está comenzando en &f1 &fsegundo",
    "2": "Su juego está comenzando en &a2 &fsegundos",
    "3": "Su juego está comenzando en &23 &fsegundos",
    "4": "Su juego está comenzando en &64 &fsegundos",
    "5": "Su juego está comenzando en &c5 &fsegundos",
    "10": "Su juego está comenzando en &c10 &fsegundos",
    "30": "Su juego está comenzando en &c30 &fsegundos"
  },
  "MSG_STEPROUND_TIMER": {
    "0": "Comienza la siguiente ronda...",
    "1": "La próxima ronda comienza en &f1 &fsegundo",
    "2": "La próxima ronda comienza en &a2 &fsegundos",
    "3": "La próxima ronda comienza en &23 &fsegundos",
    "4": "La próxima ronda comienza en &64 &fsegundos",
    "5": "La próxima ronda comienza en &c5 &fsegundos",
    "15": "La próxima ronda comienza en &c15 &fsegundos"
  },
  "MSG_STEP_TIMER_MAPSTART_TITLE": {
    "0": "&c>>  IR  <<",
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
  "MSG_PRE_RANK": "&7\nClasificación:\n",
  "MSG_PRE_SCORE": "&7\nMarcador:\n",
  "MSG_YOURRANK": "&7Su rango en este mapa: &c{RANK}",
  "MSG_YOURSCORE": "&7Su clasificación general es: &c{RANK} &7con &c{SCORE} &7puntos",
  "MSG_ARG_RANK_TIME_DNF": "&cNHT",
  "MSG_ARG_RANK_TIME_TIME": "&c{TIME}",
  "TELEPORTING": "&7Teletransporte...",
  "TIMEFORMAT": "{MINUTES}m {SECONDS}.{MILLISECONDS}s",
  "TIMEFORMAT_WM": "{MINUTES}m {SECONDS}s",
  "PLACEHOLDER_NOTFOUND_PLAYER": "Ninguno",
  "PLACEHOLDER_DEFAULT_NUMBER": "0",
  "PLACEHOLDER_DEFAULT_TEXT": "",
  "PLACEHOLDER_DEFAULT_RANKING": "-",
  "ERMAP_MAP_DELETE": "&cEl mapa se borrará después de una recarga/reinicio",
  "MSG_MAPNOTFOUND": "&cEste mapa no se puede encontrar",
  "MSG_SAVE_SUCCESSFUL": "&fLos cambios se han &guardado con éxito",
  "MSG_FILE_RELOAD": "&fLos archivos han sido &cargados con éxito.",
  "MSG_SHOW_ON": "&aActivación de ...",
  "MSG_SHOW_OFF": "&cDesactivación de ...",
  "MSG_CHECKPOINT_NOTFOUND": "&cEste punto de control no se puede encontrar",
  "MSG_END_NOTFOUND": "&cEste final no se puede encontrar",
  "ID_ORDER_ARG": "&c[id_order] debe ser un número entero",
  "ID_ORDER_TARGET_ARG": "&c[id_order_target] debe ser un número entero",
  "DEGREES_ARG": "&c[rotation] debe ser un número entero",
  "MULTIPLIER_ARG": "&c[amount] debe ser un flotador",
  "SIZE_ARG": "&c[size] debe ser un flotador",
  "AMOUNT_ARG": "&c[amount] debe ser un número entero",
  "SECONDS_ARG": "&c[seconds] debe ser un número entero entre 0 y 59",
  "MINUTES_ARG": "&c[minutes] debe ser un número entero mayor que 0",
  "MAX_PLAYER_ARG": "&c[slots] debe ser un número entero mayor que 0",
  "PAGE_ARG": "&c[page] debe ser un entero superior a 0",
  "ERCONFIG_SETITEM_ID_NOT_FOUND": "&cEste [id_item] no puede ser encontrado",
  "ERCONFIG_SETITEM_ITEM_NOT_FOUND": "&cEl artículo en su mano no puede ser encontrado",
  "SPEC_PERM": null,
  "SPEC_PERM_MESSAGE": "&cNo tienes permiso para presenciar un partido.",
  "HOST_GAMENOTOPEN": "&cSu juego no está abierto",
  "SPECTATORMODE": "&aHa entrado en modo espectador &7(Pulse aquí para salir o escriba '/er quitspec')",
  "STUCKSPECTATOR": "&aUtiliza /er near de §f para teletransportarte al jugador más cercano",
  "AVAILABLE_MAPS": "&aMapas disponibles: {MAPS}",
  "ERGAMES_LIST": "&6Lista de autogames: {AUTOGAMES}",
  "ERGAMES_ENABLED_PREFIX": "&a",
  "ERGAMES_DISABLED_PREFIX": "&c",
  "ERGAMES_LIST_SEPERATION_PREFIX": "&7",
  "ERGAMES_NOTFOUND": "&cEste autojuego no se puede encontrar",
  "ERGAMES_ALREADYGAME": "&cNo puedes activar este autogame porque ya existe un juego con el mismo nombre",
  "TABLIST_RANK_SCORE_TITLE": "&7Scoreboard",
  "TABLIST_RANK_SCORE_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "TABLIST_GRANDPRIX_PERSONAL_PERSONAL": "&6Estadísticas personales en este mapa:",
  "TABLIST_GRANDPRIX_PERSONAL_TIME": "&9Mejor tiempo personal: &c{TIME}",
  "TABLIST_GRANDPRIX_PERSONAL_RANK": "&9Su rango: &c{RANK}",
  "TABLIST_GRANDPRIX_PERSONAL_WINRATE": "&9Su porcentaje de victorias: &c{WINRATE} %",
  "HOLOGRAMS_RANK_SCORE_TITLE": "&6&lLas 15 mejores puntuaciones",
  "HOLOGRAMS_RANK_SCORE_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "-2": "&9{RANK} &7- &9-------- &7- &c0",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_RANK_WON_RACEMODE_TITLE": "&6&lLas 15 carreras más ganadas",
  "HOLOGRAMS_RANK_WON_RACEMODE_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "-2": "&9{RANK} &7- &9-------- &7- &c0",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_RANK_WON_GRANDPRIX_TITLE": "&6&lTop 15 Grandes premios ganados",
  "HOLOGRAMS_RANK_WON_GRANDPRIX_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "-2": "&9{RANK} &7- &9-------- &7- &c0",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_RANK_MAP_TITLE": "&6&lLos 15 mejores momentos en {MAP}",
  "HOLOGRAMS_RANK_MAP_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "-2": "&9{RANK} &7- &9-------- &7- &c0",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_PERSONAL_MAPS_TITLE": "&6&lEstadísticas personales en los mapas",
  "HOLOGRAMS_PERSONAL_MAPS_SPECIFIC": "&6{MAP_NAME} &7: &c{PLAYER_TIME} &7(#{PLAYER_RANK}) (porcentaje de victorias: {WINRATE}%)",
  "HOST_MAPCHOOSER_CHANGEPAGE": "Haga clic aquí para cambiar de página",
  "DNF_INSTANT_QUIT": false,
  "MSG_LISTMAPS_INFO": [
    "&a>> {MAP_NAME}",
    " ",
    "&f>> &7Válido: {VALID}",
    "&f>> &7Activado: {ENABLED}",
    " ",
    "&f>> &7Puntos de control: &c{CHECKPOINTS}",
    "&f>> &7Finaliza: &c{ENDS}",
    "&f>> &7Ubicación del vestíbulo: &c{LOBBY}",
    "&f>> &7Lugar de inicio: &c{START}",
    "&f>> &7Lugar de finalización: &c{END}",
    "&f>> &7Podio: &c{PODIUM}",
    " ",
    "&f>> &7Tiempo máx.: &c{TIME}",
    "&f>> &7Dificultad: &c{DIFFICULTY}",
    " "
  ],
  "HOST_TITLE_PERM": "&7Permiso: &c{PERMISSION}",
  "HOST_DESC_PERM": [
    " ",
    "&f/erhost setperm &c[permission/none]",
    "&fPara definir el permiso para unirse a su juego.",
    " "
  ],
  "HOST_TITLE_ALERT": "&aAlerta",
  "HOST_DESC_ALERT": [
    " ",
    "&fHaga clic aquí para transmitir una invitación para unirse a su juego",
    " "
  ],
  "HOST_TITLE_START": "&aInicie",
  "HOST_DESC_START": [
    " ",
    "&fHaga clic aquí para iniciar el juego",
    " "
  ],
  "HOST_TITLE_END": "&cCancelar la cuenta atrás",
  "HOST_DESC_END": [
    " ",
    "&fPulse aquí para detener la cuenta atrás",
    " "
  ],
  "HOST_TITLE_SLOTS": "&cNombre del lugar",
  "HOST_DESC_SLOTS": [
    " ",
    "&fNúmero de ranuras: &c{SLOTS}",
    " ",
    "&7Clic izquierdo: +1 (+ Shift: +10)",
    "&7Clic derecho: -1 (+ Shift: -10)",
    " "
  ],
  "HOST_TITLE_OPEN": "&fSu anfitrión es actualmente: &aAbrir",
  "HOST_TITLE_CLOSED": "&fSu anfitrión está actualmente: &cCerrado",
  "HOSTCREATOR_CREATE_TITLE": "&aCrear el anfitrión",
  "HOSTCREATOR_CREATE_DESCRIPTION": [
    " ",
    "&fNombre: &c{NAME}",
    " ",
    "&fNúmero de ranuras: &c{SLOTS}",
    "&fNúmero de mapas: &c{MAP_NUMBER}",
    "&fModo: &c{MODE}",
    " "
  ],
  "HOSTCREATOR_MAPS_TITLE": "&fNúmero de mapas: &c{MAP_NUMBER}",
  "HOSTCREATOR_MAPS_DESCRIPTION": "&f{ORDER}. {MAP_NAME}",
  "HOSTCREATOR_MAXPLAYERS_TITLE": "&fNúmero de ranuras: {SLOTS}",
  "HOST_MAXPLAYERS_SLOTS": [
    " ",
    "&fNúmero de ranuras: &c{SLOTS}",
    " ",
    "&7Clic izquierdo: +1 (+ Shift: +10)",
    "&7Clic derecho: -1 (+ Shift: -10)",
    " "
  ],
  "STATES": {
    "STARTING": "&6Comienza",
    "STARTED": "&cComenzó",
    "WAITING": "&aEsperando",
    "FINISHED": "&7Acabado"
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
    "&7Haga clic para unirse"
  ],
  "SIGN_FORMAT_DISABLED": [
    "&f[ElytraRacing]",
    " ",
    "&4DESACTIVADO",
    " "
  ],
  "MSG_LISTCHECKPOINT_INFO": [
    " ",
    "&f>> &7ID: {ID_ORDER}",
    " ",
    "&f>> &7x: &c{X}",
    "&f>> &7y: &c{Y}",
    "&f>> &7z: &c{Z}",
    "&f>> &7Mundo: &c{WORLD}",
    " ",
    "&f>> &7Radio: &c{RADIUS}",
    "&f>> &7Cantidad de partículas: &c{PARTICLE_AMOUNT}",
    "&f>> &7Multiplicador de impulso: &c{BOOST_MULTIPLIER}",
    "&f>> &7",
    "&f>> &7Tipo de partícula: &c{PARTICLE_TYPE}",
    "&f>> &7Vinculado a: &c{LINK}"
  ],
  "MSG_LISTGAMES_INFO": [
    "&a>> {GAME_NAME}",
    " ",
    "&f>> &7Jugadores: &c{PLAYER_SIZE}",
    "&f>> &7jugadores mínimos: &c{MIN_PLAYER}",
    "&f>> &7máximo de jugadores: &c{MAX_PLAYER}",
    " ",
    "&f>> &7Estado: &c{GAME_STATE}"
  ],
  "MSG_LISTEND_INFO": [
    " ",
    "&f>> &7ID: {ID_ORDER}",
    " ",
    "&f>> &7x: &c{X}",
    "&f>> &7y: &c{Y}",
    "&f>> &7z: &c{Z}",
    "&f>> &7Mundo: &c{WORLD}",
    " ",
    "&f>> &7Radio: &c{RADIUS}",
    "&f>> &7Cantidad de partículas: &c{PARTICLE_AMOUNT}",
    "&f>> &7",
    "&f>> &7Tipo de partícula: &c{PARTICLE_TYPE}"
  ],
  "ERSTATS_MAP": "&6&lEstadísticas personales en los mapas",
  "ERSTATS_MAP_EACH": "&6>> {MAP_NAME} &9: {PLAYER_TIME} &9(#{PLAYER_RANK}) \n&6> &9(porcentaje de victorias: {WINRATE}%)",
  "CHANGEPAGE": "&7Haga clic aquí para cambiar de página",
  "CHANGEPAGERIGHT": "&9➡",
  "CHANGEPAGELEFT": "&c⬅",
  "ERTRAIN_MAP_INFO": [
    "&fSu tiempo: &6{PLAYER_TIME}",
    "&fSu rango: &6#{PLAYER_RANK}",
    "&fSu porcentaje de victorias: &6{WINRATE}%",
    " "
  ],
  "ERTRAIN_MAP_INFO_PLUS": [
    "",
    "&7Dificultad: {DIFFICULTY}",
    "&7Vuelta(s): &c{LAPS}",
    "",
    "&7Haga clic aquí para seleccionar este mapa"
  ],
  "ERTRAIN_MAP_INFO_TITLE": "&f{MAP_NAME}",
  "FORCE_KICK_VERSION_BELOW_19": true,
  "PLAYER_VERSION_BELOW_19": "&cNo tienes la versión correcta para jugar a este juego",
  "USAGE_ERSTATS_SHOW": [
    "&6&lEstadísticas personales: {USERNAME}",
    "&7Carreras jugadas: &c{PLAYER_GAME_PLAYED_RACEMODE} ",
    "&7Carreras ganadas: &c{PLAYER_GAME_WON_RACEMODE} &9(#{RANK_WON_RACEMODE}) &7({PERCENTAGE_WINRATE_RACEMODE}%)",
    "&7Grandprix jugado: &c{PLAYER_GAME_PLAYED_GRANDPRIX} ",
    "&7Grandprix ganados: &c{PLAYER_GAME_WON_GRANDPRIX} &9(#{RANK_WON_GRANDPRIX}) &7({PERCENTAGE_WINRATE_GRANDPRIX}%)",
    "&7Puntuación: &c{SCORE_TOTAL} &9(#{RANK_SCORE_TOTAL})",
    "&6Mapa favorito: &6{FAVORITE_MAP} &7&o(porcentaje de victorias: {FAVORITE_MAP_WINRATE}%)",
    "[HOVERMESSAGE_MAP_STATS]&9Estadísticas personales en los mapas &7&o(hover)"
  ],
  "HOLOGRAMS_PERSONALSTATS": [
    "&6&lEstadísticas personales:",
    "&7Carreras jugadas: &c{PLAYER_GAME_PLAYED_RACEMODE} ",
    "&7Carreras ganadas: &c{PLAYER_GAME_WON_RACEMODE} &9(#{RANK_WON_RACEMODE}) &7({PERCENTAGE_WINRATE_RACEMODE}%)",
    "&7Grandprix jugado: &c{PLAYER_GAME_PLAYED_GRANDPRIX} ",
    "&7Grandprix ganados: &c{PLAYER_GAME_WON_GRANDPRIX} &9(#{RANK_WON_GRANDPRIX}) &7({PERCENTAGE_WINRATE_GRANDPRIX}%)",
    "&7Puntuación: &c{SCORE_TOTAL} &9(#{RANK_SCORE_TOTAL})",
    "&6Mapa favorito: &6{FAVORITE_MAP} &7&o(winrate: {FAVORITE_MAP_WINRATE}%)"
  ],
  "MAP_INGAME_INFO_MENU_TITLE": "&fInformación sobre mapas",
  "MAP_INGAME_INFO_DESCRIPTION": [
    "&f{ORDER}. {MAP_NAME}",
    "&f-> Sus estadísticas: {PLAYER_TIME},#{PLAYER_RANK} ({PLAYER_WINRATE}%)"
  ],
  "NOTENOUGH_MAP_HOSTCREATOR": "&cYou need at least 1 map to create a host",
  "ONEGAME": false,
  "ONEGAME_AUTOJOINGAME": "",
  "ONEGAME_KICK_AFTER_GAME": true,
  "ONEGAME_LOBBYSERVER": "",
  "ONEGAME_REMOVEJOINQUITMESSAGES": true,
  "ONEGAME_MOTD_USE": false,
  "ONEGAME_MOTD": [
    "&f>> ElytraRacing: {STATE} &7[-] Mapa: &6{MAP}",
    "§f>> &7Jugando: §c{PLAYING} &7[-] Modo: {MODE_INFORMATION}"
  ],
  "ONEGAME_MOTD_RACEMODE_INFORMATION": "&aRacemode",
  "ONEGAME_MOTD_GRANDPRIX_INFORMATION": "&aGrandPrix &f{ROUND}/{ROUND_MAX}",
  "ONEGAME_MOTD_CHANGE_MAX_PLAYERS": true,
  "CHALLENGE_MAXGAME": false,
  "CHALLENGE_MAXGAME_PER_PLAYER": 10,
  "CHALLENGE_MAXGAME_COMPLETION_COMMAND": "[CONSOLE]/give {SELF_PLAYER} minecraft:cookie §%§[PLAYER]/tell {SELF_PLAYER} has ejecutado un comando",
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
  "CONSOLE_USERNAME": "servidor",
  "RENDER_DISTANCE_CP": false,
  "RENDER_DISTANCE_CP_VALUE": 2,
  "HOOK_PARTIES_ENABLE": true
}
```

</details>

<details>

<summary>AdminGUI.json</summary>

```
{
    "world": "Mundo",
    "id": "ID",
    "map": "Mapa",
    "type": "Tipo",
    "normal": "normal",
    "ifnext": "si el siguiente",
    "name": "Nombre",
    "linkto": "Enlace a",
    "rotations": "Rotaciones",
    "shape": "Forma",
    "radius": "Radio",
    "valid": "Válido",
    "enabled": "Activado",
    "checkpoints": "Punto(s) de control",
    "ends": "Final(es)",
    "aos": "Objeto(s) adicional(es)",
    "locations": "Ubicaciones",
    "start": "Comienza",
    "end": "Finalizar",
    "lobby": "Vestíbulo",
    "boostMultiplier": "Multiplicador de impulso",
    "fireworks": "Fuegos artificiales",
    "cpangle": "Ángulo de control",
    "laps": "Vuelta(s)",
    "lap": "vuelta",
    "lapMapLong": "Aquí puedes modificar el número de vueltas en este mapa",
    "thereisare": "Existen",
    "inMapCp": "punto(s) de control en el mapa",
    "inMapEnd": "end(s) in the map",
    "inMapAo": "objeto(s) adicional(es) en el mapa",
    "clickModificationCp": "Haga clic para modificar un punto de control",
    "clickModificationEnd": "Haga clic para modificar un extremo",
    "clickModificationAo": "Haga clic para modificar un objeto adicional",
    "currentDifficulty": "Dificultad actual del mapa",
    "clickDifficulty": "Haga clic aquí para modificar la dificultad",
    "respawnCpAngle": "Ángulo de reaparición del punto de control",
    "respawnCpAngleL1": "Ángulo de reaparición del punto de control",
    "respawnCpAngleL2": "Información:",
    "PLAYER": "JUGADOR",
    "respawnCpAngleL3": "- Utiliza el ángulo que tenía el jugador al entrar en el punto de control",
    "NEXT_CHECKPOINT": "SIGUIENTE_PUNTO_DE_CONTROL",
    "Experimental": "Experimental",
    "respawnCpAngleL4": "- Crea un ángulo para redirigir al jugador hacia el siguiente punto de control",
    "respawnCpAngleL5": "Esta característica sólo funciona con los mapas que contienen §c§l1 final y sin puntos de control vinculados",
    "clickHereDefine": "Haga clic aquí para definir",
    "defaultParticleCP": "partícula por defecto para los puntos de control",
    "defaultParticleEnd": "partícula por defecto para los extremos",
    "defaultParticleAO": "partícula por defecto para objetos adicionales",
    "mapAvailableTraining": "Mapa disponible para la formación",
    "clickmapAvailableTraining": "Haga clic aquí para añadir o eliminar este mapa del conjunto de entrenamiento",
    "dbUUID": "Base de datos UUID",
    "clickDB": "Haga clic aquí para borrar la información guardada en la base de datos",
    "podiumConfiguration": "Configuración del podio",
    "qPodium": "¿Está activado el sistema de podio para este mapa?",
    "qPodiumL1": "Comando para añadir una nueva ubicación para el podio:",
    "qPodiumL2": "/ermap map [map] podium setlocation <placement... 1, 2, 3..>",
    "qPodiumL3": "Comando para teletransportar una ubicación del podio:",
    "qPodiumL4": "/ermap map [map] podium tp <placement... 1, 2, 3..>",
    "startHost": "Iniciar un anfitrión",
    "createHostMap": "Haga clic aquí para crear un anfitrión utilizando este mapa",
    "maxtimepossible": "Tiempo máximo posible",
    "difficulty": "Dificultad",
    "podium": "Podio",
    "particles": "Partículas",
    "changeName": "Cambiar el nombre",
    "confirm": "Confirm",
    "cancel": "Cancelar",
    "currentLaps": "Vuelta actual(es)",
    "currentMaxTime": "Tiempo máximo actual",
    "currentMaxTimeModification": "Aquí puedes modificar el tiempo máximo posible en el mapa",
    "minute": "minuto",
    "divideMinutes": "Dividir por 2 los minutos actuales",
    "doubleMinutes": "Doblar los minutos actuales",
    "firework": "fuegos artificiales",
    "divideFirework": "Dividir por 2 fuegos artificiales actuales",
    "doubleFirework": "Doble fuego de artificio actual",
    "second": "segundo",
    "divideSeconds": "Dividir por 2 los segundos actuales",
    "doubleSeconds": "Dobla los segundos actuales",
    "changeHologramName": "Cambiar el nombre del holograma",
    "cmdChangeHologramName": "/erconfig holograms setname [current_name] [new_name]",
    "changeMap": "Cambiar el mapa",
    "changeHologramMap": "Mapa de cambios asociado al holograma",
    "cmdChangeHologramMap": "/erconfig holograms setmap [hologram] [map]",
    "localisation": "Localización",
    "leftTeleported": "Haga clic con el botón izquierdo para ser teletransportado",
    "clickTeleported": "Haga clic para ser teletransportado",
    "shiftclickDefineLocation": "Haga clic en Shift para definir esta ubicación",
    "rightTeleported": "Haga clic con el botón derecho para ser teletransportado",
    "leftConfigure": "Clic izquierdo para configurar",
    "rightChangeLocation": "Haga clic con el botón derecho para cambiar la ubicación",
    "rightDefineLocation": "Haga clic con el botón derecho para definir la ubicación",
    "refreshDisplay": "Actualizar la pantalla",
    "clickRefreshElement": "Pulse aquí para actualizar los elementos mostrados en el holograma",
    "delete": "Borrar",
    "personalMaps": "Mapas personales",
    "clickCreateNewHolograms": "Haga clic aquí para crear un nuevo holograma de este tipo",
    "personalStats": "Estadísticas personales",
    "rankscore": "Puntuación del rango",
    "rankmap": "Mapa de clasificación",
    "rankmapL1": "Tienes que definir un mapa para este holograma.",
    "rankmapL2": "/erconfig holograms setmap [hologram] [map]",
    "rankwonr": "Rango ganado racemode",
    "rankwong": "Rango ganado Grandprix",
    "deleteHologram": "Haga clic aquí para eliminar este holograma",
    "currentParticle": "Partícula actual",
    "currentParticleLongMap": "Aquí puedes ver el conjunto de partículas actual para este mapa",
    "clickChangeParticle": "Haga clic aquí para cambiar la partícula",
    "currentFireworkAmountMap": "Aquí puedes modificar el número de fuegos artificiales en el mapa",
    "clickChangePage": "Haga clic aquí para cambiar de página",
    "particleAmount": "Cantidad de partículas",
    "information": "Información",
    "clickDefineParticleObject": "Haga clic aquí para definir la partícula del objeto",
    "currentLocation": "Ubicación actual",
    "currentParticleAmount": "Cantidad actual de partículas",
    "particleAmountLong": "Aquí puedes modificar la cantidad de partículas que se muestran",
    "currentFireworksAmount": "Cantidad actual de fuegos artificiales",
    "fireworksAmountLong": "Aquí puedes modificar el número de fuegos artificiales que da este objeto",
    "leftclick": "Clic izquierdo",
    "shiftleftclick": "Clic izquierdo de mayúsculas",
    "rightclick": "Clic derecho",
    "shiftrightclick": "Clic derecho de mayúsculas",
    "currentRadius": "Radio actual",
    "radiusmodification": "Aquí puedes modificar el radio",
    "helpMessage": "Mensaje de ayuda",
    "helpMessageL1": "Haga clic aquí para mostrar la lista de comandos para ",
    "helpMessageL2": "este objeto que completará automáticamente los argumentos",
    "helpMessageL2Map": "este mapa que completará automáticamente los argumentos",
    "currentBoostMultiplier": "Multiplicador de corriente",
    "boostMultiplierModification": "Aquí puedes modificar el multiplicador de impulso aplicado al jugador",
    "closeMenu": "Pulse aquí para cerrar este menú",
    "linkWithYou": "Vincula este objeto contigo",
    "linkModificationL1": "Haga clic aquí para vincular este objeto con usted y poder modificarlo.",
    "linkModificationL2": "Con este enlace podrá",
    "linkModificationL3": "para modificar este objeto mediante elementos",
    "linkModificationL4": "Haga clic con el botón izquierdo del ratón para vincular el objeto.",
    "linkModificationL5": "Haga clic con el botón derecho para obtener elementos",
    "linkModificationL6": "Si estás demasiado lejos del objeto se",
    "linkModificationL7": "te desbloquea automáticamente.",
    "clickDelete": "Haga clic aquí para eliminar este objeto.",
    "informationConfirmationDeleteAO": "Eliminar un objeto adicional",
    "informationConfirmationDeleteCP": "Borrar un punto de control",
    "informationConfirmationDeleteEND": "Borrar un final",
    "createNew": "Crear un nuevo",
    "clickCreateNew": "Haga clic aquí para crear un nuevo",
    "clickCreateNewCP": "puesto de control en su ubicación",
    "clickCreateNewAO": "objeto adicional en su ubicación",
    "clickCreateNewEnd": "terminar en su ubicación",
    "isLocationLobby": "¿Está definida la ubicación del vestíbulo?",
    "isLocationStart": "¿Está definida la ubicación de inicio?",
    "isLocationEnd": "¿Está definida la ubicación final?",
    "locationLobby": "Ubicación del vestíbulo",
    "locationStart": "Lugar de inicio",
    "locationEnd": "Lugar de inicio",
    "specAndWalls": "Especificaciones y paredes",
    "qspecAndWalls": "¿El espectro puede atravesar las paredes?",
    "clickChangeValue": "Haga clic aquí para cambiar el valor",
    "showMap": "Mostrar mapa",
    "clickShowMap": "Haga clic aquí para mostrar/ocultar este mapa",
    "currentParticleSet": "Aquí puedes ver el conjunto de partículas actual",
    "pageHologramPage": "Configuración del holograma",
    "pageAOCP": "Lista de objetos adicionales",
    "pageAOP": "Configuración de objetos adicionales",
    "pageConfirmationDeleteObject": "Confirmación de la supresión",
    "pageCPCP": "Lista de puntos de control",
    "pageCPP": "Configuración del punto de control",
    "pageECP": "Lista de extremos",
    "pageEP": "Configuración final",
    "pageHCP": "Lista de hologramas",
    "pageMCP": "Lista de mapas",
    "pageMS": "Configuración del mapa:"
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
        "HOST_WAITING": {
          "title": "{HOST_NAME}",
          "lines": [
            "",
            "&fJugador(es): {CURRENT_PLAYER}/{MAX_PLAYER}",
            "&fMapa: {CURRENT_MAP}",
            "&fModo: &aRace",
            "",
            "Anfitrión: {HOST}",
            "",
            "{LINK}"
          ]
        },
        "HOST_FINISHED": {
          "title": "{HOST_NAME}",
          "lines": [
            "",
            "&e1º - {RANK_PLAYER_1}",
            "&72º - {RANK_PLAYER_2}",
            "&63º - {RANK_PLAYER_3}",
            "Su rango: {SELF_RANK_PLAYER}",
            "",
            "{LINK}"
          ]
        },
        "STARTED": {
          "title": "ElytraRacing",
          "lines": [
            "",
            "Tiempo restante &c{TIME_LEFT}",
            "&fJugador(es): {CURRENT_PLAYER}/{MAX_PLAYER}",
            "",
            "&e1º - {RACE_RANK_PLAYER_1}",
            "&72º - {RACE_RANK_PLAYER_2}",
            "&63º - {RACE_RANK_PLAYER_3}",
            "Su rango: {SELF_RACE_RANK_PLAYER}",
            "",
            "Puntos de control: &6{SELF_CPS}/{MAX_CPS}",
            "Vueltas: &6{SELF_LAPS}/{MAX_LAPS}",
            "",
            "{LINK}"
          ]
        },
        "HOST_SPECTATOR": {
          "title": "{HOST_NAME}",
          "lines": [
            "",
            "Tiempo restante &c{TIME_LEFT}",
            "&fJugador(es): {CURRENT_PLAYER}/{MAX_PLAYER}",
            "",
            "&e1º - {RACE_RANK_PLAYER_1}",
            "&72º - {RACE_RANK_PLAYER_2}",
            "&63º - {RACE_RANK_PLAYER_3}",
            "&f4º - {RACE_RANK_PLAYER_4}",
            "&f5º - {RACE_RANK_PLAYER_5}",
            "",
            "{LINK}"
          ]
        },
        "SPECTATOR": {
          "title": "ElytraRacing",
          "lines": [
            "",
            "Tiempo restante &c{TIME_LEFT}",
            "&fJugador(es): {CURRENT_PLAYER}/{MAX_PLAYER}",
            "",
            "&e1º - {RACE_RANK_PLAYER_1}",
            "&72º - {RACE_RANK_PLAYER_2}",
            "&63º - {RACE_RANK_PLAYER_3}",
            "&f4º - {RACE_RANK_PLAYER_4}",
            "&f5º - {RACE_RANK_PLAYER_5}",
            "",
            "{LINK}"
          ]
        },
        "HOST_STARTING": {
          "title": "{HOST_NAME}",
          "lines": [
            "",
            "&fJugador(es): {CURRENT_PLAYER}/{MAX_PLAYER}",
            "&fMapa: {CURRENT_MAP}",
            "&fModo: &aRace",
            "",
            "Anfitrión: {HOST}",
            "&cSe inicia en {STARTING_COUNTDOWN} segundo(s)",
            "",
            "{LINK}"
          ]
        },
        "FINISHED": {
          "title": "ElytraRacing",
          "lines": [
            "",
            "&e1º - {RANK_PLAYER_1}",
            "&72º - {RANK_PLAYER_2}",
            "&63º - {RANK_PLAYER_3}",
            "Su rango: {SELF_RANK_PLAYER}",
            "",
            "{LINK}"
          ]
        },
        "HOST_STARTED": {
          "title": "{HOST_NAME}",
          "lines": [
            "",
            "Tiempo restante &c{TIME_LEFT}",
            "&fJugador(es): {CURRENT_PLAYER}/{MAX_PLAYER}",
            "",
            "&e1º - {RACE_RANK_PLAYER_1}",
            "&72º - {RACE_RANK_PLAYER_2}",
            "&63º - {RACE_RANK_PLAYER_3}",
            "Su rango: {SELF_RACE_RANK_PLAYER}",
            "",
            "Puntos de control: &6{SELF_CPS}/{MAX_CPS}",
            "Vueltas: &6{SELF_LAPS}/{MAX_LAPS}",
            "",
            "{LINK}"
          ]
        },
        "SPECTATOR_FINISHED": {
          "title": "ElytraRacing",
          "lines": [
            "",
            "&e1º - {RANK_PLAYER_1}",
            "&72º - {RANK_PLAYER_2}",
            "&63º - {RANK_PLAYER_3}",
            "&f4º - {RANK_PLAYER_4}",
            "&f5º - {RANK_PLAYER_5}",
            "",
            "{LINK}"
          ]
        },
        "STARTING": {
          "title": "ElytraRacing",
          "lines": [
            "",
            "&fJugador(es): {CURRENT_PLAYER}/{MAX_PLAYER}",
            "&fMapa: {CURRENT_MAP}",
            "&fModo: &aRace",
            "",
            "&cSe inicia en {STARTING_COUNTDOWN} segundo(s)",
            "",
            "{LINK}"
          ]
        },
        "WAITING": {
          "title": "ElytraRacing",
          "lines": [
            "",
            "&fJugador(es): {CURRENT_PLAYER}/{MAX_PLAYER}",
            "&fMapa: {CURRENT_MAP}",
            "&fModo: &aRace",
            "",
            "&cNecesita {NEEDED_PLAYER} Jugador(es) para empezar",
            "",
            "{LINK}"
          ]
        },
        "HOST_SPECTATOR_FINISHED": {
          "title": "{HOST_NAME}",
          "lines": [
            "",
            "&e1º - {RANK_PLAYER_1}",
            "&72º - {RANK_PLAYER_2}",
            "&63º - {RANK_PLAYER_3}",
            "&f4º - {RANK_PLAYER_4}",
            "&f5º - {RANK_PLAYER_5}",
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
            "&fJugador(es): {CURRENT_PLAYER}/{MAX_PLAYER}",
            "&fMapa: {CURRENT_MAP}",
            "&fModo: &aGrandPrix",
            "Ronda: 1/{MAX_ROUND}",
            "",
            "Anfitrión: {HOST}",
            "",
            "{LINK}"
          ]
        },
        "HOST_BETWEENROUND": {
          "title": "{HOST_NAME}",
          "lines": [
            "",
            "Próximo mapa: {CURRENT_MAP}",
            "{CURRENT_MAP_DIFFICULTY}",
            "&6MP: {SELF_MAP_PB}",
            "",
            "&e1º - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
            "&72º - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
            "&63º - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
            "Su rango: {SELF_RANK_PLAYER}",
            "Su puntuación: {SELF_RANK_PLAYER_SCORE}",
            "",
            "{LINK}"
          ]
        },
        "HOST_SPECTATOR": {
          "title": "{HOST_NAME}",
          "lines": [
            "",
            "Tiempo restante &c{TIME_LEFT}",
            "&fJugador(es): {CURRENT_PLAYER}/{MAX_PLAYER}",
            "Su puntuación: {CURRENT_ROUND}/{MAX_ROUND}",
            "",
            "&e1º - {RACE_RANK_PLAYER_1}",
            "&72º - {RACE_RANK_PLAYER_2}",
            "&63º - {RACE_RANK_PLAYER_3}",
            "&f4º - {RACE_RANK_PLAYER_4}",
            "&f5º - {RACE_RANK_PLAYER_5}",
            "",
            "{LINK}"
          ]
        },
        "HOST_STARTING": {
          "title": "{HOST_NAME}",
          "lines": [
            "",
            "&fJugador(es): {CURRENT_PLAYER}/{MAX_PLAYER}",
            "&fMapa: {CURRENT_MAP}",
            "&fModo: &aGrandPrix",
            "Su puntuación: 1/{MAX_ROUND}",
            "",
            "Anfitrión: {HOST}",
            "&cSe inicia en {STARTING_COUNTDOWN} segundo(s)",
            "",
            "{LINK}"
          ]
        },
        "HOST_STARTED": {
          "title": "{HOST_NAME}",
          "lines": [
            "",
            "Tiempo restante &c{TIME_LEFT}",
            "&fJugador(es): {CURRENT_PLAYER}/{MAX_PLAYER}",
            "Su puntuación: {CURRENT_ROUND}/{MAX_ROUND}",
            "",
            "&e1º - {RACE_RANK_PLAYER_1}",
            "&72º - {RACE_RANK_PLAYER_2}",
            "&63º - {RACE_RANK_PLAYER_3}",
            "Su rango: {SELF_RACE_RANK_PLAYER}",
            "",
            "Puntos de control: &6{SELF_CPS}/{MAX_CPS}",
            "Vueltas: &6{SELF_LAPS}/{MAX_LAPS}",
            "",
            "{LINK}"
          ]
        },
        "SPECTATOR_FINISHED": {
          "title": "ElytraRacing",
          "lines": [
            "",
            "&e1º - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
            "&72º - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
            "&63º - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
            "&f4º - {RANK_PLAYER_4} - {RANK_PLAYER_4_SCORE}",
            "&f5º - {RANK_PLAYER_5} - {RANK_PLAYER_5_SCORE}",
            "",
            "{LINK}"
          ]
        },
        "STARTING": {
          "title": "ElytraRacing",
          "lines": [
            "",
            "&fJugador(es): {CURRENT_PLAYER}/{MAX_PLAYER}",
            "&fMapa: {CURRENT_MAP}",
            "&fModo: &aGrandPrix",
            "Su puntuación: 1/{MAX_ROUND}",
            "",
            "&cSe inicia en {STARTING_COUNTDOWN} segundo(s)",
            "",
            "{LINK}"
          ]
        },
        "BETWEENROUND": {
          "title": "ElytraRacing",
          "lines": [
            "",
            "Próximo mapa: {CURRENT_MAP}",
            "{CURRENT_MAP_DIFFICULTY}",
            "&6MP: {SELF_MAP_PB}",
            "",
            "&e1º - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
            "&72º - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
            "&63º - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
            "Su rango: {SELF_RANK_PLAYER}",
            "Su puntuación: {SELF_RANK_PLAYER_SCORE}",
            "",
            "{LINK}"
          ]
        },
        "HOST_SPECTATOR_BETWEENROUND": {
          "title": "{HOST_NAME}",
          "lines": [
            "",
            "Próximo mapa: {CURRENT_MAP}",
            "{CURRENT_MAP_DIFFICULTY}",
            "&6MP: {SELF_MAP_PB}",
            "",
            "&e1º - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
            "&72º - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
            "&63º - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
            "&f4º - {RANK_PLAYER_4} - {RANK_PLAYER_4_SCORE}",
            "&f5º - {RANK_PLAYER_5} - {RANK_PLAYER_5_SCORE}",
            "",
            "{LINK}"
          ]
        },
        "HOST_FINISHED": {
          "title": "{HOST_NAME}",
          "lines": [
            "",
            "&e1º - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
            "&72º - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
            "&63º - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
            "Su rango: {SELF_RANK_PLAYER}",
            "Su puntuación: {SELF_RANK_PLAYER_SCORE}",
            "",
            "{LINK}"
          ]
        },
        "SPECTATOR_BETWEENROUND": {
          "title": "ElytraRacing",
          "lines": [
            "",
            "Próximo mapa: {CURRENT_MAP}",
            "{CURRENT_MAP_DIFFICULTY}",
            "&6MP: {SELF_MAP_PB}",
            "",
            "&e1º - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
            "&72º - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
            "&63º - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
            "&f4º - {RANK_PLAYER_4} - {RANK_PLAYER_4_SCORE}",
            "&f5º - {RANK_PLAYER_5} - {RANK_PLAYER_5_SCORE}",
            "",
            "{LINK}"
          ]
        },
        "STARTED": {
          "title": "ElytraRacing",
          "lines": [
            "",
            "Tiempo restante &c{TIME_LEFT}",
            "&fJugador(es): {CURRENT_PLAYER}/{MAX_PLAYER}",
            "Su puntuación: {CURRENT_ROUND}/{MAX_ROUND}",
            "",
            "&e1º - {RACE_RANK_PLAYER_1}",
            "&72º - {RACE_RANK_PLAYER_2}",
            "&63º - {RACE_RANK_PLAYER_3}",
            "Su rango: {SELF_RACE_RANK_PLAYER}",
            "",
            "Puntos de control: &6{SELF_CPS}/{MAX_CPS}",
            "Vueltas: &6{SELF_LAPS}/{MAX_LAPS}",
            "",
            "{LINK}"
          ]
        },
        "SPECTATOR": {
          "title": "ElytraRacing",
          "lines": [
            "",
            "Tiempo restante &c{TIME_LEFT}",
            "&fJugador(es): {CURRENT_PLAYER}/{MAX_PLAYER}",
            "Su puntuación: {CURRENT_ROUND}/{MAX_ROUND}",
            "",
            "&e1º - {RACE_RANK_PLAYER_1}",
            "&72º - {RACE_RANK_PLAYER_2}",
            "&63º - {RACE_RANK_PLAYER_3}",
            "&f4º - {RACE_RANK_PLAYER_4}",
            "&f5º - {RACE_RANK_PLAYER_5}",
            "",
            "{LINK}"
          ]
        },
        "FINISHED": {
          "title": "ElytraRacing",
          "lines": [
            "",
            "&e1º - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
            "&72º - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
            "&63º - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
            "Su rango: {SELF_RANK_PLAYER}",
            "Su puntuación: {SELF_RANK_PLAYER_SCORE}",
            "",
            "{LINK}"
          ]
        },
        "WAITING": {
          "title": "ElytraRacing",
          "lines": [
            "",
            "&fJugador(es): {CURRENT_PLAYER}/{MAX_PLAYER}",
            "&fMapa: {CURRENT_MAP}",
            "&fModo: &aGrandPrix",
            "Su puntuación: 1/{MAX_ROUND}",
            "",
            "&cNecesita {NEEDED_PLAYER} Jugador(es) para empezar",
            "",
            "{LINK}"
          ]
        },
        "HOST_SPECTATOR_FINISHED": {
          "title": "{HOST_NAME}",
          "lines": [
            "",
            "&e1º - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
            "&72º - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
            "&63º - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
            "&f4º - {RANK_PLAYER_4} - {RANK_PLAYER_4_SCORE}",
            "&f5º - {RANK_PLAYER_5} - {RANK_PLAYER_5_SCORE}",
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
            "&6MP: {SELF_MAP_PB}",
            "&fRango: {SELF_MAP_RANK}",
            "",
            "WR holder: {MAP_WR_PLAYER}",
            "&6Time: &c{MAP_WR_TIME}",
            "",
            "Tiempo restante &c{TIME_LEFT}",
            "&fDifficulty: {CURRENT_MAP_DIFFICULTY}",
            "Puntos de control: &6{SELF_CPS}/{MAX_CPS}",
            "Vueltas: &6{SELF_LAPS}/{MAX_LAPS}",
            "",
            "{LINK}"
          ]
        }
      }
    }
  }
```

</details>

<details>

<summary>particles/particleConfig.json</summary>

```
{
    "ENABLE": false,
    "INTERVAL_PERSONAL_PARTICLE_REFRESH": 1,
    "GUI_PARTICLE_TITLE": "Selector de partículas",
    "GUI_ITEM_PARTICLE_TITLE": "&f{PARTICLE_NAME}",
    "GUI_ITEM_PARTICLE_TITLE_SELECTED": "&a{PARTICLE_NAME}",
    "GUI_NO_PARTICLE": "Ninguno",
    "GUI_DISABLE_OTHERS_PARTICLES_UNSELECTED": "&fDesactivar otras partículas",
    "GUI_DISABLE_OTHERS_PARTICLES_SELECTED": "&fDesactivar otras partículas",
    "GUI_DISABLE_OTHERS_PARTICLES_LORE_SELECTED": "&f-> Actualmente: &a✓",
    "GUI_DISABLE_OTHERS_PARTICLES_LORE_UNSELECTED": "&f-> Actualmente: &c❌",
    "MSG_SAVE_SUCCESSFUL": "&fLos cambios se han &guardado con éxito",
    "GUI_CLICKCHANGE": "Haga clic aquí para cambiar de página",
    "GUI_ENCHANT_SELECTED": true,
    "particles": [
      {
        "name": "CírculoVerde",
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
        "name": "CírculoArcoIrisGiratorio",
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
        "name": "PuntaDelArcoIris",
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
        "name": "PuntoRojo",
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
        "name": "OndaHorizontal",
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
        "name": "PuntoDeOndulaciónVertical",
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
        "name": "TuboArcoIris",
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

</details>
