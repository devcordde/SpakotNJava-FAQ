# Java Konventionen

Hauptregel: Immer so nennen dass man anhand des Namen weiß worum es geht, Abkürzungen vermeiden.
<br><br>
**Wieso die einhalten?**:<br>
Nehmen wir mal an, einer der die Konventionen nicht einhalten möchte schreibt sowas:
`me.EinKek.BeispielPlugin.MeinPlugin.Spieler`<br>
Was ist was hier jetzt?<br>
Vieleicht ist das Package `me.EinKek.BeispielPlugin` , und `MeinPlugin` ist eine Klasse und `Spieler` ist auch eine (nested Class).<br>
Oder das Package ist `me.EinKek.BeispielPlugin`, und `MeinPlugin` ist eine Klasse und `Spieler` ist eine public static Variable?<br>
Oder das Package ist `me.EinKek` und `BeispielPlugin` ist eine Klasse wo dort die Klasse `MeinPlugin` ist, und dort ist die Variable `Spieler`?<br>
Diese Konventionen halten die Struktur in Übersicht damit man sich ohne explizite Anzeige weß was was ist.<br><br>

> __Übersicht einiger dieser Konventionen__:

- Packages: [hier](packages/Packages.md)
- Klassen: [hier](klassen/Klassen.md)
- Variablen: [hier](variablen/Variablen.md)
- Methoden: [hier](methoden/Methoden.md)

> Zurück: [hier](../../../README.md)
