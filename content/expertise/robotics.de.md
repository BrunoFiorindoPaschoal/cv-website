---
title: Robotik
weight: 3
image: images/Robotics.svg
---
In der Robotik muss alles aus der Mechatronik gleichzeitig funktionieren: Mechanik, Elektronik, Regelung und Software.

## Seilgeführtes Positioniersystem (PI7)

<img class="feature-image" src="/images/Robotics.svg" alt="Illustration des seilgeführten Positioniersystems: zwei Motortrommeln auf Türmen halten Seile, an denen eine Nutzlast hängt">

Im Integrierten Projekt 7 an der USP (2025) hat unser Achterteam einen **Seilroboter nach dem Spidercam-Prinzip** gebaut. Zwei Gleichstrommotoren oben am Rahmen wickeln Seiltrommeln auf und ab; über die beiden Seillängen bewegt das System eine hängende Nutzlast an jeden Punkt einer vertikalen Ebene.

Das Projekt deckte alle vier Säulen der Mechatronik in einem selbst gebauten System ab:

- **Mechanik:** Rahmen und Trommelmechanik, vom Team konstruiert und gefertigt.
- **Elektronik:** eigene Motortreiberplatinen (in DipTrace entworfen) mit der L298N-Doppel-H-Brücke, beide Brücken parallel für höhere Ströme, ein 7805-Spannungsregler für die Logikversorgung und ein 26-poliges Flachbandkabel zu den Steuerplatinen.
- **Regelung:** Der Motor wurde aus Sprungantworten als System erster Ordnung identifiziert; ein **PID-Positionsregler** wurde zuerst in MATLAB und dann experimentell an der fertigen Struktur eingestellt. Er läuft pro Motor auf einem PIC16F886-Mikrocontroller, liest einen Inkrementalgeber (1920 Impulse pro Umdrehung) und steuert den Motor per PWM an.
- **Informatik:** Ein Raspberry Pi Pico W empfängt Befehle vom PC (USB oder WLAN) und sendet Sollwerte seriell an beide Motorsteuerungen.

Das Ergebnis war ein stabiles, reaktionsschnelles System, das Befehle empfing, die Motoren ansteuerte und die Position in Echtzeit maß. Die wichtigste Einschränkung, unterschiedliche Getriebeübersetzungen der beiden Motoren, zeigte, wie Hardwaredetails die Grenzen reiner Rückführregelung bestimmen.

### Zugehörige Module
Advanced Control, Bewegungsplanung in der Robotik, Optimal Control and Decision Making, Methods in Neuromechanics, Modeling and Reduction of Complex Systems (TUM) · Regelungstechnik I, Dynamische Systeme I & II, Mechanismen für die Automatisierung, Mikroprozessoren in Automatisierung und Robotik, Eingebettete Systeme, Aktoren und Antriebe (USP).
