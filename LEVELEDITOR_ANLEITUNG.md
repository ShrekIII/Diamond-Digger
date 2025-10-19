# Level Editor - Anleitung

## 🎮 Leveleditor für Tunnel Game

### Funktionen:

**Werkzeuge:**
- 🟤 **Erde**: Standard-Block zum Graben
- 🟡 **Gold**: Wertvoll, bringt 50 Punkte
- ⚪ **Silber**: Bringt 20 Punkte  
- 💎 **Diamant**: Sehr wertvoll, bringt 100 Punkte
- 🟢 **Start**: Startposition des Spielers
- 🔴 **Ziel**: Zielpunkt zum Erreichen
- ⬜ **Radierer**: Löscht Blöcke

### Bedienung:

1. **Werkzeug auswählen**: Klicke auf ein Werkzeug in der linken Toolbar
2. **Zeichnen**: Klicke und ziehe auf dem Canvas um Blöcke zu platzieren
3. **Einstellungen**: Passe Level-Größe, Zeit und Punktewerte an
4. **Mit Erde füllen**: Füllt das gesamte Level mit Erde (guter Startpunkt)
5. **Exportieren**: Erstellt JSON-Code zum Speichern
6. **Importieren**: Lädt einen gespeicherten Level
7. **Testen**: Speichert Level in localStorage (öffne dann tunnel_game.html)

### Workflow zum Erstellen eines Levels:

1. ⚙️ Öffne **Einstellungen** und definiere Level-Größe und Name
2. 🌍 Klicke auf **Mit Erde füllen** als Basis
3. ⬜ Nutze den **Radierer** um Tunnel zu graben
4. 💰 Platziere **Gold, Silber und Diamanten** im Level
5. 🟢 Setze den **Startpunkt** (wo der Spieler beginnt)
6. 🔴 Setze das **Ziel** (wohin der Spieler gelangen muss)
7. 📤 **Exportiere** das Level als JSON
8. ▶️ Oder nutze **Testen** um direkt zu spielen

### Level exportieren und im Spiel verwenden:

**Methode 1: Testen (Einfach)**
- Klicke auf "▶️ Testen"
- Öffne `tunnel_game.html` im Browser
- Das Level wird automatisch geladen

**Methode 2: Permanent speichern**
- Klicke auf "📤 Exportieren"
- Kopiere den JSON-Code
- Öffne `tunnel_game.html` in einem Code-Editor
- Füge das Level in das `levels` Objekt ein

### Tipps für gute Level:

✅ **Mache den Weg nicht zu offensichtlich** - verstecke Gold in Seitengängen
✅ **Balance zwischen Herausforderung und Machbarkeit** - nicht zu schwer
✅ **Setze wertvollere Items weiter vom Weg ab** - Belohnung für Erkundung
✅ **Teste dein Level** bevor du es weitergibst
✅ **Passe das Zeitlimit an die Schwierigkeit an**

### Shortcuts:

- **Linke Maustaste gedrückt halten**: Schnelles Zeichnen
- **Radierer + Ziehen**: Schnelles Löschen

Viel Spaß beim Level-Design! ⛏️
