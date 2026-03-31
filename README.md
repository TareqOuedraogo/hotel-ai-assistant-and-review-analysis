# hotel-ai-assistant-and-review-analysis
Ce projet développe des solutions d’intelligence artificielle pour améliorer l’expérience client d’un hôtel, en combinant l’analyse des avis clients, un assistant basé sur RAG (Retrieval-Augmented Generation) et un modèle fine-tuné adapté au contexte hôtelier.


# AI for Hospitality – Customer Insights & Intelligent Assistant

## Overview

Ce projet présente la conception d’un système d’intelligence artificielle appliqué au secteur hôtelier, combinant :

* l’analyse des avis clients (NLP)
* un assistant intelligent basé sur RAG (Retrieval-Augmented Generation)
* un modèle fine-tuné orienté expérience utilisateur

L’objectif est de transformer des données textuelles en décisions exploitables et en interactions client automatisées fiables.

---

## Problem Statement

Les hôtels collectent un grand volume d’avis clients, mais :

* ces données sont rarement exploitées efficacement
* les réponses aux clients sont souvent manuelles et incohérentes
* les chatbots classiques produisent des réponses peu fiables

Ce projet propose une approche basée sur l’IA pour résoudre ces problématiques.

---

## Proposed Solution

### Customer Review Analysis

* Nettoyage et préparation des données
* Analyse de sentiment (positif, négatif, neutre)
* Extraction de thèmes clés (service, propreté, localisation, etc.)
* Identification des problèmes récurrents

### RAG-based Assistant

* Recherche d’information dans des documents internes (FAQ, politiques)
* Génération de réponses basées sur des sources réelles
* Réduction des hallucinations des modèles de langage

### Fine-tuned Assistant

* Adaptation au ton et au contexte hôtelier
* Amélioration de la cohérence des réponses
* Meilleure expérience utilisateur

---

## Skills Demonstrated

* Natural Language Processing (NLP)
* Data preprocessing and feature engineering
* Sentiment analysis
* Retrieval-Augmented Generation (RAG)
* Fine-tuning of language models
* End-to-end AI system design

---

## Technical Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Transformers (Hugging Face)
* Large Language Models (OpenAI or open-source)
* Jupyter Notebook

---

## Data

* Dataset : `all_comments_ottawa.csv`
* Données réelles d’avis clients
* Documents internes simulés :

  * FAQ
  * politiques
  * informations sur les services

---

## Results

* Identification automatique des axes d’amélioration (ex : service, propreté)
* Amélioration de la qualité et de la cohérence des réponses client
* Réduction des hallucinations grâce au RAG
* Prototype fonctionnel d’assistant intelligent

---

## Project Structure

```
.
├── data/
├── notebooks/
├── models/
├── utils/
└── README.md
```

---

## Future Improvements

* Déploiement en application web (Streamlit, FastAPI)
* Intégration avec un chatbot en production
* Dashboard d’analyse des avis clients
* Support multilingue

---

## Profile

Étudiant en intelligence artificielle avec une approche orientée projets :

* plus de 20 projets réalisés en IA
* expérience en NLP, computer vision et systèmes intelligents
* développement de solutions complètes de bout en bout

Actuellement à la recherche d’opportunités en IA / Data Science (stage ou emploi).

---

## Contact

Disponible pour discuter du projet ou d’opportunités professionnelles.
