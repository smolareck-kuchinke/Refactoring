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

Rename - Rename Method/ Rename Field / Rename Class
Move - Move  Methid / Move Field
Change Method Signature - Rename Method / Add parameter / Remove parameter / Introduce Parameter Object

## 3. Refactoring
### 3.1. Mein Code zum Ticketkauf im Projekt SpieltagPLUS

![Code vorher](images/Code.png)

### 3.2 Refactoring nach Fowler: Extract Method

![Code nachher](images/Refactoring.png)
