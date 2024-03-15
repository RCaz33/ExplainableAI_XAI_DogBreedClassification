http://vision.stanford.edu/aditya86/ImageNetDogs/

Le but de ce projet est d'explorer le processus de decision de classification de race de chien ar un réseau de neurone convolutif à l'aide d'algorithmes d'explicabilité (XAI)

Nous n'utilisons que 10 race de chiens pour entrainer 2 réseaux de neuronnes par transfert learning (VGG16, inceptionV3) dont la prise de décision sera analysé avec 2 XAI (LIME, GradCam).

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
