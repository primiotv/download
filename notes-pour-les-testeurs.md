# Primio · Notes pour les testeurs

### Bienvenue dans le test de Primio

Primio est un lecteur pour la télévision, les films et les séries. Primio ne fournit aucun contenu : vous utilisez
votre propre source (liste M3U ou accès Xtream de votre fournisseur).

**Durée :** la version de test fonctionne 7 jours à compter du premier démarrage. La veille de la fin, Primio vous
prévient (« Cette version de test expire demain. ») ; ensuite, Primio indique seulement où trouver la nouvelle
version et ne lit plus rien. Vos sources, favoris et paramètres sont conservés : installez simplement la nouvelle version
par-dessus (voir « Nouvelle version »).

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

### Appareils

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

Au premier démarrage, Primio demande s’il peut envoyer un rapport en cas de plantage. Si vous l’autorisez, seuls
l’erreur, le modèle de l’appareil et les versions d’Android et de l’application sont envoyés à un service situé dans
l’UE (Sentry). Vos identifiants, les adresses des serveurs et votre adresse IP ne sont jamais envoyés. Vous pouvez
modifier ce choix à tout moment dans Paramètres → Apparence → « Envoyer les rapports de plantage ». Sans
autorisation, Primio n’envoie rien ; les plantages figurent alors uniquement dans le rapport de diagnostic que vous
exportez vous-même.
