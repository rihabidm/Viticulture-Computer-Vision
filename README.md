# Projet Computer Vision en Viticulture

## Description du Projet

Ce projet explore l'application des technologies de vision par ordinateur et d'apprentissage profond dans le domaine de la viticulture. Il se concentre sur trois problématiques clés :

1. **Classification des maladies des feuilles de raisin** : Automatisation de la détection et de la classification des maladies des feuilles de vigne pour réduire les pertes agricoles.
2. **Prédiction de la récolte du raisin** : Détection automatique des grappes de raisin pour optimiser les récoltes et améliorer la prévision des rendements.
3. **Détection des insectes nuisibles** : Identification et suivi des insectes nuisibles aux plantes de raisin pour réduire les risques agricoles.

## Objectifs

- **Classification des maladies** : Développer un modèle de classification des maladies des feuilles de raisin en utilisant des réseaux de neurones convolutifs (CNN) et des techniques de deep learning.
- **Prédiction de la récolte** : Implémenter un système de détection automatique des grappes de raisin pour optimiser la gestion des vendanges.
- **Détection des insectes nuisibles** : Créer un modèle de détection d'insectes nuisibles pour aider les agriculteurs à protéger leurs cultures.

## Datasets Utilisés

- **Grape_disease** : Dataset pour la classification des maladies des feuilles de raisin.
- **Embrapa WGISD** : Dataset pour la détection et la segmentation des grappes de raisin.
- **Dangerous Farm Insects Dataset** : Dataset pour la détection des insectes nuisibles.

## Méthodologie

### Classification des Maladies
- **Modèles utilisés** : ResNet50 et un modèle personnalisé.
- **Techniques** : Classification supervisée, augmentation de données, régularisation.

### Prédiction de la Récolte
- **Modèle utilisé** : Faster R-CNN avec backbone ResNet50-FPN.
- **Techniques** : Détection d'objets, segmentation d'images, apprentissage profond.

### Détection des Insectes Nuisibles
- **Modèles utilisés** : Vision Transformers, ResNet50, MobileNet, EfficientNet, Xception.
- **Techniques** : Classification d'images, augmentation de données, évaluation des performances.

## Résultats

- **Classification des maladies** : Précision de 78.78% sur l'ensemble de test.
- **Prédiction de la récolte** : Modèle performant avec une amélioration constante des prédictions.
- **Détection des insectes nuisibles** : Précision de 91% pour les classes clés.

## Impact Potentiel

Ce projet a le potentiel de transformer la viticulture en automatisant la détection des maladies, des insectes nuisibles et des grappes de raisin. Cela permet aux agriculteurs d'agir de manière proactive, d'optimiser les récoltes et de réduire les pertes économiques.

## Perspectives Futures

- **Augmentation des datasets** : Enrichir les ensembles de données pour améliorer la généralisation des modèles.
- **Exploration d'architectures avancées** : Tester des modèles plus complexes comme les Vision Transformers à plusieurs échelles.
- **Intégration en temps réel** : Développer des outils en temps réel pour les agriculteurs.

## Auteurs

- Asmaa BAZIGHE
- Rihab ID M'HAND
- Lina MOUISSOU
- Sami KHALFI

## Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## Comment Contribuer

Les contributions sont les bienvenues ! Veuillez ouvrir une issue ou soumettre une pull request pour toute suggestion ou amélioration.

## Remerciements

Nous remercions les créateurs des datasets utilisés dans ce projet ainsi que la communauté open source pour les outils et bibliothèques qui ont rendu ce projet possible.
