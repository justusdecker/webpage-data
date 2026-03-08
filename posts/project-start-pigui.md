# 🚀 pigUI: Ein neues modulares UI-Framework für Pygame! 🐍

Ich freue mich, pigUI / jmpUI vorzustellen – ein neues, dediziertes, ereignisgesteuertes UI-Framework! Dieses Projekt wurde erfolgreich von meinem größeren Node-Editor-Projekt getrennt und neu strukturiert, sodass es sich zu einem eigenständigen, leistungsstarken Werkzeug für Entwickler entwickelt hat.

pigUI basiert auf Pygame und bietet alle Low-Level-UI-Komponenten, die man benötigt, um schnell Prototypen zu erstellen und anspruchsvolle grafische Programmierwerkzeuge sowie komplexe Benutzeroberflächen (UI/UX) zu entwickeln. 

Über einfache Spielmenüs hinaus denken – mit pigUI erstellen werden die Werkzeuge selbst erstellt!

## ✨ Wichtigste Funktionen im Überblick:

* **Hierarchisches UI-Management**: Der robuste UIManager übernimmt die Elementebenen und das Rendering und gewährleistet so eine einwandfreie Eingabeblockierung. Nur das oberste aktive Element (z. B. ein gezogener Knoten oder ein Texteingabefeld) empfängt Ereignisse, was komplexe Interaktionen vereinfacht.
* **Intuitive Ereignisbehandlung**: Die Klasse `Events` abstrahiert Pygame-Eingaben (Klicks, Doppelklicks, Scrollen, Tastatureingaben) in übersichtliche, benutzerfreundliche Zustandsvariablen.
* **Spezialisierte Widgets**: Enthält sofort einsatzbereite, komplexe Komponenten, darunter `UITextInput` (mit Tastenwiederholung und Validierung), `UIDropDown`, `UIMenuBar` und einen `UIColorPicker`.
* **Anpassbares Design**: Logik (`UIElement`) und visuelle Elemente (`UXElement`/`UXWrapper`) sind vollständig getrennt, was mühelose Designänderungen und die benutzerdefinierte Darstellung von Komponenten ermöglicht.

Das Kernframework ist größtenteils fertiggestellt.

Ich werde in Kürze die fehlende Dokumentation ergänzen und einige Fehler beheben.

Anschließend werden einige neue Komponenten hinzugefügt (hier drei davon):
* 7-Segment-Anzeigen
* Verschiebbare Fenster
* Schieberegler

👉 Die Dokumentation findet Ihr im Repository. Hier geht zum [Grafiktool](https://github.com/justusdecker/pigUI)