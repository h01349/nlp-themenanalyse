# NLP-Themenanalyse 
Dieses Projekt analysiert eine Sammlung von Restaurantbewertungen aus dem Kaggle-Datensatz **„Yelp Restaurant Reviews“** mithilfe von NLP-Techniken: TF-IDF, Sentence-Embeddings, LDA und BERTopic. Ziel ist die Extraktion häufig genannter Themen (vergleichbar mit kommunalen Beschwerden).

**Hinweis zur Ausführungsumgebung:** Die Umsetzung erfolgte unter Windows 11 mit Anaconda Navigator 2.6.6, JupyterLab 4.3.4 und Python 3.10.18. Die verwendeten Befehle und Pfade wurden so gestaltet, dass sie grundsätzlich auch auf anderen Plattformen lauffähig sein sollten.
Eine plattformübergreifende Testung war jedoch nicht Bestandteil dieses Projekts.

## Projektstruktur

- `env/` – Enthält die `environment.yml` zur Reproduzierbarkeit der Umgebung
- `notebooks/` – Jupyter-Notebooks zur Datenanalyse und Themenmodellierung
- `data/` – Ursprungs- und verarbeitete Datensätze (CSV, NPY)
- `README.md` – Projektbeschreibung und Hinweise zur Ausführung

## Anleitung zur Ausführung

**1. Umgebung erstellen:**  
Die Analyseumgebung basiert auf der Datei `environment.yml`, die sich im Verzeichnis `env/` befindet.
Sie kann entweder über den Anaconda Navigator (GUI) oder das Terminal eingerichtet werden:
- Anaconda Navigator: Environment importieren über „Environments → Import“ (dabei die `environment.yml` aus dem lokalen Verzeichnis `env/` auswählen)
- Terminal: `conda env create -f env/environment.yml`

**2. JupyterLab starten:**  
Nach Erstellung und Aktivierung der Umgebung kann JupyterLab auf zwei Arten gestartet werden:
- Anaconda Navigator: Über „Home → JupyterLab → Launch“
- Terminal: Aktivieren Sie zunächst die Umgebung mit `conda activate <env-name>` und starten Sie anschließend JupyterLab mit `jupyter lab`.

**3. Notebooks ausführen:**  
Die Analyse besteht aus fünf aufeinander aufbauenden Notebooks im Verzeichnis `notebooks/`.
Diese sollten in numerischer Reihenfolge (001 bis 005) geöffnet und schrittweise ausgeführt werden.
Die Ergebnisse bauen jeweils auf den vorherigen Schritten auf.

## Datenquelle

Datensatz: [Yelp Restaurant Reviews – Kaggle](https://www.kaggle.com/datasets/farukalam/yelp-restaurant-reviews)

---

*Hinweis:* Dieses Repository ist **temporär öffentlich** für die Überprüfung im Rahmen eines Projekts.
