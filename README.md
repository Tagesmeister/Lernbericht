# Lern-Bericht
von Pascal Oestrich

## Einleitung
Ich habe ein kleines Konsolespiel programmiert, indem man eine Zahl zwischen 1 und 100 erraten kann. Das kleine Spiel kann mit Fehlereingaben umgehen und gibt eine gewisse Ausgabe aus.

In diesem Bericht werde ich dokumentieren, was ich an meiner Arbeit von meinem kleinen Spiel habe. Dies werde ich hier in dieser Dokumentation in Form von Text, Bild und einem GIF darstellen.

## Mein erlerntes Wissen.
Ich habe in diesem Projekt vieles über das Programmieren gelernt, aber das, was mir am wichtigsten und interessantesten war, waren die Schleifen und deren Gebrauchsarten. Dazu weiss ich nun, wie ich eine zufällige Zahl generiere und eine Fehlermeldung programmiere (try und catch).
In diesem Lernbericht, werde ich mich ausschliesslich auf das (try and catch) fokussieren
## Beschreibung

In meinem Programm habe ich eine try and catch Schleife programmiert, dass mein Programm mit falschen Eingaben umgehen kann und nicht abstürtz.

## Beschreibung

Das Try and catch wird gebraucht, um Eingaben zu überprüfen und richtig zu behandeln, ohne dass das Programm abstürtz.
Um so eine Schleife zu programmieren, braucht man ein Try, in dem die Eingabe liegt, dass geprüft werden sollte. Und ein Catch, in dem der mögliche Fehler abgefangen  und den Code im Catch ausgeführt wird.
In meinem Programm habe ich ein Try and catch einprogrammiert. Wenn man eine ungültige Eingabe tätigt, zum Beispiel Strings und doubels, stürtz das Programm nicht ab, sondern es informiert den Spieler, dass das Eingegebene ungültig ist und man nochmal eine Eingabe tätigen sollte. Das Programm öffnet demnach wieder die Eingabe für die gesuchte Zahl.

```csharp
 try
 {
     Console.WriteLine("Suche eine Zahl zwischen (1-100): ");
     eingabe = Console.ReadLine();
     raten = Convert.ToInt32(eingabe);
 }
 catch
 {
     Console.WriteLine("Falsche Eingabe: Geben Sie eine Zahl ein!!");
     Thread.Sleep(3200);
     Console.Clear();
 }

```


![6t7bm6](https://user-images.githubusercontent.com/110892258/189845833-b8f3485c-4108-4a58-b0d4-225a9332efa2.gif)


## Verifikation

##### Text:
Der Text beschreibt, wie eine try and catch Schleife funktioniert und wie ich es in meinem Programm verwende.
##### GIF:
Das GIF zeigt die Konsole, in dem eine falsche Eingabe getätigt wurde und wie das try and catch in meinem Programm funktioniert.
##### Code:
Der Code am Ende zeigt, wie die Schleife in C# geschrieben wird.

## Reflexion

#### Was gut ging:

Da ich in meinem kleinen Projekt IPERKA verwendet habe, ging es mir beim Arbeiten gut.
Das Informieren und Planen von Codes ging mir am Anfang schwierig, aber dies besserte sich im Laufe des Projektes.
#### Wo gab es Probleme?
Ich hatte gewisse Probleme, bei der Anordnungen von der Schleife. Zum Beispiel wusste ich nicht genau, in den Try und Catch Code kommt.

**VBV** Für das nächste Mal Informiere ich mich besser über die code Schleifen und sollte mir genug früh die User-stories schreiben, das heisst: Ich sollte mir früh genug vorher überlegen, was alles in meinem Programm vorhanden sein muss.

