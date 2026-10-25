---
title: Maschinelles Lernen
weight: 2
image: images/Machine.png
papers:
  - title: Task Learning with Mechanical Neural Networks
    file: papers/Paper_TO_MNN_Bruno_Paschoal1.pdf
  - title: Classification with Hydraulic Neural Networks
    file: papers/Paper_TO_MNN_Bruno_Paschoal_Hidraulic.pdf
---
Mich interessiert maschinelles Lernen sowohl als Werkzeug für die Ingenieurarbeit als auch als etwas, das sich direkt in physische Materie einbauen lässt.

### Physikalische neuronale Netze
In meiner FAPESP-geförderten Forschung habe ich neuronale Netze entwickelt, die mit Physik statt mit Elektronik rechnen:

- ein **hydraulisches neuronales Netz**, dessen Rohrquerschnitte die trainierbaren Gewichte sind: Eingaben setzen die Randbedingungen, die stationäre Strömung kodiert die Klasse; validiert am Iris-Datensatz in COMSOL Multiphysics;
- ein **mechanisches neuronales Netz** auf nichtlinearen Fachwerken: Balkensteifigkeiten sind die lernbaren Parameter, äußere Lasten die Eingaben und Knotenverschiebungen die Ausgaben.

Beide wurden end-to-end mit gradientenbasierter Optimierung und adjungierten Sensitivitäten trainiert (COMSOL LiveLink for MATLAB), mit Blick auf Anwendungen wie intelligente Strukturen und Soft Robotics.

### ML für das Engineering
Am LPL der TUM entwickle ich **Surrogatmodelle**, die aufwendige Finite-Elemente-Simulationen in Optimierungsschleifen ersetzen.

### Zugehörige Module
Physikbasiertes Machine Learning, Machine Learning and Optimization (TUM) · Maschinelles Lernen und Mustererkennung bei Prof. Dr. Fabio Gagliardi Cozman, mit der numerischen Theorie des Lernens und der Implementierung von Klassifikationsalgorithmen (USP).
