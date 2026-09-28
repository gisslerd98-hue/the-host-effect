# THE HOST EFFECT – Projektplan Website

Stand: 28.09.2026 · Verbindlich, bis im Entscheidungslog etwas anderes festgehalten wird.

## Arbeitsregeln

1. Erst dieser Plan, dann strikt Phase für Phase. Kein Vorgriff auf spätere Phasen.
2. Reihenfolge: **Text → Design → Technik**. Jede Stufe wird mit Skills und Audits geprüft.
3. Freigabe **einzeln pro Seite**. Eine Seite geht erst in die nächste Stufe, wenn sie freigegeben ist.
4. Jede Entscheidung landet mit Datum und Begründung in `docs/ENTSCHEIDUNGSLOG.md`.
5. Referenzen statt Beschreibungen: Dominik zeigt, was gefällt und was nicht.
6. Bei Unklarheit wird gefragt, bevor gebaut wird. Nicht raten.
7. Bildmaterial: nur die Bilder aus dem Bildordner. Stockfotos nur als Ausnahme, mit Begründung und ausdrücklicher Freigabe.
8. Fakten, Zahlen und Aussagen über Personen stammen nur aus freigegebenen Quellen (Übergabe, Modul-Zusammenfassung). Nichts wird erfunden.

## Feste Grundlagen (Übergabe)

| Bereich | Festlegung | Status |
|---|---|---|
| Marke | THE HOST EFFECT · „People. Culture. Growth.“ · Dominik Gissler | fest |
| Inhalt | Fünf Trainingsmodule laut `The_Host_Effect_Module_Zusammenfassung.pdf` | fest |
| Farben | laut Brand Guide; **reines Weiß verboten**, stattdessen Off-White `#FAF9F6` | fest |
| Schrift | **Widerspruch offen**, siehe Offene Fragen | offen |
| Tonalität + Verbotsliste | laut Übergabe | liegt Claude noch nicht vor |
| Bildmaterial | Bildordner | liegt Claude noch nicht vor |
| Sicherheitsregeln | laut Übergabe | liegt Claude noch nicht vor |

## Phase 0 – Fundament (vor jedem Text)

Ziel: Alle Grundlagen liegen vollständig im Repository und sind widerspruchsfrei.

- 0.1 Brand Guide, Tonalität mit Verbotsliste, Faktenblatt, Sicherheitsregeln und Bildordner ins Repo (`brand/`, `assets/images/`).
- 0.2 Schrift-Widerspruch klären, Ergebnis ins Entscheidungslog.
- 0.3 Faktencheck der Modul-Zusammenfassung (Rechenbeispiele, Quellen von Statistiken). Korrekturen nur mit Freigabe.
- 0.4 Zielgruppen und Ziel der Website festlegen (z. B. Anfrage für Workshop, Erstgespräch). Eine primäre Handlung pro Seite.
- 0.5 Sitemap festlegen: welche Seiten, welche Reihenfolge der Bearbeitung.

**Abschluss:** Freigabe von Fundament und Sitemap.

## Phase 1 – Keyword-Recherche und Suchintention

- 1.1 Keyword-Recherche pro Seite (Haupt-Keyword, Neben-Keywords, Fragen, die Nutzer stellen).
- 1.2 Suchintention je Keyword einordnen (informativ, vergleichend, anfragebereit).
- 1.3 Keyword-Map: jedes Keyword gehört genau einer Seite (keine Kannibalisierung).
- 1.4 Fragen für AEO/GEO sammeln (was eine KI-Suche beantworten soll und wo wir zitiert werden wollen).

Offen: Mit welchem Tool? Ohne Zugang zu Suchvolumen-Daten (z. B. Google Keyword Planner, Sistrix, Ahrefs) kann Claude nur Intention und Themenstruktur liefern, keine belastbaren Suchvolumen.

**Abschluss:** Freigabe der Keyword-Map.

## Phase 2 – Text, Seite für Seite

Pro Seite derselbe Ablauf:

1. **Input:** Dominik sendet Entwürfe, Varianten und Referenzen.
2. **Vergleich:** Claude bewertet die Varianten ehrlich (Note von 10, Begründung) gegen Tonalität, Verbotsliste, Keyword-Map und Faktenlage.
3. **Entwurf:** eine zusammengeführte Fassung.
4. **Audit:**
   - Tonalität und Verbotsliste (Wort für Wort)
   - SEO: Title, Meta-Description, H1–H3-Struktur, Keyword-Platzierung, interne Links
   - AEO: direkte Antworten auf Nutzerfragen, FAQ-Block, klare Definitionen
   - GEO: zitierfähige Aussagen, Autorschaft (E-E-A-T), eindeutige Fakten mit Herkunft
   - Faktencheck: jede Zahl gegen Quelle bzw. Nachrechnung
   - Lesbarkeit
5. **Überarbeitung** nach Audit, Audit-Ergebnis wird mitgeliefert.
6. **Freigabe der Seite** → Eintrag im Entscheidungslog.

**Abschluss:** Alle Seiten textlich einzeln freigegeben.

## Phase 3 – Design

- 3.1 Referenzen sammeln und auswerten (was gefällt, was nicht, warum).
- 3.2 Designsystem: Farben als Tokens (Off-White statt Weiß), Schriftpaar, Abstände, Bildsprache, Komponenten.
- 3.3 Bildzuordnung: welches Bild aus dem Ordner auf welche Seite. Lücken werden benannt, Stockfoto nur mit Begründung und Freigabe.
- 3.4 Entwurf Startseite als erste Seite, dann Seite für Seite.
- 3.5 Audit: Markenkonformität, Barrierefreiheit (Kontrast WCAG AA), mobile Darstellung.
- 3.6 Freigabe je Seite.

## Phase 4 – Technik

- 4.1 Technologie festlegen (Vorschlag: statische Seite, Deployment über Vercel; Entscheidung in dieser Phase).
- 4.2 Umsetzung der freigegebenen Designs.
- 4.3 Technisches SEO: strukturierte Daten (Person, Organization, Course/Service, FAQPage), Sitemap.xml, robots.txt, Canonicals, Open Graph.
- 4.4 Performance: Bildoptimierung, Core Web Vitals.
- 4.5 Recht: Impressum, Datenschutz, Cookie-Lösung (Inhalte liefert Dominik bzw. Rechtsberatung, nicht Claude).
- 4.6 Audit: Lighthouse, Barrierefreiheit, Links, strukturierte Daten.

## Phase 5 – Abnahme und Launch

- 5.1 Gesamtprüfung auf Vorschau-Umgebung.
- 5.2 Freigabe Launch.
- 5.3 Nach Launch: Search Console einrichten, Indexierung prüfen.

## Werkzeuge (ehrlicher Stand)

In dieser Umgebung sind **keine** eigenen Skills für SEO, GEO, AEO oder Webdesign aktiviert. Verfügbar sind: docs, pdf, docx, xlsx, pptx, skill-creator. Die Audits in Phase 2 laufen daher als feste Checklisten (siehe oben). Sollen bestimmte Skills genutzt werden, müssen sie aktiviert oder mit skill-creator gebaut werden.
