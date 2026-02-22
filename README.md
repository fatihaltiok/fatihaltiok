# Fatih Altiok — AI Systems Builder

**Offenbach · Raum Frankfurt**

Ich baue autonome KI-Systeme die tatsächlich in Produktion laufen.

Kein klassischer Softwareentwickler — ich denke Systeme, orchestriere KI-Modelle und bringe Automatisierung in den Alltag. Seit über einem Jahr entwickle ich **Timus**, ein autonomes Multi-Agent-System das selbstständig Aufgaben ausführt, Browser und Desktop steuert, per Telegram kommuniziert und rund um die Uhr läuft.

Offen für: **Freelance-Projekte** · **KI-Integration** · **Prozessautomatisierung**

---

## Hauptprojekt: Timus

> Autonomes Multi-Agent-System · 7 spezialisierte KI-Agenten · 50+ Tools · läuft als systemd-Service

**[→ github.com/fatihaltiok/Agentus-Timus](https://github.com/fatihaltiok/Agentus-Timus)**

Was Timus kann:
- Aufgaben aus einer priorisierten Queue **selbstständig abarbeiten** — auch unbeaufsichtigt
- Per **Telegram** steuern: Text, Sprache (Whisper STT), Bilder, Dokumente
- **Browser und Desktop** autonom bedienen — Screenshots, Klicks, Formulare, Navigation
- **Tiefenrecherchen** durchführen und strukturierte Berichte erstellen
- **Bilder generieren** (DALL-E 3), Code schreiben, Systeme überwachen
- **Echtzeit-Monitoring** im Browser — Canvas-UI mit Live-Agent-LEDs und Chat

```
Telegram → TelegramGateway → SQLite TaskQueue → AutonomousRunner
                                                       ↓
                              7 Agenten (OpenAI · Anthropic · DeepSeek · lokal)
                                                       ↓
                              MCP-Server · 50+ Tools · systemd · Port 5000
```

**Stack:**
`Python` `FastAPI` `asyncio` `SQLite` `Playwright` `PyAutoGUI`
`OpenAI API` `Anthropic API` `Florence-2` `Whisper` `Telegram Bot API` `systemd` `Linux`

---

## Was ich anbiete

| Bereich | Konkret |
|---|---|
| **KI-Automatisierung** | Wiederkehrende Prozesse mit KI-Agenten automatisieren |
| **LLM-Integration** | OpenAI, Anthropic, lokale Modelle in bestehende Systeme einbinden |
| **Browser-/Desktop-Automation** | Formulare, Portale, Datenpflege automatisch erledigen |
| **Telegram-Bots & KI-Assistenten** | Unternehmens-Bots die echte Aufgaben ausführen |
| **Prototypen & MVPs** | Schnelle KI-Lösungen von der Idee bis zum laufenden System |

---

## Mein Ansatz

Ich nutze KI als Werkzeug — nicht als Ersatz für Denken.
Architektur, Entscheidungen, Debugging und Produktionsreife: das ist meine Arbeit.
Den Code erstelle ich zu großen Teilen KI-gestützt — konzipiert, bewertet und verantwortet von mir.

Das ist keine Einschränkung. Es ist die Arbeitsweise die Ergebnisse liefert.

---

## Kontakt

📧 fatihaltiok@outlook.com
🔗 [github.com/fatihaltiok](https://github.com/fatihaltiok)
📍 Offenbach · Raum Frankfurt · Remote möglich
