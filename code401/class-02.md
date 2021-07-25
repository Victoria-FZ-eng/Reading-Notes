# Arrays, Loops, Import

## Imports 

we have 3 options 
1. `import javax.swing.*;` Make all classes visible altho only one is used.
2. `import javax.swing.JOptionPane;`   Make a single class visible.
3.  type `javax.swing.` before the function within the class

**Some Imports :**
* `import java.awt.*;`	Common GUI elements.
* `import java.awt.event.*;`	The most common GUI event listeners.
* `import javax.swing.*;`	More common GUI elements. Note "javax".
* `import java.util.*;`	Data structures (Collections), time, Scanner, etc classes.
* `import java.io.*;`	Input-output classes.
* `import java.text.*;`	Some formatting classes.
* `import java.util.regex.*;`	Regular expression classes. 

## Loops

### for loop

```
// a simple for loop
for ( ; ; ) {
    // Infinite for loop
}

// an enhanced for loop
for(Type item : items)
  statement;
```

### while loop

```
while (Boolean-expression) 
    statement;
```

### do while loop

```
do {
    statement;
} while (Boolean-expression);
```



References:

* [Java Imports ](https://perso.ensta-paris.fr/~diam/java/online/notes-java/language/10basics/import.html)

* [Loops](https://www.baeldung.com/java-loops)