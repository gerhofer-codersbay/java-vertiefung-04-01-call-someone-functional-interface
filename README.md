# Java 

In dieser Übung geht es darum, ein functional interface zu deklarieren und durch Anwendung verschiedener Lambdas zu implementieren.

## Lambdas - findWithCondition in Range

Implementiere ein funktionales Interface `NumberChecker`, welches eine Methode `boolean check(Integer number)` hat. 
Schreibe dann eine Methode `filterInRange` welche einen `Integer from`, `Integer to` und einen `NumberChecker checker` als Parameter empfängt und dann alle Zahlen zwischen from und to in einer Liste returniert für welche die check Methode im Checker zu true evaluiert.

Implementiere dann folgende Fälle und schreibe auch für jeden Fall einen Test! 
* Alle Zahlen zwischen 1 und 50 die gerade sind. 
* Alle Zahlen zwischen 1 und 100 die eine Primzahl sind. 
* Alle Zahlen zwischen 10 und 200 die entweder durch 7 teilbar sind oder die Ziffer 7 enthalten. 

💡 Ein funktionales Interface ist ein Interface welches genau eine abstrakte Methode hat. 
Dieses Interface muss mit `@FunctionalInterface` annotiert werden. Ein funktionales Interface darf zusätzlich statische und default Methoden haben.

💡 Eine Annotation ist eine Art syntaktische Metainformation die zu Klassen, Methoden, Variablen, Parametern oder Packages hinzugefügt werden kann. 
Viele Frameworks verwenden Annotationen um einer Methode oder Klasse besonderes Verhalten hinzuzufügen.