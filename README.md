# BB84

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## English

Interactive demonstration of the **BB84 quantum key distribution protocol**, intended as a compact educational and technical illustration of the core exchange logic.

**Online version:** https://philipperackette.github.io/BB84/

### Features

- Step-by-step simulation: random bases and bits, polarized photons, Bob's measurements, sifting, error-rate estimation, key generation
- Optional eavesdropper (Eve, intercept-resend attack) with adjustable interception probability: expected error rate ≈ probability / 4 (25% when every photon is intercepted)
- The exchange is aborted when the measured error rate exceeds 11%
- Alice's and Bob's final keys are shown side by side, with differing bits highlighted, along with the share of the key Eve actually knows
- French / English interface (FR/EN button; the language is remembered, and the current simulation is translated in place)

### Contents

- `bb84.html`: main interactive demonstration
- `index.html`: lightweight entry page
- `LICENSE`: MIT license

### Usage

Clone the repository and open the HTML file in a browser.

```bash
git clone https://github.com/philipperackette/BB84.git
cd BB84
# Open bb84.html in a browser
```

### Intended audience

- readers interested in introductory quantum cryptography,
- teachers and students,
- anyone wanting a simple browser-based BB84 demonstration.

---

## Français

Démonstrateur interactif du protocole de distribution quantique de clés **BB84**, pensé comme une illustration compacte, pédagogique et technique du mécanisme d'échange.

**Version en ligne :** https://philipperackette.github.io/BB84/

### Fonctionnalités

- Simulation pas à pas : bases et bits aléatoires, photons polarisés, mesures de Bob, tamisage, estimation du taux d'erreur, génération de la clé
- Espionne optionnelle (Eve, attaque interception-réémission) avec probabilité d'interception réglable : taux d'erreur attendu ≈ probabilité / 4 (25 % si tous les photons sont interceptés)
- L'échange est abandonné si le taux d'erreur mesuré dépasse 11 %
- Les clés finales d'Alice et de Bob sont affichées côte à côte, bits différents mis en évidence, avec la part de la clé réellement connue d'Eve
- Interface en français / anglais (bouton FR/EN ; la langue est mémorisée et la simulation en cours est traduite sans être relancée)

### Contenu

- `bb84.html` : démonstrateur interactif principal
- `index.html` : page d'entrée légère
- `LICENSE` : licence MIT

### Utilisation

Clonez le dépôt puis ouvrez le fichier HTML dans un navigateur.

```bash
git clone https://github.com/philipperackette/BB84.git
cd BB84
# Ouvrir bb84.html dans un navigateur
```

### Public visé

- personnes intéressées par une première approche de la cryptographie quantique,
- enseignants et étudiants,
- toute personne voulant une démo BB84 simple dans le navigateur.

---

## Licence / License

Ce projet est distribué sous licence [MIT](LICENSE).  
This project is distributed under the [MIT License](LICENSE).
