---
title: "Titanic – Machine Learning from Disaster"
date: 2025-02-25
summary: "Ein Machine-Learning-Projekt zur Vorhersage der Überlebenschancen von Titanic-Passagieren mit Fokus auf Datenanalyse, Feature Engineering und Modellauswahl."
tags: [Machine Learning, KI, Python, Scikit-Learn, Titanic]
categories: [KI-Projekt]
thumbnail: https://mahntk.github.io/uploads/titanic.jpg
links:
  - icon: kaggle
    icon_pack: fab
    name: Titanic Dataset (Kaggle)
    url: https://www.kaggle.com/competitions/titanic/overview
---

### 🧠 Titanic – Machine Learning from Disaster

In diesem KI-Projekt habe ich gemeinsam mit meinem Team den berühmten **Titanic-Datensatz** aus Kaggle analysiert, um die **Überlebenswahrscheinlichkeit von Passagieren vorherzusagen**.

#### 🔍 Vorgehensweise:
- **Datenvorverarbeitung:** Umgang mit fehlenden Werten (Median, lineare Regression), Entfernung irrelevanter Spalten, Umwandlung kategorialer Daten in numerische Form.
- **Datenanalyse:** Untersuchung der Korrelationen – etwa Geschlecht, Ticketklasse und Preis als starke Prädiktoren für Überleben.
- **Feature Engineering:** Neue Merkmale wie `FamilySize`, `IsAloneTicket` und `TicketFrequency` wurden erstellt, um die Modellleistung zu verbessern.

#### 🧪 Modellierung:
Es wurden drei verschiedene Algorithmen implementiert:
- **Naive Bayes:** Einfach und schnell, aber sensibel gegenüber Annahmen.
- **Logistische Regression:** Gute Balance aus Genauigkeit und Interpretierbarkeit.
- **K-Nearest Neighbors (KNN):** Sehr gute Performance mit optimalem `k` durch Grid Search.

#### ⚙️ Ergebnisse:
| Modell                | Genauigkeit |
|-----------------------|-------------|
| **KNN (k=10)**        | **83.62 %** |
| Logistische Regression| 80.62 %     |
| Naive Bayes           | 78.71 %     |

#### 📊 Visualisierung:

![Modellvergleich](https://mahntk.github.io/uploads/modellvergleich_gridsearch.png)

![Überlebensrate](https://mahntk.github.io/uploads/ueberlebensrate.png)

![Korrelationen](https://mahntk.github.io/uploads/korrelation.png)



#### 📚 Learnings:
- **Feature Engineering** hatte einen großen Einfluss auf die Modellqualität.
- **KNN** zeigte das beste Ergebnis mit sorgfältiger Merkmalsauswahl und Tuning.
- Weitere Verbesserungen wären durch Modelle wie **Random Forests** oder **Ensemble-Methoden** möglich.

> 👥 Team: Amirmahan Tajik, Christian Reikischke, Helene Nicolai, Marharyta Horak, Merna Mohsen  
> 🔗 [Zum Datensatz auf Kaggle](https://www.kaggle.com/competitions/titanic/overview)
---