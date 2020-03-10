
*** Comment est structur� ce r�pertoire ? ***

Dossier mod�lisation : contient les donn�es et les deux notebooks de mod�lisation (baseline et XLNet)

Sous la racine : Le rapport de synth�se, contenant �galement une �tat de l'art des algorithmes de deep learning utilis�s
		 pour des t�ches de NLP



*** Comment utiliser ce r�pertoire ? ***

Pour consulter les r�sultats, il suffit d�ouvrir le rapport.

Le notebook de mod�lisation avec la baseline peut �tre ouvert avec jupyter notebook et ex�cut�.
Il ne n�cessite pas de ressources particuli�res, si ce n�est les librairies suivantes :

- Pandas
- Numpy
- Sciait Learn
- Seaborg
- Matplotlib

Pour le notebook de mod�lisation avec XLNet, il est conseill� de l��x�cuter avec google colab car
tr�s consommateur en ressources. La mod�lisation a �t� effectu�e avec une GPU Tesla T4 (12Gb de RAM).
L�ex�cution dans Colab n�cessite que les donn�es soient plac�es dans un Google Drive, dans un dossier �test_nlp�. 
Les librairies n�cessaires quant � elles seront install�es automatiquement.

Le code d'utilisation d'XLNet est bas� sur le code de Josh Xin Jie Lee disponible � l'adresse suivante :

https://towardsdatascience.com/multi-label-text-classification-with-xlnet-b5f5755302df
