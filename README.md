# Geldberechnung
Geldberechnung in Münzen

Aufgabe
Bitte programmiere einen Algorithmus für einen Geldwechsel-Automaten. Dieser soll einen fest einprogrammierten Betrag x in Kleingeld, d.h. Münzen, wieder ausgeben. Dabei sollen möglichst wenig Münzen zurückgegeben werden. 
Der Automat hat Zugriff auf so viele Münzen, wie er benötigt. Geldscheine kann er jedoch nicht ausgeben. 
Der Automat soll sich durch eine kleine Änderung (nur ein bis zwei Zeilen) an beliebige andere Währungen anpassen lassen. Es ist in Ordnung, wenn er dafür neu kompiliert werden muss! Beispielsweise soll er nicht nur mit europäischen, sondern auch mit britischen, amerikanischen oder beliebigen anderen Münzen arbeiten können. Diese können sich auch in der Stückelung des Kleingelds unterscheiden. Die Stückelung 0,01 bzw. 1 (vergleichbar mit 0,01€ also 1 Cent) gibt es jedoch in jedem Fall. 
Bitte implementiere Deine Lösung nur für eine Währung, nicht für mehrere!

Ein Beispiel: 
Es sollen 4,36€ zurückgegeben werden. 
Der Automat muss in diesem Fall berechnen, dass er 1x0,20€, 2x2€, 1x0,05€, 1x0,10€ und 1x0,01€ ausgeben muss.

Der Automat muss natürlich nicht nur mit 4,36€ funktionieren, sondern auch mit anderen Werten, wie z.b. 0,11€ oder 0,30€.

Technische Rahmenbedingungen
Die Aufgabe muss in einer beliebigen realen, imperativen oder objektorientierten (nicht deklarativen) Programmiersprache gelöst werden.
Bitte verzichte auf Kommentare und schreibe sprechenden Code.
Bitte vermeide eine Eingabe über die Konsole. Wir können Werte auch im Code verändern.
Bitte sorge dafür, dass die Lösung nur eine einzige Datei benötigt.
