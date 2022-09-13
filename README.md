# Lern-Bericht
von Pascal Oestrich

## Einleitung
Ich habe ein kleines Consolespiel prgorammiert, indem man eine zahl zwischen 1 und 100 erraten kann. Das kleine Spiel kann mit Fehlereingaben umgehen und gibt eine gewisse Ausgaben aus.
In diesem Bericht werde ich dokumentieren, was ich an meiner Arbeit von meinem kleinen Spiel habe. Dies werde ich hier in dieser Dokumentation in Form von Text, Bild und Video darstellen.

## Mein erlerntes Wissen.
Ich habe in diesem Projekt vieles über das Programmieren gelernt, aber das was mir am wichtigsten und interesantesten war, waren die Schleifen und deren gebrauchsarten. Dazu weiss ich nun, wie ich eine zufällige zahl generiere und eine Fehlermeldung programmiere (try und catch).
In dieserm Lernbericht, werde ich mich ausschliesslich auf das (try and catch) fokusieren
## Beschreibung

In meinem Programm habe ich eine try and catch Schleife programmiert, dass mein Programm mit falschen Eingaben umgehen kann und nicht abstürtzt.

## Beschreibung

Das try and catch wird gebraucht, um Eingaben zu überprüfen und richtig zu behandeln, ohne dass das Programm abstürtzt.
Um so eine Schleife zu programmieren, braucht man ein try, in dem die Eingabe liegt, dass gebprüft werden sollte. Und ein catch, in dem der mögliche fehler abgefangt  und den Code im catch ausgeführt wird.
In meinem Programm, habe ich ein try and catch einprogrammiert. Wenn man eine ungültige Eingabe tätigt, zum Beispiel Strings und doibels, stürtzt das Programm nicht ab, sonder es informiert den Spieler, dass das Eingegebene ungültig ist und man nochmal eine Eingabe tätigen sollte. Das Programm öffnet demnach wieder die Eingabe für die gesuchte Zahl.

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

##### Text
Der Text beschreibt, wie eine try and catch Schleife funktioniert und wie ich es in meinem Programm verwende.
##### Gif
Das Gif zeigt die Konsole, in dem eine falsche Eingabe getätigt wurde und wie das try and catch in meine Programm funktioniert.
##### Code
Der Code am Ende zeigt, wie die Schleife in C# geschhrieben wird.

## Reflexion

#### Was gut ging:

Das Negative war, mein Arbeitsplatz war ein bisschen unaufgeräumt, somit war es ein bisschen unpraktisch, dort zu lernen.

**VBV** Für das Nächstemal werde ich meinen Arbeitsplatz gründlich aufräumen, dass mir einen angenehmen Arbeitsplatz zu Verfügung steht.
