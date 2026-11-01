# Sternenklinge

Ein Weltraum-Abenteuer für Kinder, gebaut mit [Phaser 3](https://phaser.io).

- **Laserschwert-Duell:** Blitze der Trainings-Drohnen abwehren und zurückschlagen.
- **Sternenjäger-Flug:** Fliegen, schießen, Asteroiden ausweichen, das Mutterschiff besiegen.
- **Zu zweit fliegen:** Zwei Schiffe auf einem Tablet, gemeinsame Herzen.

Das Spiel braucht nach dem ersten Öffnen kein Internet mehr und lässt sich wie eine App auf den Startbildschirm legen.

## Auf GitHub Pages veröffentlichen

1. Auf [github.com/new](https://github.com/new) ein neues Repository anlegen, zum Beispiel `sternenklinge`. Sichtbarkeit: **Public** (GitHub Pages ist für private Repos nur mit bezahltem Konto verfügbar).
2. Im neuen Repository auf **„uploading an existing file"** klicken und den **Inhalt** dieses Ordners hineinziehen (nicht den Ordner selbst, `index.html` muss ganz oben liegen). Auf **Commit changes** klicken.
3. **Settings → Pages** öffnen. Unter „Build and deployment" bei *Source* **Deploy from a branch** wählen, dann Branch **main** und Ordner **/ (root)**, und **Save** klicken.
4. Nach ein bis zwei Minuten erscheint oben auf der Pages-Seite der Link, etwa
   `https://DEIN-NAME.github.io/sternenklinge/`

Hinweis: Die Datei `.nojekyll` ist unsichtbar und wird beim Hochladen per Browser manchmal ausgelassen. Das Spiel funktioniert auch ohne sie.

## Für die Zugfahrt

1. Den Link **vor der Abfahrt** auf jedem Gerät einmal mit Internet öffnen und kurz das Menü anzeigen lassen. Danach ist alles auf dem Gerät gespeichert.
2. Als App auf den Startbildschirm legen:
   - **iPad/iPhone (Safari):** Teilen-Symbol → „Zum Home-Bildschirm".
   - **Android (Chrome):** Menü (⋮) → „Zum Startbildschirm hinzufügen" bzw. „App installieren".
3. Danach startet das Spiel im Vollbild, auch ohne Netz.

## Steuerung

| | Touch | Tastatur |
|---|---|---|
| Duell | Dorthin tippen, wo der Blitz herkommt (Finger halten = Schwert bleibt aktiv) | Pfeile drehen das Schwert, Leertaste schlägt |
| Flug | Finger aufs Display, Schiff folgt | Pfeiltasten oder WASD |
| Zu zweit | Linke Hälfte = Orange, rechte Hälfte = Grün | Spieler 1: WASD, Spieler 2: Pfeile |
| Pause | Knopf oben rechts | P oder Esc |

## Spiel später ändern

Wenn `index.html` geändert wird, in `sw.js` die Zeile `const CACHE = 'sternenklinge-v1';` auf `v2` (usw.) erhöhen. Sonst zeigen Geräte, die das Spiel schon gespeichert haben, weiter die alte Fassung.

## Lizenzen

- Phaser: MIT-Lizenz, siehe `LICENSE-Phaser.md`
- Schrift „Russo One": SIL Open Font License, siehe `fonts/LICENSE-Russo-One.txt`
- Alle Spielgrafiken werden im Code gezeichnet, es gibt keine fremden Bilder.
