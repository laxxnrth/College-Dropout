# College-Dropout

**Objectif du projet** : Ce projet a pour but de développer un modèle de Machine Learning capable de prédire les décrochages scolaires dans l'enseignement supérieur.

1. Nettoyage et visualisation des données :

Une analyse statistique des données est réalisée pour mieux comprendre la distribution des variables, notamment en étudiant les proportions de décrochage selon différentes caractéristiques démographiques telles que le genre et l'âge des étudiants.

Nous effectuons également une transformation de la variable à prédire (décrochage : oui/non) pour s'assurer qu'elle est adaptée à nos modèles de classification.

3. Echantillonnage

L’échantillonnage est une étape clé pour obtenir un ensemble de données représentatif pour l’entraînement et la validation des modèles. Nous divisons nos données en deux ensembles : un ensemble d'entraînement et un ensemble de test, dans une proportion de 1/3 et 2/3, afin d'évaluer la performance des modèles de manière impartiale.

5. Application des différents modèles
   
Nous appliquons plusieurs algorithmes de Machine Learning pour comparer leurs capacités à prédire le décrochage scolaire :
- LDA (Linear Discriminant Analysis) : Un modèle de classification linéaire qui cherche à séparer les classes en maximisant la variance entre elles.
- QDA (Quadratic Discriminant Analysis) : Variante de la LDA, mais plus flexible, en permettant des frontières de décision quadratiques.
- Régression Logistique : Modèle de classification binaire qui prédit la probabilité d'appartenance à une classe, en utilisant une fonction logistique.
- KNN (K-Nearest Neighbors) : Algorithme de classification basé sur les observations les plus proches dans l’espace des caractéristiques.
- SVM (Support Vector Machines) : Modèle qui sépare les classes avec une hyperplane maximale, capable de gérer des frontières linéaires et non linéaires.
- Arbre de décision : Modèle qui segmente les données en différentes branches en fonction de critères de décision simples, créant un arbre de décisions.
- Forêt Aléatoire (Random Forest) : Algorithme d'ensemble qui combine plusieurs arbres de décision pour obtenir des prédictions plus robustes.
- Boosting : Technique d'ensemble qui construit séquentiellement des modèles pour corriger les erreurs des modèles précédents et améliorer la précision globale.
  
7. Comparaison des modèles grâce à différents critères

Les modèles seront comparés selon plusieurs critères de performance pour identifier celui qui prédit le mieux le décrochage scolaire :
- Aire sous la courbe ROC (AUC) : Mesure de la capacité du modèle à différencier les classes (décrochage vs non-décrochage).
- Accuracy : Pourcentage de prédictions correctes sur l'ensemble de test.
- F-1 Score : Une mesure équilibrée entre la précision et le rappel, particulièrement utile lorsque les classes sont déséquilibrées.

Cela nous permet d'évaluer non seulement la performance globale, mais aussi la capacité des modèles à bien identifier les étudiants à risque de décrochage, avec une attention particulière portée aux faux négatifs (les étudiants prévus comme non-décrocheurs, mais qui abandonnent effectivement).

   


