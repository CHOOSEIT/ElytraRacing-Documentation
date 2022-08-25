---
description: 'Version: 1.5.1'
---

# 🇩🇪 German

{% hint style="warning" %}
Files translated using multiple translation websites

The goal of this translation is not to have the perfect on but to have a version that will help you to start to configure the plugin in the language you want

If you see bad translations please send me a message on discord
{% endhint %}

{% hint style="warning" %}
Dateien, die mit mehreren Übersetzungs-Websites übersetzt wurden Das Ziel dieser Übersetzung ist nicht, das perfekte On zu haben, sondern eine Version, die Ihnen hilft, mit der Konfiguration des Plugins in der gewünschten Sprache zu beginnen Wenn Sie schlechte Übersetzungen sehen, senden Sie mir bitte eine Nachricht auf Discord
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
  "ER_TRAIN_MAP_NOTFOUND": "&cDiese Karte ist nicht für die Ausbildung geeignet",
  "ER_TRAIN_CHOOSE_MAP_GUI_TITLE": "Wählen Sie eine Karte",
  "SIGN_RELOAD_SEC": 3,
  "TELEPORT_SOLVER": false,
  "UNLOCK_DISTANCE": 100,
  "UNLOCK_OBJECT": "&fUngesperrtes Objekt",
  "LOCK_OBJECT": "&fDieses Objekt mit Ihnen verknüpft &aerfolgreich",
  "LOCK_ITEMS_GIVE": "&fDie Artikel wurden &aerfolgreich &fgegeben",
  "LOCK_OBJECT_NEAR_NOTFOUND": "&cEs wurde kein Objekt in Ihrer Nähe gefunden",
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
  "MAP_DIFFICULTY_MESSAGE": "&7Schwierigkeit der Karte: {DIFFICULTY}",
  "DNF_POINT": -1,
  "TABLIST_GRANDPRIX": true,
  "COMMANDS_WHITELIST": false,
  "COMMANDS_WHITELIST_COMMANDS": [
    "msg",
    "rl",
    "reload"
  ],
  "COMMANDS_WHITELIST_BYPASS_PERMISSION": "elytraracing.wlcommands.bypass",
  "COMMANDS_MESSAGE": "&cSie können diesen Befehl hier nicht ausführen!",
  "SPECTATOR_ITEM": true,
  "STATIC_ITEMS": true,
  "RankingMaxPlayers": 8,
  "PODIUM_FIREWORKS": true,
  "PODIUM_FIREWORK_NUMBER": 10,
  "END_TIME": 30,
  "DISABLE_ELYTRA": false,
  "COMMAND_EXECUTION_PER_RANK_IN_HOST": false,
  "COMMAND_EXECUTION_PER_RANK_GRANDPRIX": {
    "-1": "[CONSOLE]/give {SELF_PLAYER} minecraft:cookie {SCORE} §%§[PLAYER]/tell {SELF_PLAYER} Sie haben einen Befehl ausgeführt",
    "0": "[PLAYER]/tell {SELF_PLAYER} Sie haben einen Befehl ausgeführt"
  },
  "COMMAND_EXECUTION_PER_RANK_RACEMODE": {
    "-1": "[CONSOLE]/give {SELF_PLAYER} minecraft:cookie 5 §%§[PLAYER]/tell {SELF_PLAYER} Sie haben einen Befehl ausgeführt",
    "0": "[PLAYER]/tell {SELF_PLAYER} Sie haben einen Befehl ausgeführt"
  },
  "PERMISSION_MESSAGE": "&cSie dürfen diesen Befehl nicht ausführen",
  "PERMISSION_MESSAGE_HOST": "&cDu darfst diesem Spiel nicht beitreten",
  "MSG_NUMBER_LAP": "&eAnzahl der Runde(n): {LAPS}",
  "HOLOGRAM_NOT_FOUND": "&cDieses Hologramm kann nicht gefunden werden.",
  "ITEM_1CP_BACK": "&cVorheriger Kontrollpunkt",
  "ITEM_1CP_BACK_MATERIAL": null,
  "ITEM_1CP_BACK_SLOT": 0,
  "ITEM_2CP_BACK": "&c2 Kontrollpunkte zurück",
  "ITEM_2CP_BACK_MATERIAL": null,
  "ITEM_2CP_BACK_SLOT": 1,
  "ITEM_RESTART": "&cRESTART",
  "ITEM_RESTART_MATERIAL": null,
  "ITEM_RESTART_SLOT": 4,
  "ITEM_DNF": "&cDNF",
  "ITEM_DNF_MATERIAL": null,
  "ITEM_DNF_SLOT": 8,
  "ITEM_BED": "&cSpiel verlassen",
  "ITEM_BED_MATERIAL": null,
  "ITEM_BED_SLOT": 8,
  "ITEM_SPEC": "&aJoin-Spec-Modus",
  "ITEM_SPEC_MATERIAL": null,
  "ITEM_SPEC_SLOT": 4,
  "ITEM_CUSTOM": "&aJoin-Spec-Modus",
  "ITEM_CUSTOM_MATERIAL": null,
  "ITEM_CUSTOM_SLOT": 3,
  "ITEM_HOST": "&aHost-Konfiguration",
  "ITEM_HOST_MATERIAL": null,
  "ITEM_HOST_SLOT": 4,
  "ITEM_PARTICLE": "&aPartikel-Selektor",
  "ITEM_PARTICLE_MATERIAL": null,
  "ITEM_PARTICLE_SLOT": 2,
  "ITEM_FIREWORK_SLOT": 2,
  "ITEM_PAPERMAPINFO_SLOT": 4,
  "ITEM_PAPERMAPINFO_MATERIAL": null,
  "ITEM_HOSTSEPARATION_TITLE": "&fAuswahl der Karte",
  "ITEM_HOSTSEPARATION_DESCRIPTION": "&a⬇  ⬇  ⬇  ⬇  ⬇  ⬇",
  "ITEM_HOSTSEPARATION_MATERIAL": null,
  "ITEM_HOSTMAP_TITLE_SELECTED": "&a{MAP_NAME}",
  "ITEM_HOSTMAP_TITLE_NOTSELECTED": "&f{MAP_NAME}",
  "ITEM_HOSTMAP_MATERIAL_SELECTED": null,
  "ITEM_HOSTMAP_MATERIAL_NOTSELECTED": null,
  "HOSTMAP_CREATOR_INVENTORY_TITLE": "Host-Ersteller",
  "ALERT_HOST": "&6{PLAYER} &ahat gerade begonnen, Gastgeber zu sein &7(Klicken Sie hier, um beizutreten)",
  "ERROR_MESSAGE": "&cWährend des Prozesses ist ein Fehler aufgetreten",
  "ACTIONBAR_TIME": "&7Verbleibende Zeit: &c{TIME}",
  "MSG_PAGE": "&7Seite &c{PAGE} &7von &c{MAX_PAGE}",
  "MSG_ENDMAP": "&6{PLAYER} &7-> &c{ARG}",
  "MSG_GAMEFULL": "&cDieses Spiel ist bereits voll",
  "MSG_GAMESTARTED": "&cDieses Spiel hat bereits begonnen",
  "LOCATIONNOTDEFINED": "&cDieser Ort ist nicht definiert!",
  "MSG_ERHOST_LISTGAMES": "&aListe der Spiele &7&o(schweben): ",
  "MSG_ERMAP_LISTGAMES_GAMESFORMAT": "&c>> &f{GAME_NAME} ",
  "MSG_ERMAP_LISTCHECKPOINT": "&aListe der Kontrollpunkte &7&o(schweben): ",
  "DEFAULT": "&6DEFAULT",
  "NONE": "&6NONE",
  "NOBODY": "Nobody",
  "MSG_ERMAP_LISTCHECKPOINT_CHECKPOINTFORMAT": "&f#{CHECKPOINT_ID_ORDER} &c>> &f({X},{Y},{Z}) &7&o(Zum Teleportieren anklicken)",
  "MSG_ERMAP_LISTEND": "&aListe der Enden &7&o(schweben): ",
  "MSG_ERMAP_LISTEND_ENDFORMAT": "&f#{END_ID_ORDER} &c>> &f({X},{Y},{Z}) &7&o(Zum Teleportieren anklicken)",
  "YES": "&aJa",
  "NO": "&cNein",
  "CHECK": "&a✓",
  "CROSS": "&cx",
  "MSG_STATE_WAITING": "&aWarten",
  "MSG_STATE_STARTING": "&6Start:",
  "MSG_STATE_STARTED": "&cGestartet",
  "MSG_SPEC_JOINING": "&7Dem Spiel als Zuschauer beitreten...",
  "PERM_SPECGAME": "elytraracing.specgame",
  "MSG_NOGAMETOLEAVE": "&cSie brauchen nicht zu gehen, Sie sind noch nicht im Spiel.",
  "MSG_GAMENOTEXIST": "&cDieses Spiel gibt es nicht",
  "MSG_NOTYOURHOST": "&cSie sind nicht der Gastgeber dieses Spiels",
  "MSG_TIMERSTART": "&aTimer gestartet",
  "MSG_TIMERCANCEL": "&cTimer abgebrochen",
  "MSG_HOST_NOTEXIST": "&cIhr Gastgeber kann nicht gefunden werden",
  "MSG_LEAVEYOURGAME": "&cSie befinden sich bereits in einem Spiel",
  "MSG_GAMENOTOPEN": "&cDies ist nicht offen",
  "MSG_MAPCREATING": "&aKarte erstellen...",
  "MSG_MAPNAMEEXIST": "&cDieser Kartenname existiert bereits",
  "MSG_GAMENAME_EXIST": "&cDieser Spielname existiert bereits",
  "MSG_HOST_CREATING": "&aErstellen von Host...",
  "MSG_CHECKPOINT_VERIFIED": "&fCheckpoint bestanden! ({CHECKPOINT_PASSED} / {CHECKPOINT_MAX})",
  "MSG_LAP_VERIFIED": "&eRunde beendet! ({LAP_PASSED} / {LAP_MAX})",
  "MSG_GAME_PLAYERJOIN": "&6{PLAYER_NAME} &fhat sich dem Rennen angeschlossen ! &7&o({PLAYER_SIZE} / {MAX_PLAYER})",
  "MSG_GAME_PLAYERJOIN_PLAYERNEEDEDLEFT": " &c({PLAYER_NEEDED} links benötigt)",
  "MSG_GAME_PLAYERLEAVE": "&6{PLAYER_NAME} &fhat das Rennen verlassen! &7&o({PLAYER_SIZE} / {MAX_PLAYER})",
  "MSG_GAME_NOTENOUGHPLAYERS": "&cTimer abgebrochen, nicht genug Spieler",
  "PLAYER_NOTFOUND": "&cSpieler nicht gefunden.",
  "ERHOST_PLAYER_NOTFOUND": "&cDieser Spieler ist nicht in Ihrem Spiel.",
  "MSG_MAP_NOTAVAILABLE": "&cDiese Karte ist nicht verfügbar!",
  "MSG_MAP_NOTAVAILABLE2": "&c{MAP} ist nicht verfügbar!",
  "MSG_MAPNOTFOUND2": "&c{ARG} kann nicht gefunden werden",
  "MSG_ALERT": "&cSie haben bereits zu viele Warnmeldungen gesendet",
  "PARTICLE_LIST": "&7Partikelliste (Zum Aktivieren anklicken): ",
  "PARTICLE_LIST_ITEMS": " &7{item}",
  "PARTICLE_LIST_ITEMS_HOVER": "&7{item}: Click to activate",
  "PARTICLE_LIST_NOTFOUND": "&cDieser Partikeltyp kann nicht gefunden werden",
  "GRANDPRIX": "Grandprix",
  "RACEMODE": "Race",
  "PERSONAL_BEST": " &6&k&llol &6&lPersönliche Bestleistung&k&llol",
  "TIME_NOT_FOUND": " - ",
  "RANK_NOT_FOUND": "-",
  "ER_PLAY_GAME": "&cEs wurde kein Spiel gefunden!",
  "MSG_STEP_TIMER": {
    "0": "Ihr Spiel beginnt...",
    "1": "Ihr Spiel beginnt in &f1 &fzweite",
    "2": "Ihr Spiel beginnt in &a2 &fSekunden",
    "3": "Ihr Spiel beginnt in &23 &fSekunden",
    "4": "Ihr Spiel beginnt in &64 &fSekunden",
    "5": "Ihr Spiel beginnt in &c5 &fSekunden",
    "10": "Ihr Spiel beginnt in &c10 &fSekunden",
    "30": "Ihr Spiel beginnt in &c30 &fSekunden"
  },
  "MSG_STEPROUND_TIMER": {
    "0": "Die nächste Runde beginnt...",
    "1": "Die nächste Runde beginnt in &f1 &fzweite",
    "2": "Die nächste Runde beginnt in &a2 &fSekunden",
    "3": "Die nächste Runde beginnt in &23 &fSekunden",
    "4": "Die nächste Runde beginnt in &64 &fSekunden",
    "5": "Die nächste Runde beginnt in &c5 &fSekunden",
    "15": "Die nächste Runde beginnt in &c15 &fSekunden"
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
  "MSG_PRE_RANK": "&7\nRangliste:\n",
  "MSG_PRE_SCORE": "&7\nAnzeiger:\n",
  "MSG_YOURRANK": "&7Ihr Rang auf dieser Karte: &c{RANK}",
  "MSG_YOURSCORE": "&7Ihr Gesamtrang ist: &c{RANK} &7mit &c{SCORE} &7Punkte",
  "MSG_ARG_RANK_TIME_DNF": "&cDNF",
  "MSG_ARG_RANK_TIME_TIME": "&c{TIME}",
  "TELEPORTING": "&7Teleportieren...",
  "TIMEFORMAT": "{MINUTES}m {SECONDS}.{MILLISECONDS}s",
  "TIMEFORMAT_WM": "{MINUTES}m {SECONDS}s",
  "PLACEHOLDER_NOTFOUND_PLAYER": "Keine",
  "PLACEHOLDER_DEFAULT_NUMBER": "0",
  "PLACEHOLDER_DEFAULT_TEXT": "",
  "PLACEHOLDER_DEFAULT_RANKING": "-",
  "ERMAP_MAP_DELETE": "&cDie Karte wird nach einem Neuladen gelöscht/Neustart",
  "MSG_MAPNOTFOUND": "&cDiese Karte kann nicht gefunden werden",
  "MSG_SAVE_SUCCESSFUL": "&fEs wurden Änderungen &aErfolgreich &fgespeichert",
  "MSG_FILE_RELOAD": "&fDie Datei(en) wurde(n) &fneu geladen.",
  "MSG_SHOW_ON": "&aErmöglichung von ...",
  "MSG_SHOW_OFF": "&cDeaktivieren von ...",
  "MSG_CHECKPOINT_NOTFOUND": "&cDieser Kontrollpunkt kann nicht gefunden werden",
  "MSG_END_NOTFOUND": "&cDieses Ende kann nicht gefunden werden",
  "ID_ORDER_ARG": "&c[id_order] muss eine ganze Zahl sein",
  "ID_ORDER_TARGET_ARG": "&c[id_order_target] muss eine ganze Zahl sein",
  "DEGREES_ARG": "&c[rotation] muss eine ganze Zahl sein",
  "MULTIPLIER_ARG": "&c[amount] muss ein Float sein",
  "SIZE_ARG": "&c[size] muss ein Float sein",
  "AMOUNT_ARG": "&c[amount] muss eine ganze Zahl sein",
  "SECONDS_ARG": "&c[seconds] muss eine ganze Zahl zwischen 0 und 59 sein",
  "MINUTES_ARG": "&c[minutes] muss eine ganze Zahl größer als 0 sein",
  "MAX_PLAYER_ARG": "&c[slots] muss eine ganze Zahl größer als 0 sein",
  "PAGE_ARG": "&c[page] muss eine ganze Zahl größer als 0 sein",
  "ERCONFIG_SETITEM_ID_NOT_FOUND": "&cDiese [id_item] kann nicht gefunden werden",
  "ERCONFIG_SETITEM_ITEM_NOT_FOUND": "&cDer Gegenstand in deiner Hand kann nicht gefunden werden",
  "SPEC_PERM": null,
  "SPEC_PERM_MESSAGE": "&cSie haben keine Erlaubnis, einem Spiel beizuwohnen.",
  "HOST_GAMENOTOPEN": "&cIhr Spiel ist nicht geöffnet",
  "SPECTATORMODE": "&aSie sind in den Zuschauermodus eingetreten &7(Klicken Sie hier zum Verlassen oder tippen Sie '/er quitspec')",
  "STUCKSPECTATOR": "&aVerwenden Sie /er near §fzum nächstgelegenen Spieler teleportieren",
  "AVAILABLE_MAPS": "&aVerfügbare Karten: {MAPS}",
  "ERGAMES_LIST": "&6Liste der Autospiele: {AUTOGAMES}",
  "ERGAMES_ENABLED_PREFIX": "&a",
  "ERGAMES_DISABLED_PREFIX": "&c",
  "ERGAMES_LIST_SEPERATION_PREFIX": "&7",
  "ERGAMES_NOTFOUND": "&cDieses Autogame kann nicht gefunden werden",
  "ERGAMES_ALREADYGAME": "&cDu kannst dieses automatische Spiel nicht aktivieren, weil es bereits ein Spiel mit demselben Namen gibt",
  "TABLIST_RANK_SCORE_TITLE": "&7Anzeiger",
  "TABLIST_RANK_SCORE_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "TABLIST_GRANDPRIX_PERSONAL_PERSONAL": "&6Persönliche Statistiken zu dieser Karte:",
  "TABLIST_GRANDPRIX_PERSONAL_TIME": "&9Persönliche Bestzeit: &c{TIME}",
  "TABLIST_GRANDPRIX_PERSONAL_RANK": "&9Ihr Rang: &c{RANK}",
  "TABLIST_GRANDPRIX_PERSONAL_WINRATE": "&9Ihre Gewinnrate: &c{WINRATE} %",
  "HOLOGRAMS_RANK_SCORE_TITLE": "&6&lTop 15 Höchste Punktzahlen",
  "HOLOGRAMS_RANK_SCORE_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "-2": "&9{RANK} &7- &9-------- &7- &c0",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_RANK_WON_RACEMODE_TITLE": "&6&lTop 15 Höchste gewonnene Rennen",
  "HOLOGRAMS_RANK_WON_RACEMODE_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "-2": "&9{RANK} &7- &9-------- &7- &c0",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_RANK_WON_GRANDPRIX_TITLE": "&6&lTop 15 Höchster gewonnener Grandprix",
  "HOLOGRAMS_RANK_WON_GRANDPRIX_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "-2": "&9{RANK} &7- &9-------- &7- &c0",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_RANK_MAP_TITLE": "&6&lTop 15 Beste Zeiten auf {MAP}",
  "HOLOGRAMS_RANK_MAP_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "-2": "&9{RANK} &7- &9-------- &7- &c0",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_PERSONAL_MAPS_TITLE": "&6&lPersönliche Statistiken auf Karten",
  "HOLOGRAMS_PERSONAL_MAPS_SPECIFIC": "&6{MAP_NAME} &7: &c{PLAYER_TIME} &7(#{PLAYER_RANK}) (winrate: {WINRATE}%)",
  "HOST_MAPCHOOSER_CHANGEPAGE": "Klicken Sie hier, um die Seite zu wechseln",
  "DNF_INSTANT_QUIT": false,
  "MSG_LISTMAPS_INFO": [
    "&a>> {MAP_NAME}",
    " ",
    "&f>> &7Gültig: {VALID}",
    "&f>> &7Aktiviert: {ENABLED}",
    " ",
    "&f>> &7Kontrollpunkte: &c{CHECKPOINTS}",
    "&f>> &7Endet: &c{ENDS}",
    "&f>> &7Standort Lobby: &c{LOBBY}",
    "&f>> &7Startort: &c{START}",
    "&f>> &7Standort beenden: &c{END}",
    "&f>> &7Podium: &c{PODIUM}",
    " ",
    "&f>> &7Zeit max.: &c{TIME}",
    "&f>> &7Schwierigkeitsgrad: &c{DIFFICULTY}",
    " "
  ],
  "HOST_TITLE_PERM": "&7Erlaubnis: &c{PERMISSION}",
  "HOST_DESC_PERM": [
    " ",
    "&f/erhost setperm &c[permission/none]",
    "&fSo definieren Sie die Berechtigung zum Beitritt zu Ihrem Spiel.",
    " "
  ],
  "HOST_TITLE_ALERT": "&aAlarmierung",
  "HOST_DESC_ALERT": [
    " ",
    "&fKlicken Sie hier, um eine Einladung zu Ihrem Spiel zu senden",
    " "
  ],
  "HOST_TITLE_START": "&aStart",
  "HOST_DESC_START": [
    " ",
    "&fKlicken Sie hier, um das Spiel zu starten",
    " "
  ],
  "HOST_TITLE_END": "&cCountdown abbrechen",
  "HOST_DESC_END": [
    " ",
    "&fKlicken Sie hier, um den Countdown zu stoppen",
    " "
  ],
  "HOST_TITLE_SLOTS": "&cAnzahl der Slots",
  "HOST_DESC_SLOTS": [
    " ",
    "&fAnzahl der Steckplätze: &c{SLOTS}",
    " ",
    "&7Links klicken: +1 (+ Schicht: +10)",
    "&7Rechtsklick: -1 (+ Schicht: -10)",
    " "
  ],
  "HOST_TITLE_OPEN": "&fIhr Gastgeber ist derzeit: &aÖffnen Sie",
  "HOST_TITLE_CLOSED": "&fIhr Gastgeber ist derzeit: &cGeschlossen",
  "HOSTCREATOR_CREATE_TITLE": "&aErstellen Sie den Host",
  "HOSTCREATOR_CREATE_DESCRIPTION": [
    " ",
    "&fName: &c{NAME}",
    " ",
    "&fAnzahl der Steckplätze: &c{SLOTS}",
    "&fAnzahl der Karten: &c{MAP_NUMBER}",
    "&fModus: &c{MODE}",
    " "
  ],
  "HOSTCREATOR_MAPS_TITLE": "&fAnzahl der Karten: &c{MAP_NUMBER}",
  "HOSTCREATOR_MAPS_DESCRIPTION": "&f{ORDER}. {MAP_NAME}",
  "HOSTCREATOR_MAXPLAYERS_TITLE": "&fAnzahl der Steckplätze: {SLOTS}",
  "HOST_MAXPLAYERS_SLOTS": [
    " ",
    "&fAnzahl der Steckplätze: &c{SLOTS}",
    " ",
    "&7Links klicken: +1 (+ Schicht: +10)",
    "&7Rechtsklick: -1 (+ Schicht: -10)",
    " "
  ],
  "STATES": {
    "STARTING": "&6Start:",
    "STARTED": "&cIngame",
    "WAITING": "&aWarten",
    "FINISHED": "&7Fertigstellung"
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
    "&7Zum Beitritt klicken"
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
    "&f>> &7Welt: &c{WORLD}",
    " ",
    "&f>> &7Radius: &c{RADIUS}",
    "&f>> &7Partikelmenge: &c{PARTICLE_AMOUNT}",
    "&f>> &7Boost-Multiplikator: &c{BOOST_MULTIPLIER}",
    "&f>> &7",
    "&f>> &7Partikeltyp: &c{PARTICLE_TYPE}",
    "&f>> &7Verbunden mit: &c{LINK}"
  ],
  "MSG_LISTGAMES_INFO": [
    "&a>> {GAME_NAME}",
    " ",
    "&f>> &7Spieler: &c{PLAYER_SIZE}",
    "&f>> &7min. Spieler: &c{MIN_PLAYER}",
    "&f>> &7max. Spieler: &c{MAX_PLAYER}",
    " ",
    "&f>> &7Staat: &c{GAME_STATE}"
  ],
  "MSG_LISTEND_INFO": [
    " ",
    "&f>> &7ID: {ID_ORDER}",
    " ",
    "&f>> &7x: &c{X}",
    "&f>> &7y: &c{Y}",
    "&f>> &7z: &c{Z}",
    "&f>> &7Welt: &c{WORLD}",
    " ",
    "&f>> &7Radius: &c{RADIUS}",
    "&f>> &7Partikelmenge: &c{PARTICLE_AMOUNT}",
    "&f>> &7",
    "&f>> &7Partikeltyp: &c{PARTICLE_TYPE}"
  ],
  "ERSTATS_MAP": "&6&lPersönliche Statistiken auf Karten",
  "ERSTATS_MAP_EACH": "&6>> {MAP_NAME} &9: {PLAYER_TIME} &9(#{PLAYER_RANK}) \n&6> &9(winrate: {WINRATE}%)",
  "CHANGEPAGE": "&7Klicken Sie hier, um die Seite zu wechseln",
  "CHANGEPAGERIGHT": "&9➡",
  "CHANGEPAGELEFT": "&c⬅",
  "ERTRAIN_MAP_INFO": [
    "&fIhre Zeit: &6{PLAYER_TIME}",
    "&fIhr Rang: &6#{PLAYER_RANK}",
    "&fIhre Gewinnrate: &6{WINRATE}%",
    " "
  ],
  "ERTRAIN_MAP_INFO_PLUS": [
    "",
    "&7Schwierigkeitsgrad: {DIFFICULTY}",
    "&7Runde(n): &c{LAPS}",
    "",
    "&7Klicken Sie hier, um diese Karte auszuwählen"
  ],
  "ERTRAIN_MAP_INFO_TITLE": "&f{MAP_NAME}",
  "FORCE_KICK_VERSION_BELOW_19": true,
  "PLAYER_VERSION_BELOW_19": "&cSie haben nicht die richtige Version, um dieses Spiel zu spielen",
  "USAGE_ERSTATS_SHOW": [
    "&6&lPersönliche Statistiken: {USERNAME}",
    "&7Gespielte Rennen: &c{PLAYER_GAME_PLAYED_RACEMODE} ",
    "&7Gewonnene Rennen: &c{PLAYER_GAME_WON_RACEMODE} &9(#{RANK_WON_RACEMODE}) &7({PERCENTAGE_WINRATE_RACEMODE}%)",
    "&7Grandprix gespielt: &c{PLAYER_GAME_PLAYED_GRANDPRIX} ",
    "&7Grandprix gewonnen: &c{PLAYER_GAME_WON_GRANDPRIX} &9(#{RANK_WON_GRANDPRIX}) &7({PERCENTAGE_WINRATE_GRANDPRIX}%)",
    "&7Ergebnis: &c{SCORE_TOTAL} &9(#{RANK_SCORE_TOTAL})",
    "&6Bevorzugte Karte: &6{FAVORITE_MAP} &7&o(winrate: {FAVORITE_MAP_WINRATE}%)",
    "[HOVERMESSAGE_MAP_STATS]&9Persönliche Statistiken auf Karten &7&o(hover)"
  ],
  "HOLOGRAMS_PERSONALSTATS": [
    "&6&lPersönliche Statistiken:",
    "&7Gespielte Rennen: &c{PLAYER_GAME_PLAYED_RACEMODE} ",
    "&7Gewonnene Rennen: &c{PLAYER_GAME_WON_RACEMODE} &9(#{RANK_WON_RACEMODE}) &7({PERCENTAGE_WINRATE_RACEMODE}%)",
    "&7Grandprix gespielt: &c{PLAYER_GAME_PLAYED_GRANDPRIX} ",
    "&7Grandprix gewonnen: &c{PLAYER_GAME_WON_GRANDPRIX} &9(#{RANK_WON_GRANDPRIX}) &7({PERCENTAGE_WINRATE_GRANDPRIX}%)",
    "&7Ergebnis: &c{SCORE_TOTAL} &9(#{RANK_SCORE_TOTAL})",
    "&6Bevorzugte Karte: &6{FAVORITE_MAP} &7&o(winrate: {FAVORITE_MAP_WINRATE}%)"
  ],
  "MAP_INGAME_INFO_MENU_TITLE": "&fKarteninformationen",
  "MAP_INGAME_INFO_DESCRIPTION": [
    "&f{ORDER}. {MAP_NAME}",
    "&f-> Deine Statistiken: {PLAYER_TIME},#{PLAYER_RANK} ({PLAYER_WINRATE}%)"
  ],
  "NOTENOUGH_MAP_HOSTCREATOR": "&cSie benötigen mindestens 1 Karte, um einen Host zu erstellen",
  "ONEGAME": false,
  "ONEGAME_AUTOJOINGAME": "",
  "ONEGAME_KICK_AFTER_GAME": true,
  "ONEGAME_LOBBYSERVER": "",
  "ONEGAME_REMOVEJOINQUITMESSAGES": true,
  "ONEGAME_MOTD_USE": false,
  "ONEGAME_MOTD": [
    "&f>> ElytraRacing: {STATE} &7[-] Karte: &6{MAP}",
    "§f>> &7Spielen: §c{PLAYING} &7[-] Modus: {MODE_INFORMATION}"
  ],
  "ONEGAME_MOTD_RACEMODE_INFORMATION": "&aRacemode",
  "ONEGAME_MOTD_GRANDPRIX_INFORMATION": "&aGrandPrix &f{ROUND}/{ROUND_MAX}",
  "ONEGAME_MOTD_CHANGE_MAX_PLAYERS": true,
  "CHALLENGE_MAXGAME": false,
  "CHALLENGE_MAXGAME_PER_PLAYER": 10,
  "CHALLENGE_MAXGAME_COMPLETION_COMMAND": "[CONSOLE]/give {SELF_PLAYER} minecraft:cookie §%§[PLAYER]/tell {SELF_PLAYER} Sie haben einen Befehl ausgeführt",
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

<summary>AdminGUI.json</summary>

```
{
  "world": "Welt",
  "id": "ID",
  "map": "Karte",
  "type": "Typ",
  "normal": "normal",
  "ifnext": "wenn nächste",
  "name": "Name",
  "linkto": "Link zu",
  "rotations": "Umdrehungen",
  "shape": "Form",
  "radius": "Radius",
  "valid": "Gültig",
  "enabled": "Aktiviert",
  "checkpoints": "Kontrollpunkt(e)",
  "ends": "Ende(n)",
  "aos": "Zusätzliche(s) Objekt(e)",
  "locations": "Standorte",
  "start": "Start",
  "end": "Ende",
  "lobby": "Lobby",
  "boostMultiplier": "Boost-Multiplikator",
  "fireworks": "Feuerwerk(e)",
  "cpangle": "Kontrollpunkt Winkel",
  "laps": "Runde(n)",
  "lap": "Runde",
  "lapMapLong": "Hier können Sie die Anzahl der Runden auf dieser Karte ändern",
  "thereisare": "Es gibt/sind",
  "inMapCp": "Kontrollpunkt(e) auf der Karte",
  "inMapEnd": "Ende(n) auf der Karte",
  "inMapAo": "zusätzliche(s) Objekt(e) in der Karte",
  "clickModificationCp": "Klicken Sie auf , um einen Kontrollpunkt zu ändern",
  "clickModificationEnd": "Klicken Sie, um ein Ende zu ändern",
  "clickModificationAo": "Klicken Sie, um ein weiteres Objekt zu ändern",
  "currentDifficulty": "Aktueller Schwierigkeitsgrad der Karte",
  "clickDifficulty": "Klicken Sie hier, um den Schwierigkeitsgrad zu ändern",
  "respawnCpAngle": "Respawn-Winkel der Kontrollpunkte",
  "respawnCpAngleL1": "Klicken Sie auf Ändern des für die Karte verwendeten Winkels",
  "respawnCpAngleL2": "Informationen:",
  "PLAYER": "SPIELER",
  "respawnCpAngleL3": "- Verwenden Sie den Winkel, den der Spieler hatte, als er den Kontrollpunkt betrat.",
  "NEXT_CHECKPOINT": "NÄCHSTER_PRÜFPUNKT",
  "Experimental": "Experimentelle",
  "respawnCpAngleL4": "- Erstellen Sie einen Winkel, um den Spieler zum nächsten Kontrollpunkt umzuleiten.",
  "respawnCpAngleL5": "∞This feature is only working with maps that contains §c§l1 end and no linked checkpoints∞",
  "clickHereDefine": "Klicken Sie hier, um zu definieren",
  "defaultParticleCP": "Standardpartikel für Checkpoints",
  "defaultParticleEnd": "Standardpartikel für Enden",
  "defaultParticleAO": "Standardpartikel für zusätzliche Objekte",
  "mapAvailableTraining": "Karte für Schulungen verfügbar",
  "clickmapAvailableTraining": "Klicken Sie hier, um diese Karte des Trainingssatzes hinzuzufügen oder zu entfernen",
  "dbUUID": "Datenbank UUID",
  "clickDB": "Klicken Sie hier, um gespeicherte Informationen in der Datenbank zu löschen",
  "podiumConfiguration": "Konfiguration des Podiums",
  "qPodium": "Ist das Podiumssystem für diese Karte aktiviert?",
  "qPodiumL1": "Befehl zum Hinzufügen eines neuen Standorts für das Podium:",
  "qPodiumL2": "/ermap map [map] podium setlocation <placement... 1, 2, 3..>",
  "qPodiumL3": "Befehl zum Teleportieren einer Stelle des Podiums:",
  "qPodiumL4": "/ermap map [map] podium tp <placement... 1, 2, 3..>",
  "startHost": "Start eines Hosts",
  "createHostMap": "Klicken Sie hier, um einen Host mit dieser Karte zu erstellen",
  "maxtimepossible": "Maximal mögliche Zeit",
  "difficulty": "Schwierigkeitsgrad",
  "podium": "Podium",
  "particles": "Partikel",
  "changeName": "Name ändern",
  "confirm": "Bestätigen Sie",
  "cancel": "Abbrechen",
  "currentLaps": "Aktuelle Runde(n)",
  "currentMaxTime": "Aktuelle Maximalzeit",
  "currentMaxTimeModification": "Hier können Sie die maximal mögliche Zeit auf der Karte ändern",
  "minute": "Minute",
  "divideMinutes": "Dividieren durch 2 laufende Minuten",
  "doubleMinutes": "Aktuelle Minuten verdoppeln",
  "firework": "Feuerwerk",
  "divideFirework": "Dividieren durch 2 aktuelle Feuerwerke",
  "doubleFirework": "Doppeltes Stromfeuerwerk",
  "second": "zweite",
  "divideSeconds": "Dividieren durch 2 aktuelle Sekunden",
  "doubleSeconds": "Doppelte aktuelle Sekunden",
  "changeHologramName": "Name des Hologramms ändern",
  "cmdChangeHologramName": "/erconfig holograms setname [current_name] [new_name]",
  "changeMap": "Karte ändern",
  "changeHologramMap": "Zum Hologramm gehörende Veränderungskarte",
  "cmdChangeHologramMap": "/erconfig holograms setmap [hologram] [map]",
  "localisation": "Lokalisierung",
  "leftTeleported": "Linksklick um teleportiert zu werden",
  "clickTeleported": "Klicken Sie, um teleportiert zu werden",
  "shiftclickDefineLocation": "Klicken Sie bei gedrückter Umschalttaste, um diesen Ort zu definieren",
  "rightTeleported": "Rechtsklick um teleportiert zu werden",
  "leftConfigure": "Linksklick zum Konfigurieren",
  "rightChangeLocation": "Rechtsklick zum Ändern der Position",
  "rightDefineLocation": "Rechtsklick zum Festlegen der Position",
  "refreshDisplay": "Anzeige aktualisieren",
  "clickRefreshElement": "Klicken Sie hier, um die angezeigten Elemente auf dem Hologramm zu aktualisieren",
  "delete": "Löschen",
  "personalMaps": "Persönliche Karten",
  "clickCreateNewHolograms": "Klicken Sie hier, um ein neues Hologramm dieses Typs zu erstellen",
  "personalStats": "Persönliche Statistiken",
  "rankscore": "Wertung",
  "rankmap": "Rangkarte",
  "rankmapL1": "Sie müssen eine Karte für dieses Hologramm definieren.",
  "rankmapL2": "/erconfig holograms setmap [hologram] [map]",
  "rankwonr": "Gewonnener Rang racemode",
  "rankwong": "Gewonnener Rang grandprix",
  "deleteHologram": "Klicken Sie hier, um dieses Hologramm zu löschen",
  "currentParticle": "Aktuelle Partikel",
  "currentParticleLongMap": "Hier sehen Sie das aktuelle Partikelset für diese Karte",
  "clickChangeParticle": "Klicken Sie hier, um den Partikel zu ändern",
  "currentFireworkAmountMap": "Hier können Sie die Anzahl der Feuerwerke auf der Karte ändern",
  "clickChangePage": "Klicken Sie hier, um die Seite zu wechseln",
  "particleAmount": "Partikelmenge",
  "information": "Informationen",
  "clickDefineParticleObject": "Klicken Sie hier, um den Partikel des Objekts zu definieren",
  "currentLocation": "Aktueller Standort",
  "currentParticleAmount": "Aktuelle Partikelmenge",
  "particleAmountLong": "Hier können Sie die angezeigte Partikelmenge ändern",
  "currentFireworksAmount": "Aktuelle Feuerwerksmenge",
  "fireworksAmountLong": "Hier können Sie die Anzahl der Feuerwerkskörper ändern, die von diesem Objekt abgegeben werden",
  "leftclick": "Links klicken",
  "shiftleftclick": "Umschalttaste links klicken",
  "rightclick": "Rechtsklick",
  "shiftrightclick": "Rechtsklick bei gedrückter Umschalttaste",
  "currentRadius": "Aktueller Radius",
  "radiusmodification": "Hier können Sie den Radius ändern",
  "helpMessage": "Hilfe-Nachricht",
  "helpMessageL1": "Klicken Sie hier, um die Liste der Befehle für ",
  "helpMessageL2": "dieses Objekt, das Argumente automatisch vervollständigen wird",
  "helpMessageL2Map": "diese Karte, die automatisch Argumente ergänzt",
  "currentBoostMultiplier": "Stromverstärkungsmultiplikator",
  "boostMultiplierModification": "Hier können Sie den auf den Spieler angewandten Verstärkungsmultiplikator ändern",
  "closeMenu": "Klicken Sie hier, um dieses Menü zu schließen",
  "linkWithYou": "Verbinden Sie dieses Objekt mit Ihnen",
  "linkModificationL1": "Klicken Sie hier, um dieses Objekt mit Ihnen zu verknüpfen und es ändern zu können.",
  "linkModificationL2": "Mit diesem Link können Sie",
  "linkModificationL3": "um dieses Objekt mit Hilfe von Elementen zu ändern",
  "linkModificationL4": "Klicken Sie mit der linken Maustaste, um das Objekt zu verknüpfen.",
  "linkModificationL5": "Rechtsklick zum Abrufen von Elementen",
  "linkModificationL6": "Wenn Sie zu weit vom Objekt entfernt sind, wird es",
  "linkModificationL7": "automatisch freigeschaltet werden.",
  "clickDelete": "Klicken Sie hier, um dieses Objekt zu löschen.",
  "informationConfirmationDeleteAO": "Ein zusätzliches Objekt löschen",
  "informationConfirmationDeleteCP": "Einen Kontrollpunkt löschen",
  "informationConfirmationDeleteEND": "Ein Ende löschen",
  "createNew": "Erstellen Sie eine neue",
  "clickCreateNew": "Klicken Sie hier, um eine neue",
  "clickCreateNewCP": "Kontrollpunkt an Ihrem Standort",
  "clickCreateNewAO": "zusätzliches Objekt an Ihrem Standort",
  "clickCreateNewEnd": "an Ihrem Standort enden",
  "isLocationLobby": "Ist der Standort der Lobby festgelegt?",
  "isLocationStart": "Ist der Startort definiert?",
  "isLocationEnd": "Ist der Endpunkt definiert?",
  "locationLobby": "Standort Lobby",
  "locationStart": "Startort",
  "locationEnd": "Standort beenden",
  "specAndWalls": "Spezifikation und Wände",
  "qspecAndWalls": "Spec kann durch Wände gehen?",
  "clickChangeValue": "Klicken Sie hier, um den Wert zu ändern",
  "showMap": "Karte anzeigen",
  "clickShowMap": "Zum Anzeigen hier klicken/diese Karte ausblenden",
  "currentParticleSet": "Hier können Sie den aktuellen Partikelsatz sehen",
  "pageHologramPage": "Hologramm-Konfiguration",
  "pageAOCP": "Liste der zusätzlichen Objekte",
  "pageAOP": "Zusätzliche Objektkonfiguration",
  "pageConfirmationDeleteObject": "Bestätigung der Löschung",
  "pageCPCP": "Liste der Kontrollpunkte",
  "pageCPP": "Konfiguration der Kontrollpunkte",
  "pageECP": "Liste der Enden",
  "pageEP": "Konfiguration beenden",
  "pageHCP": "Liste der Hologramme",
  "pageMCP": "Liste der Karten",
  "pageMS": "Karteneinstellungen:"
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
      "HOST_STARTING": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&fSpieler(innen): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fKarte: {CURRENT_MAP}",
          "&fModus: &aRace",
          "",
          "Gastgeber: {HOST}",
          "&cBeginnend in {STARTING_COUNTDOWN} sekunde(n)",
          "",
          "{LINK}"
        ]
      },
      "HOST_FINISHED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&e1° - {RANK_PLAYER_1}",
          "&72° - {RANK_PLAYER_2}",
          "&63° - {RANK_PLAYER_3}",
          "Ihr rang: {SELF_RANK_PLAYER}",
          "",
          "{LINK}"
        ]
      },
      "WAITING": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&fSpieler(innen): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fKarte: {CURRENT_MAP}",
          "&fModus: &aRace",
          "",
          "&cBedarf {NEEDED_PLAYER} zu startende(r) spieler",
          "",
          "{LINK}"
        ]
      },
      "SPECTATOR": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "Verbleibende Zeit: &c{TIME_LEFT}",
          "&fSpieler(innen): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "",
          "&e1° - {RACE_RANK_PLAYER_1}",
          "&72° - {RACE_RANK_PLAYER_2}",
          "&63° - {RACE_RANK_PLAYER_3}",
          "&f4° - {RACE_RANK_PLAYER_4}",
          "&f5° - {RACE_RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "SPECTATOR_FINISHED": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&e1° - {RANK_PLAYER_1}",
          "&72° - {RANK_PLAYER_2}",
          "&63° - {RANK_PLAYER_3}",
          "&f4° - {RANK_PLAYER_4}",
          "&f5° - {RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "HOST_SPECTATOR_FINISHED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&e1° - {RANK_PLAYER_1}",
          "&72° - {RANK_PLAYER_2}",
          "&63° - {RANK_PLAYER_3}",
          "&f4° - {RANK_PLAYER_4}",
          "&f5° - {RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "HOST_SPECTATOR": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "Verbleibende Zeit: &c{TIME_LEFT}",
          "&fSpieler(innen): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "",
          "&e1° - {RACE_RANK_PLAYER_1}",
          "&72° - {RACE_RANK_PLAYER_2}",
          "&63° - {RACE_RANK_PLAYER_3}",
          "&f4° - {RACE_RANK_PLAYER_4}",
          "&f5° - {RACE_RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "HOST_WAITING": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&fSpieler(innen): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fKarte: {CURRENT_MAP}",
          "&fModus: &aRace",
          "",
          "Gastgeber: {HOST}",
          "",
          "{LINK}"
        ]
      },
      "STARTED": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "Verbleibende Zeit: &c{TIME_LEFT}",
          "&fSpieler(innen): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "",
          "&e1° - {RACE_RANK_PLAYER_1}",
          "&72° - {RACE_RANK_PLAYER_2}",
          "&63° - {RACE_RANK_PLAYER_3}",
          "Ihr rang: {SELF_RACE_RANK_PLAYER}",
          "",
          "Kontrollpunkte: &6{SELF_CPS}/{MAX_CPS}",
          "Runden: &6{SELF_LAPS}/{MAX_LAPS}",
          "",
          "{LINK}"
        ]
      },
      "STARTING": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&fSpieler(innen): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fKarte: {CURRENT_MAP}",
          "&fModus: &aRace",
          "",
          "&cBeginnend in {STARTING_COUNTDOWN} sekunde(n)",
          "",
          "{LINK}"
        ]
      },
      "FINISHED": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&e1° - {RANK_PLAYER_1}",
          "&72° - {RANK_PLAYER_2}",
          "&63° - {RANK_PLAYER_3}",
          "Ihr rang: {SELF_RANK_PLAYER}",
          "",
          "{LINK}"
        ]
      },
      "HOST_STARTED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "Verbleibende Zeit: &c{TIME_LEFT}",
          "&fSpieler(innen): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "",
          "&e1° - {RACE_RANK_PLAYER_1}",
          "&72° - {RACE_RANK_PLAYER_2}",
          "&63° - {RACE_RANK_PLAYER_3}",
          "Ihr rang: {SELF_RACE_RANK_PLAYER}",
          "",
          "Kontrollpunkte: &6{SELF_CPS}/{MAX_CPS}",
          "Runden: &6{SELF_LAPS}/{MAX_LAPS}",
          "",
          "{LINK}"
        ]
      }
    }
  },
  "GrandPrix": {
    "perState": {
      "HOST_STARTING": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&fSpieler(innen): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fKarte: {CURRENT_MAP}",
          "&fModus: &aGrandPrix",
          "Rund: 1/{MAX_ROUND}",
          "",
          "Gastgeber: {HOST}",
          "&cBeginnend in {STARTING_COUNTDOWN} sekunde(n)",
          "",
          "{LINK}"
        ]
      },
      "BETWEENROUND": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "Nächste Karte: {CURRENT_MAP}",
          "{CURRENT_MAP_DIFFICULTY}",
          "&6PERSÖNLICHE BESTLEISTUNG: {SELF_MAP_PERSÖNLICHE BESTLEISTUNG}",
          "",
          "&e1° - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72° - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63° - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "Ihr rang: {SELF_RANK_PLAYER}",
          "Ihr ergebnis: {SELF_RANK_PLAYER_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "HOST_SPECTATOR": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "Verbleibende Zeit: &c{TIME_LEFT}",
          "&fSpieler(innen): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "Rund: {CURRENT_ROUND}/{MAX_ROUND}",
          "",
          "&e1° - {RACE_RANK_PLAYER_1}",
          "&72° - {RACE_RANK_PLAYER_2}",
          "&63° - {RACE_RANK_PLAYER_3}",
          "&f4° - {RACE_RANK_PLAYER_4}",
          "&f5° - {RACE_RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "STARTING": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&fSpieler(innen): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fKarte: {CURRENT_MAP}",
          "&fModus: &aGrandPrix",
          "Rund: 1/{MAX_ROUND}",
          "",
          "&cBeginnend in {STARTING_COUNTDOWN} sekunde(n)",
          "",
          "{LINK}"
        ]
      },
      "FINISHED": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&e1° - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72° - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63° - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "Ihr rang: {SELF_RANK_PLAYER}",
          "Ihr ergebnis: {SELF_RANK_PLAYER_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "HOST_FINISHED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&e1° - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72° - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63° - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "Ihr rang: {SELF_RANK_PLAYER}",
          "Ihr ergebnis: {SELF_RANK_PLAYER_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "WAITING": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&fSpieler(innen): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fKarte: {CURRENT_MAP}",
          "&fModus: &aGrandPrix",
          "Rund: 1/{MAX_ROUND}",
          "",
          "&cBedarf {NEEDED_PLAYER} zu startende(r) spieler",
          "",
          "{LINK}"
        ]
      },
      "SPECTATOR": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "Verbleibende Zeit: &c{TIME_LEFT}",
          "&fSpieler(innen): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "Rund: {CURRENT_ROUND}/{MAX_ROUND}",
          "",
          "&e1° - {RACE_RANK_PLAYER_1}",
          "&72° - {RACE_RANK_PLAYER_2}",
          "&63° - {RACE_RANK_PLAYER_3}",
          "&f4° - {RACE_RANK_PLAYER_4}",
          "&f5° - {RACE_RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "SPECTATOR_FINISHED": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&e1° - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72° - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63° - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "&f4° - {RANK_PLAYER_4} - {RANK_PLAYER_4_SCORE}",
          "&f5° - {RANK_PLAYER_5} - {RANK_PLAYER_5_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "HOST_SPECTATOR_FINISHED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&e1° - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72° - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63° - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "&f4° - {RANK_PLAYER_4} - {RANK_PLAYER_4_SCORE}",
          "&f5° - {RANK_PLAYER_5} - {RANK_PLAYER_5_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "HOST_BETWEENROUND": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "Nächste Karte: {CURRENT_MAP}",
          "{CURRENT_MAP_DIFFICULTY}",
          "&6PERSÖNLICHE BESTLEISTUNG: {SELF_MAP_PERSÖNLICHE BESTLEISTUNG}",
          "",
          "&e1° - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72° - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63° - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "Ihr rang: {SELF_RANK_PLAYER}",
          "Ihr ergebnis: {SELF_RANK_PLAYER_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "HOST_SPECTATOR_BETWEENROUND": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "Nächste Karte: {CURRENT_MAP}",
          "{CURRENT_MAP_DIFFICULTY}",
          "&6PERSÖNLICHE BESTLEISTUNG: {SELF_MAP_PERSÖNLICHE BESTLEISTUNG}",
          "",
          "&e1° - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72° - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63° - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "&f4° - {RANK_PLAYER_4} - {RANK_PLAYER_4_SCORE}",
          "&f5° - {RANK_PLAYER_5} - {RANK_PLAYER_5_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "HOST_WAITING": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&fSpieler(innen): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fKarte: {CURRENT_MAP}",
          "&fModus: &aGrandPrix",
          "Rund: 1/{MAX_ROUND}",
          "",
          "Gastgeber: {HOST}",
          "",
          "{LINK}"
        ]
      },
      "STARTED": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "Verbleibende Zeit: &c{TIME_LEFT}",
          "&fSpieler(innen): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "Rund: {CURRENT_ROUND}/{MAX_ROUND}",
          "",
          "&e1° - {RACE_RANK_PLAYER_1}",
          "&72° - {RACE_RANK_PLAYER_2}",
          "&63° - {RACE_RANK_PLAYER_3}",
          "Ihr rang: {SELF_RACE_RANK_PLAYER}",
          "",
          "Kontrollpunkte: &6{SELF_CPS}/{MAX_CPS}",
          "Runden: &6{SELF_LAPS}/{MAX_LAPS}",
          "",
          "{LINK}"
        ]
      },
      "HOST_STARTED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "Verbleibende Zeit: &c{TIME_LEFT}",
          "&fSpieler(innen): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "Rund: {CURRENT_ROUND}/{MAX_ROUND}",
          "",
          "&e1° - {RACE_RANK_PLAYER_1}",
          "&72° - {RACE_RANK_PLAYER_2}",
          "&63° - {RACE_RANK_PLAYER_3}",
          "Ihr rang: {SELF_RACE_RANK_PLAYER}",
          "",
          "Kontrollpunkte: &6{SELF_CPS}/{MAX_CPS}",
          "Runden: &6{SELF_LAPS}/{MAX_LAPS}",
          "",
          "{LINK}"
        ]
      },
      "SPECTATOR_BETWEENROUND": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "Nächste Karte: {CURRENT_MAP}",
          "{CURRENT_MAP_DIFFICULTY}",
          "&6PERSÖNLICHE BESTLEISTUNG: {SELF_MAP_PB}",
          "",
          "&e1° - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72° - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63° - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "&f4° - {RANK_PLAYER_4} - {RANK_PLAYER_4_SCORE}",
          "&f5° - {RANK_PLAYER_5} - {RANK_PLAYER_5_SCORE}",
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
          "&6PERSÖNLICHE BESTLEISTUNG: {SELF_MAP_PERSÖNLICHE BESTLEISTUNG}",
          "&fRank: {SELF_MAP_RANK}",
          "",
          "WEltrekordhalter: {MAP_WR_PLAYER}",
          "&6Zeit: &c{MAP_WR_TIME}",
          "",
          "Verbleibende Zeit: &c{TIME_LEFT}",
          "&fSchwierigkeitsgrad: {CURRENT_MAP_DIFFICULTY}",
          "Kontrollpunkte: &6{SELF_CPS}/{MAX_CPS}",
          "Runden: &6{SELF_LAPS}/{MAX_LAPS}",
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
  "GUI_PARTICLE_TITLE": "Partikel-Selektor",
  "GUI_ITEM_PARTICLE_TITLE": "&f{PARTICLE_NAME}",
  "GUI_ITEM_PARTICLE_TITLE_SELECTED": "&a{PARTICLE_NAME}",
  "GUI_NO_PARTICLE": "Keine",
  "GUI_DISABLE_OTHERS_PARTICLES_UNSELECTED": "&fDie Änderungen wurden erfolgreich gespeichert.",
  "GUI_DISABLE_OTHERS_PARTICLES_SELECTED": "&fDie Änderungen wurden erfolgreich gespeichert.",
  "GUI_DISABLE_OTHERS_PARTICLES_LORE_SELECTED": "&f-> Derzeit: &a✓",
  "GUI_DISABLE_OTHERS_PARTICLES_LORE_UNSELECTED": "&f-> Derzeit: &c❌",
  "MSG_SAVE_SUCCESSFUL": "&fEs wurden Änderungen",
  "GUI_CLICKCHANGE": "Klicken Sie hier, um die Seite zu wechseln",
  "GUI_ENCHANT_SELECTED": true,
  "particles": [
    {
      "name": "GrünerKreis",
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
      "name": "RotierenderRegenbogenkreis",
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
      "name": "Regenbogenpunkt",
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
      "name": "RoterPunkt",
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
      "name": "HorizontaleWelle",
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
      "name": "VertikalWellenförmigerPunkt",
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
      "name": "Regenbogenröhre",
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
