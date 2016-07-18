# jdownloader-folderwatch

### jDownloader Einstellungen
Unter Einstellungen -> Ordnerüberwachung folgende Werte überprüfen:

| Einstellung                   | Wert            |
| ------------------------------|:---------------:|
| FolderWatch: Folders          | ["folderwatch"] |
| FolderWatch: Debug            | false           |
| FolderWatch: Check Interval   | 10000           |

### crawljob - Dateien hinzufügen
Der Ordner "folderwatch", der unter den Einstellungen angegeben wurde, wird in einem Interval nach *.crawljob* - Dateien untersucht. Dieser Ordner befindet sich nach Standard Einstellungen in Installationsverzeichnis von jDownloader. Falls man gerade nicht weiß, wo genau dieser nun ist, kann man auch mithilfe der Kommandozeile (cmd) den Pfad herausfinden.

###### **für jDownloader v2**
In der Kommandozeile (cmd.exe) folgendes eingeben:
```shell
$ SET JD2_HOME
JD2_HOME=C:\Users\cooolinho\AppData\Local\JDownloader v2.0>
```

Anschließend muss dieser Ordner nur noch mit *.crawljob* - Dateien gefüllt werden und jDownloader beginnt automatisch mit dem Download.

