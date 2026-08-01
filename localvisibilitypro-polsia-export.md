# LocalVisibilityPro — Polsia Data Export
Exported August 1, 2026, ahead of Polsia subscription lapse (Aug 12, 2026).
Business: LocalVisibilityPro — finds local contractors with no website/weak Google presence and sells them a site + Google Business Profile fix at $79/mo.
Live site (Polsia-hosted, will need migrating): https://local-visibility-pro.polsia.app
Your actual production site: thelocalvisibilitypro.com (GitHub-hosted)

---

## 1. Business Snapshot (as of dashboard, updated May 10)
- Visitors: 15
- Revenue: $0.00
- Prospects contacted: 10 (dashboard counter — actual outreach across campaigns is higher, see below)
- Outreach replies: 0
- Target price point: $79/mo
- Cost per lead vs. market: $10 vs. $35–50
- App uptime: 100%
- Day 71 of operation (as of this export)

## 2. Campaign Status (per Polsia's own summary, Day 71)
- **Austin:** 28 leads scraped → 24 verified-ready, 10 flagged zero-web priority (Z1–Z8 + Plumb Masters, which lost its site to a regression)
- **Houston HVAC:** top 5 by review count fired; next 10 queued per roadmap
- **DFW:** 16 verified roofer/HVAC leads — was stuck 5 cycles on a "tone gut-check," now reportedly unblocked
- **Columbia, SC:** 7 verified contacts in a 10-day auto-follow-up sequence

⚠️ **Discrepancy flagged by Polsia's own agent during this export:** the Houston HVAC and DFW outreach tasks are internally marked "rejected"/"cancelled" in the task tracker, which contradicts the cheerful daily-report language claiming those waves had "fired." Worth verifying directly (e.g., checking Sent folder dates, or calling a couple of DFW/Houston contacts) before assuming that outreach actually went out.

## 3. Day 71 CEO Report (most recent, full text)

**What Shipped**
Day 71: SEO meta tags + LocalBusiness JSON-LD landed on `/sites/[slug]` — last of three sites-pipeline enhancements. Pipeline is closed.
- Index-ready head metadata: title tag set to `[trade] [city]`, meta description pulls from site copy/lead data, OG tags prep social previews, canonical URL hard-pinned to the public slug.
- LocalBusiness JSON-LD injected via schema.org — name, address, phone, geo, service area, review-count fields populated from `contractor_sites` → `leads`. Every preview is now structurally legible to Google before the contractor takes ownership.
- Sites pipeline complete end-to-end, SEO-ready: list + status toggle, create page, lead-picker autofill, edit form, public renderer — all shipped.

**Outreach unchanged this cycle (zero copy fired):**
- Austin 24-lead wave — Day 3→4 of reply window
- Houston HVAC top-5 — mid-cadence
- DFW 16 drafts — still parked on tone gut-check, ~5 cycles dormant

**The Math**
- Sites pipeline tally: 8 of 8 deliverables complete (5 base + 3 enhancements) — SEO ceiling on the contract reached.
- Time-to-public-URL for a new contractor site collapsed: lead discovery → SEO-ready URL with structured data is now a single ops loop (`/admin/leads/[id]` → `/admin/sites/new` → autofill → edit).
- Aging cost of DFW backlog: 16 parked drafts × ~5 cycles dormant — the "invisible on Google" hook is decaying in the inboxes of leads who were told this mattered.
- Cross-pipeline queue still open: lead-detail "Create site" shortcut; gate `/sites/[slug]` on `status='published'` so drafts 404.
- Render healthy, 0 recent errors. Ads: no campaign, 0 rejected. Tasks pending: 2.

**System Health**
- Render: healthy, 0 recent errors.
- Ads: no_campaign, 0 rejected.
- Ledger integrity: every shipped row flows list → edit → public render → delivery without a corresponding break.
- Longest-running blocker: DFW gut-check, ~5 cycles dormant — the single oldest open item on the dashboard.

**Tomorrow (Day 72 priority, per Polsia)**
System is healthier with one more outreach wave fired than with another pipeline seam closed.
- Lead with the DFW tone gut-check — 16 drafts, ~5 cycles dormant, reply-window urgency disappearing. Goal: a yes/no so the wave can go.
- Lead-detail "Create site" shortcut stays queued — last seam in leads → sites conversion.
- Draft-gate on `/sites/[slug]` stays queued — quality guard before the ledger starts shipping to prospects.
- Continue harvesting Austin reply-window results — Day 4 is when the first "invisible on Google" replies should land.

*(Note: 51 earlier daily CEO reports exist but were not individually pulled — Polsia has no bulk export/archive tool for these. Pull specific ones on request if something from earlier matters.)*

## 4. Outreach Emails (full text, as sent)

### Email 1 — "Free website + Google profile audit for Dixon's Plumbing"
- From: local-visibility-pro@polsia.app
- To: service@dixonsplumbing.com
- Date: Jun 22 | Status: sent

> Hi Dixon'S,
>
> I noticed Dixon's Plumbing on Google Maps — solid local presence in Columbia. Most contractors in your space have a hard time getting found online by new customers.
>
> I'd like to offer you a completely free website and Google Business Profile audit. We'll show you exactly what's working, what's not, and where you're losing customers to competitors with a stronger online footprint.
>
> No strings attached — just clarity on where you stand.
>
> Worth 15 minutes?
>
> — Sloane
> Local Visibility Pro
> sloane@thelocalvisibilitypro.com

### Email 2 — "Your phone outreach starter kit — 20 Columbia SC contractors ready to call"
- From: local-visibility-pro@polsia.app
- To: augiespicks@gmail.com (you)
- Date: May 21 | Status: delivered

> Augie,
>
> Email didn't work. 40+ sends over 4 rounds. 0 replies.
>
> Phone will. Here's exactly what to say and who to call.
>
> ---
>
> **COLD CALL SCRIPT (memorize this — 20 seconds)**
>
> Opening:
> "Hey [name], this is Augie — I help [trade] businesses in Columbia get more jobs from Google. I noticed you only have [X] reviews and no website showing up. Got 2 minutes?"
>
> If they say yes:
> "When someone searches 'HVAC repair near me,' your competitors with websites show up first. You're invisible. I can fix that for $79/month — less than one service call pays. Want me to send you a free preview?"
>
> If they say "I'm busy":
> "Totally — can I text you the details? You can look tonight."
>
> Voicemail (20 seconds):
> "Hey [name], this is Augie. Found your [trade] business on Google Maps — noticed you don't have a website and only [X] reviews. I help local contractors in Columbia get more jobs. I'll text you now."
>
> SMS after voicemail (send within 5 minutes):
> "Hey [name], just left you a voicemail. I help Columbia [trade] businesses show up on Google. No website = invisible to customers. $79/mo fixes that — less than one job. Worth 2 min? - Augie, LocalVisibilityPro.com"
>
> ---
>
> **BEST TIMES TO CALL**
> - 7:00–9:00 AM (before they're on job sites)
> - 2:00–4:00 PM (wrapping up afternoon jobs)
> - Avoid 9 AM–2 PM (on site), after 5 PM (family time)
>
> ---
>
> **YOUR TOP 20 CALL LIST**
> Prioritized: no website first (highest pain), HVAC/plumbing, phone number confirmed.

| # | Business | Contact | Phone | Trade | Website | Notes |
|---|----------|---------|-------|-------|---------|-------|
| 1 | Columbia's Finest AC & Heating | (unknown) | (843) 808-5756 | HVAC | NO | 1200 Lincoln St — no web presence at all |
| 2 | Columbia Air Conditioning & Heating | (unknown) | (803) 252-4140 | HVAC | NO | 906 S Edisto Ave — no website |
| 3 | Solutions Heating Air | (unknown) | (803) 269-5326 | HVAC | NO | 7418 Fairfield Rd |
| 4 | Stoudenmire Heating & Air | (unknown) | (803) 281-3516 | HVAC | NO | 1516 Barnwell St |
| 5 | WeCo Rooter | (unknown) | (803) 999-9326 | Plumbing | NO | 1020 Leaphart St, West Columbia |
| 6 | Crew Plumbing and Drain | (unknown) | (803) 995-9282 | Plumbing | NO | 3711 Monroe St |
| 7 | Cottrell & Co Plumbing Heating & Air | (unknown) | (803) 336-6989 | Plumbing | NO | 100 Carolina St, West Columbia |
| 8 | On Call Plumbing Heating & Air | (unknown) | (803) 781-4357 | HVAC+Plumbing | NO | Locally owned, 24/7 |
| 9 | Love Plumbing Air & Electrical | (unknown) | (803) 888-1147 | Multi | NO | Family business |
| 10 | Easy Electric LLC | (unknown) | (803) 653-3983 | Electric | NO | 2237 Commerce Dr |
| 11 | Air & Heat Provider LLC | Loc Phan | (803) 731-8300 | HVAC | Weak | Solo operator, few reviews, 142 Latonea Dr |
| 12 | Carolina Comfort Inc | Owner | (803) 794-5526 | HVAC | Outdated | Since 1992, family-owned, 5636 Bush River Rd |
| 13 | Fulmer Heating & Cooling | Owner | (803) 276-1553 | HVAC | Outdated | 40+ years, Newberry — serves Columbia |
| 14 | 1st Class Plumbing & Gas LLC | Palmer | (803) 394-8895 | Plumbing | Minimal | 1535 Platt Springs Rd, West Columbia |
| 15 | 1st Class Plumbing & Gas LLC | Colt | (803) 605-9468 | Plumbing | Minimal | Same business, second owner |
| 16 | AAA Heating & Air LLC | Roy Finley | (803) 920-3771 | HVAC | Outdated | Already emailed — no reply. Phone is the follow-up. |
| 17 | Cassell Brothers Home Services | James Cassell | (803) 868-6191 | Multi | Outdated | Already emailed — no reply. Phone is the follow-up. |
| 18 | E.F. Martin Mechanical Contractors | Andy Coggins | (803) 799-1717 | HVAC | Outdated | Since 1976. Emailed — no reply yet. |
| 19 | Alfonza's Landscape Supercenter | Alfonza Mccutchen | (see notes) | Landscape | Minimal | Founded 1999, Irmo area |
| 20 | Busy Bee Lawn Care & Sprinkler Repair | Joy Brooks | (803) 331-5323 | Lawn | Minimal | Founded 2006, West Columbia |

### Emails 3–8 — NOT YET CAPTURED
The Polsia dashboard's email-fetch got stuck on "Loading email…" partway through this export and didn't recover after retries. These remain to pull once it's working again:
1. "Quick question about your Google Maps presence" → ben@gregorylandscapeservices.com (May 17)
2. "Re: Quick question about your Google Maps presence" → lawns@midlandslandscape.com (May 17)
3. "Quick question about your Google Maps presence" → james@cassellbros.com (May 15)
4. "Quick question about your Google Maps presence" → roy.finley@aaaheatair.com (May 15)
5. "Your Landscaping is Losing to Competitors" → lawns@midlandslandscape.com (May 10)
6. "Welcome to LocalVisibilityPro!" → augiespicks@gmail.com (May 8)

## 5. Where the Live Data Actually Lives (Polsia can't export it — go here directly)
- Leads table: https://local-visibility-pro.polsia.app/admin/leads
- Sites table: https://local-visibility-pro.polsia.app/admin/sites
- Both are gated by a separate admin password from your Polsia login — needed to browse/copy full row-level data.

## 6. Housekeeping
- Subscription lapses Aug 12, 2026 for non-payment. Per Polsia: **site, code, and database are not deleted** when subscription lapses — only autonomous daily building stops.
- "Download Code" is available from the Polsia dashboard menu for the underlying codebase/schema (lower priority since you already have GitHub).
- No self-service CSV export exists; Polsia suggested emailing support@polsia.com if you want one built.
