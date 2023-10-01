
# Détection de fraude et simulation de données

Ces dernières années, la fraude financière a suscité beaucoup de préoccupations et d’attention car elle représente une menace de plus en plus importante qui a de graves conséquences sur le secteur financier. En conséquence, les institutions financières sont obligées d’améliorer continuellement leurs systèmes de détection de la fraude.
La plupart du temps, dans le domaine de la finance, les données ne sont pas accessibles à ceux qui souhaitent effectuer des recherches sur le comportement criminel des individus. Cela est principalement dû à des politiques juridiques et autres qui protègent la confidentialité des dossiers financiers des clients. Même si elles sont parfois accessibles, il n’est pas toujours possible de traiter de grandes quantités de données pour détecter les fraudes.
Pour résoudre le problème du manque de données financières dans le cadre de la recherche sur la détection de la fraude en finance, des techniques d'apprentissages automatiques ont été utilisées pour éviter les problèmes juridiques et de confidentialité des ensembles de données réels et pour générer des données synthetiques afin de les utiliser pour détecter la fraude.

Nous nous sommes concentrés sur la suréchantillonnage en utilisant des Réseaux Adversariaux Génératifs Conditionnels (CGANs), qui sont une extension du modèle GAN. Les GAN ont été introduits en 2014 par Ian J. Goodfellow dans l'article "Generative Adversarial Network". Les Réseaux Adversariaux Génératifs font partie de la catégorie des modèles génératifs, ce qui signifie qu'ils peuvent produire et de générer de nouveaux contenus. La différence entre les GAN et les CGAN est que le CGAN utilise des informations de conditionnement supplémentaires pour guider la génération.

Nous avons évalué deux types d'algorithmes sur deux bases de données, à savoir la base de données réelle et la base de données synthétique : la régression logistique et un réseau de neurones, puis nous avons comparé les résultats. Les résultats obtenus avec la base de données synthétique se sont révélés nettement meilleurs.

## 1. Prérequis
Ce projet nécessite les packages suivants pour fonctionner :
* [Python 3](https://www.python.org/)
* [Pandas](https://pandas.pydata.org/)
* [NumPy](https://numpy.org/)
* [MatPlotLib](https://matplotlib.org/)
* [Sklearn](https://scikit-learn.org/stable/)
* [Keras](https://keras.io/)
* [Keras](https://keras.io/)
* [YData-Synthetic](https://docs.greatexpectations.io/docs/0.15.50/deployment_patterns/how_to_use_great_expectations_with_ydata_synthetic/#:~:text=YData%2DSynthetic%20is%20an%20open,that%20resemble%20the%20original%20data.)
* [Tensorflow](https://www.tensorflow.org/install?hl=fr)

## 2. Fichiers
Ce projet est composé des fichiers suivants:
* Fraud_detection_and_data_simulation.ipynb -> Fichier principal qui contient le code.
* Synthetic_Financial_Datasets_For_Fraud_Detection.csv -> Base de données.

## 3. Execution du projet
Pour mettre en marche ce projet, importez le fichier **Fraud_detection_and_data_simulation.ipynb** dans Google Colab. Cela vous permettra de l'exécuter en utilisant processeur graphique de colab, réduisant ainsi les temps d'apprentissage. Assurez-vous également de télécharger la base de données **Synthetic_Financial_Datasets_For_Fraud_Detection.csv** dans votre espace Google Drive, puis exécutez les différentes cellules du projet.

