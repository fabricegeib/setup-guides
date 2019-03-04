# Installation

## Se connecter en ssh

Ouvrez votre terminal et taper la commande suivante :

```
ssh root@IPv4_de_votre_VPS
```

Installer les mises à jours de Debian :

```text
apt update
apt upgrade
apt dist-upgrade
```

## Créer un utilisateur

Taper la commande suivante dans le terminal  :

{% hint style="info" %}
Remplacer mynewuser par le nom d'utilisateur souhaiter
{% endhint %}

```
adduser mynewuser
```

Ajouter ce nouveau compte utilisateur au groupe "sudo" :

```
usermod -aG sudo mynewuser
```

Se connecter sur ce nouveau compte utilisateur :

```text
su - mynewuser
```

## Installation du serveur web Apache 2

```text
sudo apt-get install apache2 apache2-doc
```

Il est possible de vérifier que le service Apache fonctionne correctement en utilisant la commande suivante :

```text
sudo service apache2 status
```

{% hint style="info" %}
La mention "active \(running\)" doit apparaître.
{% endhint %}

