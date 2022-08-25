# 🇫🇷 French

{% hint style="warning" %}
Files translated using multiple translation websites

The goal of this translation is not to have the perfect on but to have a version that will help you to start to configure the plugin in the language you want

If you see bad translations please send me a message on discord
{% endhint %}

{% hint style="warning" %}
Fichiers traduits à l'aide de plusieurs sites Web de traduction.

Le but de cette traduction n'est pas d'avoir le parfait sur mais d'avoir une version qui vous aidera à commencer à configurer le plugin dans la langue que vous souhaitez.

Si vous voyez de mauvaises traductions merci de m'envoyer un message sur discord
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
  "ER_TRAIN_MAP_NOTFOUND": "&cCette carte n'est pas éligible à la formation",
  "ER_TRAIN_CHOOSE_MAP_GUI_TITLE": "Choisissez une carte",
  "SIGN_RELOAD_SEC": 3,
  "TELEPORT_SOLVER": false,
  "UNLOCK_DISTANCE": 100,
  "UNLOCK_OBJECT": "&fObjet déverrouillé",
  "LOCK_OBJECT": "&fAssocié cet objet avec vous &aavec succès",
  "LOCK_ITEMS_GIVE": "&fLes articles ont été &aavec succès &fdonné",
  "LOCK_OBJECT_NEAR_NOTFOUND": "&cAucun objet n'a été trouvé près de chez vous",
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
  "MAP_DIFFICULTY_MESSAGE": "&7Difficulté de la carte: {DIFFICULTY}",
  "DNF_POINT": -1,
  "TABLIST_GRANDPRIX": true,
  "COMMANDS_WHITELIST": false,
  "COMMANDS_WHITELIST_COMMANDS": [
    "msg",
    "rl",
    "reload"
  ],
  "COMMANDS_WHITELIST_BYPASS_PERMISSION": "elytraracing.wlcommands.bypass",
  "COMMANDS_MESSAGE": "&cVous ne pouvez pas exécuter cette commande ici !",
  "SPECTATOR_ITEM": true,
  "STATIC_ITEMS": true,
  "RankingMaxPlayers": 8,
  "PODIUM_FIREWORKS": true,
  "PODIUM_FIREWORK_NUMBER": 10,
  "END_TIME": 30,
  "DISABLE_ELYTRA": false,
  "COMMAND_EXECUTION_PER_RANK_IN_HOST": false,
  "COMMAND_EXECUTION_PER_RANK_GRANDPRIX": {
    "-1": "[CONSOLE]/give {SELF_PLAYER} minecraft:cookie {SCORE} §%§[PLAYER]/tell {SELF_PLAYER} vous avez exécuté une commande",
    "0": "[PLAYER]/tell {SELF_PLAYER} vous avez exécuté une commande"
  },
  "COMMAND_EXECUTION_PER_RANK_RACEMODE": {
    "-1": "[CONSOLE]/give {SELF_PLAYER} minecraft:cookie 5 §%§[PLAYER]/tell {SELF_PLAYER} vous avez exécuté une commande",
    "0": "[PLAYER]/tell {SELF_PLAYER} vous avez exécuté une commande"
  },
  "PERMISSION_MESSAGE": "&cVous n'êtes pas autorisé à exécuter cette commande",
  "PERMISSION_MESSAGE_HOST": "&cVous n'êtes pas autorisé à rejoindre ce jeu",
  "MSG_NUMBER_LAP": "&eNombre de tour(s): {LAPS}",
  "HOLOGRAM_NOT_FOUND": "&cCet hologramme est introuvable.",
  "ITEM_1CP_BACK": "&cPrécédent point de contrôle",
  "ITEM_1CP_BACK_MATERIAL": null,
  "ITEM_1CP_BACK_SLOT": 0,
  "ITEM_2CP_BACK": "&c2 points de contrôle en arrière",
  "ITEM_2CP_BACK_MATERIAL": null,
  "ITEM_2CP_BACK_SLOT": 1,
  "ITEM_RESTART": "&cRESTART",
  "ITEM_RESTART_MATERIAL": null,
  "ITEM_RESTART_SLOT": 4,
  "ITEM_DNF": "&cDNF",
  "ITEM_DNF_MATERIAL": null,
  "ITEM_DNF_SLOT": 8,
  "ITEM_BED": "&cQuitter le jeu",
  "ITEM_BED_MATERIAL": null,
  "ITEM_BED_SLOT": 8,
  "ITEM_SPEC": "&aRejoindre le mode spec",
  "ITEM_SPEC_MATERIAL": null,
  "ITEM_SPEC_SLOT": 4,
  "ITEM_CUSTOM": "&aRejoindre le mode spec",
  "ITEM_CUSTOM_MATERIAL": null,
  "ITEM_CUSTOM_SLOT": 3,
  "ITEM_HOST": "&aConfiguration de l'hôte",
  "ITEM_HOST_MATERIAL": null,
  "ITEM_HOST_SLOT": 4,
  "ITEM_PARTICLE": "&aSélecteur de particules",
  "ITEM_PARTICLE_MATERIAL": null,
  "ITEM_PARTICLE_SLOT": 2,
  "ITEM_FIREWORK_SLOT": 2,
  "ITEM_PAPERMAPINFO_SLOT": 4,
  "ITEM_PAPERMAPINFO_MATERIAL": null,
  "ITEM_HOSTSEPARATION_TITLE": "&fSélection de la carte",
  "ITEM_HOSTSEPARATION_DESCRIPTION": "&a⬇  ⬇  ⬇  ⬇  ⬇  ⬇",
  "ITEM_HOSTSEPARATION_MATERIAL": null,
  "ITEM_HOSTMAP_TITLE_SELECTED": "&a{MAP_NAME}",
  "ITEM_HOSTMAP_TITLE_NOTSELECTED": "&f{MAP_NAME}",
  "ITEM_HOSTMAP_MATERIAL_SELECTED": null,
  "ITEM_HOSTMAP_MATERIAL_NOTSELECTED": null,
  "HOSTMAP_CREATOR_INVENTORY_TITLE": "Créateur de l'hôte",
  "ALERT_HOST": "&6{PLAYER} &avient de commencer à accueillir &7(Cliquez ici pour vous inscrire)",
  "ERROR_MESSAGE": "&cUne erreur a été rencontrée pendant le processus",
  "ACTIONBAR_TIME": "&7Temps restant: &c{TIME}",
  "MSG_PAGE": "&7Page &c{PAGE} &7de &c{MAX_PAGE}",
  "MSG_ENDMAP": "&6{PLAYER} &7-> &c{ARG}",
  "MSG_GAMEFULL": "&cCe jeu est déjà complet",
  "MSG_GAMESTARTED": "&cCe jeu a déjà commencé",
  "LOCATIONNOTDEFINED": "&cCet emplacement n'est pas défini !",
  "MSG_ERHOST_LISTGAMES": "&aListe de jeux &7&o(survol): ",
  "MSG_ERMAP_LISTGAMES_GAMESFORMAT": "&c>> &f{GAME_NAME} ",
  "MSG_ERMAP_LISTCHECKPOINT": "&aListe des points de contrôle &7&o(survol): ",
  "DEFAULT": "&6DEFAULT",
  "NONE": "&6NONE",
  "NOBODY": "Nobody",
  "MSG_ERMAP_LISTCHECKPOINT_CHECKPOINTFORMAT": "&f#{CHECKPOINT_ID_ORDER} &c>> &f({X},{Y},{Z}) &7&o(Cliquez pour vous téléporter)",
  "MSG_ERMAP_LISTEND": "&aListe des extrémités &7&o(survol): ",
  "MSG_ERMAP_LISTEND_ENDFORMAT": "&f#{END_ID_ORDER} &c>> &f({X},{Y},{Z}) &7&o(Cliquez pour vous téléporter)",
  "YES": "&aOui",
  "NO": "&cNon",
  "CHECK": "&a✓",
  "CROSS": "&cx",
  "MSG_STATE_WAITING": "&aAttente",
  "MSG_STATE_STARTING": "&6Démarrage",
  "MSG_STATE_STARTED": "&cDémarré",
  "MSG_SPEC_JOINING": "&7Rejoindre le jeu en tant que spectateur...",
  "PERM_SPECGAME": "elytraracing.specgame",
  "MSG_NOGAMETOLEAVE": "&cPas besoin de partir, vous n'êtes pas encore dans un jeu.",
  "MSG_GAMENOTEXIST": "&cCe jeu n'existe pas",
  "MSG_NOTYOURHOST": "&cVous n'êtes pas l'hôte de ce jeu.",
  "MSG_TIMERSTART": "&aMinuterie démarrée",
  "MSG_TIMERCANCEL": "&cMinuterie annulée",
  "MSG_HOST_NOTEXIST": "&cVotre hôte est introuvable",
  "MSG_LEAVEYOURGAME": "&cVous êtes déjà dans un jeu",
  "MSG_GAMENOTOPEN": "&cCe n'est pas ouvert",
  "MSG_MAPCREATING": "&aCréer une carte...",
  "MSG_MAPNAMEEXIST": "&cCe nom de carte existe déjà",
  "MSG_GAMENAME_EXIST": "&cCe nom de jeu existe déjà",
  "MSG_HOST_CREATING": "&aCréer un hôte...",
  "MSG_CHECKPOINT_VERIFIED": "&fLe point de contrôle est passé ! ({CHECKPOINT_PASSED} / {CHECKPOINT_MAX})",
  "MSG_LAP_VERIFIED": "&eTour terminé ! ({LAP_PASSED} / {LAP_MAX})",
  "MSG_GAME_PLAYERJOIN": "&6{PLAYER_NAME} &fa rejoint la course ! &7&o({PLAYER_SIZE} / {MAX_PLAYER})",
  "MSG_GAME_PLAYERJOIN_PLAYERNEEDEDLEFT": " &c({PLAYER_NEEDED} gauche nécessaire)",
  "MSG_GAME_PLAYERLEAVE": "&6{PLAYER_NAME} &fa quitté la course ! &7&o({PLAYER_SIZE} / {MAX_PLAYER})",
  "MSG_GAME_NOTENOUGHPLAYERS": "&cTimer annulé, pas assez de joueurs",
  "PLAYER_NOTFOUND": "&cLecteur non trouvé.",
  "ERHOST_PLAYER_NOTFOUND": "&cCe joueur n'est pas dans votre jeu.",
  "MSG_MAP_NOTAVAILABLE": "&cCette carte n'est pas disponible !",
  "MSG_MAP_NOTAVAILABLE2": "&c{MAP} n'est pas disponible !",
  "MSG_MAPNOTFOUND2": "&c{ARG} ne peut pas être trouvé",
  "MSG_ALERT": "&cVous avez déjà envoyé trop d'alertes",
  "PARTICLE_LIST": "&7Liste des particules (Cliquez pour activer): ",
  "PARTICLE_LIST_ITEMS": " &7{item}",
  "PARTICLE_LIST_ITEMS_HOVER": "&7{item}: Click to activate",
  "PARTICLE_LIST_NOTFOUND": "&cCe type de particule est introuvable",
  "GRANDPRIX": "Grandprix",
  "RACEMODE": "Race",
  "PERSONAL_BEST": " &6&k&llol &6&lMeilleur résultat personnel&k&llol",
  "TIME_NOT_FOUND": " - ",
  "RANK_NOT_FOUND": "-",
  "ER_PLAY_GAME": "&cAucun jeu n'a été trouvé !",
  "MSG_STEP_TIMER": {
    "0": "Votre jeu commence...",
    "1": "Votre jeu commence dans &f1 &fdeuxième",
    "2": "Votre jeu commence dans &a2 &fsecondes",
    "3": "Votre jeu commence dans &23 &fsecondes",
    "4": "Votre jeu commence dans &64 &fsecondes",
    "5": "Votre jeu commence dans &c5 &fsecondes",
    "10": "Votre jeu commence dans &c10 &fsecondes",
    "30": "Votre jeu commence dans &c30 &fsecondes"
  },
  "MSG_STEPROUND_TIMER": {
    "0": "Le prochain tour commence...",
    "1": "Le prochain tour commence en &f1 &fdeuxième",
    "2": "Le prochain tour commence en &a2 &fsecondes",
    "3": "Le prochain tour commence en &23 &fsecondes",
    "4": "Le prochain tour commence en &64 &fsecondes",
    "5": "Le prochain tour commence en &c5 &fsecondes",
    "15": "Le prochain tour commence en &c15 &fsecondes"
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
  "MSG_PRE_RANK": "&7\nClassement:\n",
  "MSG_PRE_SCORE": "&7\nTableau d'affichage:\n",
  "MSG_YOURRANK": "&7Votre rang sur cette carte: &c{RANK}",
  "MSG_YOURSCORE": "&7Votre rang global est: &c{RANK} &7avec &c{SCORE} &7points",
  "MSG_ARG_RANK_TIME_DNF": "&cDNF",
  "MSG_ARG_RANK_TIME_TIME": "&c{TIME}",
  "TELEPORTING": "&7Téléportation...",
  "TIMEFORMAT": "{MINUTES}m {SECONDS}.{MILLISECONDS}s",
  "TIMEFORMAT_WM": "{MINUTES}m {SECONDS}s",
  "PLACEHOLDER_NOTFOUND_PLAYER": "Aucun",
  "PLACEHOLDER_DEFAULT_NUMBER": "0",
  "PLACEHOLDER_DEFAULT_TEXT": "",
  "PLACEHOLDER_DEFAULT_RANKING": "-",
  "ERMAP_MAP_DELETE": "&cLa carte sera supprimée après un rechargement/redémarrer",
  "MSG_MAPNOTFOUND": "&cCette carte est introuvable",
  "MSG_SAVE_SUCCESSFUL": "&fLes changements ont été &aavec succès &fsauvegardé",
  "MSG_FILE_RELOAD": "&fLe(s) fichier(s) ont été &frechargé.",
  "MSG_SHOW_ON": "&aPermettre l'accès à ...",
  "MSG_SHOW_OFF": "&cDésactivation de ...",
  "MSG_CHECKPOINT_NOTFOUND": "&cCe point de contrôle est introuvable",
  "MSG_END_NOTFOUND": "&cCette fin ne peut être trouvée",
  "ID_ORDER_ARG": "&c[id_order] doit être un nombre entier",
  "ID_ORDER_TARGET_ARG": "&c[id_order_target] doit être un nombre entier",
  "DEGREES_ARG": "&c[rotation] doit être un nombre entier",
  "MULTIPLIER_ARG": "&c[amount] doit être un flottant",
  "SIZE_ARG": "&c[size] doit être un flottant",
  "AMOUNT_ARG": "&c[amount] doit être un nombre entier",
  "SECONDS_ARG": "&c[seconds] doit être un nombre entier compris entre 0 et 59",
  "MINUTES_ARG": "&c[minutes] doit être un nombre entier supérieur à 0",
  "MAX_PLAYER_ARG": "&c[slots] doit être un nombre entier supérieur à 0",
  "PAGE_ARG": "&c[page] doit être un nombre entier supérieur à 0",
  "ERCONFIG_SETITEM_ID_NOT_FOUND": "&cCe site [id_item] ne peut pas être trouvé",
  "ERCONFIG_SETITEM_ITEM_NOT_FOUND": "&cL'objet dans votre main ne peut pas être trouvé",
  "SPEC_PERM": null,
  "SPEC_PERM_MESSAGE": "&cVous n'avez pas la permission d'assister à un match.",
  "HOST_GAMENOTOPEN": "&cVotre jeu n'est pas ouvert",
  "SPECTATORMODE": "&aVous êtes entré en mode spectateur &7(Cliquez ici pour quitter ou taper '/er quitspec')",
  "STUCKSPECTATOR": "&aUtilisez /er near §fpour se téléporter vers le joueur le plus proche",
  "AVAILABLE_MAPS": "&aCartes disponibles: {MAPS}",
  "ERGAMES_LIST": "&6Liste des jeux vidéo: {AUTOGAMES}",
  "ERGAMES_ENABLED_PREFIX": "&a",
  "ERGAMES_DISABLED_PREFIX": "&c",
  "ERGAMES_LIST_SEPERATION_PREFIX": "&7",
  "ERGAMES_NOTFOUND": "&cCet autogame est introuvable",
  "ERGAMES_ALREADYGAME": "&cVous ne pouvez pas activer ce jeu automatique car il existe déjà un jeu portant le même nom.",
  "TABLIST_RANK_SCORE_TITLE": "&7Tableau d'affichage",
  "TABLIST_RANK_SCORE_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "TABLIST_GRANDPRIX_PERSONAL_PERSONAL": "&6Statistiques personnelles sur cette carte:",
  "TABLIST_GRANDPRIX_PERSONAL_TIME": "&9Meilleur temps personnel: &c{TIME}",
  "TABLIST_GRANDPRIX_PERSONAL_RANK": "&9Votre rang: &c{RANK}",
  "TABLIST_GRANDPRIX_PERSONAL_WINRATE": "&9Votre taux de réussite: &c{WINRATE} %",
  "HOLOGRAMS_RANK_SCORE_TITLE": "&6&lLes 15 meilleurs scores",
  "HOLOGRAMS_RANK_SCORE_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "-2": "&9{RANK} &7- &9-------- &7- &c0",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_RANK_WON_RACEMODE_TITLE": "&6&lTop 15 des courses les plus remportées",
  "HOLOGRAMS_RANK_WON_RACEMODE_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "-2": "&9{RANK} &7- &9-------- &7- &c0",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_RANK_WON_GRANDPRIX_TITLE": "&6&lTop 15 Plus grand nombre de grands prix remportés",
  "HOLOGRAMS_RANK_WON_GRANDPRIX_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "-2": "&9{RANK} &7- &9-------- &7- &c0",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_RANK_MAP_TITLE": "&6&lTop 15 des meilleurs moments sur {MAP}",
  "HOLOGRAMS_RANK_MAP_SPECIFIC": {
    "-1": "&9{RANK} &7- &9{USERNAME} &7- &c{SCORE}",
    "-2": "&9{RANK} &7- &9-------- &7- &c0",
    "1": "&e{RANK} &7- &e{USERNAME} &7- &c{SCORE}",
    "2": "&7{RANK} &7- &7{USERNAME} &7- &c{SCORE}",
    "3": "&6{RANK} &7- &6{USERNAME} &7- &c{SCORE}"
  },
  "HOLOGRAMS_PERSONAL_MAPS_TITLE": "&6&lStatistiques personnelles sur les cartes",
  "HOLOGRAMS_PERSONAL_MAPS_SPECIFIC": "&6{MAP_NAME} &7: &c{PLAYER_TIME} &7(#{PLAYER_RANK}) (winrate: {WINRATE}%)",
  "HOST_MAPCHOOSER_CHANGEPAGE": "Cliquez ici pour changer de page",
  "DNF_INSTANT_QUIT": false,
  "MSG_LISTMAPS_INFO": [
    "&a>> {MAP_NAME}",
    " ",
    "&f>> &7Valable: {VALID}",
    "&f>> &7Activé: {ENABLED}",
    " ",
    "&f>> &7Points de contrôle: &c{CHECKPOINTS}",
    "&f>> &7Jusqu'à: &c{ENDS}",
    "&f>> &7Emplacement du hall d'entrée: &c{LOBBY}",
    "&f>> &7Lieu de départ: &c{START}",
    "&f>> &7Emplacement final: &c{END}",
    "&f>> &7Podium: &c{PODIUM}",
    " ",
    "&f>> &7Temps max.: &c{TIME}",
    "&f>> &7Difficulté: &c{DIFFICULTY}",
    " "
  ],
  "HOST_TITLE_PERM": "&7Permission: &c{PERMISSION}",
  "HOST_DESC_PERM": [
    " ",
    "&f/erhost setperm &c[permission/none]",
    "&fPour définir l'autorisation de rejoindre votre jeu.",
    " "
  ],
  "HOST_TITLE_ALERT": "&aAlerte",
  "HOST_DESC_ALERT": [
    " ",
    "&fCliquez ici pour diffuser une invitation à rejoindre votre jeu.",
    " "
  ],
  "HOST_TITLE_START": "&aDébut",
  "HOST_DESC_START": [
    " ",
    "&fCliquez ici pour lancer le jeu",
    " "
  ],
  "HOST_TITLE_END": "&cAnnuler le compte à rebours",
  "HOST_DESC_END": [
    " ",
    "&fCliquez ici pour arrêter le compte à rebours",
    " "
  ],
  "HOST_TITLE_SLOTS": "&cNombre d'emplacements",
  "HOST_DESC_SLOTS": [
    " ",
    "&fNombre d'emplacements: &c{SLOTS}",
    " ",
    "&7Clic gauche: +1 (+ Maj: +10)",
    "&7Clic droit: -1 (+ Maj: -10)",
    " "
  ],
  "HOST_TITLE_OPEN": "&fVotre hôte est actuellement: &aOuvrir",
  "HOST_TITLE_CLOSED": "&fVotre hôte est actuellement: &cFermé",
  "HOSTCREATOR_CREATE_TITLE": "&aCréer l'hôte",
  "HOSTCREATOR_CREATE_DESCRIPTION": [
    " ",
    "&fNom: &c{NAME}",
    " ",
    "&fNombre d'emplacements: &c{SLOTS}",
    "&fNombre de cartes: &c{MAP_NUMBER}",
    "&fMode: &c{MODE}",
    " "
  ],
  "HOSTCREATOR_MAPS_TITLE": "&fNombre de cartes: &c{MAP_NUMBER}",
  "HOSTCREATOR_MAPS_DESCRIPTION": "&f{ORDER}. {MAP_NAME}",
  "HOSTCREATOR_MAXPLAYERS_TITLE": "&fNombre d'emplacements: {SLOTS}",
  "HOST_MAXPLAYERS_SLOTS": [
    " ",
    "&fNombre d'emplacements: &c{SLOTS}",
    " ",
    "&7Clic gauche: +1 (+ Maj: +10)",
    "&7Clic droit: -1 (+ Maj: -10)",
    " "
  ],
  "STATES": {
    "STARTING": "&6Démarrage",
    "STARTED": "&cEn jeu",
    "WAITING": "&aAttente",
    "FINISHED": "&7Fin"
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
    "&7Cliquez pour adhérer"
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
    "&f>> &7Monde: &c{WORLD}",
    " ",
    "&f>> &7Rayon: &c{RADIUS}",
    "&f>> &7Quantité de particules: &c{PARTICLE_AMOUNT}",
    "&f>> &7Multiplicateur de boost: &c{BOOST_MULTIPLIER}",
    "&f>> &7",
    "&f>> &7Type de particule: &c{PARTICLE_TYPE}",
    "&f>> &7Lié à: &c{LINK}"
  ],
  "MSG_LISTGAMES_INFO": [
    "&a>> {GAME_NAME}",
    " ",
    "&f>> &7Joueurs: &c{PLAYER_SIZE}",
    "&f>> &7joueurs minimum: &c{MIN_PLAYER}",
    "&f>> &7joueurs max.: &c{MAX_PLAYER}",
    " ",
    "&f>> &7État: &c{GAME_STATE}"
  ],
  "MSG_LISTEND_INFO": [
    " ",
    "&f>> &7ID: {ID_ORDER}",
    " ",
    "&f>> &7x: &c{X}",
    "&f>> &7y: &c{Y}",
    "&f>> &7z: &c{Z}",
    "&f>> &7Monde: &c{WORLD}",
    " ",
    "&f>> &7Rayon: &c{RADIUS}",
    "&f>> &7Quantité de particules: &c{PARTICLE_AMOUNT}",
    "&f>> &7",
    "&f>> &7Type de particule: &c{PARTICLE_TYPE}"
  ],
  "ERSTATS_MAP": "&6&lStatistiques personnelles sur les cartes",
  "ERSTATS_MAP_EACH": "&6>> {MAP_NAME} &9: {PLAYER_TIME} &9(#{PLAYER_RANK}) \n&6> &9(winrate: {WINRATE}%)",
  "CHANGEPAGE": "&7Cliquez ici pour changer de page",
  "CHANGEPAGERIGHT": "&9➡",
  "CHANGEPAGELEFT": "&c⬅",
  "ERTRAIN_MAP_INFO": [
    "&fVotre temps: &6{PLAYER_TIME}",
    "&fVotre rang: &6#{PLAYER_RANK}",
    "&fVotre taux de réussite: &6{WINRATE}%",
    " "
  ],
  "ERTRAIN_MAP_INFO_PLUS": [
    "",
    "&7Difficulté: {DIFFICULTY}",
    "&7Lap(s): &c{LAPS}",
    "",
    "&7Cliquez ici pour sélectionner cette carte"
  ],
  "ERTRAIN_MAP_INFO_TITLE": "&f{MAP_NAME}",
  "FORCE_KICK_VERSION_BELOW_19": true,
  "PLAYER_VERSION_BELOW_19": "&cVous n'avez pas la bonne version pour jouer à ce jeu.",
  "USAGE_ERSTATS_SHOW": [
    "&6&lStatistiques personnelles: {USERNAME}",
    "&7Courses jouées: &c{PLAYER_GAME_PLAYED_RACEMODE} ",
    "&7Courses gagnées: &c{PLAYER_GAME_WON_RACEMODE} &9(#{RANK_WON_RACEMODE}) &7({PERCENTAGE_WINRATE_RACEMODE}%)",
    "&7Grandprix a joué: &c{PLAYER_GAME_PLAYED_GRANDPRIX} ",
    "&7Grandprix gagné: &c{PLAYER_GAME_WON_GRANDPRIX} &9(#{RANK_WON_GRANDPRIX}) &7({PERCENTAGE_WINRATE_GRANDPRIX}%)",
    "&7Score: &c{SCORE_TOTAL} &9(#{RANK_SCORE_TOTAL})",
    "&6Carte préférée: &6{FAVORITE_MAP} &7&o(winrate: {FAVORITE_MAP_WINRATE}%)",
    "[HOVERMESSAGE_MAP_STATS]&9Statistiques personnelles sur les cartes &7&o(hover)"
  ],
  "HOLOGRAMS_PERSONALSTATS": [
    "&6&lStatistiques personnelles:",
    "&7Courses jouées: &c{PLAYER_GAME_PLAYED_RACEMODE} ",
    "&7Courses gagnées: &c{PLAYER_GAME_WON_RACEMODE} &9(#{RANK_WON_RACEMODE}) &7({PERCENTAGE_WINRATE_RACEMODE}%)",
    "&7Grandprix a joué: &c{PLAYER_GAME_PLAYED_GRANDPRIX} ",
    "&7Grandprix gagné: &c{PLAYER_GAME_WON_GRANDPRIX} &9(#{RANK_WON_GRANDPRIX}) &7({PERCENTAGE_WINRATE_GRANDPRIX}%)",
    "&7Score: &c{SCORE_TOTAL} &9(#{RANK_SCORE_TOTAL})",
    "&6Carte préférée: &6{FAVORITE_MAP} &7&o(winrate: {FAVORITE_MAP_WINRATE}%)"
  ],
  "MAP_INGAME_INFO_MENU_TITLE": "&fInformations sur les cartes",
  "MAP_INGAME_INFO_DESCRIPTION": [
    "&f{ORDER}. {MAP_NAME}",
    "&f-> Vos statistiques: {PLAYER_TIME},#{PLAYER_RANK} ({PLAYER_WINRATE}%)"
  ],
  "NOTENOUGH_MAP_HOSTCREATOR": "&cVous avez besoin d'au moins une carte pour créer un hôte.",
  "ONEGAME": false,
  "ONEGAME_AUTOJOINGAME": "",
  "ONEGAME_KICK_AFTER_GAME": true,
  "ONEGAME_LOBBYSERVER": "",
  "ONEGAME_REMOVEJOINQUITMESSAGES": true,
  "ONEGAME_MOTD_USE": false,
  "ONEGAME_MOTD": [
    "&f>> ElytraRacing: {STATE} &7[-] Carte: &6{MAP}",
    "§f>> &7Jouer à: §c{PLAYING} &7[-] Mode: {MODE_INFORMATION}"
  ],
  "ONEGAME_MOTD_RACEMODE_INFORMATION": "&aRacemode",
  "ONEGAME_MOTD_GRANDPRIX_INFORMATION": "&aGrandPrix &f{ROUND}/{ROUND_MAX}",
  "ONEGAME_MOTD_CHANGE_MAX_PLAYERS": true,
  "CHALLENGE_MAXGAME": false,
  "CHALLENGE_MAXGAME_PER_PLAYER": 10,
  "CHALLENGE_MAXGAME_COMPLETION_COMMAND": "[CONSOLE]/give {SELF_PLAYER} minecraft:cookie §%§[PLAYER]/tell {SELF_PLAYER} vous avez exécuté une commande",
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
  "world": "Monde",
  "id": "ID",
  "map": "Carte",
  "type": "Type",
  "normal": "normal",
  "ifnext": "SiProchain",
  "name": "Nom",
  "linkto": "LiéA",
  "rotations": "Rotations",
  "shape": "Forme",
  "radius": "Rayon",
  "valid": "Valable",
  "enabled": "Activé",
  "checkpoints": "Point(s) de contrôle",
  "ends": "Fin(s)",
  "aos": "Objet(s) supplémentaire(s)",
  "locations": "Sites",
  "start": "Début",
  "end": "Fin",
  "lobby": "Lobby",
  "boostMultiplier": "Multiplicateur de boost",
  "fireworks": "Feu d'artifice(s)",
  "cpangle": "Angle du point de contrôle",
  "laps": "Lap(s)",
  "lap": "lap",
  "lapMapLong": "Ici vous pouvez modifier le nombre de tours sur cette carte",
  "thereisare": "Il y a/sont",
  "inMapCp": "point(s) de contrôle dans la carte",
  "inMapEnd": "fin(s) dans la carte",
  "inMapAo": "objet(s) supplémentaire(s) dans la carte",
  "clickModificationCp": "Cliquez pour modifier un point de contrôle",
  "clickModificationEnd": "Cliquez pour modifier une extrémité",
  "clickModificationAo": "Cliquez pour modifier un objet supplémentaire",
  "currentDifficulty": "Difficulté actuelle de la carte",
  "clickDifficulty": "Cliquez ici pour modifier la difficulté",
  "respawnCpAngle": "Angle de respawn au point de contrôle",
  "respawnCpAngleL1": "Cliquez sur modifier l'angle utilisé pour la carte",
  "respawnCpAngleL2": "Information:",
  "PLAYER": "JOUEUR",
  "respawnCpAngleL3": "- Utilisez l'angle que le joueur avait lorsqu'il est entré dans le point de contrôle.",
  "NEXT_CHECKPOINT": "POINT DE CONTRÔLE SUIVANT",
  "Experimental": "Expérimental",
  "respawnCpAngleL4": "- Créez un angle pour rediriger le joueur vers le prochain point de contrôle.",
  "respawnCpAngleL5": "∞This feature is only working with maps that contains §c§l1 end and no linked checkpoints∞",
  "clickHereDefine": "Cliquez ici pour définir",
  "defaultParticleCP": "particule par défaut pour les points de contrôle",
  "defaultParticleEnd": "particule par défaut pour les extrémités",
  "defaultParticleAO": "particule par défaut pour les objets supplémentaires",
  "mapAvailableTraining": "Carte disponible pour la formation",
  "clickmapAvailableTraining": "Cliquez ici pour ajouter ou supprimer cette carte de l'ensemble de formation.",
  "dbUUID": "Base de données UUID",
  "clickDB": "Cliquez ici pour effacer les informations enregistrées dans la base de données",
  "podiumConfiguration": "Configuration du podium",
  "qPodium": "Le système de podium est-il activé pour cette carte ?",
  "qPodiumL1": "Commande pour ajouter un nouvel emplacement pour le podium:",
  "qPodiumL2": "/ermap map [map] podium setlocation <placement... 1, 2, 3..>",
  "qPodiumL3": "Commande permettant de téléporter un emplacement du podium:",
  "qPodiumL4": "/ermap map [map] podium tp <placement... 1, 2, 3..>",
  "startHost": "Démarrer un hôte",
  "createHostMap": "Cliquez ici pour créer un hôte en utilisant cette carte",
  "maxtimepossible": "Durée maximale possible",
  "difficulty": "Difficulté",
  "podium": "Podium",
  "particles": "Particules",
  "changeName": "Changement de nom",
  "confirm": "Confirmer",
  "cancel": "Annuler",
  "currentLaps": "Tour(s) actuel(s)",
  "currentMaxTime": "Temps max. actuel",
  "currentMaxTimeModification": "Ici, vous pouvez modifier le temps maximal possible sur la carte.",
  "minute": "minute",
  "divideMinutes": "Divisez par 2 les minutes actuelles",
  "doubleMinutes": "Doublement des minutes en cours",
  "firework": "feu d'artifice",
  "divideFirework": "Diviser par 2 feux d'artifice actuels",
  "doubleFirework": "Doublement des feux d'artifice actuels",
  "second": "deuxième",
  "divideSeconds": "Diviser par 2 les secondes actuelles",
  "doubleSeconds": "Double des secondes actuelles",
  "changeHologramName": "Changer le nom de l'hologramme",
  "cmdChangeHologramName": "/erconfig holograms setname [current_name] [new_name]",
  "changeMap": "Modifier la carte",
  "changeHologramMap": "Carte de changement associée à l'hologramme",
  "cmdChangeHologramMap": "/erconfig holograms setmap [hologram] [map]",
  "localisation": "Localisation",
  "leftTeleported": "Clic gauche pour être téléporté",
  "clickTeleported": "Cliquez pour être téléporté",
  "shiftclickDefineLocation": "Cliquez avec la touche Shift pour définir cet emplacement",
  "rightTeleported": "Clic droit pour être téléporté",
  "leftConfigure": "Cliquez à gauche pour configurer",
  "rightChangeLocation": "Cliquez à droite pour changer d'emplacement",
  "rightDefineLocation": "Clic droit pour définir l'emplacement",
  "refreshDisplay": "Rafraîchir l'affichage",
  "clickRefreshElement": "Cliquez ici pour rafraîchir les éléments affichés sur l'hologramme",
  "delete": "Supprimer",
  "personalMaps": "Cartes personnelles",
  "clickCreateNewHolograms": "Cliquez ici pour créer un nouvel hologramme de ce type",
  "personalStats": "Statistiques personnelles",
  "rankscore": "Rang score",
  "rankmap": "Carte de rang",
  "rankmapL1": "Vous devez définir une carte pour cet hologramme.",
  "rankmapL2": "/erconfig holograms setmap [hologram] [map]",
  "rankwonr": "Rang gagné racemode",
  "rankwong": "Rang gagné grandprix",
  "deleteHologram": "Cliquez ici pour supprimer cet hologramme",
  "currentParticle": "Particule actuelle",
  "currentParticleLongMap": "Vous pouvez voir ici le jeu de particules actuel pour cette carte.",
  "clickChangeParticle": "Cliquez ici pour changer la particule",
  "currentFireworkAmountMap": "Ici, vous pouvez modifier le nombre de feux d'artifice sur la carte.",
  "clickChangePage": "Cliquez ici pour changer de page",
  "particleAmount": "Quantité de particules",
  "information": "Information",
  "clickDefineParticleObject": "Cliquez ici pour définir la particule de l'objet",
  "currentLocation": "Localisation actuelle",
  "currentParticleAmount": "Quantité actuelle de particules",
  "particleAmountLong": "Vous pouvez ici modifier la quantité de particules affichée",
  "currentFireworksAmount": "Quantité actuelle de feux d'artifice",
  "fireworksAmountLong": "Ici, vous pouvez modifier le nombre de feux d'artifice donnés par cet objet.",
  "leftclick": "Clic gauche",
  "shiftleftclick": "Shift clic gauche",
  "rightclick": "Clic droit",
  "shiftrightclick": "Shift clic droit",
  "currentRadius": "Rayon actuel",
  "radiusmodification": "Ici, vous pouvez modifier le rayon",
  "helpMessage": "Message d'aide",
  "helpMessageL1": "Cliquez ici pour afficher la liste des commandes de ",
  "helpMessageL2": "cet objet qui complétera automatiquement les arguments",
  "helpMessageL2Map": "cette carte qui complétera automatiquement les arguments",
  "currentBoostMultiplier": "Multiplicateur de courant",
  "boostMultiplierModification": "Ici, vous pouvez modifier le multiplicateur de boost appliqué au joueur.",
  "closeMenu": "Cliquez ici pour fermer ce menu",
  "linkWithYou": "Associez cet objet à vous",
  "linkModificationL1": "Cliquez ici pour associer cet objet à vous et pouvoir le modifier.",
  "linkModificationL2": "Grâce à ce lien, vous pourrez",
  "linkModificationL3": "pour modifier cet objet en utilisant les éléments",
  "linkModificationL4": "Cliquez à gauche pour lier l'objet.",
  "linkModificationL5": "Cliquez à droite pour obtenir des éléments",
  "linkModificationL6": "Si vous êtes trop loin de l'objet, il sera",
  "linkModificationL7": "vous déverrouiller automatiquement.",
  "clickDelete": "Cliquez ici pour supprimer cet objet.",
  "informationConfirmationDeleteAO": "Supprimer un objet supplémentaire",
  "informationConfirmationDeleteCP": "Supprimer un point de contrôle",
  "informationConfirmationDeleteEND": "Supprimer une fin",
  "createNew": "Créer un nouveau",
  "clickCreateNew": "Cliquez ici pour créer un nouveau",
  "clickCreateNewCP": "point de contrôle à votre emplacement",
  "clickCreateNewAO": "objet supplémentaire à votre emplacement",
  "clickCreateNewEnd": "fin à votre emplacement",
  "isLocationLobby": "L'emplacement du lobby est-il défini ?",
  "isLocationStart": "Le lieu de départ est-il défini ?",
  "isLocationEnd": "L'emplacement final est-il défini ?",
  "locationLobby": "Emplacement du hall d'entrée",
  "locationStart": "Lieu de départ",
  "locationEnd": "Emplacement final",
  "specAndWalls": "Spec et murs",
  "qspecAndWalls": "Spec peut passer à travers les murs ?",
  "clickChangeValue": "Cliquez ici pour modifier la valeur",
  "showMap": "Afficher la carte",
  "clickShowMap": "Cliquez ici pour afficher/cacher cette carte",
  "currentParticleSet": "Ici vous pouvez voir le jeu de particules actuel",
  "pageHologramPage": "Configuration de l'hologramme",
  "pageAOCP": "Liste d'objets supplémentaires",
  "pageAOP": "Configuration supplémentaire des objets",
  "pageConfirmationDeleteObject": "Confirmation de la suppression",
  "pageCPCP": "Liste des points de contrôle",
  "pageCPP": "Configuration des points de contrôle",
  "pageECP": "Liste des extrémités",
  "pageEP": "Configuration finale",
  "pageHCP": "Liste des hologrammes",
  "pageMCP": "Liste des cartes",
  "pageMS": "Paramètres de la carte :"
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
      "HOST_SPECTATOR": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "Temps restant: &c{TIME_LEFT}",
          "&fJoueur(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "",
          "&e1er - {RACE_RANK_PLAYER_1}",
          "&72e - {RACE_RANK_PLAYER_2}",
          "&63e - {RACE_RANK_PLAYER_3}",
          "&f4e - {RACE_RANK_PLAYER_4}",
          "&f5e - {RACE_RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "WAITING": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&fJoueur(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fCarte: {CURRENT_MAP}",
          "&fMode: &aRace",
          "",
          "&cIl manque {NEEDED_PLAYER} joueur(s) pour commencer",
          "",
          "{LINK}"
        ]
      },
      "FINISHED": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&e1er - {RANK_PLAYER_1}",
          "&72e - {RANK_PLAYER_2}",
          "&63e - {RANK_PLAYER_3}",
          "Votre rang: {SELF_RANK_PLAYER}",
          "",
          "{LINK}"
        ]
      },
      "SPECTATOR": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "Temps restant: &c{TIME_LEFT}",
          "&fJoueur(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "",
          "&e1er - {RACE_RANK_PLAYER_1}",
          "&72e - {RACE_RANK_PLAYER_2}",
          "&63e - {RACE_RANK_PLAYER_3}",
          "&f4e - {RACE_RANK_PLAYER_4}",
          "&f5e - {RACE_RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "HOST_STARTING": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&fJoueur(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fCarte: {CURRENT_MAP}",
          "&fMode: &aRace",
          "",
          "Hôte: {HOST}",
          "&cCommence dans {STARTING_COUNTDOWN} seconde(s)",
          "",
          "{LINK}"
        ]
      },
      "HOST_STARTED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "Temps restant: &c{TIME_LEFT}",
          "&fJoueur(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "",
          "&e1er - {RACE_RANK_PLAYER_1}",
          "&72e - {RACE_RANK_PLAYER_2}",
          "&63e - {RACE_RANK_PLAYER_3}",
          "Votre rang: {SELF_RACE_RANK_PLAYER}",
          "",
          "Checkpoints: &6{SELF_CPS}/{MAX_CPS}",
          "Tours: &6{SELF_LAPS}/{MAX_LAPS}",
          "",
          "{LINK}"
        ]
      },
      "HOST_SPECTATOR_FINISHED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&e1er - {RANK_PLAYER_1}",
          "&72e - {RANK_PLAYER_2}",
          "&63e - {RANK_PLAYER_3}",
          "&f4e - {RANK_PLAYER_4}",
          "&f5e - {RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "STARTED": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "Temps restant: &c{TIME_LEFT}",
          "&fJoueur(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "",
          "&e1er - {RACE_RANK_PLAYER_1}",
          "&72e - {RACE_RANK_PLAYER_2}",
          "&63e - {RACE_RANK_PLAYER_3}",
          "Votre rang: {SELF_RACE_RANK_PLAYER}",
          "",
          "Checkpoints: &6{SELF_CPS}/{MAX_CPS}",
          "Tours: &6{SELF_LAPS}/{MAX_LAPS}",
          "",
          "{LINK}"
        ]
      },
      "STARTING": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&fJoueur(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fCarte: {CURRENT_MAP}",
          "&fMode: &aRace",
          "",
          "&cCommence dans {STARTING_COUNTDOWN} seconde(s)",
          "",
          "{LINK}"
        ]
      },
      "SPECTATOR_FINISHED": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&e1er - {RANK_PLAYER_1}",
          "&72e - {RANK_PLAYER_2}",
          "&63e - {RANK_PLAYER_3}",
          "&f4e - {RANK_PLAYER_4}",
          "&f5e - {RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "HOST_WAITING": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&fJoueur(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fCarte: {CURRENT_MAP}",
          "&fMode: &aRace",
          "",
          "Hôte: {HOST}",
          "",
          "{LINK}"
        ]
      },
      "HOST_FINISHED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&e1er - {RANK_PLAYER_1}",
          "&72e - {RANK_PLAYER_2}",
          "&63e - {RANK_PLAYER_3}",
          "Votre rang: {SELF_RANK_PLAYER}",
          "",
          "{LINK}"
        ]
      }
    }
  },
  "GrandPrix": {
    "perState": {
      "BETWEENROUND": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "Carte suivante: {CURRENT_MAP}",
          "{CURRENT_MAP_DIFFICULTY}",
          "&6PB: {SELF_MAP_PB}",
          "",
          "&e1er - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72e - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63e - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "Votre rang: {SELF_RANK_PLAYER}",
          "Votre score: {SELF_RANK_PLAYER_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "HOST_SPECTATOR": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "Temps restant: &c{TIME_LEFT}",
          "&fJoueur(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "Round: {CURRENT_ROUND}/{MAX_ROUND}",
          "",
          "&e1er - {RACE_RANK_PLAYER_1}",
          "&72e - {RACE_RANK_PLAYER_2}",
          "&63e - {RACE_RANK_PLAYER_3}",
          "&f4e - {RACE_RANK_PLAYER_4}",
          "&f5e - {RACE_RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "FINISHED": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&e1er - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72e - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63e - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "Votre rang: {SELF_RANK_PLAYER}",
          "Votre score: {SELF_RANK_PLAYER_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "HOST_SPECTATOR_FINISHED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&e1er - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72e - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63e - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "&f4e - {RANK_PLAYER_4} - {RANK_PLAYER_4_SCORE}",
          "&f5e - {RANK_PLAYER_5} - {RANK_PLAYER_5_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "STARTED": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "Temps restant: &c{TIME_LEFT}",
          "&fJoueur(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "Round: {CURRENT_ROUND}/{MAX_ROUND}",
          "",
          "&e1er - {RACE_RANK_PLAYER_1}",
          "&72e - {RACE_RANK_PLAYER_2}",
          "&63e - {RACE_RANK_PLAYER_3}",
          "Votre rang: {SELF_RACE_RANK_PLAYER}",
          "",
          "Checkpoints: &6{SELF_CPS}/{MAX_CPS}",
          "Tours: &6{SELF_LAPS}/{MAX_LAPS}",
          "",
          "{LINK}"
        ]
      },
      "STARTING": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&fJoueur(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fCarte: {CURRENT_MAP}",
          "&fMode: &aGrandPrix",
          "Round: 1/{MAX_ROUND}",
          "",
          "&cCommence dans {STARTING_COUNTDOWN} seconde(s)",
          "",
          "{LINK}"
        ]
      },
      "SPECTATOR_FINISHED": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&e1er - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72e - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63e - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "&f4e - {RANK_PLAYER_4} - {RANK_PLAYER_4_SCORE}",
          "&f5e - {RANK_PLAYER_5} - {RANK_PLAYER_5_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "HOST_BETWEENROUND": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "Carte suivante: {CURRENT_MAP}",
          "{CURRENT_MAP_DIFFICULTY}",
          "&6PB: {SELF_MAP_PB}",
          "",
          "&e1er - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72e - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63e - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "Votre rang: {SELF_RANK_PLAYER}",
          "Votre score: {SELF_RANK_PLAYER_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "HOST_WAITING": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&fJoueur(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fCarte: {CURRENT_MAP}",
          "&fMode: &aGrandPrix",
          "Round: 1/{MAX_ROUND}",
          "",
          "Hôte: {HOST}",
          "",
          "{LINK}"
        ]
      },
      "SPECTATOR_BETWEENROUND": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "Carte suivante: {CURRENT_MAP}",
          "{CURRENT_MAP_DIFFICULTY}",
          "&6PB: {SELF_MAP_PB}",
          "",
          "&e1er - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72e - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63e - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "&f4e - {RANK_PLAYER_4} - {RANK_PLAYER_4_SCORE}",
          "&f5e - {RANK_PLAYER_5} - {RANK_PLAYER_5_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "HOST_FINISHED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&e1er - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72e - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63e - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "Votre rang: {SELF_RANK_PLAYER}",
          "Votre score: {SELF_RANK_PLAYER_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "WAITING": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "&fJoueur(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fCarte: {CURRENT_MAP}",
          "&fMode: &aGrandPrix",
          "Round: 1/{MAX_ROUND}",
          "",
          "&cIl manque {NEEDED_PLAYER} joueur(s) pour commencer",
          "",
          "{LINK}"
        ]
      },
      "SPECTATOR": {
        "title": "ElytraRacing",
        "lines": [
          "",
          "Temps restant: &c{TIME_LEFT}",
          "&fJoueur(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "Round: {CURRENT_ROUND}/{MAX_ROUND}",
          "",
          "&e1er - {RACE_RANK_PLAYER_1}",
          "&72e - {RACE_RANK_PLAYER_2}",
          "&63e - {RACE_RANK_PLAYER_3}",
          "&f4e - {RACE_RANK_PLAYER_4}",
          "&f5e - {RACE_RANK_PLAYER_5}",
          "",
          "{LINK}"
        ]
      },
      "HOST_STARTING": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "&fJoueur(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "&fCarte: {CURRENT_MAP}",
          "&fMode: &aGrandPrix",
          "Round: 1/{MAX_ROUND}",
          "",
          "Hôte: {HOST}",
          "&cCommence dans {STARTING_COUNTDOWN} seconde(s)",
          "",
          "{LINK}"
        ]
      },
      "HOST_SPECTATOR_BETWEENROUND": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "Carte suivante: {CURRENT_MAP}",
          "{CURRENT_MAP_DIFFICULTY}",
          "&6PB: {SELF_MAP_PB}",
          "",
          "&e1er - {RANK_PLAYER_1} - {RANK_PLAYER_1_SCORE}",
          "&72e - {RANK_PLAYER_2} - {RANK_PLAYER_2_SCORE}",
          "&63e - {RANK_PLAYER_3} - {RANK_PLAYER_3_SCORE}",
          "&f4e - {RANK_PLAYER_4} - {RANK_PLAYER_4_SCORE}",
          "&f5e - {RANK_PLAYER_5} - {RANK_PLAYER_5_SCORE}",
          "",
          "{LINK}"
        ]
      },
      "HOST_STARTED": {
        "title": "{HOST_NAME}",
        "lines": [
          "",
          "Temps restant: &c{TIME_LEFT}",
          "&fJoueur(s): {CURRENT_PLAYER}/{MAX_PLAYER}",
          "Round: {CURRENT_ROUND}/{MAX_ROUND}",
          "",
          "&e1er - {RACE_RANK_PLAYER_1}",
          "&72e - {RACE_RANK_PLAYER_2}",
          "&63e - {RACE_RANK_PLAYER_3}",
          "Votre rang: {SELF_RACE_RANK_PLAYER}",
          "",
          "Checkpoints: &6{SELF_CPS}/{MAX_CPS}",
          "Tours: &6{SELF_LAPS}/{MAX_LAPS}",
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
          "WR par: {MAP_WR_PLAYER}",
          "&6Temps: &c{MAP_WR_TIME}",
          "",
          "Temps restant: &c{TIME_LEFT}",
          "&fDifficulté: {CURRENT_MAP_DIFFICULTY}",
          "Checkpoints: &6{SELF_CPS}/{MAX_CPS}",
          "Tours: &6{SELF_LAPS}/{MAX_LAPS}",
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
  "GUI_PARTICLE_TITLE": "Sélecteur de particules",
  "GUI_ITEM_PARTICLE_TITLE": "&f{PARTICLE_NAME}",
  "GUI_ITEM_PARTICLE_TITLE_SELECTED": "&a{PARTICLE_NAME}",
  "GUI_NO_PARTICLE": "None",
  "GUI_DISABLE_OTHERS_PARTICLES_UNSELECTED": "&fDésactiver les autres particules",
  "GUI_DISABLE_OTHERS_PARTICLES_SELECTED": "&fDésactiver les autres particules",
  "GUI_DISABLE_OTHERS_PARTICLES_LORE_SELECTED": "&f-> Actuellement: &a✓",
  "GUI_DISABLE_OTHERS_PARTICLES_LORE_UNSELECTED": "&f-> Actuellement: &c❌",
  "MSG_SAVE_SUCCESSFUL": "&fLes modifications ont été enregistrés avec succès",
  "GUI_CLICKCHANGE": "Cliquez ici pour changer de page",
  "GUI_ENCHANT_SELECTED": true,
  "particles": [
    {
      "name": "CercleVert",
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
      "name": "CercleArcEnCielRotatif",
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
      "name": "PointArcEnCiel",
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
      "name": "PointRouge",
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
      "name": "VagueHorizontale",
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
      "name": "PointOndulantVerticalement",
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
      "name": "TubeArcEnCiel",
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
