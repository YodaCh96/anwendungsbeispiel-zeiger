# Anwendungsbeispiel Zeiger

Mit der vorliegenden Aufgabe soll durch einfache Mittel und geringen Programmieraufwand ein konkretes Anwendungsbeispiel für die Verwendung von Zeigern demonstriert werden.

## Aufgabenstellung

Erstellen Sie ein Programm, welches als interaktives Inhaltsverzeichnis funktioniert. Im Rahmen dieser Aufgabe sollen Benutzerinnen und Benutzer die Kapitelnummer eines (fiktiven) Buches eingeben können um die Seitenzahl dieses Kapitels angezeigt zu erhalten. Etwas realistischer könnte das Nachschlagen einer Telefonnummer in einem Adressverzeichnis oder das Auffinden des Einkaufspreises von einem Produkt mit bekannter Artikelnummer ausfallen.

Das Programm soll nach dem Start solange für Auskünfte zur Verfügung stehen, bis dieses durch die Eingabe eines entsprechenden Codes beendet wird. Im nachfolgenden Screenshot
wird dafür die Zahl 0 verwendet.

Die Anzahl der Kapitel sowie die zugehörigen Seitenzahlen sind für die Umsetzung dieser Aufgabe nicht relevant. Wählen Sie dazu selbständig einige fiktive Seitenzahlen (wieso nicht die kleinsten Primzahlen in jedem Hunderterraum?). Die Informationen zu den vorhandenen Kapiteln und zugehörigen Seitenzahlen sollen im Programm als konstante Werte hinterlegt sein.

Für das Einlesen der Benutzereingabe sowie für die Zwischenspeicherung bzw. Ausgabe der relevanten Informationen sollen wo möglich (und sinnvoll) Zeiger bzw. entsprechende Operatoren (z.B.& und *) verwendet werden.

```none
Table of contents
********************

-1- Chapter 1
-2- Chapter 2
-3- Chapter 3
-4- Chapter 4
-0- EXIT

Input : 1

You'll find chapter 1 on page 1

Table of contents
********************

-1- Chapter 1
-2- Chapter 2
-3- Chapter 3
-4- Chapter 4
-0- EXIT

Input :
```

## Contributing

This is a personal learning project for me. Please feel free to fork this repo. Pull request to submit more programs.

## Feedback

If you find any bug or have any suggestion, please do file issues. I am graceful for any feedback and will do my best to improve this package.

## License

[MIT](LICENSE) © 2020 Ioannis Christodoulakis
