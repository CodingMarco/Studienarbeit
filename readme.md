# LaTeX Vorlage by Johannes Staib 2020

Dateistruktur:

- **Main.tex** Main file, hier content files einbinden
- **documentkeys.tx** Schlüsselwerte wie Studentenname und Co.
- **configuration.tex** Alle Einstellungen
- **general** Ordner mit allgemeinen Dateien, hier sollte man nichts ändern müssen
- **content** hier allen eigenen Content rein.
- **citation** hier liegt Citavi Projekt



## Programme

| Programme                                           | Verwendung                                      |
| --------------------------------------------------- | ----------------------------------------------- |
| [MiKTeX](https://miktex.org/download)               | TeX distribution                                |
| [Perl](https://strawberryperl.com/)                 | Perl                                            |
| [VS Code](https://code.visualstudio.com/download)   | Allgemeine IDE                                  |
| Erweiterungen für Latex:                            |                                                 |
| LaTeX Workshop                                      |                                                 |
| Hilfreich bei LaTeX:                                |                                                 |
| Explorer Exclude                                    | Ausblenden von .aux und so was                  |
| Spell Right                                         | Für Sprachcheck in IDE                          |
| Todo+                                               | Für #TODO Kommentare                            |
|                                                     |                                                 |
| Allgemein Hilfreich:                                |                                                 |
| _Markdown Preview Enhanced_                         |                                                 |
| _PlantUML_                                          |                                                 |
| Better Comments                                     |                                                 |
| Code Runner                                         |                                                 |
| Prettier - Code formatter                           | Automatische Formatierung, geht nicht bei Latex |
|                                                     |                                                 |
| [Git for Windows](https://git-scm.com/download/win) | Git                                             |
| [Sourcetree](https://www.sourcetreeapp.com/)        | für Git                                         |
| Python                                              |                                                 |

## Einrichten

1. install git
2. install Sourcetree
3. clone Repository
4. install Perl
5. install MiKTex
6. install VS Code
7. install VS Code Extensions
8. reboot
9. try `latexmk` in cmd
10. open `Bachelorarbeit.code-workspace`
11. open TEX extension
12. Build LaTeX Project -> Recipe: latexmk
13. try build

## Infos

- Formatierung für Latex hab ich noch nicht zum laufen bekommen
- Stricht bei gleichen Autoren in Literatur gerade noch ein Problem, ist aber nach IEEETran
- autoref für Anhang geht nicht

## Shortcuts

| Tasten             | Auswirkungen                                                  |
| ------------------ | ------------------------------------------------------------- |
| `Ctrl`+`p`         | File Auswahl bei Namen                                        |
| `Shift`+`Ctrl`+`p` | vs code suche Kommando                                         |
| `Ctrl`+`b`         | Latex build                                                   |
| `Ctrl`+`Alt`+`b`   | Rechte Leiste toggle                                         |
| `Shift`+`Alt`+`f`  | Formatieren                                                   |
| `Ctrl`+`Shift`+`f` | Suchen in allen Files                                         |
| ``Ctrl`+`.`        | Wenn auch falsch geschrieben Wort, öffnet Korrekturvorschläge |

## Helpful Commands

| Command                                          | Funktion                            |
| ------------------------------------------------ | ----------------------------------- |
| `>LaTeX Workshop: View LaTeX PDF file`           |                                     |
| `>LaTeX Workshop: Count words in LaTeX document` | In Main ausführen, Zählt die Wörter |

## Helpful LaTeX

| Befehl / Zeichen              | Bedeutung / Verwendung                                          |
| ----------------------------- | --------------------------------------------------------------- |
| `` "`<Text>"' ``              | „\<Text\>“ (Deutsche Anführungszeichen)                         |
| ` ``<Text>'' `                | “\<Text\>” (Englische Anführungszeichen                         |
| `\cite{<bib_key>}`            | `[<Quellen Nr.>]`                                               |
| `\cite[<Text>]{<bib_key>}`    | `[<Quellen Nr.>, <Text>]`, für Seitenangabe oder ähnliches      |
| `\autoref{<type>:<labelname>` | `<Type ausgeschrieben> <Nr>`, Referenz auf Bild oder ähnliches  |
| ^                             | funktioniert nicht für Anhang                                   |
| `\<befehl>*{<arg>}`           | Befehl ohne Link, z.B. `\section*{Test}` erscheint nicht in TOC |

## Sonstiges

| Was                                                                                      | Bedeutung / Verwendung                                                  |
| ---------------------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| `*.aux OR *.blg OR *.bbl OR *.bcf OR *.log OR *.lot OR *.tdo OR *.lof OR *.toc OR *.out` | Windows File Explorer Suchbegriff um alle LaTeX-Temp-Dateien zu löschen |
