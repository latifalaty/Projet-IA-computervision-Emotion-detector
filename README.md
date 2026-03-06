Emotion Detector / Détecteur d’émotions

Projet personnel : Détecte les émotions humaines à partir d’images ou d’une webcam grâce au deep learning.
Mon objectif était de combiner Computer Vision et Deep Learning pour créer une application pratique capable d’analyser les expressions faciales.

🛠️ Compétences et technologies utilisées

Python – programmation et scripts de détection

TensorFlow / Keras – entraînement et utilisation du modèle deep learning (emotion_detection_model.h5)

OpenCV – traitement d’images et capture vidéo

NumPy – manipulation de données

Machine Learning & Computer Vision – détection faciale et reconnaissance des émotions

📁 Structure du projet
Emotion-detector/
│
├── train/                       # Scripts et jeux de données pour l'entraînement
├── test/                        # Images de test
├── emotion_detection_model.h5   # Modèle pré-entraîné
├── emotion_detection_script.py  # Détection d’émotions (images et webcam)
├── reconnaissancefacial.py      # Détection faciale
└── README.md                     # Documentation
⚡ Utilisation

Détection sur image :

python emotion_detection_script.py --image path_to_image.jpg

Détection en direct avec webcam :

python emotion_detection_script.py --webcam

Reconnaissance faciale (optionnel) :

python reconnaissancefacial.py
📈 Objectifs et réalisations

Création d’un modèle capable de reconnaître plusieurs émotions (joie, tristesse, colère, surprise…).

Intégration d’une interface simple via scripts Python pour tester les images ou la webcam.

Déploiement d’un projet concret démontrant la maîtrise de Computer Vision, Deep Learning et de la manipulation de données.

