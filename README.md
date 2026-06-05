# AzerType

> L'application web pour apprendre à taper plus vite au clavier !

---

## Description

**AzerType** est une application en ligne interactive qui permet aux utilisateurs d'améliorer leur vitesse de frappe au clavier. L'utilisateur doit taper le plus rapidement possible des mots ou des phrases qui s'affichent à l'écran, et un score est calculé en fonction de ses performances.

---

## Fonctionnalités

- **Deux modes de jeu** :
  - **Mots** : taper des mots simples
  - **Phrases** : taper des phrases complètes
- **Validation en temps réel** de la saisie
- **Système de score** mis à jour automatiquement
- **Partage de score** par e-mail via une popup dédiée
- **Mise au point automatique** sur le champ de saisie au chargement de la page

---

## Structure du projet

```
AzerType/
│
├── index.html               # Page principale de l'application
│
├── style/
│   └── style.css            # Feuille de style du jeu
│
└── scripts/
    ├── config.js            # Configuration générale du jeu
    ├── popup.js             # Gestion de la popup de partage
    ├── script.js            # Logique principale du jeu
    └── main.js              # Point d'entrée principal
```

---

## Technologies utilisées

| Technologie | Utilisation |
|-------------|-------------|
| HTML5       | Structure de la page |
| CSS3        | Mise en forme et style |
| JavaScript  | Logique du jeu et interactions |

---

## Installation & Utilisation

1. **Cloner le dépôt** :
   ```bash
   git clone https://github.com/votre-utilisateur/azertype.git
   ```

2. **Accéder au dossier** :
   ```bash
   cd azertype
   ```

3. **Ouvrir le fichier** `index.html` dans votre navigateur préféré.

> Aucune installation de dépendance n'est nécessaire. Le projet fonctionne entièrement côté client.

---

## Comment jouer ?

1. Choisissez votre mode : **Mots** ou **Phrases**
2. Tapez la proposition affichée dans le champ de saisie
3. Cliquez sur **Valider** ou appuyez sur `Entrée`
4. Votre score s'incrémente à chaque bonne réponse
5. Partagez votre score avec vos amis via le bouton **Partager**

---

## Fonctionnalité de partage

En cliquant sur le bouton **Partager**, une popup s'ouvre et vous permet de :
- Entrer votre **nom**
- Renseigner l'**adresse e-mail** du destinataire
- Envoyer votre score directement par mail

---

## Auteur

**Valentin MARTIN**  
© Copyright - Tous droits réservés