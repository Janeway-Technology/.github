<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Janeway-Technology/.github/main/assets/wortmarken/janeway-technology-dunkel.svg">
    <img alt="Janeway Technology" src="https://raw.githubusercontent.com/Janeway-Technology/.github/main/assets/wortmarken/janeway-technology-hell.svg" width="520">
  </picture>
</p>

<p align="center"><b>Software mit Fokus auf Datenhoheit und Datenschutz — entwickelt und betrieben in Deutschland.</b></p>

<p align="center">
  <a href="https://janeway-technology.com">janeway-technology.com</a> ·
  <a href="https://janeway.io">janeway.io</a> ·
  <a href="mailto:contact@janeway.io">contact@janeway.io</a>
</p>

---

## Überblick

Janeway Technology ist ein Softwareunternehmen aus Neuruppin. Wir bauen Software, bei der die Daten dort bleiben,
wo sie hingehören: auf eigenen Servern in Deutschland, DSGVO-konform und ohne Abhängigkeit von US-Clouds.

## Aktivität

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Janeway-Technology/.github/main/assets/heatmaps/org-dunkel.svg">
  <img alt="Commits je Tag in den letzten 12 Monaten" src="https://raw.githubusercontent.com/Janeway-Technology/.github/main/assets/heatmaps/org-hell.svg" width="100%">
</picture>

<!-- org-listen:anfang (erzeugt: janeway-suite/dev/org-profil.py) -->
## Janeway Projekte

### Janeway Suite

Selbst gehostete Produktivitäts-Suite mit der KI-Assistentin Jane — jede App und jeder Dienst ein eigenes Repo ([Wurzel](https://github.com/Janeway-Technology/janeway-suite)). 80 Repos.

<details><summary>Alle Repos der Suite anzeigen</summary>

| Repo | Worum es geht |
|---|---|
| [janeway-admin](https://github.com/Janeway-Technology/janeway-admin) | Admin-Konsole der Janeway Suite (L4) |
| [janeway-aegis](https://github.com/Janeway-Technology/janeway-aegis) | Janeway Aegis — Security-Monitor für nexus und die Janeway Suite |
| [janeway-affiliate](https://github.com/Janeway-Technology/janeway-affiliate) | Affiliate-Portal (Self-Service) über alle aktiven Partner-Apps (L4) |
| [janeway-agent-engine](https://github.com/Janeway-Technology/janeway-agent-engine) | Self-hosted LiveKit Voice Agent Platform with SIP Trunk support |
| [janeway-agent-relay](https://github.com/Janeway-Technology/janeway-agent-relay) | Matrix-Text-Gegenstück zur agent-engine: reicht Nachrichten (auch WhatsApp/Telegram) an einen Agenten |
| [janeway-ai-chat](https://github.com/Janeway-Technology/janeway-ai-chat) | Multi-Provider-KI-Chat über ai-core mit Credits und Plattform-Billing (L4) |
| [janeway-ai-core](https://github.com/Janeway-Technology/janeway-ai-core) | Zentraler KI-Dienst (L2, Python/FastAPI): LLM-Routing, Tools, Memory/RAG, Suche, Credits |
| [janeway-ai-studio](https://github.com/Janeway-Technology/janeway-ai-studio) | AI Studio: Projekte, Präsentationen, Playground für Bild-, Video- und Audio-Modelle (L4) |
| [janeway-api](https://github.com/Janeway-Technology/janeway-api) | Unified REST-API-Gateway mit zentralem Auth (JWT, Workspace-API-Keys) (L2) |
| [janeway-api-docs](https://github.com/Janeway-Technology/janeway-api-docs) | Öffentliche Doku der Janeway-API aus dem aggregierten OpenAPI-Spec (L4) |
| [janeway-app-sdk](https://github.com/Janeway-Technology/janeway-app-sdk) | Geteilte TS-Infrastruktur aller Web-Apps: ai-core-Client, Inter-App-REST, Supabase, Auth (L2) |
| [janeway-apps](https://github.com/Janeway-Technology/janeway-apps) | Laufzeit von Janeway Blocks — rendert veröffentlichte Baukasten-Apps (L4) |
| [janeway-auth](https://github.com/Janeway-Technology/janeway-auth) | Zentrales Auth-System: Login, MFA, Onboarding, Enterprise-SSO-Broker (L4) |
| [janeway-automations](https://github.com/Janeway-Technology/janeway-automations) | Agenten- und Workflow-Dashboard: Agents, Workflows, Tools, Wissensbasis, Billing (L4) |
| [janeway-azure-mcp](https://github.com/Janeway-Technology/janeway-azure-mcp) | Konnektor-Adapter für Azure: Azure MCP Server mit vorgeschaltetem Gate (L2) |
| [janeway-brain](https://github.com/Janeway-Technology/janeway-brain) | Wissensspeicher der Suite — ein Markdown-Vault je Arbeitsbereich, mit Suche und LLM-Wiki |
| [janeway-browser](https://github.com/Janeway-Technology/janeway-browser) | Chromium für Agenten hinter HTTP mit Live-Ansicht per noVNC (L3) |
| [janeway-browser-bridge](https://github.com/Janeway-Technology/janeway-browser-bridge) | Bridge between the Janeway suite and the Jane in Chrome extension |
| [janeway-cad-editor](https://github.com/Janeway-Technology/janeway-cad-editor) | Janeway-Fork von CADCraft — CAD-Editor hinter cad.janewaylabs.com |
| [janeway-calendar](https://github.com/Janeway-Technology/janeway-calendar) | Calendar: Kalender mit Monats-, Wochen-, Tages-, Agenda- und Jahresansicht plus Buchungslinks (L4) |
| [janeway-canvas-editor](https://github.com/Janeway-Technology/janeway-canvas-editor) | Janeway-Fork von FigCraft — Design-Canvas hinter canvas.janewaylabs.com |
| [janeway-cashflow](https://github.com/Janeway-Technology/janeway-cashflow) | Cashflow: Belege erfassen, Vertraege gegenueberstellen, Ein- und Ausgaben auswerten (Alpha, nur Labs) |
| [janeway-chrome-extension](https://github.com/Janeway-Technology/janeway-chrome-extension) | Jane in Chrome — Chromium extension (Chrome/Edge) for the Janeway suite |
| [janeway-cli](https://github.com/Janeway-Technology/janeway-cli) | janeway — die CLI der Janeway Suite, ein MCP-Client von api.<domain>/mcp |
| [janeway-code-agent](https://github.com/Janeway-Technology/janeway-code-agent) | Code-Agent: nimmt Coding- und Analyseaufträge als MCP-Werkzeuge an (L2) |
| [janeway-community](https://github.com/Janeway-Technology/janeway-community) | Community — Tauschbörse für Bausteine: Skills, Agenten, Workflows (L4) |
| [janeway-compute](https://github.com/Janeway-Technology/janeway-compute) | Compute cages for Jane: one sandboxed workspace per chat (shell, files, packages, checkpoints) |
| [janeway-connect](https://github.com/Janeway-Technology/janeway-connect) | OAuth-Broker und Konnektoren: Microsoft Graph, Google und Fremddienste (L2) |
| [janeway-contacts](https://github.com/Janeway-Technology/janeway-contacts) | Contacts: Kontaktverwaltung mit Gruppen, Favoriten, VCF/CSV-Import/-Export (L4) |
| [janeway-control](https://github.com/Janeway-Technology/janeway-control) | jctl — Admin-Werkzeug der Janeway Suite |
| [janeway-craft-kit](https://github.com/Janeway-Technology/janeway-craft-kit) | Gemeinsame Quelle für die Janeway-Craft-Apps (Editor-Forks): Marke, Theme, Hülle |
| [janeway-crm](https://github.com/Janeway-Technology/janeway-crm) | CRM: Firmen, Personen, Pipelines, Deals, Aktivitäten mit Wiedervorlage (L4) |
| [janeway-dav](https://github.com/Janeway-Technology/janeway-dav) | WebDAV-/CalDAV-Adapter vor Drive: Arbeitsbereiche als Netzlaufwerk (L4) |
| [janeway-desktop](https://github.com/Janeway-Technology/janeway-desktop) | Begleiter für Linux (Prototyp): Jane sieht auf Aufforderung den Bildschirm |
| [janeway-dev](https://github.com/Janeway-Technology/janeway-dev) | Login-geschütztes Gateway der Entwicklungsumgebung dev.janeway.io |
| [janeway-device](https://github.com/Janeway-Technology/janeway-device) | Jane auf Geräten (Linux, Android, …) — ein Rust-Workspace für alle Plattformen |
| [janeway-devops](https://github.com/Janeway-Technology/janeway-devops) | Interne Dev-/Ops-Plattform der Janeway Suite |
| [janeway-dictum](https://github.com/Janeway-Technology/janeway-dictum) | Dictum: Diktat und Aufnahme — Transkript, Zusammenfassung, Aufgaben (L4) |
| [janeway-drive](https://github.com/Janeway-Technology/janeway-drive) | Drive: Cloud-Speicher mit Ordnern, Fassungen, Freigaben, OnlyOffice (L4) |
| [janeway-egress](https://github.com/Janeway-Technology/janeway-egress) | Egress proxy for janeway-compute cages: host allowlist, limits, secret placeholders |
| [janeway-guardian](https://github.com/Janeway-Technology/janeway-guardian) | Virenprüfung (ClamAV) jeder Datei in Drive- und Mail-Speicher (L2) |
| [janeway-gui-elements](https://github.com/Janeway-Technology/janeway-gui-elements) | Geteilte UI-Bibliothek und App-Framework aller Janeway-Apps, mit Showroom (L5) |
| [janeway-hostinger-mcp](https://github.com/Janeway-Technology/janeway-hostinger-mcp) | Konnektor-Adapter: MCP-Server vor der Hostinger-API (L2) |
| [janeway-hub](https://github.com/Janeway-Technology/janeway-hub) | Hub: Startseite der Suite mit App-Leiste und Dashboard (L4) |
| [janeway-immo](https://github.com/Janeway-Technology/janeway-immo) | Maklersoftware: Objekte, Interessenten, Termine, Exposé, OpenImmo (L4) |
| [janeway-infra](https://github.com/Janeway-Technology/janeway-infra) | Self-hosted Supabase-Stack mit allen Migrationen und RLS-Policies (L1) |
| [janeway-layout-editor](https://github.com/Janeway-Technology/janeway-layout-editor) | Janeway-Fork von DesignCraft — Layout/DTP-Editor hinter layout.janewaylabs.com |
| [janeway-legal](https://github.com/Janeway-Technology/janeway-legal) | Rechtstexte der Janeway Suite (DSB-Paket, intern) |
| [janeway-light-editor](https://github.com/Janeway-Technology/janeway-light-editor) | Janeway-Fork von LightCraft — Foto-Entwicklung hinter light.janewaylabs.com |
| [janeway-mail-client](https://github.com/Janeway-Technology/janeway-mail-client) | Mail: IMAP/SMTP-Mailclient mit Konten, Filtern, Abwesenheit, Suche (L4) |
| [janeway-mail-server](https://github.com/Janeway-Technology/janeway-mail-server) | Steuerebene des eigenen Mailservers: Domains und Postfächer (L2) |
| [janeway-maps](https://github.com/Janeway-Technology/janeway-maps) | Maps (Prototyp): Karten, Orte, Suche auf OpenStreetMap, ohne Tracking (L4) |
| [janeway-mcp](https://github.com/Janeway-Technology/janeway-mcp) | Remote-MCP-Server: externe KIs (Claude, ChatGPT, …) bedienen ein Janeway-Konto (L2) |
| [janeway-meet](https://github.com/Janeway-Technology/janeway-meet) | Meet: Video-Konferenzen auf LiveKit mit Gast-Links (L4) |
| [janeway-messaging-core](https://github.com/Janeway-Technology/janeway-messaging-core) | Matrix-Unterbau des Messengers: Homeserver und WhatsApp-/Telegram-Brücken |
| [janeway-messenger](https://github.com/Janeway-Technology/janeway-messenger) | Messenger: Matrix-Client mit WhatsApp- und Telegram-Brücken (L4) |
| [janeway-motion-editor](https://github.com/Janeway-Technology/janeway-motion-editor) | Janeway-Fork von EffectCraft — Motion-Compositor hinter motion.janewaylabs.com |
| [janeway-native](https://github.com/Janeway-Technology/janeway-native) | Kotlin-WebView-Hülle, aus der je Suite-App eine Android-APK entsteht |
| [janeway-notes](https://github.com/Janeway-Technology/janeway-notes) | Notes: Markdown-Notizen mit Wiki-Links, Graph und Canvas (L4) |
| [janeway-pass](https://github.com/Janeway-Technology/janeway-pass) | Pass: Passwortmanager der Janeway Suite (L4) |
| [janeway-pass-extension](https://github.com/Janeway-Technology/janeway-pass-extension) | Pass im Browser: Passwort-Manager-Erweiterung für Chrome und Edge (Manifest V3) |
| [janeway-pdf-editor](https://github.com/Janeway-Technology/janeway-pdf-editor) | Janeway-Fork von PdfCraft — PDF-Editor hinter pdf.janewaylabs.com |
| [janeway-photo-editor](https://github.com/Janeway-Technology/janeway-photo-editor) | Janeway-Fork von PhotoCraft — Bildbearbeitung mit Ebenen und PSD |
| [janeway-protocol](https://github.com/Janeway-Technology/janeway-protocol) | jw-device/1: Geräteprotokoll, Fähigkeitskatalog, Konformitätsszenarien (kein Laufzeitcode) |
| [janeway-sandbox](https://github.com/Janeway-Technology/janeway-sandbox) | Käfig für fremden Code: Python (Pyodide) und JavaScript (Deno) (L2) |
| [janeway-sdk](https://github.com/Janeway-Technology/janeway-sdk) | janeway-service-sdk: Python-Bibliothek für die Python-Dienste der Suite (L2) |
| [janeway-search](https://github.com/Janeway-Technology/janeway-search) | Search: eigene Websuche auf SearXNG, optional mit KI-Antwort und Zitaten (L4) |
| [janeway-sound-editor](https://github.com/Janeway-Technology/janeway-sound-editor) | Janeway-Fork von SoundCraft — Audio-Workstation hinter sound.janewaylabs.com |
| [janeway-status](https://github.com/Janeway-Technology/janeway-status) | Öffentliche Status-Seite: Health aller Dienste der Suite (L4) |
| [janeway-suite](https://github.com/Janeway-Technology/janeway-suite) | Janeway Suite — Wurzel: Doku, Dev-Werkzeug, Graphify-Karten (Apps in eigenen Repos) |
| [janeway-supabase-mcp](https://github.com/Janeway-Technology/janeway-supabase-mcp) | Konnektor-Adapter für selbst gehostete Supabase (L2) |
| [janeway-sync](https://github.com/Janeway-Technology/janeway-sync) | Sync von Kalender, Kontakten und Aufgaben mit Microsoft Graph und Google (L4) |
| [janeway-tasks](https://github.com/Janeway-Technology/janeway-tasks) | Tasks: Aufgaben mit Listen, Tags, Prioritäten und Kalender-Ansicht (L4) |
| [janeway-tickets](https://github.com/Janeway-Technology/janeway-tickets) | Tickets: Kundenportal und Verwaltung für Anfragen, Fehler und Wünsche, mandantenfähig (L4) |
| [janeway-translate](https://github.com/Janeway-Technology/janeway-translate) | Translate: Übersetzung mit LLM, Glossaren, Verlauf und Dokumenten (L4) |
| [janeway-vector-editor](https://github.com/Janeway-Technology/janeway-vector-editor) | Janeway-Fork von VectorCraft — Vektor-Editor hinter vector.janewaylabs.com |
| [janeway-video-editor](https://github.com/Janeway-Technology/janeway-video-editor) | Janeway-Fork von FilmCraft — Video-Schnitt hinter video.janewaylabs.com |
| [janeway-weather](https://github.com/Janeway-Technology/janeway-weather) | Weather: amtliches DWD-Wetter für jeden deutschen Ort, API- und CLI-first (L4) |
| [janeway-website](https://github.com/Janeway-Technology/janeway-website) | Marketing-Website der Janeway Suite (janeway.io) mit Tarifen und Rechtstexten |
| [janeway-workflow-engine](https://github.com/Janeway-Technology/janeway-workflow-engine) | Graph-Orchestrierung: DAG, Trigger (Cron/HTTP/Event/Voice), Retry (L3) |

</details>

### Janeway Linux

Desktop-Betriebssystem „Linux made in Germany“ (Jaynix) ([Sammelrepo](https://github.com/Janeway-Technology/janeway-linux)).

| Repo | Worum es geht |
|---|---|
| [janeway-linux](https://github.com/Janeway-Technology/janeway-linux) | Sammelrepo Janeway Linux / Jaynix: Repo-Liste, jl, Bootstrap, Fremdquellen, Paketlisten |
| [janeway-linux-artwork](https://github.com/Janeway-Technology/janeway-linux-artwork) | Icon- und Cursor-Sets, Hintergründe und Schriften der Jaynix-Designs (privat) |
| [janeway-linux-desktop](https://github.com/Janeway-Technology/janeway-linux-desktop) | Jaynix Settings, Jaynix Shell, Sitzung, eigene Themes und Design-Vorlagen, Test-Shell |
| [janeway-linux-dotfiles](https://github.com/Janeway-Technology/janeway-linux-dotfiles) | Konfiguration des Jaynix-Entwicklungsrechners und Notizen |
| [janeway-linux-installer](https://github.com/Janeway-Technology/janeway-linux-installer) | Janeway Linux: Installer, Live-ISO, jaynix-Befehl, Boot-Branding |

### Eigenständige Produkte

Laufen ohne die Suite: Hosting, CMS mit Buchungsmodul, Warenwirtschaft und Shop.

| Repo | Worum es geht |
|---|---|
| [dirs21](https://github.com/Janeway-Technology/dirs21) | DIRS21-Channelmanager-Connector für Buchungssysteme |
| [janeway-bookings](https://github.com/Janeway-Technology/janeway-bookings) | Channelmanager-Buchungsmodul für @janeway/cms (v1: Webplanner) |
| [janeway-cms](https://github.com/Janeway-Technology/janeway-cms) | Janeway CMS — modulare, brandbare CMS-Engine + gebrandete Admin-GUI (Payload/WordPress-Alternative). Ein Docker-Image, pro Marke Config. |
| [janeway-commerce](https://github.com/Janeway-Technology/janeway-commerce) | Janeway Commerce: Warenwirtschaft und Shop (WWS) |
| [janeway-hosting](https://github.com/Janeway-Technology/janeway-hosting) | Frontend der Managed-VPS-Plattform: Konfigurator, Server, SSH-Keys (L4) |
| [janeway-hosting-engine](https://github.com/Janeway-Technology/janeway-hosting-engine) | Control-Plane der Managed-VPS-Plattform: Bestellungen, Server beim Provider, Reconciler |

## Sonstige

| Repo | Worum es geht |
|---|---|
| [handy-spiegel](https://github.com/Janeway-Technology/handy-spiegel) | Android-Handy auf PC oder Fernseher spiegeln – mit wenig Verzögerung, Controller und ohne Kabel. GTK4-Oberfläche für scrcpy als AppImage. *(öffentlich)* |
| [janeway-dictate](https://github.com/Janeway-Technology/janeway-dictate) | Push-to-Talk Speech-to-Text for GNOME/Linux using faster-whisper *(archiviert, öffentlich)* |
| [matrix-e2ee-bot](https://github.com/Janeway-Technology/matrix-e2ee-bot) | Self-hosted Matrix bot microservice with E2EE and REST API *(öffentlich)* |
| [telegram-signal-analyse](https://github.com/Janeway-Technology/telegram-signal-analyse) | Telegram-Signalanalyse: liest Signalgruppen, erkennt Handelssignale und prüft sie |

## Websites

Unsere eigenen Websites und die Kundenseiten; nach Kunden geordnet: [kundenprojekte](https://github.com/Janeway-Technology/kundenprojekte).

| Repo | Worum es geht |
|---|---|
| [alomedia-website](https://github.com/Janeway-Technology/alomedia-website) | Website Alomedia — Kundenprojekt von Janeway Technology |
| [baulogistik-lueck-website](https://github.com/Janeway-Technology/baulogistik-lueck-website) | Website Baulogistik Norbert Lück — Kundenprojekt von Janeway Technology |
| [brautkleider-liana-website](https://github.com/Janeway-Technology/brautkleider-liana-website) | Website Brautkleider Liana — Next.js, Kundenprojekt von Janeway Technology |
| [db-farbdesign-website](https://github.com/Janeway-Technology/db-farbdesign-website) | Website DB Farbdesign — Kundenprojekt von Janeway Technology |
| [finance-optimizer-website](https://github.com/Janeway-Technology/finance-optimizer-website) | Finance Optimizer — Tarifvergleich Website (Strom, Gas, Internet) |
| [flossverleih-treibgut-buchungssystem](https://github.com/Janeway-Technology/flossverleih-treibgut-buchungssystem) | Buchungssystem für den Floßverleih TreibGuT — Next.js |
| [flossverleih-treibgut-website](https://github.com/Janeway-Technology/flossverleih-treibgut-website) | Website Floßverleih TreibGuT — Next.js, Inhalte aus dem Janeway Cloud-CMS |
| [golf-in-wall-website](https://github.com/Janeway-Technology/golf-in-wall-website) | Website Golf in Wall — Next.js, Kundenprojekt von Janeway Technology |
| [gut-hesterberg-website](https://github.com/Janeway-Technology/gut-hesterberg-website) | Website Gut Hesterberg — Next.js, Kundenprojekt von Janeway Technology |
| [hotel-altes-kasino-website](https://github.com/Janeway-Technology/hotel-altes-kasino-website) | Website Hotel Altes Kasino — Kundenprojekt von Janeway Technology |
| [iq-waermetechnik-website](https://github.com/Janeway-Technology/iq-waermetechnik-website) | Website IQ Wärmetechnik GmbH, Neuruppin — Next.js 16 |
| [janeway-technology-website](https://github.com/Janeway-Technology/janeway-technology-website) | Firmen-Website von Janeway Technology (janeway-technology.com) |
| [kaatzsch-website](https://github.com/Janeway-Technology/kaatzsch-website) | Website Kaatzsch — Kundenprojekt von Janeway Technology |
| [lpritzkow-website](https://github.com/Janeway-Technology/lpritzkow-website) | Personal branding website lpritzkow.de — Next.js 16, React 19, Tailwind v4, Docker |
| [notar-bensch-website](https://github.com/Janeway-Technology/notar-bensch-website) | Website Notar Bensch — Next.js, Kundenprojekt von Janeway Technology |
| [odd-fellows-website](https://github.com/Janeway-Technology/odd-fellows-website) | Website Odd Fellows — Kundenprojekt von Janeway Technology |
| [pospiech-immobilien-website](https://github.com/Janeway-Technology/pospiech-immobilien-website) | Website Pospiech Immobilien — Kundenprojekt von Janeway Technology |
| [prima-campus-website](https://github.com/Janeway-Technology/prima-campus-website) | Website Prima Campus (Prima Gruppe) — Next.js 16 mit Block-CMS |
| [prima-gruppe-website](https://github.com/Janeway-Technology/prima-gruppe-website) | Prima Gruppe – Unternehmens-Website (Next.js 16, Docker) |
| [prima-inn-website](https://github.com/Janeway-Technology/prima-inn-website) | Website Prima Inn, Neuruppin (Prima Gruppe) — Next.js |
| [prima-resorts-website](https://github.com/Janeway-Technology/prima-resorts-website) | Website Prima Resorts (Prima Gruppe) — Camping und Tiny Houses an der Ostsee |
| [prima-tiny-website](https://github.com/Janeway-Technology/prima-tiny-website) | Website Prima Tiny (Prima Gruppe) — Next.js |
| [prima-ui](https://github.com/Janeway-Technology/prima-ui) | @prima/ui — Design-System der vier Prima-Marken: Tokens und Komponenten |
| [primus-fs-website](https://github.com/Janeway-Technology/primus-fs-website) | Website Primus FS — Kundenprojekt von Janeway Technology |
| [rhinpassage-website](https://github.com/Janeway-Technology/rhinpassage-website) | Website RhinPassage (Pospiech Gruppe) — Next.js |
| [rhinquartier-website](https://github.com/Janeway-Technology/rhinquartier-website) | RhinQuartier Website — Next.js 16 App Router, mehrsprachig (de/en/ru), Docker-Production |
| [rundum-ruppin](https://github.com/lpritzkow21/rundum-ruppin) | Monorepo der Unternehmensgruppe Rundum Ruppin — je Bereich eine Next.js-App |
| [ruppiner-ingenieur-gesellschaft-website](https://github.com/Janeway-Technology/ruppiner-ingenieur-gesellschaft-website) | Website Ruppiner Ingenieurgesellschaft mbH — Kundenprojekt von Janeway Technology |
| [sag-protection-website](https://github.com/Janeway-Technology/sag-protection-website) | Website SAG Protection — Kundenprojekt von Janeway Technology |
| [unibau-website](https://github.com/Janeway-Technology/unibau-website) | Website Unibau — Kundenprojekt von Janeway Technology |
| [wbg-website](https://github.com/Janeway-Technology/wbg-website) | Website WBG — Next.js, Kundenprojekt von Janeway Technology |
<!-- org-listen:ende -->

---

<p align="center"><sub>Janeway Technology · Neuruppin, Brandenburg</sub></p>
