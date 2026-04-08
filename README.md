# Replikationsarbeit zur Arbeit Artificial Hiveminds Jiang et al. 2025: The Open-Ended Homogeneity of Language Models (and Beyond)

Dieses Verzeichnis beinhaltet den Quellcode für die Replikation der Intra- und Intermodellhomogenitäten nach Jiang et al. 2025.

## Directory Overview

```
data_mining_projekt/
└── artificial-hivemind-main/
        └── src/
            ├── data_construction/
            ├── human_annotations/
            └── model_calibration_analysis/
└── Generate/
        └── Antworten/
└── Embeddings/
        └── embeddings_json/
└── Similarity/
        └── eigenanteil/
        └── replikation/

```

### `Generate/`

Beinhaltet ein Jupyter Notebook als Skript für die Generierung von Antworten auf den INFINITYCHAT100 Datensatz.
Zusätzlich sind alle generierten Antworten als Textdatein abgelegt.

### `Embeddings/`

Beinhaltet ein Jupyter Notebook als Skript für die Nutzung der OpenAI Platform API für die Anfrage des Embedding-Modells "text-embedding-3-small".
Zusätzlich ist ein Skript enthalten, das JSON-Datein mit Embeddings im korrekten Format zusammenführen kann und alle generierten Embeddings aus den Antworten.

### `Similarity/`

Beinhaltet zwei Jupyter Notebooks als Skripte für die Berechnung und grafische Darstellung der Intra- und Intermodellhomogenität.
Zusätzlich sind die relevanten Embeddings für die Berechnung der Homogenitäten in den Unterordnern `eigenanteil/` und `replikation/` hinterlegt.
