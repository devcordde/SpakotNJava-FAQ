> __Methoden__:
- Methoden nennt man in **lowerCamelCase** also z.B. `myMethod`, erstes Wort in klein, danach Binnenmajuskel.
- Der Name einer Methode sollte zu der Funktion passen.
- Methoden sollten aufgeräumt sein. Kommentier den Code in deinen Methoden, also z.B. `// Update the message cache`.
- Sollte durch den Methoden Namen nicht eindeutig klar sein, was in der Methode passiert, sollte die Methode kommentiert werden. Dies machst du folgendermaßen:
```
    /**
     * This method establishes the connection to MongoDB and creates the necessary collections. 
     * In addition, the mongoDatabase variable is defined.
     */
    public void connectAndPrepareDatabase() {
        // Your method content
    }
```
> Zurück: [hier](../README.md)
