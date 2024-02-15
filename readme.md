http://vision.stanford.edu/aditya86/ImageNetDogs/

The aim of this project is to explore the decision process of CNN for dog breed classification.

We use only the 10 dogs breed having the maximum amount of pictures ('Afghan_hound', 'Bernese_mountain_dog', 'Great_Pyrenees','Irish_wolfhound', 'Leonberg', 'Maltese_dog', 'Pomeranian','Samoyed', 'Scottish_deerhound', 'Shih-Tzu').



Objectif général 1: Entrainer 2 réseaux CNN pour la classification de races de chiens

	Objectif opérationnel 1.1: Transfert Learning
	-https://keras.io/api/applications/vgg/
	-https://keras.io/api/applications/inceptionv3/

	Objectif opérationnel 1.22: Optimiser les hyperparamètres
	-https://keras.io/keras_tuner/

	Objectif opérationnel 1.3: Evaluer les algorithmes de classification
	-https://scikit-learn.org/stable/modules/generated/sklearn.metrics.confusion_matrix.html
	-https://scikit-learn.org/stable/modules/generated/sklearn.metrics.classification_report.html

Objectif général 2: utiliser les algorithme XAI pour expliquer le processus de décision des CNN

	Objectif opérationnel 1.1: Lime, Tout type de données, Post-hoc, Local, Agnostique.
	-https://arxiv.org/abs/1602.04938 
	("Why Should I Trust You?": Explaining the Predictions of Any Classifier)

	Objectif opérationnel 1.2: GradCam, Image uniquement, Post-hoc, Local, Spécifique.
	-https://link.springer.com/article/10.1007/s11263-019-01228-7
	(Grad-CAM: Visual Explanations from Deep Networks via Gradient-Based Localization)
