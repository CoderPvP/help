# Anleitung zum Aktualisieren des TXAdmin-Panels auf einem Linux-Server

Folge diesen Schritten, um das TXAdmin-Panel auf die neueste Version zu aktualisieren:

1. **Server herunterfahren:**
   - Stelle sicher, dass der Server gestoppt ist, bevor du Änderungen vornimmst.

2. **Zum Alpine-Ordner navigieren:**
   - Der Pfad zum TXAdmin-Panel lautet: `/alpine/opt/cfx-server/citizen/system_resources/monitor`.

3. **TXAdmin-Ordner leeren:**
   - Lösche den Inhalt des `monitor`-Ordners, um Platz für die neue Version zu schaffen.

4. **Aktuellste Version von TXAdmin herunterladen:**
   - Gehe zu [GitHub TXAdmin Releases](https://github.com/tabarra/txAdmin/releases).
   - Lade die neueste `monitor.zip`-Datei herunter.

5. **ZIP-Datei auf den Server hochladen und entpacken:**
   - Lade die `monitor.zip`-Datei auf deinen Server.
   - Entpacke die ZIP-Datei im `monitor`-Ordner.

6. **ZIP-Datei löschen:**
   - Nachdem die Datei entpackt wurde, kannst du die `monitor.zip`-Datei löschen, um Speicherplatz freizugeben.

7. **Server neu starten:**
   - Starte deinen Server neu.
   - Überprüfe, ob das TXAdmin-Panel jetzt auf die neueste Version aktualisiert wurde.

Durch diese Schritte sollte dein TXAdmin-Panel auf die neueste Version aktualisiert sein und reibungslos funktionieren.
