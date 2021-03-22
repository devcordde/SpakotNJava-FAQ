# Java Konventionen

Hauptregel 1: Durch den Namen einer Variable, Klasse, etc. sollte klar erkennbar sein, worum es geht. Abkürzungen sollten vermieden werden.
Hauptregel 2: Englisch! Jeder Kommentar, jede Klasse, jede Variable, jeder Git commit und was es sonst alles noch zum schreiben gibt. Englisch! Und auch kein Denglisch. Englisch, Englisch, Englisch!
<br><br>
**Wieso solltest du dich an die Java Konventionen halten?**:<br>
Nehmen wir mal an, einer der die Konventionen nicht einhalten möchte schreibt:
`me.EinKek.BeispielPlugin.MeinPlugin.Spieler`<br>
Was ist was hier jetzt?<br>
Vielleicht ist das Package `me.EinKek.BeispielPlugin`, und `MeinPlugin` ist eine Klasse und `Spieler` ist eine nested Class.<br>
Oder das Package ist `me.EinKek.BeispielPlugin`, `MeinPlugin` ist eine Klasse und `Spieler` ist eine static Variable?<br>
Oder das Package ist `me.EinKek` und `BeispielPlugin` ist eine Klasse, wo dort die Klasse `MeinPlugin` ist, und dort ist die Variable `Spieler`?<br>
Die Konventionen strukturieren dein Projekt und helfen anderen Entwicklern sich einfacher in deinen Code einzuarbeiten.<br><br>

> __Übersicht einiger dieser Konventionen__:

- Packages: [hier](packages/Packages.md)
- Klassen: [hier](classes/Classes.md)
- Variablen: [hier](variables/Variables.md)
- Methoden: [hier](methods/Methods.md)

> Zurück: [hier](../../../README.md)
