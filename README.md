# Mentalo
Bekannt aus der TV Serie "King of Queens" stellt Mentalo einen orientalischen Schamanen dar.
Nach dem Stellen der Frage an Mentalo erfolgt dessen Antwort nach einem Zug an der Kordel.
Während der Antwort leuchten Mentalos Augen rot auf. Die Antwort setzt sich aus zwei Teilen zusammen. 
Der erste Teil ist eine Einleitung und wird zufällig aus folgenden drei Varianten gewählt:
a) "Die Stimmen aus der Tiefe des Grabes sagen..."
b) "Meine Grabesquellen haben mit mitgeteilt..."
c) "Die spirituelle Welt sagt mir..."
Der zweite Teil ist die eigentliche Antwort und wird zufällig aus folgenden drei Varianten gewählt:
a) "Ja"
b) "Nein"
c) "Mach weiter"
In der HTML Datei wird nach dem Klicken auf den Button dieser deaktiviert, Mentalos Bild 
durch eines mit roten Augen geöffnet und die Soundausgabe des ersten Teils begonnen. Dabei wird eine ganzzahlige 
Zufallszahl zwischen 1 und 3 bestimmt und als String konvertiert. Damit wird der Pfad zur MP3 Datei 
gebildet und die entsprechende Datei abgespielt. Das bei erfolgtem Abspielen ausgelöste Event 
bewirkt die Erzeugung des Ausgabe des zweiten Teils nach gleichem Prinzip. Nach dessen Event über das 
erfolgte Abspielen wird das Bild von Mentalo zurückgewechselt und der Button aktiviert.
Die Mediendateien befinden sich in /res/.

Viel Spaß,
André Frank Nikisch, Dipl.-Ing.
