# Hébergement

DataCenterLight.ch: serveur propulsé par 100% d'énergie renouvelable.

- Ubuntu 18.04
- 1 CPU, 4 Go RAM, 40 Go HD

# Configuration

* Créer les records DNS requis

```
my           IN A     IP.DU.SERVEUR
agora        IN A     IP.DU.SERVEUR
chat         IN A     IP.DU.SERVEUR
cloud        IN A     IP.DU.SERVEUR
wiki         IN A     IP.DU.SERVEUR
...
```

* Installer Cloudron

Suivre les instructions sur https://cloudron.io/documentation/installation/.

* Installer les bibliothèques requises

`apt install imagemagick php-imagick`

