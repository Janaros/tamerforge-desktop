# TamerForge Desktop

**Sessions leiten, auch ohne Internet.** TamerForge Desktop ist das Windows-Programm zu [tamerforge.de](https://tamerforge.de), dem Werkzeug für Spielleitungen von Pen-&-Paper-Rollenspielen. Du planst Kampagnen, Abenteuer, Sessions und Szenen, leitest am Tisch mit dem Cockpit und bereitest danach nach. Der Desktop-Client macht dasselbe auf deinem Rechner, ganz ohne Netz, und gleicht später alles mit deinem Konto ab.

> Dieses Repository enthält nur die fertigen Installer und Updates. Der Quellcode ist nicht öffentlich.

## Was du damit kannst
- **Alles wie im Browser, nur offline:** Einträge und Editor, Bibliothek, Kompendium, Cockpit mit Szenen, Live-Log, Würfeln und Initiative, Soundboard, Nachbereitung.
- **Spieltisch:** Battlemaps aus Dungeondraft (`.dd2vtt`), Dungeon Alchemist oder Czepeku Architect (`.uvtt`), DungeonFog (`.df2vtt`) oder Foundry-Kartenpaketen. Wände, Türen, Licht, Fog of War, Licht- und Wassereffekte.
- **Spieler-Display als zweites Fenster:** Zieh es auf einen Fernseher oder Beamer. Deine Gruppe sieht nur, was du zeigst.
- **Abgleich mit tamerforge.de:** Was du offline änderst, kommt danach automatisch auf den Server und umgekehrt. Nichts wird still überschrieben: Hat sich etwas auf beiden Seiten geändert, siehst du beide Fassungen und entscheidest.

Offline nicht verfügbar sind die KI-Grundfunktionen, E-Mails, der geheime Display-Link für Spieler-Handys und die Abo-Verwaltung. Dafür brauchst du die Website.

## Voraussetzungen
- Windows 10 oder 11 (64 Bit)
- Ein Konto auf [tamerforge.de](https://tamerforge.de). Für die erste Anmeldung brauchst du einmal Internet.
- Etwa 500 MB freier Speicher, dazu deine Bilder und Töne

## Installieren
1. Unter **[Releases](../../releases/latest)** die Datei `TamerForge-<Version>-setup.exe` herunterladen.
2. Doppelklick auf die Datei. Das Programm installiert sich für deinen Windows-Benutzer, Administratorrechte brauchst du nicht.
3. **Windows-Warnung „Der Computer wurde durch Windows geschützt“:** Das Programm ist noch nicht digital signiert. Klicke auf **„Weitere Informationen“** und dann auf **„Trotzdem ausführen“**. Die Warnung kommt nur beim ersten Mal.
4. TamerForge startet und erscheint im Startmenü.

## Erster Start
1. Es erscheint **„Offline spielen“**. Melde dich mit E-Mail und Passwort deines tamerforge.de-Kontos an, bei aktivierter Zwei-Faktor-Anmeldung zusätzlich mit dem Code.
2. Hake die Kampagnen an, die du offline dabeihaben willst (auch deine **Bibliothek**).
3. **„Jetzt abgleichen“** lädt Einträge, Bilder und Töne herunter. Beim ersten Mal kann das je nach Umfang ein paar Minuten dauern.

Danach bleibst du angemeldet und musst das nicht wiederholen.

## Am Spieltisch
- Arbeite ganz normal: Kampagne öffnen, Session vorbereiten, im **Cockpit** spielen.
- **Spieler-Display:** in der Kampagnenübersicht **„Im zweiten Fenster öffnen“**. Zieh das Fenster auf den zweiten Bildschirm und schalte es per „Vollbild“ auf volle Größe.
- Oben rechts siehst du den **Stand des Abgleichs**, zum Beispiel „Gerade abgeglichen“ oder „Offline – alles bleibt lokal“. Ohne Internet speichert TamerForge alles auf deinem Rechner.

## Abgleich
- **Automatisch** beim Start, alle 10 Minuten und sobald wieder Internet da ist. Das passiert nur auf der Kampagnenübersicht, der Seite „Abgleich“ und im Kompendium, also nie mitten im Bearbeiten oder Spielen.
- **Von Hand** über „Abgleich“ → „Jetzt abgleichen“. Dort kannst du den automatischen Abgleich auch abschalten.
- **Konflikte:** Hast du etwas offline geändert, das inzwischen auch online geändert wurde, siehst du unter „Abgleich“ beide Fassungen und wählst, welche gilt.

## Updates
TamerForge sucht beim Start nach einer neuen Version, lädt sie im Hintergrund herunter und installiert sie **beim nächsten Beenden**. Deine Daten bleiben dabei erhalten. Du kannst eine neue Version auch jederzeit von der [Release-Seite](../../releases/latest) über die alte installieren.

## Wo liegen meine Daten?
- Alles Lokale liegt in deinem Windows-Benutzerordner unter `%APPDATA%\tamerforge`: Datenbank, Bilder, Töne und eine automatische Sicherung bei jedem Start (die letzten 14).
- Die Anmeldung auf diesem Gerät ist verschlüsselt und an dein Windows-Konto gebunden.
- Willst du wechseln oder das Gerät abgeben, gehe auf „Abgleich“ → **„Abmelden“**. Deine lokalen Daten bleiben erhalten, bis du sie löschst.

## Deinstallieren
Windows-Einstellungen → Apps → **TamerForge** → Deinstallieren. Deine Daten in `%APPDATA%\tamerforge` bleiben dabei liegen. Wenn du sie nicht mehr brauchst und alles abgeglichen ist, kannst du den Ordner selbst löschen.

## Hilfe und Datenschutz
- Fragen und Probleme: über das Impressum auf [tamerforge.de](https://tamerforge.de/impressum).
- Was mit deinen Daten passiert: [Datenschutzerklärung](https://tamerforge.de/datenschutz).
