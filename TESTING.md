# Tests und Reproduzierbarkeit — Lernfunke

## Voraussetzungen
Node 22+; npm ci bei fehlender gepinnter Playwright-Testabhängigkeit; vorhandenes Chrome.

## Befehle
```text
npm test
npm run test:browser
```

Start/Build: npm start; Loopback-URL aus dem Terminal öffnen. Keine Konten erforderlich.

## Tatsächlicher Befund vom 02.11.2026
10 Node-Testgruppen und 31 Chrome-Prüfungen bestanden nach Erweiterung auf zwölf Übungen; Offline-Ausführung, alte V1/V2-Fortschritte und atomare Fehlerpfade geprüft.

Bei fehlenden Paketen/Hardware/Betriebssystemen ist das Ergebnis „nicht ausgeführt“, kein Pass. Plattformnachweise aus älteren Detailberichten gelten nur für die dort genannten Versionen. Android-Automatisierung ausschließlich mit expliziter emulator-Seriennummer und bestätigtem ro.kernel.qemu=1. Physische Geräte, persönliche Medien und Produktionskonten sind keine Testfixtures.

## Vor Merge
`git diff --check` ausführen; relevante Funktionstests wiederholen, wenn Codeänderungen ihren Befund entwerten. Speicherdaten/alte Versionen erhalten. Fehlende externe Abnahmen in HANDOFF.md benennen.
