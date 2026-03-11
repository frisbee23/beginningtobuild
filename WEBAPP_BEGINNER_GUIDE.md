# Webapps bauen als Anfänger: die einfache 90%-Liste

Wenn du schnell produktive Webapps bauen willst, brauchst du **nicht alles**.  
Lerne die folgenden Themen in dieser Reihenfolge — damit deckst du ca. **90 %** der typischen Apps ab.

## 1) Internet-Basics (muss sitzen)
- **HTTP/HTTPS**: Request/Response, `GET/POST/PUT/DELETE`, Statuscodes (`200/401/404/500`)
- **Browser-Basics**: Cookies, CORS, Local Storage
- **JSON** als Datenformat

## 2) Frontend-Basis
- **HTML, CSS, JavaScript** (wirklich verstehen, nicht skippen)
- **TypeScript** (Standard für wartbaren Code)
- **React + Next.js** (opinionated Industriestandard)
- **Tailwind CSS** für schnelles, konsistentes UI

## 3) Backend-Basis
- **Next.js Route Handlers / API Routes** (Fullstack in einem Repo)
- **REST API** als einfacher, robuster Start
- **Input-Validierung** auf dem Server (z. B. mit Zod)

## 4) Datenbank
- **PostgreSQL** als Default-Datenbank
- **Prisma ORM** für Schema + Migrationen
- SQL-Grundlagen: `SELECT`, `JOIN`, Indizes, Constraints

## 5) Login & Sicherheit
- **Auth.js (NextAuth)** für Login-Flows
- Passwort-Hashing (Argon2/Bcrypt)
- Schutz vor **XSS, CSRF, SQL-Injection**
- Rollen/Rechte (RBAC) von Anfang an einfach mitdenken

## 6) Deployment (live gehen)
- **Vercel** für Next.js
- **Managed Postgres** (z. B. Neon/Supabase/RDS)
- Env-Variablen/Secrets sauber verwalten
- Fehlertracking mit **Sentry**

## 7) Qualität ohne Overengineering
- **Git + GitHub + Pull Requests**
- **ESLint + Prettier**
- Ein paar gezielte Tests:
  - Unit-Tests für wichtige Business-Logik
  - 1–2 E2E-Tests für kritische Flows (Login, Checkout, etc.)

---

## Die klare Empfehlung (einfach nehmen)
Wenn du nicht lange vergleichen willst, nimm diesen Stack:

1. **Next.js + React + TypeScript**
2. **PostgreSQL + Prisma**
3. **Auth.js (NextAuth)**
4. **Tailwind CSS**
5. **Vercel + Managed Postgres**
6. **Sentry + ESLint + Prettier**

Damit kannst du die meisten SaaS-, Dashboard- und CRUD-Webapps sauber bauen.

## Was du am Anfang bewusst ignorierst
- Microservices
- Kubernetes
- komplizierte Event-Architekturen
- GraphQL (optional, später)
- Multi-Cloud-Setups

**Regel:** Erst eine funktionierende App shippen, dann Architektur komplexer machen.
