# BeFree

> Une application de focus **hardcore** pour Windows. Pas de gamification molle, pas de rappels gentils — un dojo numérique où tu signes un contrat avec toi-même et où les distractions sont mises en quarantaine.

BeFree bloque tes applications et sites distrayants pendant tes sessions de travail. En mode **Hardcore**, une fois la session lancée, tu ne peux plus l'arrêter avant la fin : ni pause, ni annulation, et les `.exe` distrayants sont déplacés en quarantaine sur le disque.

## 📥 Télécharger

| Plateforme | Fichier |
|---|---|
| Windows | `BeFreeSetup.exe` (installeur, sans droits administrateur) |

→ [Voir toutes les Releases](https://github.com/gohansenseiyt-ux/BeFree-app/releases/latest)

## ✨ Fonctionnalités

- **Assistant de session en 2 étapes** — d'abord le mode (Libre / Tunnel / Hardcore), puis le type (Infini, Pomodoro, Durée Fixe, Quarantaine), filtré selon le mode.
- **Contrat de travail** — tu écris ton objectif et tu signes avant de commencer.
- **Liste blanche d'applications** et **blocage de sites web**.
- **Système de grades** (Deep Work Score) — 6 rangs du dojo, de *Novice* à *BeFree*.
- **Statistiques** — temps passé par application, graphiques, séries de jours.
- **Physical Lock** — seule une clé USB physique peut ouvrir les réglages / autoriser un abandon.
- **Persistance de session** — la session se réactive après un redémarrage.
- **Français / English** — choix de langue au premier lancement.
- **Compte Premium** (optionnel) — les 500 premiers inscrits débloquent un code Premium unique.
- **Local par défaut** — sessions, statistiques et blocages ne quittent jamais ton PC. Seul le compte Premium (optionnel) envoie ton email à un service distant pour gérer les 500 places.

## 🚀 Installation

1. Va sur la page [Releases](https://github.com/gohansenseiyt-ux/BeFree-app/releases/latest) et télécharge `BeFreeSetup.exe`.
2. Lance-le et suis l'assistant (Suivant → Suivant → Installer). Aucun droit administrateur requis, installation dans ton profil utilisateur.

L'exécutable n'étant pas encore signé, Windows peut afficher un avertissement "Éditeur inconnu" au premier lancement — clique sur **Plus d'infos** puis **Exécuter quand même**.

## ⚠️ Avertissement

BeFree modifie temporairement le fichier `hosts` de Windows et peut fermer / déplacer des applications pendant une session. Le mode Hardcore est **volontairement difficile à contourner** — c'est le but. Utilise-le en connaissance de cause.
