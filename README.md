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
```
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
|  1  | Datenbank ist verbunden | C# Code zum lesen | Inhalt der Datenbank |    |
|  2  | Datenbank ist verbunden | C# Code zum schreiben | Der Datenbank werden neue Inhalte hinzugefügt. |    |
|  3  | C# Code wird ausgeführt | Man gibt eine Fehleingabe ein | Fehleingabe wird ignoriert |    |
|  4  | Eingaben sind erfolgt | Man möchte die Eingaben ansehen | Eingaben werden wiedergegeben |    |


## Reflexion

Formen Sie Ihre Zusammenfassungen in Hinblick auf Ihren VBV zu einem zusammenhängenden Text von 100 bis 200 Wörtern (wieder mit Angabe in Klammern).
