# INFINITY Telegram Mini App — starter

A responsive React + Vite frontend for the INFINITY verification service.

## Run locally
1. Install Node.js (LTS).
2. In this folder run `npm install`
3. Run `npm run dev`

## Deploy to Cloudflare Pages
- Framework preset: **Vite**
- Build command: `npm run build`
- Build output directory: `dist`
- Root directory: `/`

## Current scope
This is the frontend starter: navigation, language toggle, theme toggle, plan cards, application form, status and profile views.
It is **not yet connected** to Telegram authentication, Supabase API, ownership checks, or Telegram Stars payments. Do not accept real payments or claim verification from this prototype.

Next integration steps:
1. Validate Telegram `initData` in a Supabase Edge Function.
2. Add server-side application and ownership checks.
3. Implement Telegram Stars invoices and payment callbacks.
4. Add a protected admin review workflow.
5. Set the Telegram bot menu button to open the deployed Mini App URL.
