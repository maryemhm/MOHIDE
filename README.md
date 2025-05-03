
# 🎮 MoHide

**MoHide** est un jeu développé avec Unity où le joueur peut se cacher en se transformant en objets pour échapper à ses ennemis.  
Ce dépôt présente une structure modulaire pour une meilleure organisation du code, des assets et des scènes.

---

## 📁 Structure du projet

### `Assets/MoHide/`

| Dossier              | Description |
|----------------------|-------------|
| `Animations/`        | Fichiers d’animations (personnages, objets, UI). |
| `Materials/`         | Matériaux pour personnaliser l’apparence des objets. |
| `Models/`            | Modèles 3D utilisés dans le jeu (`.fbx`, etc.). |
| `Prefabs/`           | Objets préfabriqués réutilisables dans les scènes. |
| `Scenes/`            | Scènes du jeu (ex. `ApartmentScene`, `ShowRoomScene`). |
| `Scripts/`           | Code source du jeu, organisé par fonctionnalité. |
| `Shaders/`           | Shaders personnalisés (verre, cartoon, etc.). |
| `Sounds/`            | Fichiers audio (`.wav`, effets sonores, musiques). |
| `Sprites/`           | Images pour UI, mini-jeux, et icônes de scripts. |

#### 📁 Scripts

Les scripts sont classés selon leur fonctionnalité :

- `Animations/` – Contrôle des animations.
- `Apartment/` – Logique spécifique à la scène d’appartement.
- `Audio/` – Gestion des sons et musiques.
- `Camera/` – Gestion de la caméra.
- `Effects/` – Effets visuels (grayscale, etc.).
- `Enemy/` – IA et logique des ennemis.
- `Hide scripts/` – Mécanique de transformation en objets.
- `Player/` – Déplacements et actions du joueur.
- `Post processing/` – Effets de post-traitement.
- `Sound/` – Gestion centralisée du son.
- `UI/` – Interface utilisateur (barres de vie, panels de victoire/défaite…).

---

### `Assets/MoHide2/`

| Fichier                  | Description |
|--------------------------|-------------|
| `Level2.unity`           | Scène du deuxième niveau. |
| `Level2Settings.lighting` | Paramètres d’éclairage pour `Level2`. |

---

### Dossiers système Unity

- `Library/`, `Packages/`, `ProjectSettings/`  
➡️ Gérés automatiquement par Unity. **Ne pas modifier manuellement.**

---

## ✅ Bonnes pratiques suivies

- Nommage cohérent des fichiers et dossiers.
- Structure modulaire (séparation par fonctionnalité).
- Scènes et niveaux organisés par dossier.
- Préparation à l’évolution du jeu (ajout de niveaux, gestion du son, UI évolutive…).

---

## 📌 À venir

### 12. Ouverture à l’évolution (fonctionnalités futures)

- **Objets piégés** :  
  Certains objets présents sur le toit sont des leurres. Ils sont plus fréquemment vérifiés par les ennemis en patrouille. Se transformer en l’un d’eux augmente considérablement le risque d’être repéré.

- **Objets interactifs** :  
  Le joueur peut désormais interagir avec certains éléments du décor — faire tomber une chaise, déplacer légèrement un objet — afin de créer une diversion temporaire et détourner l’attention de l’ennemi.

- **Transformations limitées** :  
  Pour renforcer la tension, le nombre de transformations est restreint. Le joueur doit donc réfléchir stratégiquement avant de changer d’apparence, sous peine de se retrouver sans défense.

- **Ramasser des objets spéciaux sans se faire repérer par l’ennemi** :  
  Des objets spéciaux sont disséminés dans l’environnement. Si le joueur parvient à les collecter sans se faire repérer, il débloque une victoire instantanée, récompensant la prise de risque et la maîtrise de la furtivité.

---

## 📁 Requis pour exécuter le projet

- Unity (version recommandée : 2021.3 LTS ou ultérieure)
- Modules : 3D Core, Input System, Post Processing Stack

---

## 👩‍💻 Auteur·rice

**MoHide** a été conçu et développé par *MARYEM & HOUDA*.  
Merci d’utiliser, de contribuer ou de tester ce projet ✨
