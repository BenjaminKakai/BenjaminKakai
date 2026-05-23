# Benjamin Kakai

**Senior Full-Stack Engineer · Nairobi, Kenya**
Building production systems across web, mobile, and microservices — billing real users, in real currencies, across East and Southern Africa.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/benjamin-kakai-7b599121a)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:benjaminkakaimasai@gmail.com)

---

## What I do

I take products from `git init` to a live URL with real users — backend, web, mobile, infra, the lot. Most of my recent work sits inside private organisations (Webmasters Kenya, Wasaachat, web-masters-ke), so this profile won't show the code, but every link below is a live system you can hit from a browser today.

---

## Currently shipping

### 🇲🇿 [nepmz.com](https://nepmz.com) — Mozambique National Employment Portal
The Government of Mozambique's official job portal. Operated under the Ministry of Youth and Sports.
- **Stack**: Spring Boot 17 · PostgreSQL · Flyway · JWT/Spring Security · Next.js 14 · Tailwind · Flutter 3.35 · Riverpod
- **Surface area**: 4-app monorepo — `backend/`, `web-client/` (nepmz.com), `web-admin/` (admin.nepmz.com), `flutter/` (iOS + Android)
- **Features**: AI-powered job matching, INEFP officer workbench (counselling/programmes/beneficiaries), labour inspections, TVET courses + certificates, M-Pesa/e-Mola wallet, ministries hierarchy, 10-role RBAC, bilingual pt-MZ/en
- **Deploy**: GitHub Actions → GHCR → Helm → ArgoCD → Kubernetes

### 🏢 BrickShare — Property tokenisation + investment platform
Multi-issuer real-estate platform letting accredited investors buy fractional ownership in vetted properties.
- **Stack**: NestJS · PostgreSQL · Next.js 14 · Tailwind · KYC integration · Stripe + M-Pesa
- **Apps**: Issuer dashboard, investor frontend, admin console

### 🤖 [TestPilot AI](https://testpilot.ai) — AI-driven QA platform
Generates and runs functional tests against arbitrary web apps using LLMs.
- **Stack**: Next.js · NestJS · 6-service ML stack (Python · FastAPI · OpenAI · Anthropic · vector store · job queue)
- **Apps**: backend, admin, frontend, Flutter

### 💊 [AfyaPass](https://afyapass.com) — Healthcare appointments + records SaaS
Patient-facing health platform with appointments, e-prescriptions, and clinic management.
- **Stack**: NestJS · PostgreSQL · Next.js · Flutter · AWS EC2 (us-east-2)

### 💸 [PesaFlow](https://pesaflow.ai) — Government payments gateway
Production gateway powering government service payments across Kenya.

### 🌐 eCitizen Service Command Centre
Support + analytics console for Kenya's eCitizen platform.
- **Stack**: Next.js admin + webclient · NestJS backend · Flutter admin

### 📱 Wasaa Suite — wasaachat, remit, lifestyle, tipping, escrow, payroll
- **wasaa-mobile-app**: Flutter chat client (in production)
- **wasaa-remit**: Cross-border remittance — Stripe, M-Pesa, Thunes, KCB Vooma
- **wasaa-lifestyle**: Service booking marketplace (admin web + client web)
- **wasaa-services**: Tipping, escrow, payroll microservices

### 🌱 SnapHarvest · Msafiri Ventures · ProfitZone · FaithPanda · SkillSasa · PostNet · DMRV · Kins · PartyPass · Shanzz Gaming
Active client products at various stages — from production with daily users to first-mile MVPs.

---

## Tech I reach for

**Backend**: Spring Boot · NestJS · Express · FastAPI · Ruby on Rails
**Frontend**: Next.js · React · TypeScript · Tailwind · Material 3
**Mobile**: Flutter · Riverpod · GoRouter · iOS code-signing · Play upload keys
**Data**: PostgreSQL · Flyway · Prisma · Redis · vector stores
**Infra**: Docker · Kubernetes · Helm · ArgoCD · GitHub Actions · GHCR · AWS · DigitalOcean
**Payments**: M-Pesa Daraja · Stripe · Thunes · KCB Vooma · Safaricom integrations
**AI**: OpenAI · Anthropic Claude · embeddings · RAG pipelines

---

## Engineering principles I work by

- **Ship to production**, then iterate. A live URL beats a perfect plan.
- **Trace bugs to root cause** — never just paper over them with a fallback.
- **Strict separation of concerns** between auth, RBAC, business logic, and data.
- **Type-safe end-to-end** — TypeScript on the wire, JPA + DTOs on the server.
- **Idempotent migrations** + **defensive seed data** so prod restores cleanly.
- **Atomic transactions** on anything that touches money or grants access.

---

## Get in touch

- 📧 [benjaminkakaimasai@gmail.com](mailto:benjaminkakaimasai@gmail.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/benjamin-kakai-7b599121a)
- 🏢 Webmasters Kenya Ltd

If you want a real demo of any of the systems above, reach out — I'll spin you up a test account in the relevant role and walk you through it live.
