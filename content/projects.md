---
title: "Titanic – Machine Learning from Disaster"
date: 2025-02-25
summary: "Ein Machine-Learning-Projekt zur Vorhersage der Überlebenschancen von Titanic-Passagieren mit Fokus auf Datenanalyse, Feature Engineering und Modellauswahl."
tags: [Machine Learning, KI, Python, Scikit-Learn, Titanic]
categories: [KI-Projekt]
thumbnail: images/titanic.jpg
links:
  - icon: kaggle
    icon_pack: fab
    name: Titanic Dataset (Kaggle)
    url: https://www.kaggle.com/competitions/titanic/overview
---

In diesem Projekt wurde der berühmte Titanic-Datensatz verwendet, um ein Klassifikationsmodell zur Vorhersage der Überlebenschancen von Passagieren zu entwickeln.

### 🔍 Ziele
- Untersuchung von Korrelationen zwischen Merkmalen wie **Geschlecht**, **Alter**, **Ticketklasse** und **Überleben**
- Umsetzung mehrerer Algorithmen:
  - **Naive Bayes**
  - **Logistische Regression**
  - **K-Nearest Neighbors (KNN)**

### ⚙️ Methoden
- **Datenvorverarbeitung:** Umgang mit fehlenden Werten (Median, lineare Regression), One-Hot-Encoding, Entfernen irrelevanter Spalten
- **Feature Engineering:** Erzeugung neuer Merkmale wie `FamilySize`, `IsAloneTicket`, `TicketFrequency`
- **Modelltraining & Hyperparameter-Tuning:** mit Grid Search optimiert

### 📊 Ergebnisse
- Bestes Modell: **KNN mit k=10** – **Accuracy: 83.62%**
- Logistische Regression: **Accuracy: 80.62%**
- Naive Bayes: **Accuracy: 78.71%**

### 📚 Learnings
- Feature Engineering hatte signifikanten Einfluss auf die Modellqualität.
- Modelle mit klarer Interpretierbarkeit (z. B. logistische Regression) sind für solche Datensätze gut geeignet.
- Weitere Verbesserungen wären mit Random Forest oder Ensemble-Methoden möglich.

> Projektteam: Amirmahan Tajik, Christian Reikischke, Helene Nicolai, Marharyta Horak, Merna Mohsen
