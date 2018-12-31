# Affinitic website

### Installation du package

Développer le buildout et ses dépendances.

```sh
$ virtualenv-2.7 .
$ bin/pip install -I -r requirements.txt
$ ln -s dev.cfg buildout.cfg
$ bin/buildout
```

Lancer l'instance

```sh
$ bin/instance fg
```


### Installer le package
  - Aller sur http://localhost:8080/
  - Créer un nouveau site plone
  - [Aller dans le control panel section "Modules"](http://localhost:8080/Plone/prefs_install_products_form)
  - Installer "affinitic.policy" 

### Ajouter le contenu d'exemple
  - [Aller dans le portal_setup section upgrades "Modules"](http://localhost:8080/Plone/portal_setup/manage_upgrades)
  - Choisisser le profil "affinitic.core"
  - Cliquer sur "show" de Show old upgrades
  - Cocher l'upgrade 1 -> 2
  - Cliquer sur "upgrade"

### Ajouter des tiles dans le mosaic de la homepage
  - [Aller sur "Modifier" de la homepage](http://localhost:8080/Plone/home/edit)
  - Selectionner le layout de votre choix
  - Cliquer sur "Layout" puis sur "Customize"
  - Dans l'onglet "Insert" choisir les contenus à ajouter, il est recommander de les rajouter dans l'ordre suivant :
      - About us
      - Our services
      - Our testimony
      - Our last projects
      - Our references
      - Our team

# Le site Affinitic est prêt!
