# 📌ToDo-App

Une application de gestion de tâches développée avec React JS, Tailwind CSS, TypeScript, Redux Toolkit et d'autres technologies.

## 📝 Description

ToDo-App permet d'organiser efficacement vos tâches grâce aux fonctionnalités suivantes :

- **Gestion des tâches** : Chaque tâche comprend un titre, une description, une date, ainsi que des options pour la marquer comme complétée ou importante.
- **Organisation des tâches par catégories** :
  - 📅 Tâches du jour
  - ⭐ Tâches importantes
  - ❌ Tâches incomplètes
  - ✅ Tâches complètes
  - 📂 Toutes les tâches
  - 🗂 Tâches par répertoire (dossier)
- **Gestion des répertoires** :
  - Possibilité de créer, modifier et supprimer des répertoires et des tâches.
  - Un répertoire principal nommé `Main` est prédéfini et le nom du répertoire ne peut être ni modifié ni supprimé.
- **Tri des tâches** : Affichage des tâches en fonction de leur date d'échéance (la plus proche ou la plus éloignée) et de leur statut (complétée ou incomplète).
- **Recherche rapide** : Un champ de recherche permet de retrouver facilement une tâche.
- **Affichage dynamique** :
  Les tâches du jour sont affichées dans la section utilisateur et dans les notifications.
- **Persistance des données** :
  Les tâches, répertoires et préférences du mode sombre sont enregistrés dans le localStorage du navigateur.

## 🎯 Objectif

Ce projet a pour principal objectif de mettre en pratique les connaissances en TypeScript, Tailwind CSS, Redux Toolkit et React JS à travers une application interactive et fonctionnelle.

## 🛠️ Technologies utilisées

  - React JS
  - TypeScript
  - Tailwind CSS
  - Redux Toolkit
  - HTML

## 🚀 Installation et exécution

Cloner le projet

```bash
git clone <URL_DU_RÉPÔ>
```

Se rendre dans le dossier du projet

```bash
cd tasks-app
```

Installer les dépendances

```bash
npm install
```

Démarrer l'application

```bash
npm start
```

## 💡 Remarques

- Les tâches, répertoires et préférences du mode sombre sont stockés dans le localStorage du navigateur.
- Un bouton "Delete all data" est disponible pour effacer ces informations.
- À des fins de démonstration, l'application contient par défaut trois tâches et un répertoire nommé "Main".
