🇬🇧 English | [🇨🇿 Česky](README.cs.md)

# Shoutfloor

Mobile communication platform for companies with frontline workers. One app for news, improvements, safety, polls, chat — everything that used to be on paper or bulletin boards.

Built with AI where it actually helps — correcting text, translating across languages, analyzing employee feedback — not just another chatbot.

## The Problem

Company communication is broken. Important info takes days to reach people. Improvement suggestions sit on paper forms. Safety reports get lost. Shift handovers happen verbally. Multilingual teams can't participate because everything is in one language.

## How Shoutfloor Solves It

- One feed for the entire company — news, updates, and announcements reach everyone instantly
- AI where it matters — text correction, translation, anonymous employee pulse reports — real productivity, not gimmicks
- Digital improvement suggestions (Kaizen) with approval workflows — no more paper forms
- Safety and fault reporting with photos — instant, traceable, accountable
- 20 languages natively — everyone participates in their own language
- Modular — each company enables only the features they need
- Works offline, syncs when connected
- Multi-tenant SaaS — one codebase, isolated data per company

## Features

**Core**

- News feed with likes, threaded comments, bookmarks
- AI text correction & translation (20 languages)
- Polls & surveys with real-time results
- Calendar with leave requests
- Push notifications targeted by department, line, shift, or role
- Dark mode, RTL support (Arabic)

**Modules (enable per tenant)**

- Improvement suggestions (Kaizen) with approval workflow
- Safety & near-miss reporting — two-tier approval
- Whistleblower / anonymous box — architecturally guaranteed anonymity
- Chat — 1:1 and group messaging with E2E encryption
- Canteen menu (display or ordering)
- Shift management & shift swaps
- Shift handover reports
- Digital checklists & inspections
- Emergency broadcast system
- AI Pulse Bot — monthly anonymous employee check-ins with aggregated reports
- Fault reporting with photo capture
- Benefits catalog
- Digital payslips
- Personal notifications (HR → employee)

## Architecture

- **Mobile app** (PWA) — for all employees
- **Admin dashboard** — desktop-first for HR and management
- **Marketing site** — landing page, pricing, onboarding
- **Multi-tenant** — Firebase Auth with Identity Platform, isolated user pools per company
- **Self-service onboarding** — company registers, configures, adds employees, done

## Roles

| Role | Description |
|------|-------------|
| Operator | Read feed, submit improvements & safety reports, vote, request leave |
| Supervisor | Post news, manage team, approve/reject requests |
| HR | Employee management, personal notifications, GDPR |
| Quality | Quality complaints across all lines |
| Safety | Manage safety reports and incidents |
| Admin | Full access, analytics, tenant configuration, module management |

## Target Market

Any company with frontline workers who need better internal communication:

🏭 Factories · 📦 Warehouses · 🏗️ Construction · 🏨 Hotels · 🏥 Hospitals · 🛒 Retail · 🧹 Cleaning · 🌾 Agriculture

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,firebase&theme=dark&perline=5" />
</p>

Next.js · React · TypeScript · Tailwind CSS · Firebase · Claude AI (Anthropic) · PWA

## Status

🚧 In active development

## Author

**Cristian Bucioaca** — [cristianb.cz](https://cristianb.cz)
