# Praxisheft Elektrizität ⚡️

Dieses Repository enthält ein vollständig ausgearbeitetes, didaktisch durchdachtes **Praxisheft zur Einführung in die Elektrizitätslehre** für den Physikunterricht auf Sekundarstufe I oder II. Es kombiniert **anschauliche Theorie**, **praktische Experimente**, **grafisch aufbereitete Abbildungen**, ein **Glossar**, sowie interaktive und kreative Aufgabenformate.

Das Material wurde mit **LuaLaTeX** erstellt und ist modular aufgebaut. Es eignet sich sowohl zur direkten Verwendung im Unterricht als auch zur Anpassung und Weiterentwicklung durch Lehrpersonen.

---

## Kompilierung

Zur Kompilierung wird **LuaLaTeX** verwendet. Voraussetzung ist ein LaTeX-System mit folgenden Paketen:

- `fontspec`
- `polyglossia`
- `unicode-math`
- `scrlayer-scrpage`
- `tikz` / `pgfplots`
- `siunitx`
- `tcolorbox`
- `emoji`
- u. v. m. (siehe `00_preamble.tex`)

### Kompilieren (empfohlen):
```bash
lualatex praxisheft.tex
```


### Elektrizitätsboxen
Die Elektrizitätsboxen JX-D03 sind von Paxeroly und wurden über Aliexpress gekauft.

https://www.aliexpress.com/store/1103438345

https://de.aliexpress.com/item/1005007357173497.html


## Lizenz

Dieses Projekt steht unter der **CC BY-NC-SA 4.0-Lizenz**. Siehe `LICENSE`-Datei
für weitere Details.
