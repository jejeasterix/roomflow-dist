# roomflow-dist

Canal de **distribution et de mises à jour automatiques** de la coque native **RoomFlow 2** (installateurs [Velopack](https://velopack.io)).

> Le **code source** est privé : il vit dans `jejeasterix/roomflow2`. Ce dépôt ne contient **que** les installateurs publiés (GitHub Releases), pour que l'application puisse télécharger ses mises à jour sans authentification.

## Installation / mise à jour

- **Nouvelle installation** : télécharger `RoomFlow2-win-Setup.exe` depuis la [dernière release](https://github.com/jejeasterix/roomflow2-dist/releases) et l'exécuter. SmartScreen affichera un avertissement « éditeur inconnu » (app non signée) → *Informations complémentaires* → *Exécuter quand même*.
- **Mise à jour** : automatique. L'app interroge ce dépôt à chaque démarrage et propose de redémarrer quand une nouvelle version est disponible.

Les releases sont produites automatiquement par le workflow `release.yml` du dépôt source (sur tag `v*`).
