# Hi, I'm Daniel Aboderin 👋

**Senior Frontend & Mobile Engineer** · React · Next.js · React Native · TypeScript
📍 Lagos, Nigeria · 🌍 Open to remote (contract, full-time, relocation)

I build polished, high-end web and mobile products, backed by serious engineering: payments, role-based access, real-time state, and data integrity. My work spans fintech, e-commerce, civic-tech, edtech, and health-tech, mostly for the Nigerian market, with live payment rails (Paystack, Flutterwave, Stripe, MTN MoMo, NOWPayments) and real users.

---

## What I do well

- **Design quality:** a keen eye for high-end, polished interfaces: custom Tailwind v4 token systems, dark mode, WCAG-minded accessibility, and motion with Framer Motion / GSAP. I've shipped Figma designs pixel-accurately across public sites and multi-role dashboards
- **Frontend architecture:** Next.js App Router (RSC, Server Actions, ISR/SSG), React 19, TanStack Query, Zustand, design systems on Tailwind CSS v4
- **Mobile:** React Native / Expo (expo-router, NativeWind, secure session storage, biometric auth, push notifications)
- **Payments & security:** HMAC-verified webhooks, idempotency keys, server-side price recalculation, Row-Level Security, multi-layer RBAC
- **Real-time & performance:** Supabase Realtime, Firebase, Web Push (VAPID), PWAs, caching and rate limiting (Upstash Redis)
- **Quality:** Vitest + Testing Library, Playwright, CI/CD on Vercel, accessibility-minded UI

---

## Selected work

| Project | What it is | Highlights |
|---|---|---|
| **[Carmel Mart](https://carmelmart.store)** | Multi-vendor marketplace with five role-based portals | 110 API route handlers · Flutterwave + Paystack · QoreID KYC · Fast Link delivery + Mapbox · tier-gated digital goods · 29 Vitest files |
| **Mannaly** | Cashless campus food-ordering & vendor settlement platform | Multi-tenant · wallet via transactional Postgres RPCs · Monnify/OPay payouts · HMAC-verified idempotent webhooks · realtime order tracking |
| **Bookhushly** | Hospitality & services booking platform (hotels, events, logistics, security) | Unified Paystack + crypto payment layer · wallet · booking-lock conflict prevention · AI support assistant · VAPID push |
| **OEMS** | Multi-tenant computer-based testing platform for universities | Credential-less student auth via server-minted sessions · three-layer authorization with Postgres RLS · ~325 Vitest tests |
| **Atunluto** | Political party management & INEC-style election results platform | Five-tier RBAC enforced at server-action level · PU → LGA → State result collation · SHA-256 checksummed submissions with audit log · signed Cloudinary uploads · offline-capable PWA |
| **TBM** | AI interior-design & renovation platform (client project, frontend) | Three portals with separate httpOnly-cookie auth · AI session state machine (8 states) with polling · runtime pricing + discount engine · idempotency-keyed Paystack checkout · 100+ endpoints wrapped in TanStack Query hooks |
| **[Litway Picks](https://litwaypicks.com)** | Liberian e-commerce on **web + native mobile** (Next.js + Expo) | MTN MoMo checkout · webhook/poll race-safe settlement · biometric login · push notifications |
| **Aiefashion** | Luxury e-commerce, US + Nigeria | Stripe + Paystack under one order state machine · live FX fallback chain · ISR/SSG strategy · full admin ops (refunds, analytics) |
| **Farz Supplements** | Herbal e-commerce built for a 35+ audience | Paystack HMAC-SHA512 webhooks · stock via Postgres RPCs with compensating restore · per-state delivery fees |
| **[OTO for Senate](https://otoforsenate.ng)** | Live campaign site with a schema-driven CMS | Recursive schema form + deep-merge content · RLS with security-definer policy · ~63 test files |
| **Ears For You** | AI-companion mental-health platform | Kafka-based crisis detection pipeline · AI kill switch + telemetry · resilient token refresh |
| **PCU Digital Suite** | Course catalogue CMS, certificate verification, exam timetable builder | Hand-written PHP/MySQL API · built for shared cPanel hosting · 50-test timetable suite with .docx export |

Also built: Olanrewaju Okesooto campaign platform (donations + field results portal), Think – Winners Movement (hierarchical membership platform), Ebunly (three-portal gifting marketplace), Casanova (real-time social platform).

---

## Tech stack

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat&logo=expo&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwindcss&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat&logo=reactquery&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433E38?style=flat)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat&logo=framer&logoColor=white)

![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=flat&logo=node.js&logoColor=white)
![Redis](https://img.shields.io/badge/Upstash_Redis-DC382D?style=flat&logo=redis&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)

![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=flat&logo=git&logoColor=white)

**Payments & integrations:** Paystack · Flutterwave · Stripe · MTN MoMo · NOWPayments · Monnify · Twilio · Resend · Cloudinary

---

## Currently

- Building for remote teams as a senior frontend / mobile engineer
- Going deeper on performance, accessibility, and testing in production React apps

---

## Let's talk

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aboderindaniel482@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-HANDLE)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/Dnlcodess)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/Dnlcodes.js)

![GitHub stats](https://github-readme-stats.vercel.app/api?username=DNLCodess&show_icons=true&theme=dark&hide_border=true&count_private=true)
