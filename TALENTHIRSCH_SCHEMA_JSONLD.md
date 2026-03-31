# TALENTHIRSCH_SCHEMA_JSONLD

## 1) Global (sitewide)

### Organization + ProfessionalService + EmploymentAgency + WebSite
```json
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "Organization",
      "name": "Talenthirsch",
      "url": "https://talenthirsch.de",
      "email": "info@talenthirsch.de",
      "telephone": "+49-7135-7179310",
      "address": {
        "@type": "PostalAddress",
        "streetAddress": "Manfred-Weinmann-Ring 6",
        "postalCode": "74072",
        "addressLocality": "Heilbronn",
        "addressCountry": "DE"
      }
    },
    {
      "@type": "ProfessionalService",
      "name": "Talenthirsch",
      "areaServed": "Deutschland",
      "telephone": "+49-7135-7179310"
    },
    {
      "@type": "EmploymentAgency",
      "name": "Talenthirsch",
      "areaServed": "Deutschland"
    },
    {
      "@type": "WebSite",
      "name": "Talenthirsch",
      "url": "https://talenthirsch.de"
    }
  ]
}
```

## 2) BreadcrumbList (je Unterseite)
- Für jede Seite/Unterseite automatisch aus URL-Hierarchie erzeugen.

## 3) FAQPage
- Pflicht auf `/faq/`.
- Optional zusätzlich auf Seiten mit echten FAQ-Blöcken (Branchenseiten).

## 4) Article (für Blogposts)
- Für alle 10 Blogartikel je ein `Article`-Schema.
- Keine erfundenen Autorenprofile; Publisher/Author als Organization „Talenthirsch“.

## 5) Hinweis für Yoast + Custom Code
- Yoast für Standard-Schema nutzen.
- Fehlende Typen/Details über Custom JSON-LD (Code Snippets/Theme Hook) ergänzen.
