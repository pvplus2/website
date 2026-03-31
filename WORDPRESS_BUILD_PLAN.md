# WORDPRESS_BUILD_PLAN — Talenthirsch Relaunch (Kadence + Gutenberg)

## 1) Ziel und Rahmen
Dieser Handoff ersetzt **keine** Live-WordPress-Implementierung. Er ist die umsetzungsreife Übergabe für eine WordPress-Installation mit:
- Theme: Kadence
- Editor: Gutenberg (+ Kadence Blocks optional)
- SEO: Yoast SEO
- Caching: LiteSpeed Cache (wenn LiteSpeed), sonst WP Fastest Cache
- Stack-Ziel: schlank, schnell, dark mode, conversion-orientiert

## 2) Verbindliche Marken- und Kontaktdaten
- Marke: Talenthirsch
- Domain: talenthirsch.de
- Gründer/Geschäftsführung: Sercan Erisoglu
- Telefon: 07135 7179310
- E-Mail: info@talenthirsch.de
- Adresse: Manfred-Weinmann-Ring 6, 74072 Heilbronn
- Schwesterunternehmen: PersonalvermittlungPlus
- Weitere Marke: Education by PVPLUS

## 3) Verbindliche URL-Struktur
1. /
2. /leistungen/
3. /branchen/handwerk/
4. /branchen/pflege/
5. /branchen/gastronomie/
6. /branchen/it/
7. /branchen/logistik/
8. /branchen/industrie/
9. /preise/
10. /ueber-uns/
11. /blog/
12. /kontakt/
13. /faq/
14. /standorte/heilbronn/
15. /standorte/stuttgart/
16. /standorte/mannheim/
17. /blog/social-media-recruiting-kosten/
18. /blog/handwerker-ueber-instagram-finden/
19. /blog/pflegekraefte-ueber-facebook-gewinnen/
20. /blog/social-recruiting-vs-headhunter/
21. /blog/performance-recruiting-erklaert/
22. /blog/stellenanzeige-vs-social-ads/
23. /blog/social-media-recruiting-kleine-unternehmen/
24. /blog/tiktok-recruiting/
25. /blog/recruiting-funnel-aufbauen/
26. /blog/warum-stellenportale-nicht-mehr-funktionieren/

## 4) Design-System (Kadence Global Settings)
- Stilrichtung: Dark, modern, digital, selbstbewusst
- Hintergrund: #090D14
- Flächen/Karten: #0B1220 / #111827
- Text hell: #F8FAFC
- Primary CTA: #6EE7B7
- Secondary Accent: #60A5FA
- Border: #1F2937 / #334155
- Typografie:
  - Headline: Inter/Manrope (klar, druckvoll)
  - Body: Inter/System Sans
- Komponenten: Hero, Kennzahlen-/Badge-Module, FAQ-Accordion, Pricing-Tabelle, CTA-Bars

## 5) Inhaltsmodule je Seitentyp
- Startseite: Hero, Branchen, Prozess, Warum Talenthirsch, Preise, FAQ-Auszug, Cross-Brand-Hinweise
- Leistungen: Plattformen, Funnel, Zielgruppenansprache, Bewerbungsprozess, Reporting, CTA
- Branchen: Problem, Grenzen klassischer Anzeigen, Talenthirsch-Ansatz, Rollenbeispiele, 4 Schritte, FAQ, CTA
- Preise: exakte Pakettabelle + Zusatzkosten + Preisstand
- Kontakt: Telefon, E-Mail, Adresse, Formular, Datenschutzhinweis, Calendly-TODO (kein Fake-Link)
- FAQ: echte Fragen + FAQPage-Schema
- Standorte: lokal sinnvoll, keine Doorway-Texte
- Blog: 10 Artikelstrukturen vorhanden; vor Go-Live final redaktionell erweitern

## 6) Umsetzungsschritte in WordPress
1. Frische WP-Instanz bereitstellen, Permalinks auf „Beitragsname“.
2. Kadence Theme + Child Theme aktivieren.
3. Yoast SEO installieren und konfigurieren.
4. Caching-Plugin je Servertyp setzen.
5. Seitenstruktur exakt nach URL-Plan anlegen.
6. Inhalte aus `TALENTHIRSCH_PAGE_CONTENT.md` einpflegen.
7. SEO-Metadaten aus `TALENTHIRSCH_SEO_MAP.csv` in Yoast übernehmen.
8. Schema aus `TALENTHIRSCH_SCHEMA_JSONLD.md` einbinden (Yoast + Custom JSON-LD wo nötig).
9. Navigation/Footer gem. `TALENTHIRSCH_NAVIGATION.md` aufbauen.
10. Bilder erst nach Upload gem. `TALENTHIRSCH_IMAGE_REQUIREMENTS.md` integrieren.
11. QA: interne Links, mobile Darstellung, Core Web Vitals Basis, Schema-Validierung.

## 7) Nicht erledigt (bewusst)
- Kein Live-WP-Adminzugriff umgesetzt.
- Keine Kadence-Konfiguration auf produktiver Instanz ausgeführt.
- Keine Bildintegration ohne bereitgestellte, verbindliche Assets.
