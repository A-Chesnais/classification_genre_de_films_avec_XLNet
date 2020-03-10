
*** Comment est structuré ce répertoire ? ***

Dossier modélisation : contient les données et les deux notebooks de modélisation (baseline et XLNet)

Sous la racine : Le rapport de synthèse, contenant également une état de l'art des algorithmes de deep learning utilisés
		 pour des tâches de NLP



*** Comment utiliser ce répertoire ? ***

Pour consulter les résultats, il suffit d’ouvrir le rapport.

Le notebook de modélisation avec la baseline peut être ouvert avec jupyter notebook et exécuté.
Il ne nécessite pas de ressources particulières, si ce n’est les librairies suivantes :

- Pandas
- Numpy
- Sciait Learn
- Seaborg
- Matplotlib

Pour le notebook de modélisation avec XLNet, il est conseillé de l’éxécuter avec google colab car
très consommateur en ressources. La modélisation a été effectuée avec une GPU Tesla T4 (12Gb de RAM).
L’exécution dans Colab nécessite que les données soient placées dans un Google Drive, dans un dossier ’test_nlp’. 
Les librairies nécessaires quant à elles seront installées automatiquement.

Le code d'utilisation d'XLNet est basé sur le code de Josh Xin Jie Lee disponible à l'adresse suivante :

https://towardsdatascience.com/multi-label-text-classification-with-xlnet-b5f5755302df
