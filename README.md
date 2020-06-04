# Projet de fin d'étude - Exploration tactile et interactive d’une œuvre

## Rapel

Ce dépôt contient des sous-modules, il est fortement recommandé d'utiliser la commande "git clone --recurse-submodules"

## Le projet

### Introduction
#### Contexte
L’accessibilité au savoir et plus largement à culture est une grande problématique. Cette réflexion amène des questions sur comment vulgariser la connaissance mais aussi comment le transmettre via le medium. Ainsi dans le cadre du projet de fin d’étude, M. Venturini propose un sujet pour rendre accessible des maquettes/œuvres d’art au personnes malvoyant. L’idée est de créer une interaction physique entre l’utilisateur et la maquette à l’aide de zones déclenchant des messages audios. Ces derniers décrivent l’œuvre ou la situation dans laquelle l’utilisateur évoluera.
#### Problématique
Ce projet a pour but d’obtenir un système autonome pouvant se greffer sur une statue ou une maquette. En fonction d’interaction de toucher, elle effectuera une ou plusieurs actions de sortie. Ces actions de sorties seront des informations l’utilisateur par le biais de messages audios.

### Objectif
L’objectif de ce projet consiste principalement à miniaturiser le système existant. Pour se faire, une analyse sur deux architectures différentes devra être réaliser pour déterminer, c’est-à-dire choisir entre MCU ou SBC (Single Board Computer).
Pour résumé, il faut :
* Miniaturiser pour tenir dans un carré de 20x20cm (choisir une architecture adaptée)
* Détecter un appui long/court
* Lire un fichier audio
* Prévoir une solution pour changer les fichier audios


### Livrable disponible

* [x] dossier projet de l’application Phidget
* [x] dossier projet de l’application de mise à jour des fichiers audio
* [ ] clone de l’OS utilisé (impossible de récupéré le SBC utilisé pour en faire une copie à cause du confinement)
* [x] cahier de spécification
* [x] cahier d’analyse
* [x] rapport
* [x] manuel d’utilisateur pour le mainteneur
* [x] manuel d’installation


## Structure du dépôt

PFE_livrable/<br>
├── Documentation/<br>
│   └── Projet<br>
│       ├── Planning<br>
│       ├── Rapport<br>
│       └── Soutenance<br>
└── programmation/<br>
    ├── copying_program<br>
    │   └── test_copy // fichier projet<br>
    └── embedded_program<br>
        └── test_phidget // fichier projet<br>
