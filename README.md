# Nandi Gems Customer Finder

A premium black-and-gold lead management starter for Nandi Gems & Jewels.

## Current starter capabilities
- USA-focused lead pipeline for jewellery retailers, boutiques, wholesalers, distributors and private-label brands.
- CVD diamond priority and a target of 100 qualified business leads per month.
- Lead scoring with visible reasons, search, status updates, notes and deduplication by website/email.
- CSV import/export.
- Personalised outreach drafts with explicit human approval; this starter does **not** send email.
- Suppression/opt-out flag on each lead.
- Clearly labelled sample leads; no live prospect discovery is claimed.
- Browser local storage for this starter. Connect Supabase before using it as a shared or production CRM.

## Run locally
1. Install Node.js 20 or newer.
2. In this folder run `npm install`.
3. Run `npm run dev` and open the local URL printed by Vite.
4. Run `npm run build` to verify a production build.

## Publish using GitHub + Vercel
1. Upload the contents of this folder to your private GitHub repository (not the enclosing folder).
2. In Vercel, import `darpanpasad81-cloud/Nandi-gems-customer-finder`.
3. Framework preset: Vite; build command `npm run build`; output directory `dist`.
4. Deploy. No environment variables are needed for this local-storage demo.

## Before production
- Create a Supabase project and apply `supabase/schema.sql`.
- Configure Supabase Auth, row-level security and server-side functions.
- Add credentials as Vercel environment variables; never commit `.env` files.
- Connect a lawful B2B lead provider or import permission-appropriate business contacts. Do not scrape websites or harvest personal email addresses.
- Add a verified sending provider only after compliance review. Keep approval-before-send enabled.
- For US commercial email, implement CAN-SPAM requirements including accurate sender information, non-deceptive subjects, a valid postal address, a clear opt-out and timely suppression.

## Product positioning
Promote CVD diamond jewellery. Natural diamonds belong only in the customised jewellery offer. Nandi Gems sells embellished jewellery (diamonds, pearls and coloured gemstones), not plain gold or plain silver jewellery.
