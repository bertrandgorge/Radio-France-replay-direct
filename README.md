# Fip et France Musique

Petit projet pour avoir un player léger pour Fip et France Musique.

- Très léger, pas de pub, pas d'éléments superfétatoires
- Compatible chromecast (flux aac hifi)
- Flux hifi HLS sur le navigateur
- Compatible avec les boutons pause/play/next/prev bluetooth (dans la voiture ou sur le casque), permet de passer d'une station à l'autre
- Fonctionne sur téléphone, peut être enregistré comme icone sur l'écran d'accueil pour remplacer complètement l'application Radio France
- Possibilité de démarrer sur une radio en particulier en ajoutant ?radio=fiprock par exemple
- Utilise l'API Radio France pour récupérer les titres des morceaux en cours (sur un intervale de 30s pour ne pas être trop lourd)

Utilise https://github.com/castjs/castjs pour la partie ChromeCast et https://github.com/video-dev/hls.js pour HLS
