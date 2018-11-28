# 2018-lp-ciasie-prog-web-project-cordova
Membres du projet :
- Maeva Butaye    ( Lilychaan )
- Camille Schwarz ( S-Camille )
- Léo Galassi     ( ElGitariste )
- Quentin Rimet   ( QuentinRimet )

# Pour lancer l'application mobile que nous avons créé
* Prérequis :
    - avoir Node.js d'installer
    - avoir Cordova d'installer --> il vous suffit de taper dans un terminal si vous ne l'avez pas la commande :
```
    npm install -g cordova (si vous êtes sous Windows)
    sudo npm install -g cordova (si vous êtes sous Linux ou Mac)
```
* Cloner le projet soit :
    - via SSH : git clone git@github.com:teaching-mnicolas/2018-lp-ciasie-prog-web-project-cordova.git
    - via HTTPS : git clone https://github.com/teaching-mnicolas/2018-lp-ciasie-prog-web-project-cordova.git

* Une fois le projet cloné, il vous suffit de vous rendre dans le dossier du projet, puis :
   - il vous suffit de taper les commandes suivantes pour lancer l'application :
```
    cordova platform add android (pour ajouter la plateforme Android au projet)
    codrova build (pour construire le projet)
    cordova run android --device (si votre téléphone Android est branché par USB à votre ordinateur)
    cordova emulate android (si vous voulez lancez un émulateur Android)
```
