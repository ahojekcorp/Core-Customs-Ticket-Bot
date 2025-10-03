# Core-Customs-Ticket-Bot
Free Ticket Bot for your Discord. 
## Bot verwenden

### 1. Ticket-Panel einrichten

Gehe in einen Discord-Kanal und gib ein:

/setup


Der Bot erstellt ein Panel mit einem Button "📩 Ticket erstellen"

### 2. Ticket erstellen

Benutzer klicken auf den Button → Ein privater Ticket-Kanal wird erstellt

### 3. Weitere Commands

- `/close [grund]` - Ticket schließen
- `/add @benutzer` - Benutzer zum Ticket hinzufügen
- `/remove @benutzer` - Benutzer aus Ticket entfernen
## Anpassungen
### Farben ändern

Bearbeite die Hex-Codes in den Dateien unter `bot/commands/` und `bot/events/`:
- `#5865F2` - Blau (Info)
- `#57F287` - Grün (Erfolg)
- `#ED4245` - Rot (Fehler)

### Texte anpassen

Alle deutschen Texte findest du in:
- `bot/commands/*.js` - Command-Beschreibungen
- `bot/events/interactionCreate.js` - Ticket-Nachrichten

## Lizenz

MIT - Frei verwendbar für private und kommerzielle Projekte
