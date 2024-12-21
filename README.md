# AI_Vehicle_classification_Wicki
Dieses Projekt befasst sich mit der Bildklassifikation verschiedener Fahrzeuge.
Die Bilder werden mit unterschiedlichen Modellen trainiert und klassifiziert.
Anschlieend werden die Modelle anhand verschiedener Merkmale miteinander verglichen.

# Übersicht
Dieses Verzeichnis enthält zwei Jupyter Notebooks, die Machine-Learning-Modelle mit neuronalen Netzen untersuchen und implementieren. Die Dateien sind:

1. **CNN_RELU.ipynb**: Implementiert ein Convolutional Neural Network (CNN) mit ReLU-Aktivierungsfunktionen.
2. **hugging_face_efficient_net.ipynb**: Nutzt ein vortrainiertes Modell von Hugging Face, basierend auf der EfficientNet-Architektur.

# CNN_RELU.ipynb
- Ziel: Aufbau und Training eines CNN mit ReLU-Aktivierungsfunktionen.
- Kernpunkte:
  - Modellarchitektur: Schichtenaufbau und Verwendung von ReLU zur Aktivierung.
  - Training: Aufbereitung von Daten und Optimierung des Modells.
  - Evaluation: Messung der Performance auf Validierungsdaten.

# hugging_face_efficient_net.ipynb
- Ziel: Einsatz eines vortrainierten EfficientNet-Modells.
- Kernpunkte:
  - Modellinitialisierung: Laden des Modells über die Hugging Face Bibliothek.
  - Transfer Learning: Feinabstimmung des Modells auf spezifische Daten.
  - Inferenz: Vorhersagen mit den feingetunten Gewichten.