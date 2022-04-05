# Metadaten löschen

Es gibt verschiedene Gründe, Metadaten loswerden zu wollen. Etwa, wenn Verlage unsichtbare Metadaten einfügen, um Leser\*innen identifizieren und verfolgen zu können.[^fn1] Ein hervorragendes Beispiel, warum es nichts schadet, als Archivar\*in mal eine Kommandozeile aus der Nähe gesehen zu haben.

## Tools

Eine Auswahl von Tools, die halbwegs einfach nutzbar sind:

  - [Dangerzone](https://dangerzone.rocks/) (GUI, verwandelt PDF-Dateien zunächst in Bilddateien und dann zurück, macht Texte mit OCR wieder kopierbar; Linux, Mac, Windows)
  - [ExifTool](https://exiftool.org/) (Terminal; Mac, Linux, Windows)
  - [MAT2](https://0xacab.org/jvoisin/mat2) (GUI, verwandelt PDF-Dateien in Bilddateien; Mac, für Linux [Metadata Cleaner](https://gitlab.com/rmnvgr/metadata-cleaner))

## Beispiele

Mit ExifTool und [QPDF](https://qpdf.sourceforge.io/) können große Teile der Metadaten in zwei Schritten bereinigt werden:[^fn2]

```bash
exiftool -all:all= <path.pdf> -o <output1.pdf>
qpdf --linearize <output1.pdf> <output2.pdf>
```

Für Unix-Systeme gibt es auch fertige Skripte, z.B. hier: [Sneakers the Rat: clean_pdf.sh](https://gist.github.com/sneakers-the-rat/172e8679b824a3871decd262ed3f59c6)

Eine Einführung in die Nutzung von MAT2 unter Linux (oder in einer virtuellen Maschine) gibt es [hier](https://linux-gefaellt-mir.blogspot.com/2014/12/metadaten-loeschen-mit-mat.html) eine Anleitung.

[^fn1]: Vgl. [Klaus Graf: Versteckte IDs in Metadaten von PDFs erlauben Identifikation von Quelle und Downloadern. In: Archivalia, 14.02.2022](https://archivalia.hypotheses.org/140376)
[^fn2]: Vgl. [Tweets von @json_dirs, 26.01.2022](https://twitter.com/json_dirs/status/1486120144141123584)
