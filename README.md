# Alternance Quest - Jeu Vidéo RPG 2D

## Description

Ce projet consiste à créer un jeu vidéo utilisant le framework Phaser, simulant la recherche d'un contrat d'alternance. Vous incarnez un candidat en quête d'un emploi dans différentes entreprises. Vous devez choisir le contrat qui correspond le mieux à vos caractéristiques et affronter les questions des recruteurs lors des entretiens d'embauche, dans un style de combat RPG.

## Gameplay

### Boucle de Gameplay

1. **Choix du candidat :** Sélectionnez parmi au moins 3 candidats différents, chacun ayant des caractéristiques distinctes telles que l'âge, le genre, les compétences techniques et comportementales.

2. **Exploration :** Contrôlez le candidat pour explorer la carte et visiter les différentes entreprises disponibles.

3. **Offres d'emploi :** Chaque entreprise propose différentes offres d'emploi. Choisissez celle qui correspond le mieux aux caractéristiques de votre candidat. Si elles sont compatibles, passez à l'étape suivante.

4. **Entretien d'embauche :** Engagez-vous dans un combat de questions-réponses avec le recruteur. Chaque réponse correcte affaiblit le recruteur tandis qu'une réponse incorrecte vous affaiblit.

5. **Conditions de victoire :** Si le recruteur n'a plus de points de vie, vous avez décroché le contrat et le jeu est gagné.

6. **Conditions de défaite :**
   - Si vous n'avez plus de points de vie lors d'un entretien, vous devez quitter l'entreprise et en trouver une autre.
   - Si le recruteur a encore des points de vie à la fin de l'entretien, vous n'obtenez pas le contrat.

## Cahier des Charges

### Langages Utilisés
- JavaScript
- HTML
- Framework Phaser

### Contraintes Techniques
- Programmation Orientée Objet pour assurer une qualité de code.
- Les entités du jeu doivent être conçues de manière orientée objet.

### Fonctionnalités Obligatoires
- **Personnages jouables :** Au moins 3 candidats différents avec des caractéristiques variées.
- **Entreprises sur la carte :** Un minimum de 4 entreprises à visiter.
- **Gestion des déplacements :** Les candidats doivent pouvoir se déplacer sur la carte.
- **Gestion des collisions :** Évitez les collisions avec les obstacles sur la carte.
- **Interface de combat :** Un système de combat pour les entretiens d'embauche avec des animations.
- **Animations personnages :** Animations pour les mouvements et les combats.
- **Conditions de victoire et de défaite :** Conditions claires pour gagner ou perdre le jeu.
- **Boucle de jeu complète :** Le jeu doit être jouable de bout en bout.

### Fonctionnalités bonus
- **Mode de jeu :** Mettez en place deux modes de jeu différents `Hardcore` ou `Light`.
- **Édition d'une application de jeu `Desktop` :** Exportez votre jeu web en application Desktop via le framework `Electron`.