# Static Site Generators (SSG)

Mit Static Site Generatoren lassen sich Webseiten als statische Seiten herstellen (rendern). Diese haben aus meiner Sicht insbesondere dahingehend Vorteile, dass sich die Seiten - einmal gerendert - auch auf eher "schwachbrüstiger" Hardware wie einem Raspberry Pi bereitstellen lassen. Benötigt wird meist nur ein ganz einfacher Webserver wie Apache oder Nginx, jedoch keine Datenbanken, PHP oder ähnliches. Dynamische Inhalte wie filterbare Tabellen können mit im Browser ausgeführtem JavaScript bereitgestellt werden. Die (Text-)Inhalte werden meist mit Markdown hergestellt und bleiben in diesem Format vorhanden.

Insbesondere bei Inhalten, die nicht häufig geändert werden müssen, sinkt aufgrund der Anforderungen der Betreuungsaufwand. Zwar muss der Webserver weiterhin aktuell gehalten werden - aber keine Datenbank, kein CMS, etc. 

## Ausgewählte Generatoren

  - [Hugo](https://gohugo.io/):: Sehr schneller SSG
  - [Jekyll](https://jekyllrb.com/): In Ruby geschriebener SSG, einer der "Platzhirsche". Kann (teils mit Plugins) alles von Blog bis Warenkorb, also eine Art eierlegende Wollmilchsau.
  - [MkDocs](https://www.mkdocs.org/): SSG mit Fokus auf die Erstellung von Dokumentationen, verwende ich etwa für dieses "Wiki". Derzeit mein Tool der Wahl, meiner Ansicht nach sinnvolle Ergänzungen stehen [unten](###MkDocs).

### MkDocs

#### Erweiterungen

Ich bevorzuge das [Material Theme](https://squidfunk.github.io/mkdocs-material/).

**Erweiterungen/Plugins:**

  - [footnotes](https://python-markdown.github.io/extensions/footnotes/): Fußnoten
  - [Highlight](https://facelessuser.github.io/pymdown-extensions/extensions/highlight/): Code-Highlighting in Blöcken
  - [InlineHilite](https://facelessuser.github.io/pymdown-extensions/extensions/inlinehilite/): Inline-Code-Highlighting
  - [Keys](https://facelessuser.github.io/pymdown-extensions/extensions/keys/): Hervorhebung von Tastenkombinationen
  - [mdx_truly_sane_lists](https://github.com/radude/mdx_truly_sane_lists): Verschachtelte Listen
  - [Superfences](https://facelessuser.github.io/pymdown-extensions/extensions/superfences/): Code-Verschachtelung, Blöcke
  - [toc](https://python-markdown.github.io/extensions/toc/): Inhaltsverzeichnisse

Diese Erweiterungen sind natürlich nicht für jede Installation sinnvoll oder gar notwendig, aber insgesamt hilfreich.

## Hosting

Neben dem Hosting auf eigenen Geräten gibt es auch spezialisierte Anbieter. Eine Auswahl:

  - [Cloudflare Pages](https://pages.cloudflare.com/)[^fn1]
  - [GitHub Pages](http://pages.github.com/)
  - [Netlify](https://www.netlify.com/)


[^fn1]: Vgl. [Jörg Kantel: Ein neues Zuhause für den Schockwellenreiter? (Update)](http://blog.schockwellenreiter.de/2022/03/2022033002.html)
