---
title: Optimierung
weight: 1
image: images/Topologic.png
papers:
  - title: Topologieoptimierung elektrischer Maschinen
    file: papers/Paper_TO___Electric_Machines.pdf
---
Numerische Optimierung ist der rote Faden meiner Arbeit: Ein Algorithmus, nicht allein die Intuition, entscheidet, wie ein System gestaltet sein soll.

### Topologieoptimierung
Die Topologieoptimierung verändert die Materialverteilung in einem Designraum, um die Leistung eines Systems zu maximieren. Als FAPESP-Stipendiat am Multiphysics Systems Optimization Laboratory (MSOL) der USP habe ich einen eigenen Algorithmus zur Optimierung **geschalteter Reluktanzmotoren** entwickelt:

- thermomagnetische Finite-Elemente-Modelle auf der Open-Source-Plattform **FEniCS**, mit **dolfin-adjoint** für die Sensitivitäten und **IPOPT** als Optimierer;
- deutliche Materialeinsparung bei messbar höherem Wirkungsgrad;
- Erweiterung auf **diskrete Multimaterial-Optimierung** mit TOBS, validiert mit kommerzieller Software.

### Designoptimierung an der TUM
Am Lehrstuhl für Produktentwicklung und Leichtbau (LPL) der TUM arbeite ich an **multidisziplinärer Designoptimierung** und der **Lösungsraum-Methode (Solution Spaces)**, die statt eines einzelnen Optimums ganze Bereiche guter Entwürfe findet. Ich entwickle Surrogatmodelle, die aufwendige Finite-Elemente-Analysen ersetzen, und betreue die Optimization Toolbox des Lehrstuhls. Mit einem bayerischen Industriepartner haben wir die Methode auf einen Bodenverdichtungs-Motorhammer angewendet und so Leistung und Arbeitssicherheit verbessert.

### Zugehörige Module
Multidisciplinary Design Optimization, Optimal Control and Decision Making, Machine Learning and Optimization, Numerische Methoden für Erhaltungsgleichungen (TUM) · Numerische Methoden und Anwendungen, Numerische Mechanik für die Mechatronik (USP).
