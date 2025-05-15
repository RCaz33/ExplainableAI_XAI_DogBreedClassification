
# 🐶 Dog Breed Classification with Explainable AI (XAI)

Bienvenue dans ce projet de classification de races de chiens utilisant l’**apprentissage profond** et des **algorithmes d’explicabilité (XAI)** !  
L'objectif est de comprendre les décisions prises par des réseaux de neurones convolutifs (CNN) grâce à des outils d’interprétabilité.

🔗 Dataset utilisé : [Stanford Dogs Dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/)  
📁 Ce projet se concentre sur **10 races de chiens** uniquement.

---

## 📂 Structure du projet

```bash
Cazelles_Remi_projet7/
│
├── Cazelles_remi_rapport_102023.pdf                # Rapport détaillé
├── Remi_Cazelles_presentation_102023.pptx          # Présentation PowerPoint
│
├── code/                                           # 📊 Dossiers notebooks et scripts
│   ├── XAI_DogBreedClass_TrainModel_InceptionV3.ipynb    # Entraînement avec InceptionV3
│   ├── XAI_DogBreedClass_TrainModel_VGG16.ipynb          # Entraînement avec VGG16
│   ├── XAI_GradCam_InceptionV3.ipynb                     # Grad-CAM pour InceptionV3
│   ├── XAI_GradCam_VGG16.ipynb                           # Grad-CAM pour VGG16
│
├── BARD prompt for explainable ML algorithm.docx   # Prompt pour génération IA
├── .gitignore
└── readme.md
```

---

## 🎯 Objectifs du projet

### 🧠 Objectif général 1 : Entraîner 2 modèles CNN pour la classification

#### 📌 Objectif opérationnel 1.1 : Transfert Learning
- Utilisation de [VGG16](https://keras.io/api/applications/vgg/) et [InceptionV3](https://keras.io/api/applications/inceptionv3/)

#### 📌 Objectif opérationnel 1.2 : Optimisation des hyperparamètres
- Grâce à [Keras Tuner](https://keras.io/keras_tuner/)

#### 📌 Objectif opérationnel 1.3 : Évaluation des performances
- [Confusion matrix](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.confusion_matrix.html)
- [Classification report](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.classification_report.html)

---

### 🔍 Objectif général 2 : Expliquer les décisions des modèles via XAI

#### 📌 Objectif opérationnel 2.1 : LIME (Local Interpretable Model-agnostic Explanations)
- Agnostique, post-hoc, local, tout type de données  
- 📄 Paper : [“Why Should I Trust You?”](https://arxiv.org/abs/1602.04938)

#### 📌 Objectif opérationnel 2.2 : Grad-CAM (Gradient-weighted Class Activation Mapping)
- Spécifique aux images, post-hoc, local  
- 📄 Paper : [Grad-CAM](https://link.springer.com/article/10.1007/s11263-019-01228-7)

---

## 🛠️ Technologies utilisées

- 🐍 Python
- 🧠 TensorFlow / Keras
- 📊 Scikit-learn
- 📈 Matplotlib, Seaborn
- 🪄 Keras Tuner
- 📷 Grad-CAM
- 📋 LIME

---

## 📎 Ressources complémentaires

- Dataset : [Stanford Dogs](http://vision.stanford.edu/aditya86/ImageNetDogs/)
- Frameworks CNN : [Keras Applications](https://keras.io/api/applications/)
- Interprétabilité : LIME, Grad-CAM

---

## 🙋‍♂️ Auteur

Projet réalisé par **Rémi Cazelles** dans le cadre du projet 7 de la formation Data Scientist.
