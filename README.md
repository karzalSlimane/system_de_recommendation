# system_de_recommendation



# 📌 Système de Recommandation de Films en Temps Réel

## 📝 Table des Matières
1. [Introduction](#introduction)
2. [Technologies Utilisées](#technologies-utilisées)
3. [Architecture du Projet](#architecture-du-projet)
4. [Installation et Configuration](#installation-et-configuration)
5. [Utilisation](#utilisation)
6. [Explication des Étapes](#explication-des-étapes)
7. [Résultats Attendus](#résultats-attendus)
8. [Conformité RGPD](#conformité-rgpd)
9. [Contributeurs](#contributeurs)
10. [Licence](#licence)

---

## 📌 1. Introduction
Ce projet vise à développer un système de recommandation de films en temps réel en exploitant les données de MovieLens. L'objectif est de collecter, traiter, analyser et présenter les recommandations aux utilisateurs en utilisant Apache Spark, Elasticsearch et Kibana.

## 🛠 Technologies Utilisées
- **Apache Spark** 🛠️ - Traitement des données
- **Elasticsearch** 🔎 - Stockage des recommandations
- **Kibana** 📊 - Visualisation
- **Flask (ou FastAPI)** ⚡ - API REST
- **Docker & Docker Compose** 🐳 - Conteneurisation

## 🏢 3. Architecture du Projet
![Architecture du projet](./architecture.png)  

## 🚀 4. Installation et Configuration

### 🔹 Prérequis
- Docker & Docker Compose
- Python 3.x

### 🔹 Lancer le projet
```bash
git clone https://github.com/karzalSlimane/system_de_recommendation.git  
cd repo  
docker-compose up -d  
```

## 💻 5. Utilisation
Une fois les services démarrés, accéder à :
- **API Flask** : `http://localhost:5000/recommend?movie=Inception`
- **Kibana** : `http://localhost:5601`

## 🔄 6. Explication des Étapes
1. **Prétraitement des données** avec Spark
2. **Entraînement du modèle** de recommandation (ALS)
3. **Indexation des données** dans Elasticsearch
4. **Développement de l'API** Flask pour récupérer les recommandations
5. **Visualisation des données** avec Kibana

## 📊 7. Résultats Attendus
- Top 10 des films populaires
- Distribution des genres
- Activité des utilisateurs
- Notes moyennes par film

## 🔒 8. Conformité RGPD
- Anonymisation des données utilisateur
- Suppression des données personnelles après une période définie
- Consentement explicite des utilisateurs



## 📚 9. Licence
Ce projet est sous licence MIT.
