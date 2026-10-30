# Notes de mise à jour

## [0.2.3] - 2026-10-30

### Nouveautés
- **Carte de profil** : nouveau format vertical avec rangs, Sightline Rating, statistiques, rôle et agent de prédilection, et un aperçu avant l'enregistrement.
- **Rating de chaque partie** : cliquez sur la note d'une partie, dans l'historique ou dans le tableau des scores (pour chaque joueur), pour savoir pourquoi elle a été obtenue, ce qui n'allait pas et quoi corriger à la prochaine.
- **Live** : bouton pour quitter la sélection d'agent sans relancer le jeu.
- **Casier** : export en image de votre équipement, avec la valeur de l'inventaire en VP.
- **Statut Discord** : ce que vous faites (menu, recherche, sélection d'agent, partie avec carte, mode, agent, score et rang) s'affiche dans votre profil Discord. Désactivable dans les paramètres.
- **Cartes** (onglet Infos) : composition conseillée, site d'attaque où chaque agent réussit le mieux et lineups en vidéo.
- **Skins** : aperçu en plein écran, vidéos comprises.
- **Groupe** : tous les modes ouverts en ce moment, et la partie personnalisée.
- **Amis** : la liste des amis qui ne font plus partie de votre liste, avec une notification Windows quand cela arrive.

### Améliorations
- **Groupes adverses** : les joueurs venus ensemble dans l'équipe adverse sont maintenant repérés.
- **Détection de smurf** plus précise : RR gagnés par victoire, montée de rang récente, pic passé et premiers kills.
- **Sightline Rating** : celui du profil ne compte plus que les parties classées, quel que soit le filtre affiché. Chaque partie garde sa note, quel que soit le mode.
- Les parties de **Combat à mort** apparaissent dans l'historique.
- **Mode performance** : Sightline coupe ses animations pendant une partie pour moins peser sur vos FPS.

## [0.2.2] - 2026-10-29

### Nouveautés
- **Profil** : anneau de RR autour du rang actuel et boucliers anti-dérank en division 1 (barré, à moitié ou plein).
- **Historique** : chaque partie classée affiche les RR gagnés ou perdus et le rang obtenu, avec une flèche en cas de promotion ou de rétrogradation.
- **Live** : cliquez sur le rang d'un joueur pour voir son rang actuel, son pic et ses triangles d'acte.
- **Boutique** : cliquez sur un skin, un pack ou une offre du marché nocturne pour voir les variantes, les niveaux et les vidéos.
- **Équipement** : tous les skins du jeu, avec filtres possédés, non possédés, favoris, arme et édition.
- **Nouveaux onglets** : Signets (profils suivis avec une note), Pseudos (changements de Riot ID repérés) et Achats (contenu ajouté à votre compte).
- **Profil** : victoires par agent et par carte, parties jouées par rôle, et triangle d'acte qui distingue les divisions de chaque rang.
- **Rôle conseillé** : en cliquant sur votre SLR, Sightline indique le rôle qui correspond le mieux à votre style de jeu, et pourquoi.
- **Thèmes** : Graphite, Braise, Néon, Émeraude et Chroma, un arc-en-ciel animé façon éclairage de clavier.

### Améliorations
- Les RR et le rang s'actualisent en revenant sur le profil après une partie.
- L'onglet Infos ne saccade plus en affichant les agents et les cartes.

## [0.2.1] - 2026-10-29

### Nouveautés
- **Mises à jour automatiques** : Sightline vérifie les nouvelles versions au démarrage puis toutes les 6 heures, et s'installe en un clic.

## [0.2.0] - 2026-10-28

### Nouveautés
- **Accès bêta par Discord** : connexion avec votre compte Discord, écran de verrouillage sans le rôle de testeur et onglet **Compte** (avatar, pseudo, badge de rôle).
- **Triangle d'acte** dans le profil : vos victoires classées par rang pour chaque acte, avec les actes précédents en miniature.
- **Pic historique** avec l'épisode et l'acte où il a été atteint, et l'épisode en cours sous le rang actuel.
- **Partager en PNG** : la carte de profil et la boutique s'exportent en image haute définition.
- **Pack vedette** en grande bannière dans la boutique, avec le prix de la collection.
- **Skins du compagnon** : un pack peut proposer des costumes (`pikachu_detective_idle.gif`).
- **Mises à jour** : une fenêtre propose d'installer la nouvelle version en un clic, et cette page affiche les notes de version.

### Corrections
- Le Live s'actualise aussi quand Sightline est réduit, et ne s'arrête plus sur une erreur HTTP 400 en fin de sélection ou de partie.
- Les groupes restent affichés pendant tout le match, et apparaissent aussi dans le tableau des scores du profil.

## [0.1.2] - 2026-10-28

### Corrections
- La notification de smurf fonctionne quel que soit l'onglet affiché, même fenêtre réduite.

## [0.1.1] - 2026-10-27

### Nouveautés
- Thèmes (dont thèmes à fond animé) et compagnon de bureau qui réagit à votre SLR.
- Anneau du SLR cliquable : détail de la note.
- Onglet Objectif, profils de paramètres de jeu et patchnotes de Valorant.
- Score en direct dans le Live, skins du lobby, onglet Infos et comparaison de rating.

### Corrections
- Équipement et changement de mode du groupe (HTTP 404).
- Pseudos absents des détails de match.

## [0.1.0] - 2026-10-26

- Première version : Live, groupe, carrière, Sightline Rating, détection de smurfs, boutique, classement et amis.
