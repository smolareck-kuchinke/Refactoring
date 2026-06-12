# Refactoring

## 1. Ausgewählte Refactorings von Fowler

### 1.1 Extract Method
Finde ich selbst toll, weil die Lesbarkeit von Code auch durch kleine Änderungen schon verbessert wird. 
Ergo wereden lange Methoden hier in kleinere aufgeteilt, damit wird der Code verständlicher, wartbarer und testbarer.
Also eine einfache Methode mit großer Wirkung. 

### 1.2 Replace Conditional with Polymorphism 
Finde ich auch interessant und nützlich, da große if/switch-Konzepte dann weggelassen werden können, indem man das dann auf verschiedene Unterklassen aufteilt.
Ergo weniger komplex, leichetr erweiterbar, bessere Wartbarkeit. Sinnvoller Einsatz also von Vererbung und Polymorphie.

### 1.3. Rename method
Finde ich überflüssig. IDEs können heute Methoden auch schon automatisch umbenennen. Das Refactoring hat hier kaum Auswirkungen auf Struktur oder Architerktur des Programms.

## 2. IDE

Ich verwende hauptsächlich Eclipse.
Über den Reiter "Refactoring" sind viele strukturellen Refactorings von Fowler abrufbar wie

Extract Method
Extract Variable (Extract Local Variable)
Extract Constant
Extract Class
Extract Interface (Extract Superclass)
Inline Method
Inline Variable (Inline Temp)
Rename (Rename Field, Rename Variable, Rename Method, Rename Class)
Move Method (Move Static Members / Move Instance Method)
Move Field
Pull Up Method
Pull Up Field etc. 

Jedoch nicht komplexere Umbauten wie

Conditionals
Polymorphismus etc.

Diese müssen tatsächlich manuelle vorgenommen werden.


## 3. Refactoring
### 3.1. Mein Code zum Ticketkauf im Projekt SpieltagPLUS

![Code vorher](images/Code.png)

### 3.2 Refactoring nach Fowler: Extract Method

![Code nachher](images/Refactoring.png)

Erklärung: 
Methode in 3.1. enthält mehrere unterschiedliche Aufgaben.
Für das Refactoring habe ich die Refactoring-Funktion von Eclipse genutzt. Also nacheinander den betreffenden Codeblock ausgewählt und dann unter Refactoring -> Methode extrahieren ... ausgewählt und der neuen Methode einen entsprechenden Namen vergeben.
Durch das Extrahieren der verschiedenen Codeblöcke in eigene Methoden ist der Code besser wartbar und klar nach Verantwortlichkeiten getrennt. 

