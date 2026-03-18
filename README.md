# KuchenTV Evidence-Based Research

Hey Leute, hier ist Toni Cubano, Security Researcher und Frontend Developer. Ich hab mich mal hingesetzt und eine evidenzbasierte Recherche zu KuchenTV gemacht - dem YouTube-Kanal von Tim Heldt. Warum? Weil ich neugierig war, was hinter diesem ganzen Hype steckt. Als jemand, der sich mit Daten und Sicherheit beschäftigt, wollte ich mal sehen, wie man systematisch Influencer-Daten sammelt und analysiert.

## Was ist das hier?

Dieses Repository enthält eine umfassende, evidenzbasierte Analyse des YouTube-Kanals KuchenTV. Ich hab alles strukturiert gesammelt: Videos, Channel-Info, Google-Suchen und sogar ChatGPT-Analysen. Ziel war es, eine solide Datenbasis zu schaffen, die man für weitere Analysen nutzen kann.

### Warum evidenzbasiert?
- **Primäre Quellen**: Direkte Daten von YouTube über MCP Browser Tools
- **Sekundäre Quellen**: Google-Suchen für Biografie-Infos
- **KI-Analyse**: ChatGPT für Content-Insights
- **Strukturierte Speicherung**: Alles in JSON und Textdateien, maschinenlesbar

## Projektstruktur

```
Influencer-Kuchen_TV/
├── data/
│   ├── channel_info/
│   │   └── channel.json          # Channel-Metadata (Subs, Links, etc.)
│   └── videos/
│       └── videos.json           # Video-Sammlung mit Details
├── research/
│   ├── google/
│   │   └── google_search_results.json  # Google-Suchergebnisse
│   ├── chatgpt/
│   │   └── chatgpt_response.txt        # KI-Analyse des Contents
│   └── research_summary.txt            # Zusammenfassung aller Daten
└── README.md                           # Diese Datei
```

## Datenquellen

### YouTube Channel (@KuchenTV)
- **Gründung**: 2014
- **Abonnenten**: 1,19 Mio.
- **Videos**: 1799
- **Style**: Direkt, humorvoll, kontrovers, ungescriptet

### Gesammelte Daten
- **Videos**: Titel, URLs, Beschreibungen, Teilnehmer, Views, Datum, Dauer
- **Channel-Info**: Links zu Social Media, anderen Kanälen, Impressum
- **Recherche**: Biografische Infos, Content-Analyse, Zukunftsaussichten

### Beispiel-Videos
1. **ApoRed Insolvenz-Diskussion** - Kuchen Talks #734
2. **Ungescriptet mit Ben** - Redefreiheit-Themen
3. **Joyce Ilg Interview** - Promis und Aliens
4. **Exsl Awkward Interview** - Gameplay-Kanal
5. **Fortnite Matchmaking** - Satire mit Kids

## Wie nutzt man das?

1. **Daten analysieren**: Die JSON-Dateien enthalten alle strukturierten Daten
2. **Recherche erweitern**: Füg mehr Videos hinzu oder scrape weitere Quellen
3. **Visualisierungen**: Baue Dashboards mit den Daten (ich als Frontend-Dev würde das mit React machen)
4. **Security-Aspekte**: Schau dir die Datenquellen an - alles über authentifizierte Browser-Tools

### Technische Details
- **Tools verwendet**: MCP Browser (YouTube-Zugang), Python für Datenverarbeitung
- **Sicherheit**: Alle Datenquellen verifiziert, keine unsicheren Skripte
- **Datenschutz**: Nur öffentlich verfügbare Infos gesammelt

## Über mich

Ich bin Toni Cubano, Security Researcher und Frontend Developer. Tagsüber bastle ich an sicheren Webanwendungen und forsche zu Cybersecurity. In meiner Freizeit interessiere ich mich für Influencer-Kultur und wie Daten darüber fließen. Dieses Projekt war für mich eine coole Übung in evidenzbasierter Recherche - kombiniert mit meinen Tech-Skills.

Falls du Fragen hast oder mitmachen willst: Schau auf meinem GitHub vorbei oder kontaktiere mich. Lass uns über Daten, Sicherheit und YouTube quatschen!

## Disclaimer

Alle Daten sind öffentlich verfügbar und wurden ethisch gesammelt. Keine persönlichen Daten von Individuen wurden gespeichert - nur Channel- und Content-Infos. Verwende die Daten verantwortungsvoll.
