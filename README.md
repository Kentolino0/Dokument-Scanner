# 📸 Dokumentenscanner mit OpenCV

Dieses Projekt ist ein **einfacher Dokumentenscanner**, entwickelt mit **Python**, **OpenCV** und **NumPy**.  
Es erfasst ein Dokument über die Webcam, erkennt die größte Kontur (das Dokument), transformiert die Perspektive und erzeugt eine saubere, top-down Ansicht des gescannten Dokuments.

---

## 🚀 Funktionen

- Echtzeit-Dokumentenerkennung über die Webcam
- Bildvorverarbeitung (Graustufen ➔ Weichzeichnen ➔ Kantenerkennung ➔ Morphologische Transformationen)
- Konturenerkennung und Auswahl des größten Rechtecks
- Perspektivische Transformation (Warping)
- Gestapelter Workflow (Original ➔ bearbeitetes Bild ➔ erkannte Kontur ➔ gescanntes Dokument)

---

## 🛠 Verwendete Technologien

- **Python 3.9+**
- **OpenCV 4.x**
- **NumPy**

---

## 📷 Funktionsweise

1. **Erfassung** eines Bildes von der Webcam.
2. **Vorverarbeitung** des Bildes (Graustufen, Weichzeichnen, Kantenerkennung, Dilatation, Erosion).
3. **Erkennung von Konturen** und Auswahl der größten viereckigen Kontur (Dokument).
4. **Perspektivische Transformation** für eine gerade Aufsicht auf das Dokument.
5. **Anzeige** sowohl des Originals als auch des gescannten Ergebnisses nebeneinander.

---

## 🧩 Installation und Ausführung

1. Installiere die benötigten Bibliotheken:
   ```bash
   pip install opencv-python numpy
