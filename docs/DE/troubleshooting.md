# Fehlersuche/-behebung am Robotron EC1834

Ich versuche hier eine Anleitung zu erstellen, wie man einen EC1834 (oder auch andere Systeme) repariert.
Vorlage soll meine Vorgehensweise an 2 defekten Boards sein.

## Ausstattung
Empfehlenswert ist folgende Ausrüstung:

* Trenntrafo
* Oszilloskop
* Logic Analyzer (16 Kanal - z.B. LA1010, besser LA2010, noch besser: HANTEK 4032L)
* Multimeter (dürfen auch mehr als eines sein)
* mind. 2 Labornetzteile mit Strombegrenzung<br>
    +12V<br>
    +5V - und hier Minimum 3,5A, besser mehr als 10A!
* POST Diagnose Karte [wie hier](https://github.com/mgoegel/EC1834-POST)
* EPROM Programmer (auch TL866II+ oder nachfolgend mit Einschränkungen nutzbar)

## Vorgehensweise Diagnostik

- [Stromversorgung/Netzteil](ts-power.md)
- [Mainboard](ts-mainboard.md)
- Erweiterungsplatinen
- Peripherie

## Beispiele Fehlerdiagnostik Mainboard

- [Board 1](ts-b1.md)
- [Board 2](ts-b2.md)
