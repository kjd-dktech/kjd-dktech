# Données des projets — prêtes à copier-coller

> Ce fichier contient les informations de chaque projet à renseigner dans le formulaire du site **mayal.tech**.  
> Chaque bloc commence par `## PROJET N` et liste tous les champs du formulaire.  
> Les champs marqués `[image à uploader]` nécessitent une capture d'écran ou illustration à fournir manuellement.

---

## PROJET 1 — GbeTo (Ewé ↔ Français)

```
Titre
GbeTo — Traducteur Ewé ↔ Français

Slug
gbeto-ewe-fr

Description courte
Fine-tuning du modèle NLLB-200-distilled-600M (Meta AI) pour la traduction neurale
bidirectionnelle Ewé ↔ Français — NLP pour une langue africaine à faibles ressources.

Image de couverture
[image à uploader — ex. capture de la démo Hugging Face Spaces]

Texte alternatif
Interface de démonstration du modèle GbeTo de traduction Ewé ↔ Français sur HuggingFace Spaces

Catégorie
NLP & LLM

Stack technique
Python, PyTorch, HuggingFace Transformers, NLLB-200, seq2seq, sacrebleu, Gradio

Tags
NLP, traduction automatique, langues africaines, Ewé, fine-tuning, transformers, low-resource

URL Live
https://huggingface.co/spaces/kjd-dktech/gbeto-ewe-french-demo

URL GitHub
https://github.com/kjd-dktech/GbeTo_ewe-fr

URL Drive
(vide)

Mis en avant
Oui

Description détaillée
Fine-tuning du modèle de traduction automatique neurale NLLB-200-distilled-600M de Meta AI
pour la traduction bidirectionnelle entre l'Ewé (langue gbe d'Afrique de l'Ouest à faibles
ressources, ma langue maternelle) et le Français.

Le projet couvre :
- Collecte et prétraitement d'un corpus parallèle Ewé–Français
- Fine-tuning avec l'API Hugging Face Trainer (PyTorch back-end)
- Évaluation quantitative avec la métrique sacrebleu (score BLEU)
- Déploiement d'une démo interactive sur Hugging Face Spaces via Gradio
- Publication du modèle fine-tuné sur le Hub Hugging Face

Résultat : score BLEU passé de 13,41 (baseline) à 16,70 après fine-tuning,
soit une amélioration de +24,5 %.

Date
2026-03-12
```

---

## PROJET 2 — Credit Risk Scoring

```
Titre
Credit Risk Scoring

Slug
credit-risk-scoring

Description courte
Application ML full-stack de prédiction du risque de crédit : modèle scikit-learn servi
via FastAPI, explicabilité SHAP, dashboard Next.js, déploiement Docker Compose en une commande.

Image de couverture
[image à uploader — ex. capture du dashboard ou de la page de résultat de scoring]

Texte alternatif
Dashboard de scoring de crédit affichant la probabilité de défaut et les valeurs SHAP explicatives

Catégorie
Machine Learning

Stack technique
Python, scikit-learn, SHAP, FastAPI, Next.js, Tailwind CSS, Docker, Jupyter

Tags
machine learning, crédit, scoring, risque financier, SHAP, FastAPI, Docker, inclusion financière

URL Live
https://kjd-dktech-credit-risk-scoring-web.hf.space/

URL GitHub
https://github.com/kjd-dktech/CreditRiskScoring

URL Drive
(vide)

Mis en avant
Oui

Description détaillée
Système complet de prédiction du risque de défaut de remboursement d'un prêt, dans le cadre
de l'inclusion financière.

Pipeline end-to-end :
- EDA + feature engineering sur données financières
- Modélisation scikit-learn (classification supervisée, optimisation des hyperparamètres)
- API REST FastAPI exposant le modèle en production
- Dashboard Next.js / Tailwind CSS pour la saisie des données et la visualisation des résultats
- Intégration de SHAP pour l'explicabilité locale et globale des prédictions
- Déploiement one-command via Docker Compose
- Hébergement sur Hugging Face Spaces

Date
2025-11-02
```

---

## PROJET 3 — ForestWatch Togo

```
Titre
ForestWatch Togo — Classification de couverture terrestre par IA

Slug
land-cover-ml-sentinel2

Description courte
Système IA de bout en bout pour la classification de la couverture terrestre et le suivi
de la déforestation au Togo, à partir d'images satellitaires Sentinel-2 et Google Earth Engine.

Image de couverture
[image à uploader — ex. carte de classification ou image satellite du Togo]

Texte alternatif
Carte de classification de la couverture terrestre au Togo générée par le modèle ML à partir d'images Sentinel-2

Catégorie
Data Engineering

Stack technique
Python, Sentinel-2, Google Earth Engine, scikit-learn, GeoPandas, Rasterio, Matplotlib, Jupyter

Tags
remote sensing, télédétection, déforestation, Togo, Sentinel-2, Google Earth Engine, machine learning, géospatial

URL Live
(vide)

URL GitHub
https://github.com/kjd-dktech/land-cover-ml-sentinel2

URL Drive
(vide)

Mis en avant
Oui

Description détaillée
Système IA de bout en bout pour la cartographie de la couverture terrestre et le suivi
de la déforestation au Togo, combinant données satellitaires et machine learning.

Étapes du pipeline :
- Ingestion d'images multispectrales Sentinel-2 via Google Earth Engine (GEE)
- Prétraitement : masquage nuages, calcul d'indices spectraux (NDVI, NDWI, EVI)
- Extraction de features et constitution du dataset d'entraînement (points d'échantillonnage géoréférencés)
- Classification ML (Random Forest, SVM) pour l'attribution d'une classe de couverture terrestre
- Évaluation des modèles (matrice de confusion, précision/rappel/F1 par classe)
- Génération de cartes de couverture terrestre et de cartes de changement (déforestation)

Applicable au suivi environnemental et à la gestion durable des forêts tropicales.

Date
2025-05-22
```

---

## PROJET 4 — OCR CNN MNIST

```
Titre
OCR — Reconnaissance de chiffres manuscrits par CNN

Slug
ocr-cnn-mnist

Description courte
Conception et entraînement d'un réseau de neurones convolutif (CNN) pour la reconnaissance
optique de chiffres manuscrits sur le dataset MNIST — pipeline complet jusqu'aux artefacts Keras.

Image de couverture
[image à uploader — ex. grille d'exemples MNIST avec prédictions ou architecture du réseau]

Texte alternatif
Exemples de chiffres manuscrits MNIST correctement classifiés par le modèle CNN entraîné

Catégorie
Machine Learning

Stack technique
Python, TensorFlow, Keras, NumPy, OpenCV, scikit-learn, Matplotlib, Seaborn, Jupyter

Tags
deep learning, CNN, MNIST, OCR, classification, vision par ordinateur, Keras, TensorFlow

URL Live
(vide)

URL GitHub
https://github.com/kjd-dktech/ocr-cnn-mnist

URL Drive
(vide)

Mis en avant
Oui

Description détaillée
Reconnaissance de caractères manuscrits (chiffres 0–9) à l'aide d'un réseau de neurones
convolutif (CNN) profond entraîné sur le dataset MNIST (70 000 images).

Pipeline complet :
- Prétraitement des images (normalisation, reshape, augmentation de données)
- Construction de l'architecture CNN : couches Conv2D → MaxPooling → BatchNorm → Dropout → Dense
- Entraînement avec callbacks (EarlyStopping, ModelCheckpoint, ReduceLROnPlateau)
- Évaluation : matrice de confusion, rapport de classification, courbes d'apprentissage
- Sauvegarde des artefacts Keras (.keras / .h5) pour déploiement

Ce projet démontre la maîtrise complète des réseaux convolutifs pour la vision par ordinateur.

Date
2025-10-27
```

---

## PROJET 5 — MathNode

```
Titre
MathNode — Chatbot Mathématique IA

Slug
mathnode

Description courte
Chatbot spécialisé en sciences mathématiques combinant un LLM et SymPy pour répondre à
des questions, expliquer des solutions étape par étape et générer des exercices interactifs.

Image de couverture
[image à uploader — ex. capture de l'interface du chatbot avec une résolution d'équation]

Texte alternatif
Interface du chatbot MathNode affichant une résolution d'équation différentielle étape par étape

Catégorie
NLP & LLM

Stack technique
Python, LLM, SymPy, Gradio, FastAPI

Tags
LLM, chatbot, mathématiques, calcul symbolique, SymPy, quiz interactif, IA générative

URL Live
(vide)

URL GitHub
https://github.com/kjd-dktech/MathNode

URL Drive
(vide)

Mis en avant
Non

Description détaillée
MathNode est un assistant mathématique intelligent combinant un modèle de langage (LLM)
avec SymPy (bibliothèque de calcul symbolique Python) pour offrir une aide mathématique avancée.

Capacités :
- Répondre à des questions en algèbre, calcul différentiel, géométrie et statistiques
- Expliquer chaque étape de la résolution avec un raisonnement clair
- Générer des exercices et quiz interactifs adaptés au niveau de l'utilisateur
- Vérification symbolique des résultats via SymPy (résolution exacte d'équations, dérivées, intégrales)

Projet en développement visant à démocratiser l'accès à un tutorat mathématique intelligent.

Date
2026-01-26
```

---

## PROJET 6 — Perceptron Lab

```
Titre
Perceptron Lab — Réseaux de neurones from scratch

Slug
perceptron-lab

Description courte
Implémentation from scratch d'un perceptron et d'un réseau de neurones à deux couches avec
NumPy — poids, activations, rétropropagation et descente de gradient, sans framework ML.

Image de couverture
[image à uploader — ex. graphique de convergence de la loss ou schéma du réseau]

Texte alternatif
Courbe de convergence de la descente de gradient lors de l'entraînement du réseau de neurones

Catégorie
Machine Learning

Stack technique
Python, NumPy, Matplotlib, Jupyter

Tags
perceptron, réseau de neurones, from scratch, backpropagation, descente de gradient, machine learning

URL Live
(vide)

URL GitHub
https://github.com/kjd-dktech/perceptron-lab

URL Drive
(vide)

Mis en avant
Non

Description détaillée
Implémentation pédagogique et rigoureuse d'un perceptron simple et d'un réseau de neurones
entièrement connecté à deux couches cachées, codés from scratch avec NumPy uniquement.

Couvre l'ensemble de la mécanique d'un réseau de neurones :
- Initialisation et mise à jour des poids (He / Xavier)
- Fonctions d'activation : Sigmoïde, ReLU, Tanh
- Calcul de la perte (log-likelihood / cross-entropy, MSE)
- Rétropropagation manuelle (calcul des gradients couche par couche)
- Mise à jour des poids par descente de gradient (batch, mini-batch, SGD)
- Visualisation des courbes d'apprentissage (loss / accuracy par époque)

Ce projet démontre une compréhension approfondie des fondements mathématiques du deep learning.

Date
2025-05-18
```

---

## PROJET 7 — ML Data Analysis Pipeline

```
Titre
ML Data Analysis Pipeline

Slug
ml-data-analysis-pipeline

Description courte
Pipeline complet d'analyse exploratoire de données et de modélisation ML sur des datasets
emblématiques (Iris, Penguins, Titanic) — KNN, Decision Tree, SVM comparés.

Image de couverture
[image à uploader — ex. graphique EDA (heatmap de corrélation ou pairplot)]

Texte alternatif
Heatmap de corrélation et pairplot générés lors de l'analyse exploratoire du dataset Titanic

Catégorie
Machine Learning

Stack technique
Python, scikit-learn, Pandas, NumPy, Matplotlib, Seaborn, Jupyter

Tags
EDA, analyse de données, KNN, SVM, decision tree, Titanic, Iris, Penguins, machine learning

URL Live
(vide)

URL GitHub
https://github.com/kjd-dktech/ml-data-analysis-pipeline

URL Drive
(vide)

Mis en avant
Non

Description détaillée
Pipeline académique complet d'analyse exploratoire de données (EDA) et de modélisation
Machine Learning sur trois datasets classiques.

Datasets traités :
- Iris : classification d'espèces florales (KNN, SVM, Decision Tree)
- Penguins (Palmer) : classification d'espèces de manchots
- Titanic : prédiction de survie (feature engineering avancé, gestion des valeurs manquantes)

Pour chaque dataset :
- EDA approfondie : distributions, boxplots, heatmaps de corrélation, pairplots
- Feature engineering : encodage, normalisation, sélection de variables
- Entraînement de modèles : KNN, Decision Tree, SVM avec cross-validation
- Comparaison des modèles et sélection du meilleur par critère (accuracy, F1, AUC)

Date
2025-05-22
```

---

## PROJET 8 — QuickNotes

```
Titre
QuickNotes — Application de prise de notes

Slug
quicknotes

Description courte
Application légère de prise de notes développée avec Next.js et React — interface moderne
Tailwind CSS, routing App Router, TypeScript, et persistance locale.

Image de couverture
[image à uploader — ex. capture de l'interface de l'application avec la liste de notes]

Texte alternatif
Interface de l'application QuickNotes montrant la liste des notes et l'éditeur de texte

Catégorie
Web & API

Stack technique
TypeScript, Next.js, React, Tailwind CSS

Tags
Next.js, React, TypeScript, Tailwind CSS, prise de notes, application web, frontend

URL Live
(vide)

URL GitHub
https://github.com/kjd-dktech/quicknotes

URL Drive
(vide)

Mis en avant
Non

Description détaillée
Application de prise de notes légère et intuitive, développée comme exercice d'apprentissage
approfondi du framework Next.js avec App Router.

Fonctionnalités :
- Création, édition et suppression de notes
- Interface moderne et réactive avec Tailwind CSS
- Persistance locale des notes (localStorage / API route)
- Architecture Next.js App Router (Server Components, Client Components)
- Typage strict TypeScript sur l'ensemble du projet

Ce projet démontre la maîtrise des fondamentaux de Next.js, React et du développement
frontend moderne avec TypeScript.

Date
2025-06-16
```
