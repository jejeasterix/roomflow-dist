# roomflow-dist

Canal de **distribution et de mises à jour automatiques** de l'application Windows **RoomFlow**
(installateurs [Velopack](https://velopack.io)).

> Le **code source** est privé : il vit dans `jejeasterix/roomflow2`. Ce dépôt ne contient **que**
> les installateurs publiés (GitHub Releases), pour que l'application puisse télécharger ses mises
> à jour sans authentification.

## Installation / mise à jour

- **Nouvelle installation** : télécharger `RoomFlow-win-Setup.exe` depuis la
  [dernière release](https://github.com/jejeasterix/roomflow-dist/releases) et l'exécuter.
  SmartScreen affichera un avertissement « éditeur inconnu » (application non signée) →
  *Informations complémentaires* → *Exécuter quand même*.
- **Mise à jour** : automatique. L'application interroge ce dépôt à chaque démarrage et propose de
  redémarrer quand une nouvelle version est disponible.

Documentation utilisateur : **https://docs.roomflow.fr**

Les releases sont produites automatiquement par le workflow `release.yml` du dépôt source
(sur tag `v*`).

## ⚠️ Si vous aviez installé la v1.0.0

La v1.0.1 a renommé le paquet : `RoomFlow2` est devenu **`RoomFlow`**, et ce dépôt est passé de
`roomflow2-dist` à `roomflow-dist`. Le « 2 » désignait une réécriture interne, sans intérêt pour
l'utilisateur.

Ce nom est l'identité de l'application pour le système de mise à jour : **une installation de la
v1.0.0 ne verra plus jamais de mise à jour.** Il faut la désinstaller (Paramètres Windows →
Applications → RoomFlow2), puis réinstaller depuis la dernière release. Les deux versions peuvent
coexister sans se gêner, dans deux dossiers distincts — mais autant ne garder que la nouvelle.
