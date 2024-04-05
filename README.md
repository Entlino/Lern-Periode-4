# Lern-Periode 4

23.2 bis 5.4.2024

## Grob-Planung

1. Immer noch gleich, gewisse Module sehr gut andere sind okay.
2. In der nächsten Lern-Periode möchte ich wie in dieser Lern-Periode den ganzen Code möglichst verständlich im GitHub darstellen und erklären.
3. Ich möchte lernen eine Datenbank in ein C# Programm zu intregieren.
4. Ich möchte ein C# Programm entwicklen welches einem ermöglicht Ein/Ausgaben zu tracken welche dann in einer SQL-Datenbank speichern.

## 23.2.2024

Am heutigen Tage mir gedanken welches Projekt ich als nächstes angehen. Dabei habe ich mich dazu entschlossen ein Finanz-Tool in C# zu erstellen, dabei liegt der Hauptfokus jedoch nicht auf dem Programm sondern darauf das ich die einzelnen Daten in einer SQL-Datenbank speichern möchte. Dazu sollte das Programm über ein Login verfügen um die bestimmten Daten danach auch wieder aufzurufen zu können. Am Anfang besteht das Programm aus einer Console-Applikation wird jedoch mit einer Zeit noch in eine WinForm-Applikation gewechselt. (84)

## 01.3.2024

- [ ] https://csharp-hilfe.de/csharp-mit-sql-verbinden/  |  Dieses Tutorial in einer Test-Datei ausprobieren und versuchen umzusetzen. (1/2)
- [ ] Tutorial weitermachen (2/2)
- [X] Console Applikation erstllen bei welcher man die Ein und Ausgaben eingeben kann.
- [X] SQL Datenbank in SQL erstellen.

| Testfall-Nummer | Ausgangslage (Given) | Eingabe (When) | Ausgabe (Then) | Erfüllt? |
| --- | --- | --- | --- | --- |
| 1   |-|hälfte der Tutorial|Hälfte funktioniert|Jain|
| 2 |hälfte des Tutorials|andere hälfte|Datenbank ist mit |Jain|
| 3 |Eingabe|System erkennt es|Kann es temporär abspeichern|Ja|
| 4   |-|Projekt-Datenbank erstellt|Datenbank ist bereit zur benutzung|Ja|

Am heutigen Tage habe ich zuerst damit begonnen das letzte Woche verlinkte Tutorial aufzuarbeiten. Da ich jedoch schneller gemerkt habe das dies einiges Komplizierter ist als ich erwartet habe und es mir Persöhnlich nicht allzu viel bringt den Code abzuschreiben habe ich zwar damit begonnen den Code zu verstehen und zu Kopieren bin jedoch noch nicht fertig. Als dann die weiteren Arbeitspakete anstanden habe ich mich dazu entschlossen das Tutorial erst einmal sein zu lassen und mich um die weiteren Arbeitspakete gekümmert, freie Zeit habe ich schliesslich wieder damit gefüllt am Tutorial zu arbeiten.  (94)

![image](https://github.com/Entlino/Lern-Periode-4/assets/111046353/4355fd33-8256-4ae4-8f89-79ce7d8db908)

Bei dem Vorlagen Code habe ich einen sehr simplen Code verwendet welcher mir schliesslich hoffentlich behilflich ist die ganze Appklikation in eine WinForms Applikation umzuwandeln.


In dem erwähnten Tutorial lernte ich das es Wichtig ist die Datenbank verbinding erstmals aufzubauen, dann die Daten zu transferieren und schliesslich die Verbindung wieder abgebrochen wird falls diese nicht mehr verwendet wird.

Der untenstehenden Code habe ich fast 1 zu 1 vom dem Tutorial kopiert da es mir in diesem Falle wichtig war keinen Fehler zu machen und dies zum wichtigsten Teil gehört.

```csharp
private void Connect(){
   string connectionString = //Link zur Datenbank, inkl Benuter und Passwort für den Server auf dem eigenen Notebook.
   SqlConnection connection = new SqlConnection(connectionString);
   connection.Open();
   // Hier Inhalte lesen/schreiben
   connection.Close();
}
```

Weiter habe ich noch gelernt das es für das Lesen und Schreiben sehr ähnlicher Code verwendet wird. Diesen verstanden habe ich jedoch nicht.

## 08.03.2024

Heute hatte ich den Orientierungstag der Armee, somit konnte ich leider nicht an den Aufträgen arbeiten. Die Arbeitspakete wurde auf nächste Woche verschoben.


## Arbeitspakete 15.03.2024

 - [ ] Schauen wie man in einer Datenbank lesen kann (Datenabfragen)
 - [ ] Wie man in einer Datenbank schreiben kann (Dateneingabe)
 - [ ] C# Code anpassen so das fehleingaben ignoriert werden
 - [ ] C# Code anpassen das man die Gespeicherten Daten wieder abrufen kann.


| Testfall-Nummer | Ausgangslage (Given) | Eingabe (When) | Ausgabe (Then) | Erfüllt? |
| --- | --- | --- | --- | --- |
|  1  | Datenbank ist verbunden | C# Code zum lesen | Inhalt der Datenbank |Ja|
|  2  | Datenbank ist verbunden | C# Code zum schreiben | Der Datenbank werden neue Inhalte hinzugefügt. |Ja|
|  3  | C# Code wird ausgeführt | Man gibt eine Fehleingabe ein | Fehleingabe wird ignoriert |Ja|
|  4  | Eingaben sind erfolgt | Man möchte die Eingaben ansehen | Eingaben werden wiedergegeben |Nein|


Heute habe ich damit begonnen, eine Datenbank mit einen Code lesen und bearbeiten zu können. Als ich dies nach einige mal versuchen endlich geschafft habe hab ich damit weitergemacht das die Fehleingaben für die Frage am anfang ob man eine Ein oder Ausgabe tätigen möchte. Dies habe ich mithilfe einer Try-Catch Methode hinbekommen. Als ich danach an die wiederholung gegangen bin, bin ich leider aus Zeitgründen gescheitert.


## Arbeitspakete 22.03.2024

- [ ] Wiederholung einarbeiten
- [x] Module weiterarbeiten (aufholen)

Heute habe ich ausschliesslich an den Aufträgen für das Modul 187 gearbeitet, bei welchem ich die Aufträge, 0796, 0707, 0708 erledigt habe. Die einzelnen Aufträge haben sich mit den Themen, Energie, Internetverbindungen sowie den Grundlagen der Betriebssysteme. Die dazugehörige Dokumentation in welcher alle Aufträge dokumentiert sind bzw. wurden, habe ich als "Nachweis" auf GitHub hochgeladen. (55)


## Arbeitspakete 05.04.2024

- [ ] Wiederholung einarbeiten
- [ ] Grundlegene Fehler beheben welche bis dahin entstanden sind

| Testfall-Nummer | Ausgangslage (Given) | Eingabe (When) | Ausgabe (Then) | Erfüllt? |
| --- | --- | --- | --- | --- |
|  1  | Programm gestartet | Eingabe | Wiederholung wird abgefragt |   |
|  2  | Programm gestartet | Eingaben der Beträgen | Keine Fehler vorhanden |   |


## Reflexion

In dieser Lernperiode hatte ich als Thema ein C# Projekt zu implementieren, welches nebenbei noch auf eine MS SQL-Datenbank zugreift und auf diesen Datenspeichern und Auslesen kann. Das Projekt an sich hat bisher nicht funktioniert, wie es sollte, jedoch habe ich glücklicherweise das Prinzip verstanden, wie das Ganze funktioniert. Dieses Prinzip werde ich nun versuchen zu erklären.
Am Anfang muss man damit beginnen, erstmals die nötigen Informationen der Datenbank dem Programm zur Verfügung zu stellen, d.h. Name, Art, usw. Wenn dies geschafft ist, muss man mit einer weiteren Zeile die Verbindung zwischen Programm und Datenbank "öffnen". Sobald diese Öffnung stattgefunden hat, kann man mithilfe zwei weiterer Codeteilen entweder etwas in die Datenbank einfügen oder etwas auslesen.
Sobald man alle nötigen Änderungen vorgenommen hat, kann man schlussendlich die Verbindung zwischen Datenbank und Programm trennen bzw. "schliessen".

Mein Verbesserungsvorschlag dieser Lernperiode war folgender:
(VBV): In der nächsten Lernperiode möchte ich wie in dieser Lernperiode den ganzen Code möglichst verständlich im GitHub darstellen und erklären.
Ich würde sagen, ich habe diesen Verbesserungsvorschlag teilweise erreicht. 100 % kann ich dieser Aussage leider nicht zustimmen, da ich leider Screenshots anstatt des eingefügten Codes "abgegeben" habe, wieso ich dies gemacht habe, habe ich mir zum jetzigen Zeitpunkt unverständlich. Zudem muss ich jedoch sagen dass , das ich sonst den Code wie gewollt auf GitHub darstellen konnte.

## Lern-Periode-5
Wie mit Herrn Colic heute besprochen, möchte ich in der 5. und somit letzten Lern-Periode des 1. Lehrjahres etwas versuchen umzusetzen, was mir einerseits einen Vorsprung für ins 2te Lehrjahr gibt, aber mich anderseits auch fordert. 

Mögliche Projekte könnte folgende sein:
- Kryptografie in C# (Das Erstellen eines Programmes, welches Verschlüsselungen vornehmen kann.)
- Multilingualer Translater (Einen Übersetzer, welcher mithilfe von Google oder Microsofts API's mehrere Sprachen übersetzen kann.)
- Sehenswürdigkeiten Empfehler (Ein Tool, welches mithilfe von Google API's Sehenswürdigkeiten für einen Ort sucht und Informationen wie der Ansturm auf die Sehenswürdigkeit oder Kosten veranschaulicht.)
- Spracherkennung (Programm kann von einem Text die Sprache erkennen.) <--

Diese Programme würden vermutlich in einer Konsole-Applikation am besten funktionieren. Vor allem die ersten 2 wäre dies vermutlich das geeignete.

## VBV

Für den Verbesserungsvorschlag möchte ich in der letzten Lernperiode ausschliesslich an dem Projekt arbeiten und versuchen, auf Modularbeit zu verzichten. (360 Wörter)
