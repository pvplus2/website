# TALENTHIRSCH_IMPORT_CHECKLIST

## Phase 0 — Voraussetzungen
- [ ] WordPress-Zugang vorhanden (Admin)
- [ ] Kadence Theme installiert
- [ ] Yoast SEO installiert
- [ ] Cache-Plugin gemäß Hosting gewählt
- [ ] Cloudflare SSL/Cache-Regeln abgestimmt

## Phase 1 — Basis-Konfiguration
- [ ] Permalinks auf „Beitragsname“
- [ ] Seitenstruktur exakt laut URL-Plan erstellt
- [ ] Blog-Posts mit den 10 Slugs angelegt
- [ ] Hauptnavigation + Footer aufgebaut

## Phase 2 — Inhalte importieren
- [ ] Seiteninhalte aus `TALENTHIRSCH_PAGE_CONTENT.md` übertragen
- [ ] Preisseite mit exakter Tabelle umgesetzt
- [ ] Kontaktseite mit Telefon/E-Mail/Adresse/Formular/Datenschutzhinweis
- [ ] Calendly nur einfügen, wenn exakte URL vorliegt

## Phase 3 — SEO + Schema
- [ ] SEO-Title/Meta/Fokuskeyword je URL aus `TALENTHIRSCH_SEO_MAP.csv` gesetzt
- [ ] Organization/ProfessionalService/EmploymentAgency/WebSite aktiv
- [ ] FAQPage auf `/faq/`
- [ ] Article-Schema für alle Blogposts
- [ ] Breadcrumbs aktiviert

## Phase 4 — Bildintegration (Blocker bis Upload)
- [ ] Verbindliche Bilder in zulässigen Ordner hochgeladen
- [ ] Exakte Dateinamen dokumentiert
- [ ] Sections zugewiesen (kein Fremdmaterial)
- [ ] Alt-Texte gesetzt

## Phase 5 — QA/Launch
- [ ] Interne Links geprüft (keine 404)
- [ ] Mobile Darstellung geprüft
- [ ] Ladezeit-Basis geprüft
- [ ] robots.txt / sitemap.xml validiert
- [ ] Search Console + GA4 + GBP als TODO/umgesetzt dokumentiert

## Offene Blocker (aktuell)
- Bildassets fehlen im Repo
- Kein Live-WP-Adminzugang in dieser Umgebung
- Keine exakte Calendly-URL
