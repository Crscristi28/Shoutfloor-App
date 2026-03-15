[🇬🇧 English](README.md) | 🇨🇿 Česky

# Shoutfloor

Mobilní komunikační platforma pro firmy s provozními zaměstnanci. Jedna aplikace pro novinky, zlepšováky, bezpečnost, ankety, chat — všechno, co dřív bylo na papíře nebo nástěnce.

Postavený s AI tam, kde to opravdu pomáhá — oprava textu, překlad mezi jazyky, analýza zpětné vazby zaměstnanců — ne jen další chatbot.

## Problém

Firemní komunikace nefunguje. Důležité informace se k lidem dostanou se zpožděním. Zlepšovací návrhy leží na papírových formulářích. Hlášení bezpečnosti se ztratí. Předávání směn probíhá ústně. Vícejazyčné týmy se nemůžou zapojit, protože všechno je v jednom jazyce.

## Jak to Shoutfloor řeší

- Jeden feed pro celou firmu — novinky a oznámení dorazí ke všem okamžitě
- AI tam, kde to dává smysl — oprava textu, překlad, anonymní pulse reporty — reálná produktivita, ne zbytečnosti
- Digitální zlepšovací návrhy se schvalovacím workflow — žádné papírové formuláře
- Hlášení bezpečnosti a závad s fotkami — okamžité, sledovatelné, zodpovědné
- 20 jazyků nativně — každý se zapojí ve svém jazyce
- Modulární — každá firma si zapne jen to, co potřebuje
- Funguje offline, synchronizuje se po připojení
- Multi-tenant SaaS — jeden kód, izolovaná data pro každou firmu

## Funkce

**Základ**

- Feed s lajky, vláknovými komentáři a záložkami
- AI oprava textu a překlad (20 jazyků)
- Ankety a průzkumy s výsledky v reálném čase
- Kalendář s žádostmi o volno
- Push notifikace cílené podle oddělení, týmu, směny nebo role
- Tmavý režim, podpora RTL (arabština)

**Moduly (zapínají se per firma)**

- Zlepšovací návrhy se schvalovacím workflow
- Hlášení bezpečnosti a skoronehod — dvoustupňové schvalování
- Whistleblower / anonymní schránka — architektonicky garantovaná anonymita
- Chat — 1:1 a skupinové zprávy s E2E šifrováním
- Jídelníček (zobrazení nebo objednávky)
- Správa směn a výměny směn
- Předávání směn
- Digitální checklisty a inspekce
- Systém nouzového vysílání
- AI Pulse Bot — měsíční anonymní check-in zaměstnanců s agregovanými reporty
- Hlášení závad s focením
- Katalog benefitů
- Digitální výplatní pásky
- Osobní notifikace (HR → zaměstnanec)

## Architektura

- **Mobilní aplikace** (PWA) — pro všechny zaměstnance
- **Admin dashboard** — desktop-first pro HR a management
- **Marketingový web** — landing page, ceník, onboarding
- **Multi-tenant** — Firebase Auth s Identity Platform, izolovaná data per firma
- **Self-service onboarding** — firma se zaregistruje, nakonfiguruje, přidá zaměstnance, hotovo

## Role

| Role | Popis |
|------|-------|
| Zaměstnanec | Čtení feedu, podávání zlepšováků a hlášení bezpečnosti, hlasování, žádosti o volno |
| Vedoucí týmu | Publikace novinek, správa týmu, schvalování/zamítání žádostí |
| HR | Správa zaměstnanců, osobní notifikace, GDPR |
| Kvalita | Řízení kvality napříč odděleními |
| Bezpečnost | Správa hlášení bezpečnosti a incidentů |
| Admin | Plný přístup, analytika, konfigurace firmy, správa modulů |

## Cílový trh

Jakákoliv firma s provozními zaměstnanci, která potřebuje lepší interní komunikaci:

🏭 Výroba · 📦 Sklady · 🏗️ Stavebnictví · 🏨 Hotely · 🏥 Nemocnice · 🛒 Retail · 🧹 Facility management · 🌾 Zemědělství

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,firebase&theme=dark&perline=5" />
</p>

Next.js · React · TypeScript · Tailwind CSS · Firebase · Claude AI (Anthropic) · PWA

## Aktuální stav

🚧 **V aktivním vývoji — první beta plánovaná za ~2-3 měsíce**

**Hotovo:**
- Kompletní frontend UI — všechny stránky, navigace, animace
- 20 jazyků implementováno
- AI oprava textu a překlad integrován
- Tmavý režim
- PWA nakonfigurováno

**V řešení:**
- Firebase backend (Auth, Firestore, Cloud Functions)
- Real-time data a push notifikace
- Admin dashboard

## Autor

**Cristian Bucioaca** — [cristianb.cz](https://cristianb.cz)
