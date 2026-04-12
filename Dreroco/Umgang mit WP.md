Hier sind alle Infos, die man fürs Aufrechthalten der Website benötigt, Erneuerungen sind natürlich nicht mit inbegriffen. 
# Texte
Alle Texte sind entweder einzelne Pages oder Posts. Posts sind alles, was im Blog erscheint, Pages sind alles andere. Die Texte oberhalb und unterhalb des Blogs sind eigene Pages.
![[Pasted image 20260412103136.png]]

Bei Texten immer eine Schriftgröße angeben (Rechts). M ist Standardgröße.
![[Pasted image 20260412103222.png]]

# Veränderungen Blogseite
Die Blogseite (Hauptseite) hat einige Veränderungen über Snippets erhalten. Diese sollten hoffentlich nie verändert werden müssen und existieren einfach. Hauptsächlich wird dadurch ein Textblock vor und nach dem Blog hinzugefügt.
![[Pasted image 20260412103336.png]]

# Customizer
## Allgemeines
Im Customizer -> Additional CSS ist einiges gemacht.
![[Pasted image 20260412103621.png]]
Ganz oben sind ganz viele Variablen definiert. 
Ich habe alles über möglichst globale Variablen gemacht, damit man einfach und schnell Anpassungen vornehmen kann, ohne dass man den gesamten Code durchsuchen muss.
Bitte daher alle Veränderungen entweder direkt in den Variablen machen oder eine neue Variable einführen, damit es halbwegs übersichtlich bleibt.
Im Code sind alle Schnippsel immer direkt 2 Mal vorhanden - einmal für den Computer, einmal fürs Handy.
![[Pasted image 20260412103826.png]]
Hier auch immer das beisammen halten, damit man Anpassungen gleich für beides machen kann.
![[Pasted image 20260412103912.png]]
Ich habe es auch grob sortiert, indem ich über Kommentare Überschriften eingefügt habe. Es sollte relativ klar sein, was wo steht. Hier auch eine Struktur beibehalten.

## Hintergründe
Hintergründe können individuell für jede Seite gesetzt werden. Dies geht hier über body.page-id-XX
![[Pasted image 20260412104140.png]]
Die id-XX wird automatisch vergeben und man kann sie erkennen, sobald man eine Page editiert.
Die Seite dann auch fürs Handy eintragen (hier ist momentan none für alle):
![[Pasted image 20260412104244.png]]
## Schriften
![[Pasted image 20260412104331.png]]
Danach gibt es noch einen Bereich für die Schriften. Hier wird (über die Variablen ganz oben) definiert welche Schriftgröße was bedeutet - also wie groß ist S, M, XL, usw.
Ebenso wird das für Links gemacht, es werden Schriftfarben und font definiert...
Wichtig hier: Alles geht über die Variablen am Anfang! Solange sich in wordpress nichts ändert, muss hier nichts geändert werden, man kann die Zahlen oben in den Variablen ändern!

# Weitere Fragen?
![[Pasted image 20260412104936.png]]