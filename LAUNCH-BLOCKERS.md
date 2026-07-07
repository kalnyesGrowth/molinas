# Molinas CVR Rebuild - Launch Status

## REMAINING (non-blocking for deploy)

- [ ] **Email is placeholder** - `hello@molinas.com` in footer. Replace with real email when available.
- [ ] **Domain spelling** - CNAME says `moliascleaningservice.com` (missing the 'n' in Molinas). Verify this is intentional.
- [ ] **Trust strip claims** - "Insured and Bonded", "Background-Checked Team". Confirm these are true. Remove if not.
- [ ] **Reviews are demo** - Labeled "Demo Reviewer". Replace with real Google/Yelp reviews when available.
- [ ] **Lighthouse mobile 90+** - Needs browser verification.
- [ ] **OG image** - No og:image tag for social media sharing. Add a preview image.

## COMPLETED

- [x] Phone number: (786) 201-9945 wired in nav, footer, mobile sticky
- [x] Competitive rates set: Standard $100+$22/bed+$15/bath, Premium $135+$32/bed+$20/bath, Deep $175+$30/bed+$25/bath (12% variance)
- [x] Supabase client created: `67b9ce5b-af66-c7f7-e64c-99ca9e5a3c24`
- [x] Supabase auth user: `molinas@kalnyesgrowth.com` / `IuT8nw3Z`
- [x] Tracker.js uncommented and wired to real client_id
- [x] Lead capture endpoint fixed (Supabase Edge Function, not dead Vercel URL)
- [x] End-to-end lead flow tested and verified (RLS scoped to Molinas only)
- [x] /gary-halbert-mentor copy review + rewrites on all sections
- [x] /qa-site pass: 91/100 CONDITIONAL GO
- [x] Estimator math spot-checked at 3 sizes (1BR/1BA, 3BR/2BA, 5BR/3BA)
- [x] Fix 7: Location anchors (#naples, #orlando) with SEO copy
- [x] Dead CSS/JS cleanup (184 lines removed)
- [x] OG meta tags added (title, description, type, url)
- [x] All 10 spec fixes implemented
- [x] EN/ES translations synced with new copy
