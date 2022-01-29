Zusammenfassung der Unterlagen, die ich mir während meiner FaMI-Ausbildung 2014-2017 (MMBBS Hannover) als Wiki zusammengestellt habe. Weil sie damals auch von anderen genutzt wurden und wohl auch weiterhin genutzt werden, ich aber keine regelmäßige Aktualisierung gewährleisten kann, habe ich das Wiki jetzt in eine statische Form überführt und hier bereitgestellt. 

Angereichert mit dem ein oder anderen Kram, den ich interessant fand, der möglicherweise auch für andere FaMIs und überhaupt Mitarbeiter:innen in Archiven und Bibliotheken relevant oder jedenfalls interessant sein kann. 

Ergänzende Inhalte, Linktipps etc. finden sich auf [meinem Blog](https://blog.grdl.eu), dort finden sich auch alternative Kontaktmöglichkeiten.

Diejenigen Inhalte der Einführung, bei denen ich etwas mehr geändert habe, sind mit Doppelpunkt gegendert, bei neuen Inhalten versuche ich darauf zu achten - möglicherweise komme ich irgendwann dazu, das nochmal überall einzuarbeiten,  



## Verwendete Software:

- [Mkdocs](https://www.mkdocs.org/)
- [Material Theme](https://squidfunk.github.io/mkdocs-material/) (Theme)
- Markdown-Extensions:
  - [footnotes](https://python-markdown.github.io/extensions/footnotes/) (Fußnoten)
  - [Highlight](https://facelessuser.github.io/pymdown-extensions/extensions/highlight/) (Code-Highlighting in Blöcken)
  - [InlineHilite](https://facelessuser.github.io/pymdown-extensions/extensions/inlinehilite/) (Inline-Code-Highlighting)
  - [Keys](https://facelessuser.github.io/pymdown-extensions/extensions/keys/) (Hervorhebung von Tastenkombinationen)
  - [mdx_truly_sane_lists](https://github.com/radude/mdx_truly_sane_lists) (Verschachtelte Listen)
  - [Superfences](https://facelessuser.github.io/pymdown-extensions/extensions/superfences/) (Code-Verschachtelung, Blöcke)
  - [toc](https://python-markdown.github.io/extensions/toc/) (Inhaltsübersichten)


## Hinweis zum Javascript

Im Repository nicht enthalten ist die js-Bibliothek [tablesort](https://github.com/tristen/tablesort) von tristen. Bei mir liegt diese lokal auf dem Server, um den Datenverkehr nach außen zu verhindern, für die Weiterverwendung muss entweder die Datei tablesort.min.js von tablesort im Ordner ``docs/_js`` eingefügt werden oder die Einstellung unter ```mkdocs.yml``` für zusätzliches Javascript (```extra_javascript```) angepasst werden. Andernfalls sind die Tabellen nicht sortierbar.