# Check.exe

Un jeu d'échecs complet jouable en ligne de commande (CLI) avec une interface rétro en caractères ASCII.

![Capture d'écran du jeu dans le terminal](capture_terminal.png)

## Description

**Check.exe** est un jeu d'échecs développé pour s'exécuter directement dans le terminal. Conçu dans un délai intensif de moins d'une semaine par une équipe de 4 développeurs, il propose une expérience de jeu complète tout en respectant l'ensemble des règles officielles, le tout via une interface ASCII au style rétro.

## Analyse Technique & Architecture

Ce projet a été un véritable défi de rapidité et d'organisation, et a mis en lumière notre capacité à livrer un logiciel complexe sous la pression.

* **Modélisation POO Avancée :** Conception rigoureuse basée sur le polymorphisme pour gérer les mouvements uniques de chaque pièce. L'architecture intègre la logique stricte des échecs, y compris les coups spéciaux (Roque, Prise en passant, Promotion).
* **Méthodologie Agile :** Application des principes Agiles pour respecter la deadline d'une semaine : découpage du projet en tâches prioritaires, réunions de synchronisation quotidiennes (daily stand-ups) et adaptation du planning en temps réel.
* **Automatisation et Scripts :** Création de scripts Bash sur mesure pour automatiser le nettoyage, la compilation et l'exécution du programme, ce qui a drastiquement simplifié et accéléré les phases de test pour toute l'équipe.
* **Collaboration Efficace :** Travail d'équipe optimisé pour éviter les blocages, avec une intégration rapide du code de chacun pour maintenir une progression fluide.

## Fonctionnalités

* Jouabilité complète d'une partie d'échecs classique.
* Affichage clair et dynamique du plateau en caractères ASCII (CLI).
* Prise en charge de tous les coups spéciaux (Roque, Prise en passant, Promotion des pions).
* Scripts de compilation et de lancement rapides.

## Technologies utilisées

* **Langage :** Java
* **Environnement :** Terminal / Ligne de commande
* **Automatisation :** Scripts Bash (Shell)
* **Méthodologie :** Agile / Scrum

## Installation et Exécution

**Environnement requis :** Un terminal bash (Linux, macOS, ou WSL sous Windows) et [Ton compilateur/interpréteur, ex: Java 17, GCC...].

**1. Clonez le dépôt :**
```bash
git clone https://github.com/Rhapeuh/Check.exe.git
```

**2. Lancez le jeu via les scripts d'automatisation :**
```bash
# Exemple si tu as un script run.sh à la racine
chmod +x run.sh
./run.sh
```

## 📂 Structure du projet

```
/
├── src/             # Code source du jeu (logique des pièces, plateau, etc.)
├── scripts/         # Scripts Bash (compilation, nettoyage, exécution)
└── README.md
```

## Auteurs

- Ylann WATTRELOS

## Licence

Ce projet est sous licence MIT.
