# Primio · Notes pour les testeurs

### Bienvenue dans le test de Primio

Primio est un lecteur pour la télévision, les films et les séries. Primio ne fournit aucun contenu : vous utilisez
votre propre source (liste M3U ou accès Xtream de votre fournisseur).

**Durée :** la version de test fonctionne pendant une durée limitée. Primio vous prévient à temps ; ensuite, Primio
indique seulement où trouver la nouvelle version et ne lit plus rien. Vos sources, favoris et paramètres sont
conservés : installez simplement la nouvelle version par-dessus (voir « Nouvelle version »).

### Installation

1. Installez l’application **Downloader** sur le téléviseur.
2. **Fire TV :** autorisez d’abord Downloader à installer des applications — Paramètres → Ma Fire TV → Options pour
   les développeurs (Developer Options) → Applications de sources inconnues (Apps from Unknown Sources). Si ces options
   n’apparaissent pas : Paramètres → Ma Fire TV → À propos de, puis appuyez sept fois sur la première entrée portant
   le nom de l’appareil (Your TV) ; elles apparaissent ensuite. Sur les téléviseurs Fire TV, « Ma Fire TV »
   s’appelle « Appareil et logiciel ».
   **Google TV :** Paramètres → Applications → Sécurité et restrictions → Sources inconnues (Unknown sources), puis
   autorisez Downloader.
3. **Application Downloader : code 9316224** à saisir. Ou saisissez cette adresse dans Downloader :
   `https://github.com/primiotv/download/releases/latest/download/primio.apk`. Installez ensuite.

### Nouvelle version

Installez la nouvelle version **par-dessus l’ancienne** (comme ci-dessus, avec le même code 9316224), **sans** désinstaller
au préalable. Vos sources, favoris et enregistrements sont ainsi conservés.

À partir de cette version, Primio vous signale lui-même les nouvelles versions. Choisissez alors « Mettre à jour » ;
vos sources et paramètres sont conservés. Si ce n’est pas possible, Primio affiche le code Downloader 9316224.

Lors de la première mise à jour, Android demande si Primio peut installer des applications. Si vous l’autorisez, Android peut fermer Primio. Rouvrez alors Primio : la fenêtre de mise à jour revient d’elle-même, au plus tard après environ une minute. Choisissez à nouveau « Mettre à jour ».

### Appareils

**Uniquement pour les appareils TV avec télécommande. Les smartphones et les tablettes ne sont pas encore pris en charge.**

Primio nécessite **Android TV / Google TV à partir d’Android 8.0** ou **Fire TV à partir de Fire OS 7**. Noms selon les
fiches techniques d’Amazon (developer.amazon.com, état au 16/10) :

- **Compatibles :** Fire TV Stick (3e génération, 2020), Fire TV Stick Lite (2020), Fire TV Stick HD avec
  télécommande vocale Alexa (2024), Fire TV Stick 4K (2e génération, 2023), Fire TV Stick 4K Max (2021 et 2023),
  Fire TV Stick 4K Plus (2025), Fire TV Cube (2e génération, 2019, et 3e génération, 2022).
- **Non compatibles :** Fire TV Stick 4K (1re génération, 2018), Fire TV Stick jusqu’en 2019 (1re et 2e génération,
  Basic Edition), Fire TV Cube (1re génération, 2018) et les boîtiers Fire TV de 2014 à 2017 (Fire OS 5 ou 6) ; ainsi
  que tous les appareils sous **Vega OS** : Fire TV Stick 4K Select (2025), Fire TV Stick HD (2026) et Fire TV Stick 4K
  (3e génération, 2026).
- Attention : le Fire TV Stick HD existe sous Fire OS 7 (2024, compatible) et sous Vega OS (2026, non compatible).
- Votre modèle et votre version de Fire OS se trouvent dans Paramètres → Ma Fire TV → À propos de.

### Bon à savoir

- **La première importation charge tout.** Après l’ajout d’une source, Primio charge entièrement les chaînes, les
  films, les séries et le programme TV ; la page affiche la progression. Selon le fournisseur, cela prend quelques
  minutes.
- **La recherche trouve les débuts de mots.** «  Tat  » trouve «  Tatort  », «  ort  » ne le trouve pas.
- **Les enregistrements sont stockés dans la mémoire de l’application et sont supprimés lors de la désinstallation.**
  Installez donc toujours les nouvelles versions par-dessus (voir «  Nouvelle version  »).
- **Si votre accès n’autorise qu’une seule connexion simultanée, ne changez pas de chaîne pendant un enregistrement.**
  Sinon, l’enregistrement peut s’interrompre.
- **Sur certains appareils sous Android 14, les enregistrements programmés ne démarrent de façon fiable que si
  Primio est ouvert.**
- **Le nom, le serveur, l’utilisateur ou le mot de passe de votre source** se modifient dans Paramètres → Sources →
  « Modifier » → « Nom et accès ». Primio vérifie la connexion avant d’enregistrer.
- **Sur la page « Nom et accès », votre mot de passe est affiché en clair. N’en envoyez pas de photo, s’il vous
  plaît.**
- Tout se commande avec la télécommande : flèches, OK, Retour. Un appui long sur OK ouvre un menu à de nombreux endroits.
- **L’image saccade dans les scènes rapides ?** Réglez la fréquence d’affichage de votre boîtier sur 50 Hz dans
  ses paramètres, par exemple 1080p 50 Hz ou 4K 50 Hz.
- **Mon Primio :** En haut à gauche, avant « Accueil ». On y trouve Rappels, Ma liste, Historique et Listes de
  favoris, avec « Changer de profil » en haut de la colonne. Ces éléments ne sont plus dans les Paramètres. Pour
  effacer l’historique : Mon Primio › Historique.
- **Listes de favoris :** Créez une nouvelle liste dans Mon Primio › Listes de favoris › « Nouvelle liste » ;
  c’est aussi là que se gèrent toutes les listes. Dans le lecteur, OK sur « Favori » ouvre toujours le choix des
  listes, même avec une seule liste, avec « Nouvelle liste… ». Dans TV en direct : maintenez OK sur une chaîne ›
  « Listes de favoris », avec les listes et « Nouvelle liste… ».
- **Couleur du profil :** Dans le profil principal, Paramètres › Profils › « Gérer les profils » › « Modifier »
  sur votre profil › « Changer de couleur » ; dans un profil sans gestion, Paramètres › Profils › « Modifier mon
  profil » › « Changer de couleur ». La couleur s’applique aussitôt, aussi à « Mon Primio » en haut à gauche. Un
  nouveau profil reçoit sa couleur dès sa création.
- **Cadres :** Dans le lecteur et dans les fenêtres des Paramètres, les boutons et le cadre autour de l’élément
  choisi ne sont plus coupés. Si vous voyez encore quelque chose de coupé, dites-nous où.
- **Plein écran depuis une liste :** Si vous lancez une chaîne depuis une liste de favoris, CH+ et CH−, la liste
  des chaînes (Gauche) et Retour restent dans cette liste.
- **Groupe de la chaîne :** Sur la page d’une liste, dans « Ajouter des chaînes » et dans le lecteur, le groupe
  s’affiche à côté de la chaîne ; deux chaînes du même nom se distinguent ainsi.
- **Déplacer :** Dans TV en direct (maintenez OK sur une chaîne › « Position et numéro » › « Déplacer »), la chaîne
  passe de nouveau aussitôt à sa nouvelle place ; dans la dernière version, cela prenait quelques secondes ou ne
  marchait pas. « Rétablir l’ordre de la source » (maintenez OK sur un groupe) s’applique aussi aussitôt.
- **Cadre de sélection :** Au bord d’une liste, le cadre autour de l’élément choisi n’est plus coupé.
- **Retour après une pause :** Si vous étiez absent moins de 15 minutes (écran d’accueil du boîtier, veille), Primio
  reprend là où vous étiez, sauf si le boîtier a fermé Primio entre-temps ; Primio redémarre alors. Le choix du
  profil, le code PIN et l’écran de démarrage ne reviennent qu’après une pause plus longue.
- **Les paramètres s’appliquent aussitôt :** Chaque modification prend effet immédiatement.

### Que signaler et comment

Signalez tout ce que vous remarquez : erreurs, saccades, temps d’attente, textes mal adaptés, et ce qui vous manque.

1. **Ce que vous avez fait** (p. ex. «  TV en direct, changement de groupe, puis deux fois chaîne suivante  »).
2. **Ce que vous attendiez** et **ce qui s’est passé**.
3. **L’heure**, approximative suffit.
4. **L’appareil** (modèle) et la **version de Primio** (Paramètres → Expert → Diagnostic).
5. Si possible le **rapport de diagnostic** : Paramètres → en haut «  Expert  » → Diagnostic → «  Exporter en texte  ». Il
   retire les adresses, noms de serveurs et identifiants avant l’export. Envoyez-le tout de même uniquement au contact
   ci-dessous, pas dans un groupe public.

N’envoyez **pas** vos identifiants, adresses de listes ou photos montrant vos identifiants.

Contact : info@primio.tv

### Une question : menu en haut ou à gauche ?

Primio affiche le menu principal (Accueil, TV en direct, Guide TV, Replay, Films, Séries, Enregistrements) sous forme de
barre **en haut**. D’autres applications le placent **à gauche**. Que préférez-vous, et pourquoi ?

### Données envoyées en cas de plantage

**Au premier démarrage, Primio demande si des rapports de plantage et des statistiques d’utilisation peuvent être envoyés ; les deux sont facultatifs et modifiables dans les paramètres.**

Au premier démarrage, Primio demande s’il peut envoyer un rapport en cas de plantage. Si vous l’autorisez, seuls
l’erreur, le modèle de l’appareil et les versions d’Android et de l’application sont envoyés à un service situé dans
l’UE (Sentry). Vos identifiants, les adresses des serveurs et votre adresse IP ne sont jamais envoyés. Vous pouvez
modifier ce choix à tout moment dans Paramètres → Données de diagnostic. Sans
autorisation, Primio n’envoie rien ; les plantages figurent alors uniquement dans le rapport de diagnostic que vous
exportez vous-même.
