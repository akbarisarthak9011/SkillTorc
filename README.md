# SkillTroc Colombia

**Aprende una habilidad. Comparte una habilidad. Crezcamos juntos.**
*Learn a skill. Share a skill. Grow together.*

SkillTroc is a peer-to-peer skill exchange platform for Colombia, starting in Medellín. People teach something they know and learn something they want from someone else, with no money changing hands. An optional Learner Plan (COP 18,000/month or COP 107,000/year) lets people learn without teaching back.

## This repository: public demo

`index.html` is a single-file web app. It runs entirely in the browser:

- Each visitor's data is saved only in their own browser (localStorage).
- Six profiles marked **(demo)** are example data so matching works right away.
- Demo buttons simulate the other person accepting, replying and confirming sessions.
- **Reiniciar** clears the demo.
- Payments are simulated; no real charges are made.

## Features

- Spanish (es-CO) by default, English toggle; COP prices; America/Bogota time
- Two streams: career & digital skills, and creative & everyday skills
- 5-step onboarding, profiles, skill listings
- Discover (match cards with reasons), search with filters
- Requests, chat, session scheduling, completion and reviews
- Learner Plan checkout (demo), block/report, complaints (PQR), data export and account deletion
- Community events, referral codes, institutional coordinators, admin metrics
- Draft legal pages (Ley 1581 de 2012, Ley 1480 de 2011), pending legal review
- External case study: Rafael Meza and SENATIC, linked to the original ILO article

## Deploy on Vercel

1. Import this repository at vercel.com/new.
2. Framework preset: **Other**. No build command, no output directory.
3. Deploy.

## Before a real launch

This demo has no shared database or real accounts. A production version needs a backend (e.g. Supabase) with authentication and row-level security, a Colombian payment gateway (e.g. Wompi or ePayco) with server-side verification, email/push notifications, and legal review of the policies, including registering the database with the SIC (RNBD).
