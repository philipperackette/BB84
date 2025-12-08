# BB84 – Démonstrateur interactif

Ce dépôt contient une page web interactive illustrant le **protocole de distribution quantique de clés BB84**.  
Tout est implémenté dans un seul fichier HTML/CSS/JavaScript : `bb84.html`.

---

## 🔗 Démo en ligne

La version en ligne est accessible ici :

- Page principale : https://philipperackette.github.io/BB64/

Le dépôt est donc utilisable directement depuis un simple navigateur, sans aucune installation locale.

---

## 🧪 Fonctionnalités

La page permet notamment de :

- visualiser les choix de bases et de bits d’**Alice** ;
- visualiser les mesures de **Bob** (avec ou sans interception) ;
- simuler la présence d’une éventuelle espionne **Eve** ;
- afficher le **criblage (sifting)** entre Alice et Bob ;
- calculer le **taux d’erreur** introduit par l’espionnage ;
- afficher la **clé finale partagée** après élimination des bits incompatibles.

L’interface est pensée pour un usage **pédagogique** (cours de cryptographie / physique quantique).

---

## 💻 Utilisation locale

Si tu veux utiliser la page en local (sans passer par GitHub Pages) :

1. Cloner le dépôt :

   ```bash
   git clone https://github.com/philipperackette/BB64.git
   cd BB64
   ```

2. Ouvrir `bb84.html` dans un navigateur (double-clic ou glisser-déposer dans la fenêtre du navigateur).

Aucun serveur web ni dépendance Python n’est nécessaire : tout est purement côté client.

---

## 📁 Contenu du dépôt

- `bb84.html` : page principale, tout le code de la démonstration BB84.
- `index.html` : petite page de redirection automatique vers `bb84.html` pour GitHub Pages.
- `README.md` : ce fichier de documentation.
