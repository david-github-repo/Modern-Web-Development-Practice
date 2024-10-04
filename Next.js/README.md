# Einführung in Next.js

## Was ist Next.js?

- **React-basiertes Framework**: Bietet zusätzliche Funktionen für Server-seitiges Rendering (SSR) und statische Webseiten-Generierung.
- **Erstellt von Vercel**: Entwickelt für eine bessere Performance und SEO im Vergleich zu klassischen Single Page Applications (SPA).
- **Full-Stack-Unterstützung**: Ermöglicht Frontend- und Backend-Logik in einer einzigen Anwendung.
- **Routing**: Dateibasierter Routing-Ansatz → Automatisches Erstellen von Routen basierend auf der Dateistruktur.
- **API-Routen**: Ermöglicht das Erstellen von Server-APIs innerhalb des Projekts.

## Vorteile von Next.js gegenüber Plain HTML, CSS und JavaScript

- **Server-seitiges Rendering (SSR)**:
  - Inhalte werden auf dem Server gerendert → Schnellere Ladezeiten und bessere SEO (Suchmaschinenoptimierung).
  - Bei Plain HTML/JavaScript: Alles wird clientseitig geladen → Schlechtere Performance für große Websites.

- **Statische Seitengenerierung (SSG)**:
  - Seiten werden im Voraus generiert und als statische HTML-Dateien bereitgestellt.
  - Extrem schnelle Ladezeiten, besonders für Blogs und Dokumentationen.
  
- **Full-Stack-Möglichkeiten**:
  - Next.js kombiniert Frontend- und Backend-Entwicklung → Integrierte API-Routen.
  - Erspart die Trennung zwischen verschiedenen Backend- und Frontend-Systemen.

- **Automatisches Code-Splitting**:
  - Nur die benötigten Teile des Codes werden geladen → Schnellere Performance.
  - Bei Plain HTML/JavaScript: Keine automatische Optimierung → Größere Ladezeiten.

- **Integrierte Bild-Optimierung**:
  - Automatische Optimierung von Bildern für bessere Ladezeiten.
  - Bei Plain HTML/JavaScript: Bilder müssen manuell optimiert werden.

- **SEO-Vorteile**:
  - Durch SSR und SSG kann Google die Seiten besser crawlen und indexieren → Bessere Platzierungen in den Suchergebnissen.
  - Plain HTML/JavaScript: Client-seitiges Rendering kann SEO erschweren, da Inhalte erst nach dem Laden sichtbar sind.

- **Hot Reloading**:
  - Änderungen am Code werden sofort sichtbar, ohne die Seite neu laden zu müssen.
  - Plain HTML/JavaScript: Manuelles Neuladen der Seite nach jeder Code-Änderung.

## Warum Next.js statt Plain HTML, CSS & JavaScript?

- **Performance**: SSR, SSG und Code-Splitting führen zu deutlich besseren Ladezeiten.
- **SEO**: Bessere Sichtbarkeit in Suchmaschinen durch serverseitiges Rendering.
- **Entwicklerfreundlichkeit**: Moderne Features und integrierte Tools vereinfachen die Entwicklung im Vergleich zu purem HTML/CSS/JavaScript.
- **Skalierbarkeit**: Next.js skaliert besser für größere und dynamischere Anwendungen.
- **Einfache Routing-Lösung**: Automatisches Routing durch Dateistruktur, keine manuelle Einrichtung notwendig.
- **Vollwertiges Framework**: Next.js bietet sowohl Frontend- als auch Backend-Lösungen, was die Entwicklung vereinfacht und beschleunigt.

---

`pnpm dlx create-next-app --use-pnpm ./`
