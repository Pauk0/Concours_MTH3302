# Prédiction de la Résistance à la Compression du Béton

## Overview
Le béton est le matériau le plus important en génie civil. La résistance à la compression du béton est une fonction fortement non linéaire de son âge et de ses constituants.

Ces constituants comprennent :
* Le ciment
* Le laitier de haut fourneau
* Les cendres volantes
* L’eau
* Le superplastifiant
* Les gros granulats
* Les granulats fins

## Données et Contexte
Vous avez accès à une vraie banque de données répertoriant la résistance à la compression du béton en fonction de ses constituants. Ces données ont déjà été analysées avec des réseaux de neurones dans plusieurs articles scientifiques, notamment Chen (1998).

* **Ensemble d'entraînement :** 700 recettes pour lesquelles la résistance est connue.
* **Tâche :** Vous aurez à développer un modèle statistique permettant la prédiction de la résistance des **330 recettes** de l'ensemble de test.

> **Référence :**
> Cheng Yeh, "Modeling of strength of high performance concrete using artificial neural networks," *Cement and Concrete Research*, Vol. 28, No. 12, pp. 1797-1808 (1998)

## But
Prédire la résistance en compression des recettes de béton de l'ensemble en fonction de leurs caractéristiques.

## Objectifs spécifiques non exhaustifs
1. **Effectuer une analyse exploratoire des données** afin d'extraire qualitativement certains liens potentiels entre les variables.
2. **Élaborer plusieurs modèles prédictifs** en fonction des caractéristiques fournies.
3. **Sélectionner le meilleur modèle prédictif** à l'aide d'un critère choisi.
4. **Exploiter le modèle choisi** pour effectuer vos prédictions.

_Ces étapes peuvent être recommencées autant de fois que nécessaire afin d'obtenir le meilleur modèle prédictif possible._
