# Saufverwaltung V1
Dies ist eine Software um Strichlisten für Getränke zu verwalten. Leider ist sie relativ benutzerunfreundlich, daher gibt es eine neue, bessere Version [hier](https://github.com/juril33t/Saufverwaltung2). 
## Installation
Um das Programm auszuführen, müssen "db.txt" und "stats.txt" im selben Verzeichnis wie die .jar, bzw. im Projektordner sein. Außerdem weise ich darauf hin, dass die Datei res/Beer-icon.png hier nicht im repository zu finden ist (aus Lizenzgründen). Wer ein Icon haben will, der möge selbst ein 32x32 großes Bild mit dem Namen "Beer-icon.png" in den Ordner res einfügen. Andernfalls alle Zeilen 
```
Image beer = tk.getImage(getClass().getResource("Beer-icon.png"));
frm.setIconImage(beer);
```
in den Klassen, die mit "Gui" beginnen, auskommentieren ;)

## Personalisierung
Um das Programm an die eigenen Bedürfnisse anzupassen, bitte die Konstanten `SUPPORTED_MEMBERS`, `ALC_PRICE` und `ANTIALC_PRICE` in der Main-Klasse anpassen. Was diese tun, sollte eigentlich selbsterklärend sein.
