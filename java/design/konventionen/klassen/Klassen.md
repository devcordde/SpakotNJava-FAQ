> __Klassennamen__:
- Immer in **UpperCamelCase** (zb. TextCommand, jedes Wort fängt mit einem Majuskel an) und **_** vermeiden.
- Der Name davon am besten von selber definieren was die Klasse macht (zb. "HealCommand" nicht einfach nur "Heal", man kann's dann nicht von selber aus verstehen).
- Abkürzungen vermeiden.
- "Manager" sowie "Handler" vermeiden.
- Hauptklassen werden am besten so genannt wie das Projekt selbst, zb. ein Heal Plugin nennt man die Main Klasse lieber `HealPlugin`, oder zb. `Luckperms` ohne `Plugin` wenn' selbstverständlich ist.
- Wenn's eine main-Methode gibt, gibt es mehrere Designs, manche erstellen ein "Main" Klasse wo dort die main-Methode drin ist und dann die Hauptklasse (siehe Punkt davor) initialisieren, andere nennen die Klasse auch "Launcher".
