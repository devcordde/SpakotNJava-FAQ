> __Packages__: 
- Packages benennt man immer im **lowercase**. Unterstriche sollte vermieden werden. Packages werden wie Variablen, Klassen, etc. in Englisch verfasst.
- `main` Package ist redundant für die Main Klasse, lieber nicht erstellen (die Main Klasse nicht `Main` nennen, siehe Klassekonventionen, die kommt im Root-Package).
- In ein `util` oder `utils` Package kommen nur Klassen rein, die **nicht** abhängig von deinem Projekt (nicht Framework gemeint) sind. Zum Beispiel sind Klassen die Zugriffe auf die Hauptklasse oder anderen System-relevante Klassen nicht in diesem Package zuzufügen.
- Formatierung beim Root-Package:
<br>  -> Allgemein solltest du `com.mywebsite.myproject` verweden.
<br>  -> Private Leute die keine eigene Domain/Website besitzten sollten `me.myname.myproject` verwenden.
<br>  -> Email benutzen: `com.gmail.mymail.myproject`
<br>  -> Dein Github Projekt: `com.github.myname.myproject`
<br>  -> Github Pages: `io.github.myname.myproject`
> Zurück: [hier](../README.md)
