# 089 Unfallakte auf dem iPhone installieren

## 1. App-Dateien entpacken
Lade `unfallakte-pwa.zip` herunter und entpacke es auf deinem Computer. Die Dateien `index.html`, `manifest.webmanifest`, `sw.js` und der Ordner `icons` müssen zusammen im obersten Ordner liegen.

## 2. Kostenlos online stellen (GitHub Pages)
1. Öffne https://github.com/new und melde dich an.
2. Erstelle ein Repository namens `unfallakte-app`. Wähle **Public**. Lass **Add a README file** ausgeschaltet und erstelle das Repository.
3. Im neuen Repository: **Add file** → **Upload files**. Ziehe alle entpackten App-Dateien und den Ordner `icons` in die Upload-Fläche. Lade nicht die ZIP-Datei selbst hoch.
4. Wähle **Commit changes**.
5. Öffne **Settings** → **Pages**. Bei **Build and deployment** wähle **Deploy from a branch**, dann Branch **main** und Ordner **/(root)**; klicke **Save**.
6. Warte, bis GitHub Pages veröffentlicht ist. Die Adresse hat dieses Format: `https://DEIN-GITHUB-NAME.github.io/unfallakte-app/`.

GitHub Pages auf einem kostenlosen GitHub-Konto benötigt ein öffentliches Repository. Der App-Code ist damit öffentlich sichtbar. Die Unfallakten und Fotos werden laut aktuellem App-Stand im lokalen Browser-Speicher des jeweiligen Geräts gespeichert; sie werden nicht zu GitHub hochgeladen und nicht zwischen Geräten synchronisiert.

## 3. Auf dem iPhone zum Home-Bildschirm hinzufügen
1. Öffne die veröffentlichte HTTPS-Adresse auf dem iPhone in **Safari**.
2. Tippe auf **Teilen** (Quadrat mit Pfeil nach oben).
3. Scrolle nach unten und tippe auf **Zum Home-Bildschirm**.
4. Tippe auf **Hinzufügen**. Danach startest du die Unfallakte über das neue Symbol.

## Hinweise zu gespeicherten Akten
Die Akten und Fotos liegen nur im Browser-Speicher des Geräts und sind derzeit nicht verschlüsselt. Sie werden nicht automatisch gesichert. Das Löschen der Website-Daten oder Deinstallieren kann gespeicherte Akten entfernen. Lade keine echten Unfallfotos oder persönlichen Daten in das GitHub-Repository hoch.


## Berichte exportieren
Öffne eine Unfallakte und tippe auf **Bericht exportieren**. In der Vorschau kannst du eine bearbeitbare Word-kompatible Datei laden oder über **PDF speichern / teilen** die Druck- und PDF-Funktion deines Geräts öffnen. Auf dem iPhone kannst du das PDF anschließend in „Dateien“ sichern oder aus der Teilen-Ansicht weitergeben. Der Export wird lokal auf dem Gerät erstellt. Unfallfotos werden in den Bericht übernommen; Bilder von Ausweisen und Karten werden aus Datenschutzgründen nicht automatisch beigefügt.


## App-Updates
Wenn ein Update verfügbar ist, zeigt die App beim nächsten Öffnen mittig die Neuerungen. Tippe auf **Update installieren**. Die App aktiviert die neue Version und startet automatisch neu; die lokal gespeicherten Akten bleiben erhalten. Dafür muss das Gerät online sein.
