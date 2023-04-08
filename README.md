# Abgabetemplate für $\LaTeX$-Dokumente

## Neue Commands

- `\surround{#1}`\
Umrahmt `#1` mit einer Box. Dadurch wird die Breite von `#1` etwas etwas kleiner.

- `\tab[#1]`\
Erstellt einen Horizontalen Abtand von 5mm oder alternativ `#1`. (Dies entspricht nicht dem eigentlichen Verhalten eines *Tabs*)

- `\seperate{#1}{#2}`\
Fügt eine tabellenartige Darstellung von *Titel* und *Beschreibung* hinzu im `description`-Environment. Dabei legt `#1` den Abstand der *Beschreibung* vom linken Text-Rand fest. In `#2` stehen sowohl *Titel* mit `\item[`*`Titel`*`]` und die *Beschreibungen*.

- `\nopic[#1]`\
Fügt ein Dummy-Bild mit "Please Insert Picture Here" als Untetitel ein. Alternativ kann mit `#1` ein eigener Untertitel gesetzt werden, um z.B. das hier noch fehlende Bild zu beschreiben.

- `\explain{#1}`\
`#1` wird *kursiv* geschrieben und darunter wird ein kurzer Abstand von 2mm gelassen. Dies kann bspw. zum Beschreiben einer Aufgabenstellung genutzt werden.

- `\exercise{#1}`\
Titel einer Aufgabenstellung in der Form "Aufgabe X: `#1`".

- `\baseindent{#1}`\
Lässt `#1` in der `addmargin`-Umgebung um 5mm einrücken.

- `\code{#1}`\
Nutzt `\texttt`, Einfärben und **Bold**, um `#1` als *Code* hervorzuheben.

- `\headline{#1}`\
Unterstreicht `#1` als `subsubtection*`.

- `\largeheading{#1}`\
Schreibt `#1` sans serif mit `Large` und **Bold** als *Titel* mit einem Folge-Abstand von 1,5mm.
