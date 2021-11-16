Welcome to my first progam

---
# Mein Portfolio
---
## Einführung
Wir haben in einer Gruppe ein Gegorafi Quiz programmiert, wo zufällige Fragen bekommt und solange beantwortet bis die Leben 0.

### Ziel
* Wie man einen Timer benutzt und wie er geht.
* Welche schwirigkeit mit einem Timer hatte im Programm 

# Inhalt 1
Wieso der Timer am schluss nicht ins Hauptprogamm kam. Es gabe Problem und zwar habe ich in meinem Programm den Code `System.Threading.Thread.Sleep(1000);`, der Code macht das alles für so viele Sekunden sthen bleid, aber durch das wird die Zeit so eingestoppt das der User keine eingaben kann machen so das Programm nicht weiter lauft.Auch war in der Zeit des Programmirens das Problem das er bei null nicht auf hörte oder sich wiederholte.

# Inhalt 2
```c#
using System;
namespace Timer
{
  class Program
         
    {
        static void Main(string[] args)
        {

            var origRow = Console.CursorTop;

            for (int seconds = 10; seconds >= 0; seconds--)
            {
                Console.SetCursorPosition(0, origRow);
                Console.Clear();
                Console.Write("Generating Preview in {0}", seconds);
                System.Threading.Thread.Sleep(1000);

            }
            

        }
    }
}
```
# Inhalt 3
[![description](http://img.youtube.com/vi/MtC5P71g8kQ/0.jpg)](https://www.youtube.com/watch?v=mmAr7VVDlFE)

# Veriflikation +  Verbesserungen
Ziel 1 ereicht der Timer wird im Inhalt dargestellt und wird im Inhalt drei als Video gezeigt was es macht.
Ziel 2 ereicht ich konnte im Inhalt eins mit einem Text das Problem schieldern, wieso der Timer ins Hauptprogramm nicht rein kam.

1 Ich habe mich in der Gruppe mit einem Gruppenmitglied ein lautes Wort gefecht.
 2 ich habe  nicht versucht,ob der Timer mit eigaben funkzioniert.
 
 1 Ich überlege , wieso ich wüten bin und frage meinem Mitglied, ob er es mir erklären kann auf Papier oder mit dem Programm selber.
 2 Ich schau beim nächsten mal was alles vorhanden ist, wo der Timer hingehört und versuch es mit eigen Beispiele

