# Portfolio M122
Autor: Angel Angelov
Datum: 02.07.2023

## Einleitung
In diesem Projekt habe ich mithilfe von PowerShell ein beeindruckendes Skript entwickelt, das automatische Windows-Updates ermöglicht. Es spart Zeit und Aufwand, indem es den gesamten Update-Prozess automatisiert. Dank meiner PowerShell-Kenntnisse konnte ich zudem zusätzliche Funktionen integrieren, um die Update-Historie in einem speziellen Ordner festzuhalten. Dieses leistungsstarke Skript gewährleistet, dass dein Windows-Betriebssystem immer auf dem neuesten Stand ist und optimal funktioniert.
## Beschreibung des Themas 
Modul 122 befasst sich mit der Einführung in Skriptsprachen, insbesondere PowerShell, und der Automatisierung von Abläufen mithilfe einer Skriptsprache.

Die Aufgabenstellung besteht darin, eine Problemstellung zu formulieren, diese zu dokumentieren und anschließend eine Lösung in PowerShell zu implementieren.
## Was habe ich gelernt?

In diesem Portfolio zeige ich auf, wie ich meine Kenntnisse in Kontrollstrukturen, die ich ursprünglich in C# erlernt habe, erfolgreich in Powershell umgesetzt habe.

## Beschreibung

In meinem Projekt geht es um die Verwendung von Kontrollstrukturen in PowerShell, insbesondere anhand des folgenden Codes:

```powershell
$Untersuche = "C:\AutoUpdates"
$Besteht = Test-Path $Untersuche
If ($Besteht -eq $false)
{
    mkdir C:\AutoUpdates
    mkdir C:\AutoUpdates\History
}
else
{
    # macht nichts
}

```
Dieser Code prüft zunächst, ob ein bestimmter Ordner namens "C:\AutoUpdates" vorhanden ist, indem die Funktion Test-Path verwendet wird. Falls der Ordner nicht existiert, wird er mithilfe des Befehls mkdir erstellt. Zusätzlich wird ein Unterordner namens "History" erstellt, der für die Aufbewahrung von Update-Protokollen verwendet werden kann.

Die Kontrollstruktur If wird verwendet, um den Codefluss basierend auf der Bedingung ($Besteht -eq $false) zu steuern. Wenn die Bedingung erfüllt ist (der Ordner existiert nicht), werden die mkdir-Befehle ausgeführt. Andernfalls wird der Codeblock unter else übersprungen.

Dieses Projekt demonstriert die Verwendung der Kontrollstrukturen If und Else in PowerShell, um die Logik und den Ablauf des Skripts zu steuern. Es bietet eine effektive Möglichkeit, den gewünschten Ordner- und Unterordneraufbau automatisch zu erstellen, wenn sie noch nicht vorhanden sind.

## Reflexion zum Arbeitsprozess

In diesem Projekt hatte ich anfangs einige Schwierigkeiten, insbesondere zu Beginn. Ursprünglich hatte ich geplant, ein Skript zur Dateisortierung zu erstellen, aber nach einiger Zeit entschied ich mich, das Thema auf Windows Updates zu wechseln. Durch umfangreiche Recherchen und erneutes Durchgehen des Materials konnte ich das Thema besser verstehen und begann, mit PowerShell effektiver zu arbeiten. Diese Erfahrung half mir, meine Fähigkeiten zu verbessern und das Projekt erfolgreich umzusetzen.

In diesen Projekt habe ich gelernt, Geduld zu haben und nach Lösungen zu suchen, auch wenn ich anfangs mit der Skriptsprache zu kämpfen hatte. 
