Accélérateur de bavardages pour les Éditions améliorées
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Version        : 1.6
Auteur         : Argent77

Téléchargement : https://github.com/Argent77/A7-BanterAccelerator/releases/latest
Discussion     : https://forums.beamdog.com/discussion/64551/mod-banter-accelerator-for-enhanced-edition-games


Généralités
~~~~~~~~~~~

Ce mod vous permet de définir le rythme des bavardages entre les personnages de votre équipe. 
Vous pouvez le choisir dans une liste pré-établie ou le définir vous-même.

Il est compatible avec tous les jeux Enhanced Edition.


Installation
~~~~~~~~~~~~

Il s'agit d'un mod WeiDU, donc très facile à installer. Il suffit de décompresser l'archive 
téléchargée dans votre répertoire de jeu et de lancer "setup-A7-BanterAccelerator.exe".

Les joueurs avertis et versés dans le modding peuvent se passer d'installer ce mod en copiant 
simplement un fichier gérant le rythme de bavardage (banttimg.2da) dans le jeu. Ces fichiers 
se trouvent dans le répertoire "A7-BanterAccelerator/override". Chacun d'eux se trouve dans un 
sous-répertoire dont le nom indique la fréquence en "ticks" ("instants" de 1/15e de seconde) 
et la probabilité (en pourcentage) de lancer un bavardage. 
Par exemple, le sous-répertoire "450_25" correspond à un intervalle de 450 ticks entre chaque 
bavardage et une probabilité de 25 % de chances d'initier les conversations.
Il suffit donc de copier le fichier banttimg.2da dans le répertoire "override" du jeu, à créer 
s'il n'existe pas.

Il n'est pas nécessaire de lancer une nouvelle partie pour que les modifications prennent effet.


Composants
~~~~~~~~~~

Ce mod ne comporte qu'un seul composant "Accélérateur de bavardages" offrant plusieurs paramétrages 
prédéfinis, ainsi qu'une option "Choisissez vous-même le rythme des bavardages" vous permettant de 
définir la fréquence et la probabilité de lancement des discussions.


Credits
~~~~~~~

Coding and testing: Argent77

French translation: Gwendolyne

Brazilian Portuguese translation: Felipe


Copyright Notice
~~~~~~~~~~~~~~~~

The mod "Banter Accelerator for Enhanced Edition games" is licensed under the "Creative Commons 
Attribution-ShareAlike 4.0 International License" (http://creativecommons.org/licenses/by-sa/4.0/).


History
~~~~~~~

1.6
- Added Simplified Chinese translation (thanks MephistoSatanDevil)

1.5
- Added Brazilian Portuguese translation (thanks Felipe)
- Added component labels for Project Infinity

1.4
- Added Project Infinity metadata
- Added German translation for WeiDU prompts
- Added WeiDU SUPPORT information
- Fixed potential display issues with component names in WeiDU.log and Project Infinity

1.3
- Made install options more user-friendly by replacing ticks with seconds

1.2
- Added French translation (thanks Gwendolyne)
- Added German translation

1.1
- Changed "seconds" to "ticks"
- Redesigned available presets

1.0
- Initial release
