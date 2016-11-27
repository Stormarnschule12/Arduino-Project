# Arduino-Project

[1.Einleitung](#6)  
[2.Die ersten Versucche mit LED's](#1)  
[3.Der Transistor](#2)  
[4.Die Windmaschinenampel](#3)  
[5.Der Motor](#4)  
[6.Der Ultraschallsensor](#5)

##Einleitung<a name="6"></a>

Zu Beginn der Unterrichtseinheit haben wir uns erst damit beschäftig, welches Projekt für uns geeignet ist. Dabei haben wir zum einen darauf geachtet, welches Projekt von dem Schwierigkeitsgrad zu uns passt. Zum anderen wollten wir ein Projekt beginnen, welches nicht nur fiktiv auf einem Bildschirm sichtbar ist, sondern real ist. Nach einer kurzen Rücksprache mit unserem Informatiklehrer sind wir schlussendlich auf den Arduino gekommen, da dieser genau zu unseren Kriterien passt. Unser Ziel ist es, am Ende unserer Projektreihe einen alleine Fahrenden Roboter zu programmieren und zu bauen. Dieser soll in einem abgesteckten Pakour ohne Einwirkungen von außen seinen Weg finden. Da unsere Informatikvorkenntnisse sehr begrenzt waren, haben wir uns am Anfang mit einfachen Schaltungen und Skripts auseinander gesetzt. Hierbei haben wir die verschiedenen Bauteile und Möglichkeiten des Arduino, welche für den Bau unseres Roboters notwendig sind, besser kennengelernt und deren Benuzung erlernt. Am Ende dieser Reihe ist es unsere Ziel mit unseren neu erworbenen Fähigkeiten einen wie oben beschriebenen Roboter herzustellen. Folgend werden wir unsere Schritte hierzu genauer erläutern.

##Die Ersten Versuche mit LED's <a name="1"></a>
<img src="https://github.com/Stormarnschule12/Arduino-Project/blob/master/IMG_1838.JPG" alt="example" width="582"><img src="https://github.com/Stormarnschule12/Arduino-Project/blob/master/Taster.PNG" alt="example" width="290">
[Skript LED's](https://github.com/Stormarnschule12/Arduino-Project/blob/master/sketch_Taster.ino)

Als erstes kleines Projekt haben wir eine einfache Ampel mit eimem Knopf als Auslöser programmiert und aufgebaut. Zu beginn brennt die grüne LED und die rote ist nicht in betrieb. Bei Benutzung der Taste geht die grüne LED aus und die rote LED beginnt zu leuchten. Nach einer in dem Skript fest definierten Zeit, wird dieser Vorgang revidiert und die LED's sind in ihrem Ausgangszustand. Dieser erste Aufbau hat es uns ermöglicht die Benutzung der Arduino Software zu erlernen. Zudem haben wir die Grundlegenden Formeln für die Programmierung kennengelernt.

##Der Transistor <a name="2"></a>
<img src="https://github.com/Stormarnschule12/Arduino-Project/blob/master/IMG_1843.JPG" alt="example" width="582"><img src="https://github.com/Stormarnschule12/Arduino-Project/blob/master/Transistor.PNG" alt="example" width="290">
[Skript Transistor](https://github.com/Stormarnschule12/Arduino-Project/blob/master/sketch_Transistor.ino)

Der nächste Schritt beihaltete, dass wir beide uns mit einem Motor auseinander gesetzt haben. Die Schaltung, sowie der Skript sind nicht besonders komplex, doch es ging uns in erster Linie darum, die Funktionalität eines Motors sowie die Energieversorgung durch eine Externe Stromquelle zu erlernen. Damit die Batterie, über den Arduino gesteuert, den Motor mit Energie versorgen kann, haben wir einen Transistor verbaut. Dieser ermöglicht bei einer anliegenden Potenzialdifferenz, welche vom Adurino aus geht, dass der Masseanschluss von der Batterie zum Motor hergestellt wird. Bei Fehlender Spannung an dem Transistor wird die Verbindung unterbrochen und der Batterie-Motor-Stromkreislauf ist nicht mehr geschlossen. Das Skript haben wir so geschrieben, dass der Motor sich beginnt zu Drehen und nach einer bestimmten Zeit wieder stoppt. Zudem haben wir festgestellt, wenn man den Zeitlichen abstandt zwischen Drehen und Stopp sehr kurz hält, so scheint es als sei der Motor gedrosselt. Folglich erscheint es dem Menschen, als würde sich der Motor langsam drehen und nicht an und aus gehen. 

##Die Windmaschinenampel <a name="3"></a>
<img src="https://github.com/Stormarnschule12/Arduino-Project/blob/master/IMG_1849.JPG" alt="example" width="582"><img src="https://github.com/Stormarnschule12/Arduino-Project/blob/master/Ampel_1.PNG" alt="example" width="290">
<img src="https://github.com/Stormarnschule12/Arduino-Project/blob/master/IMG_1850.JPG" alt="example" width="582"><img src="https://github.com/Stormarnschule12/Arduino-Project/blob/master/Ampel_2.PNG" alt="example" width="290">
[Skript Ampel](https://github.com/Stormarnschule12/Arduino-Project/blob/master/sketch_Amepl.ino)

Als 3. Miniprojekt wollten wir nun unsere Erkenntnisse und Erfloge aus den beiden vorangegangenen Aufbauten zu einem größeren und komplexeren zusammenfügen. Wir steckten also wie im vorangehenden Aufbau den Drehmotor mit Transistor zusammen, zusätzlich bauten wir auchnoch vier LEDs und den Druckknopf in dem Aufbau zusammen. Unser Ziel war es, dass man von den LEDs den Betrieb des Motors ablesen kann.
So leuchtet die grüne LED, wenn der Motor läuft. Bei drücken des Knopfes hört die Leuchte auf zu leucten, eine andere beginnt zu blinken, der Motor geht aus und die rote LED beginnt zu leuchten. Nach einer bestimmten Zeit geht die rote LED wieder aus, Grün leuchtet und der Motor dreht sich wieder.
In diesem Zwischenschritt, konnten wir verschiedene Mechanismen mit einander zu verbinden.

##Der Motor <a name="4"></a>
<img src="https://github.com/Stormarnschule12/Arduino-Project/blob/master/IMG_1864.JPG" alt="example" width="582"><img src="https://github.com/Stormarnschule12/Arduino-Project/blob/master/Stepmotor.PNG" alt="example" width="290">
[Skript Schrittmotor](https://github.com/Stormarnschule12/Arduino-Project/blob/master/sketch_Stepmotor.ino)

in unserem nun folgenden Schritt beschäftigten wir uns mit dem Motorschild
##Der Ultraschallsensor <a name="5"></a>
<img src="https://github.com/Stormarnschule12/Arduino-Project/blob/master/IMG_1954.JPG" alt="example" width="436,5"><img src="https://github.com/Stormarnschule12/Arduino-Project/blob/master/Ultraschallsensor_1.PNG" alt="example" width="436,5">
<img src="https://github.com/Stormarnschule12/Arduino-Project/blob/master/IMG_1955.JPG" alt="example" width="436,5"><img src="https://github.com/Stormarnschule12/Arduino-Project/blob/master/Ultraschallsensor_2.PNG" alt="example" width="436,5">
[Skript Ultraschallsensor](https://github.com/Stormarnschule12/Arduino-Project/blob/master/sketch_Ultraschallsensor_mit_LED.ino)
