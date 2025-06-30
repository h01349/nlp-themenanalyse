# NLP-Themenanalyse (Anaconda Navigator 2.6.6 / JupyterLab 4.3.4 / Python 3.10.18)

Dieses Projekt analysiert eine Sammlung von Restaurantbewertungen aus dem Kaggle-Datensatz **„Yelp Restaurant Reviews“** mithilfe von NLP-Techniken wie TF-IDF, Sentence-Embeddings, LDA und BERTopic. Ziel ist die Extraktion häufig genannter Themen (vergleichbar mit kommunalen Beschwerden).

## Projektstruktur

- `env/` – Enthält die `environment.yml` zur Reproduzierbarkeit der Umgebung
- `notebooks/` – Jupyter-Notebooks zur Datenanalyse und Themenmodellierung
- `data/` – Beispielhafte oder anonymisierte Datensätze (optional)
- `output/` – Ergebnisse wie Visualisierungen, Topics, Modellzusammenfassungen
- `README.md` – Projektbeschreibung und Ausführungshinweise

## Anleitung

1. Umgebung erstellen (aus dem `env/`-Verzeichnis heraus): conda env create -f env/environment.yml
2. JupyterLab starten: jupyter lab
3. Notebooks aus dem Ordner `notebooks/` durchlaufen.

## Datenquelle

Datensatz: [Yelp Restaurant Reviews – Kaggle](https://www.kaggle.com/datasets/farukalam/yelp-restaurant-reviews)

---

*Hinweis:* Alle notwendigen Python-Bibliotheken und Versionen sind in der Datei `env/environment.yml` dokumentiert.
