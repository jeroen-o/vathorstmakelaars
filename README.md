# Vathorst Makelaars

Website voor **Vathorst Makelaars** — de zelfstandige makelaarspraktijk van Michel Visser in Vathorst en regio Amersfoort.

🌐 Live op: [www.vathorstmakelaars.nl](https://www.vathorstmakelaars.nl)

## Structuur

```
/
├── index.html          # Single-page website
├── CNAME               # GitHub Pages custom domain config
├── robots.txt          # SEO + GEO (AI-crawlers) toegang
├── sitemap.xml         # Voor Google Search Console
├── README.md           # Dit bestand
└── img/
    ├── logo.png                # Vathorst Wonen Makelaars logo
    ├── michel-afspraak.jpg     # Hero foto
    ├── michel-advies.jpg       # Over Michel foto
    ├── verkocht.jpg            # Verkocht-bord (full-width)
    ├── aankoop.jpg             # Aankoopmakelaar banner (niet meer gebruikt op site)
    ├── waardebepaling-1.jpg    # Waardebepaling banner (niet meer gebruikt op site)
    └── waardebepaling-2.jpg    # Waardebepaling banner alt (niet meer gebruikt op site)
```

## DNS-instellingen

Bij de domeinregistrar (TransIP / Versio / Mijndomein):

**`www.vathorstmakelaars.nl`** — CNAME naar `jeroen-o.github.io`

**`vathorstmakelaars.nl`** — vier A-records naar GitHub Pages:
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

## GitHub Pages

In **Settings → Pages**:
- Source: Deploy from a branch → `main` / `(root)`
- Custom domain: `www.vathorstmakelaars.nl`
- ✅ Enforce HTTPS (zodra DNS propageerd is)
