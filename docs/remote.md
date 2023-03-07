---
tags:
  - SI
  - STI2D
  - Python
---

# Commande à distance de robots

## Utilisation

### Robot Sphero

Le robot [Sphero](https://sphero.com/), un petit robot sous forme de boule.

### Robot Dobot

Le bras articulé ["Dobot Magician"](https://robotdobot.com/en/dobot-magician).

## Partie enseignant

### Robot Sphero

La communication avec le robot Sphero est réalisée via bluetooth. Pour lancer le serveur qui communique avec le robot plusieurs options sont possibles :

 * utiliser un raspberry PI préconfiguré.
 * lancer le serveur sur un ordinateur avec bluetooth. **Attention, pour le moment le serveur ne fonctionne pas avec windows.**

#### Lancement manuel du server

Il faut récupérer le programme Python du serveur qui est disponible sur le dépôt Github : [gbourel/remote-robots](https://github.com/gbourel/remote-robots).

Dans le répertoire du projet, exécuter les commandes :

```sh
cd spheroCmd
python3 server.py
```

### Robot Dobot

Le robot Dobot doit être connecté en USB à l'ordinateur serveur. **Testé uniquement avec Linux (ubuntu 20.04).**
