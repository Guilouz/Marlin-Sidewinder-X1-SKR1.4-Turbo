Si vous aimez mon travail, n'hésitez pas à me soutenir en me payant une 🍺 ou un ☕. Merci 🙂

 [ ![Download](https://user-images.githubusercontent.com/12702322/115148445-e5a40100-a05f-11eb-8552-c1f5d4355987.png) ](https://www.paypal.me/CyrilGuislain)


![GitHub](https://img.shields.io/github/license/marlinfirmware/marlin.svg)
[![Build Status](https://github.com/MarlinFirmware/Marlin/workflows/CI/badge.svg?branch=bugfix-2.0.x)](https://github.com/MarlinFirmware/Marlin/actions)

<img align="right" width=175 src="buildroot/share/pixmaps/logo/marlin-250.png" />

**Firmware Marlin 2.0.9.1 bugfix configuré pour Artillery Sidewinder X1 avec carte mère BigTreeTech SKR 1.4 Turbo.**

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
- Support de l'extinction de la chauffe après 15 minutes d'inactivité de la hotend
- Activation du ventilateur de la hotend uniquement quand la chauffe dépasse 50°C
- Support des commandes d'action de l'hôte
- Optimisation du buffer pour Octoprint
- Marlin en français
