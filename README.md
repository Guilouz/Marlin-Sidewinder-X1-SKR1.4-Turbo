Si vous aimez mon travail, n'hésitez pas à me soutenir en me payant une 🍺 ou un ☕. Merci 🙂

 [ ![Download](https://user-images.githubusercontent.com/12702322/115148445-e5a40100-a05f-11eb-8552-c1f5d4355987.png) ](https://www.paypal.me/CyrilGuislain)

<img align="right" width=175 src="buildroot/share/pixmaps/logo/marlin-250.png" />

**Firmware Marlin configuré pour Artillery Sidewinder X1 avec carte mère BigTreeTech SKR 1.4 Turbo.**

Le firmware pour écran BigTreeTech TFT43 3.0 est disponible [ici](https://github.com/Guilouz/BTT-TFT43-Sidewinder-X1).

Le firmware pour carte mère BigTreeTech SKR 2.0 est disponible [ici](https://github.com/Guilouz/Marlin-Sidewinder-X1-SKR2.0).

## Principales fonctionnalités configurées :

- Support carte mère BigTreeTech SKR 1.4 Turbo
- Support drivers TMC2209/TMC2226
- Support écrans BigTreeTech
- Support Bed Leveling Bilinear 5 x 5 points
- Support BLTouch (High Speed Mode)
- Support M600 & Nozzle Park / Advanced Pause
- Support Babystepping
- Support Neopixels
- Support EEPROM
- Support PID Buse & Plateau
- Support protection thermique contre l'emballement
- Support S-Curve Acceleration & Junction Deviation
- Support G34 - Z Steppers Auto-Alignment
- Support G26 - Mesh Validation Pattern
- Support du transfert de fichier binaire (transfert du fichier firmware à distance via Octoprint)
- Activation du ventilateur de la hotend uniquement quand la chauffe dépasse 50°C
- Support des commandes d'action de l'hôte
- Optimisation du buffer pour Octoprint
- Marlin en français

## Procédure d'installation :

- Effectuez un reset EEPROM avant flash du nouveau firmware (commande M502 suivi de la commande M500 ou via l'écran TFT).
- Copiez le fichier `firmware.bin` à la racine de la carte microSD (capacité max de 32Go, formatée en FAT32, taille d'unité d'allocation 4096).
- Imprimante éteinte, insérez la carte microSD dans le port dédié sur la carte mère et allumez l'imprimante.
- La procédure de flash démarre (sans rien afficher à l'écran) et dure quelques secondes.
- Vérifiez le contenu de la carte microSD, le fichier `firmware.bin` a été renommé en `FIRMWARE.CUR` ce qui indique que le flash s'est bien déroulé.
- Effectuez de nouveau un reset EEPROM (commande M502 suivi de la commande M500 ou via l'écran TFT).
- Lancez un PID Buse & Plateau depuis les paramètres de l'écran.
- Lancez une calibration de l'extrudeur depuis les paramètres de l'écran.
- Lancez une calibration Delta depuis les menus de l'écran.
- Lancez un auto-nivellement depuis les menus de l'écran.
