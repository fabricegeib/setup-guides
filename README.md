---
description: Installation and configuration
---

# VPS - Debian 9

## Se connecter en ssh

Ouvrez votre terminal et taper la commande suivante :

```
$ ssh root@IPv4_de_votre_VPS
```

{% hint style="info" %}
 Super-powers are granted randomly so please submit an issue if you're not happy with yours.
{% endhint %}

La première fois il faut accepter le certificat ssh

```
// Ain't no code for that yet, sorry
echo 'You got to trust me on this, I saved the world'
```

## Installer les mises à jours de Debian

```text
apt update
apt upgrade
apt dist-upgrade
```

