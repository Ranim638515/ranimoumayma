# ranimoumayma
📌 Système Complet de Reconnaissance Faciale
Ce projet implémente une solution de reconnaissance faciale en deux parties :

1️⃣ Entraînement du Modèle (train_model.py)
Charge un dataset organisé (images par personne)

Détecte les visages via Haar Cascade

Extrait les features et entraîne un modèle LBPH

Sauvegarde :

Modèle (face_trained.yml)

Features/Labels (features.npy, labels.npy)

2️⃣ Reconnaissance Faciale (face_recognition.py)
Charge le modèle pré-entraîné

Détecte et reconnaît les visages dans une nouvelle image

Affiche :

🟢 Rectangle autour du visage

📝 Nom prédit + score de confiance

⚙️ Optionnel:
Un script supplémentaire(telechargement du dataset-lfw) permet de télécharger/structurer un dataset personnalisé.

Fonctionnalité clé : Système modulable pour reconnaissance faciale personnalisée avec apprentissage et prédiction.
