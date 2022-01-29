# Commandline

Was sich über die Zeit so an Helferlein angesammelt hat. Wenn nicht explizit anders angegeben, für die Linux-Bash, sollten auch in einem Windows-Linux-Subsystem funktionieren.

## Zeichenketten in vielen Dateien ersetzen

Wir haben einen Stapel Textdateien in mehreren (Unter-)Ordnern, in denen "alt" steht, wo "neu" stehen sollte. Lösung:[^fn-zeichenketten]

```sh
grep -RiIl 'alt' | xargs sed -i 's/alt/neu/g'
```

## Dateien in .tar.gz-Archiven durchsuchen

Bspw. alle älteren Minecraft-Log-Dateien nach "Baumhaus" durchforsten:[^fn-zgrep]

```bash
zgrep -i "Baumhaus" *.tar.gz
```

**Sinnvolle Optionen:**

- ```-i``` ignoriert die Groß-/Kleinschreibung
- ```-n``` gibt die Zeilennummer aus
- ```-l``` gibt die Dateinamen zurück, in denen der Ausdruck gefunden wurde

[^fn-zeichenketten]: Via [https://stackoverflow.com/questions/11392478/how-to-replace-a-string-in-multiple-files-in-linux-command-line](https://stackoverflow.com/questions/11392478/how-to-replace-a-string-in-multiple-files-in-linux-command-line)
[^fn-zgrep]: Via [https://www.geeksforgeeks.org/zgrep-command-in-linux-with-examples/](https://www.geeksforgeeks.org/zgrep-command-in-linux-with-examples/)