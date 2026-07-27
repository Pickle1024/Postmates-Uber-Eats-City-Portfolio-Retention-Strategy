# Postmates Case — Industry Benchmarks & External Context

> **Purpose.** Ground every external claim in the deck (`narrative_and_insights.md`) on a citable source. Pulled May 2026 from public sources covering 2022-2024 timeframe.
>
> **How to use.** When writing a slide, find the relevant section here, footnote the source. Where multiple sources disagree, note the range.

---

## 1. US food-delivery market shares & growth

### 1.1 Market share (Bloomberg Second Measure, observed consumer transactions, March 2024)

| Brand | Market share |
|---|---|
| **DoorDash + Caviar** | **67%** |
| Uber Eats | 23% |
| **Postmates** (separate line) | **2%** |
| **Uber total (UE + PM)** | **25%** |
| Grubhub + Seamless / Eat24 / Tapingo | 8% |
| ASAP / Waitr (now bankrupt April 2024) | <1% |

Note: Bloomberg notes their data could not reliably track Postmates Oct-Dec 2022 (panel issue), so PM specific time series during our case period has gaps in this source.

**Implication for our case**: PM's 2% national observed share by Mar 2024 confirms that PM is no longer a top-line brand player nationally — but our case data (2022-23) shows it still has 11-43% share in specific cities. This is the structural pattern: PM is geographically concentrated, not nationally distributed.

> Source: [Bloomberg Second Measure — Which company is winning the restaurant food delivery war? (Apr 2024)](https://secondmeasure.com/datapoints/food-delivery-services-grubhub-uber-eats-doordash-postmates/)

### 1.2 Industry YoY growth

| Period | Combined YoY |
|---|---|
| Apr 2020 (pandemic peak) | +162% |
| Through March 2023 | +11% |
| March 2024 | +8% |

**Implication for our case**: 2022-23 industry growth ≈ 11% YoY. **UE +17% is materially above market** — UE is taking share. **PM −11% is materially below market** — PM is losing share.

> Source: same as 1.1.

### 1.3 Los Angeles — what we can defensibly say (and what we can't)

> ⚠️ **Methodology note.** Public, citable data points for LA are sparse and don't form a continuous time series. We list only confirmed data points and explicitly flag inferences.

**Confirmed data points**

| Year | Source-confirmed data | Source |
|---|---|---|
| 2019 | PM = **38%** of LA market (PM's #1 city) | Food On Demand (Edison Trends) |
| April 2021 | PM = **29%** of LA market | Statista |
| 2023-24 | LA CBSA: **DoorDash 41.8%, "Uber Eats" 41.9%, Grubhub 11%** | Earnest Analytics |

**Disaggregating Uber's 41.9% LA share into PM brand vs UE brand using our case-data ratio**

Earnest reports the brand label "Uber Eats" — but **does not publicly disaggregate Uber's LA share into PM brand vs UE brand**. Bloomberg Second Measure breaks them out at the **national** level (PM ~2%, UE ~23%) but **does not publish city-level brand splits**.

We can estimate the PM/UE split inside Uber's LA share using our case data. In our case data, within L2 (Jun-22 → Jun-23), **PM = 39% of combined Uber GB and UE = 61%**. Applying that ratio to Earnest's 2024 Uber LA share (41.9%):

| Brand | LA market share (2024 estimate) | Methodology |
|---|---|---|
| **PM brand** | **~16.3%** | 39% (case-data PM/UE ratio in L2) × 41.9% (Earnest Uber total LA) |
| **UE brand** | **~25.5%** | 61% × 41.9% |
| Combined Uber | 41.9% | Earnest direct |
| DoorDash | 41.8% | Earnest direct |
| Grubhub | 11.0% | Earnest direct |

Sanity check vs Bloomberg national-level brand splits:
- **PM in LA ~16%** is **~8× its national 2% share** → LA is a genuine PM stronghold (consistent with PM = 29% LA share in April 2021)
- **UE in LA ~25.5%** is only marginally above its national 23% share → **LA is not a special UE strength market**

**Strategic implication**: PM contributes **~40% of Uber's LA market share** (16.3 / 41.9 = 39%). If PM disappeared in LA, Uber's LA market share would drop from ~42% to ~25.5%, leaving DoorDash (~42%) clearly ahead. **"Defend LA" is preserving Uber's competitive parity with DoorDash in LA, not just protecting a niche premium brand**. This dramatically raises the strategic stakes.

**What we deliberately do NOT claim** (removed from earlier drafts): specific 2021-2023 LA trajectory; that "Uber consolidated PM into UE in LA"; that "DD has been steadily gaining" — these were inferences without source.

**Caveat on the disaggregation**: assumes the PM/UE within-Uber ratio in LA hasn't shifted dramatically between Jun-2023 (end of our case data) and the 2024 Earnest report. Could be confirmed/refined with Uber's internal city-brand-level reporting → metrics-to-collect.

> Sources: [Earnest Analytics — DoorDash leads US delivery share](https://www.earnestanalytics.com/insights/doordash-leads-us-delivery-share-but-some-cities-still-competitive); [Statista — Postmates' share of sales in select cities, 2021](https://www.statista.com/statistics/916803/cities-where-postmates-is-the-most-used-food-delivery-service-us/); [Food On Demand — Data Shows Regionalized Delivery Share](https://foodondemand.com/07252019/data-shows-regionalized-delivery-share/)

### 1.4 PM regional strongholds (acquisition-era data, 2020-2021)

**Confirmed**:
- LA: 29% PM share (Apr 2021)
- Other PM strongholds at acquisition: **Phoenix, Las Vegas**, broader Southern California (Orange County, San Diego)
- Uber explicitly cited PM's strength in these Western markets as a key strategic rationale for the acquisition

**Implication**: confirms **L2 = LA** and **V1 = Vegas** city-mapping inference, and validates the "PM strongholds in Western US" framing.

> Sources: [Statista — Postmates' share of sales in select cities, 2021](https://www.statista.com/statistics/916803/cities-where-postmates-is-the-most-used-food-delivery-service-us/); [Supermarket News — Uber completes purchase of Postmates](https://www.supermarketnews.com/grocery-trends-data/uber-completes-purchase-of-postmates)

---

## 2. Multi-homing & user behavior

### 2.1 Multi-app prevalence (CivicScience, Nov 2023)

- **60% of US food delivery app users use multiple apps**
- 18% use 4+ apps (up 5 points from January 2023)
- 77% of UE users say they're "at least somewhat likely" to use DD

**Implication for our deck**:
- Removing PM does NOT consolidate users into UE. Most PM users likely already have UE installed; the marginal PM-only user (the 30-40% who multi-home with at most one Uber app) is who sunsetting would lose to DD.
- This grounds Hypothesis 1 (multi-app shelf) in our narrative doc — "PM lets Uber capture brand-affinity users who otherwise install DD instead of UE".

> Source: [CivicScience — Multi-App Users and Subscriptions Power DoorDash Q3 Momentum](https://civicscience.com/multi-app-users-and-subscriptions-power-doordash-q3-momentum-amid-new-tipping-initiative/)

### 2.2 Customer loyalty trend
Industry consensus: customers are increasingly *less* loyal to single platforms. Grubhub's former CEO publicly called these "promiscuous customers" in earnings discussion. Multi-homing is increasing year over year.

> Source: [Reuters — Grubhub blames "promiscuous diners" for slowing growth](https://www.reuters.com/article/grubhub-results/grubhub-blames-promiscuous-diners-for-slowing-growth-shares-sink-30-idUSL3N27D4CG); also Bloomberg Second Measure article above.

---

## 3. Subscription benchmarks (DashPass cohort)

### 3.1 DashPass retention curve, March 2023 cohort

| Tenure | Retention rate |
|---|---|
| 1 month | **69%** |
| 6 months | **36%** |
| 12 months | **28%** |

**Implication for our LTV math**: DashPass-equivalent food-delivery sub retention curve gives us a reasonable benchmark for Uber One's economics and for the LTV of subscribed PM users. **Subscribers are ~35-40% retained at one year** in this category — a real anchor for Story 3.

**Caveat**: DashPass benefits from Chase / Chegg / Roku free-membership partnerships not in this retention number. Pure paid retention may be lower.

> Source: [Bloomberg Second Measure (same as 1.1)](https://secondmeasure.com/datapoints/food-delivery-services-grubhub-uber-eats-doordash-postmates/)

### 3.2 Subscription product timeline (relevant context)

- 2016: **Postmates Unlimited** — first food-delivery subscription in US
- 2018: DashPass (DoorDash)
- 2020: Grubhub+
- **November 2021: Uber One** — combined Eats + Rides + Postmates membership

**Implication**: PM was the *original* subscription pioneer. Uber One launched ~2 years before our case period — by Jun 2022, our PM data should already show Uber One sub effects. The 1.1% subscription revenue / GB on PM (vs 0.8% UE) in our data is the empirical residue.

> Source: [Uber Newsroom — Introducing Uber One](https://www.uber.com/newsroom/introducing-uber-one/)

### 3.3 Uber One vs DashPass — head-to-head comparison

| Dimension | **Uber One** | **DashPass** |
|---|---|---|
| Monthly price | $9.99 | $9.99 |
| Annual price | $99 | $96 |
| Core benefit | $0 delivery on eligible Eats orders + 10% off Eats + 6% Uber Cash on Rides | $0 delivery on eligible orders + 5% off |
| Cross-platform scope | **Eats + Rides + PM** (only one in US that bundles delivery + rideshare) | DoorDash only |
| Free / discounted via partners | **Amex Platinum**: $120/yr Uber One credit (effectively free); **Amex Gold**: $10/mo Uber Cash; **Delta SkyMiles Reserve / Platinum Amex**: 12 mo free | **Chase Sapphire Reserve / Preferred**: free or discounted; **Chegg**: free for college students; **Roku** users; **Capital One** select cards: free |
| Free-membership ecosystem breadth | Premium credit cards + airlines | Mainstream credit cards + education + streaming + retail-credit |
| Membership penetration | Disclosed by Uber but not at PM-vs-UE granularity in our case data — sub revenue 1.1% PM GB / 0.8% UE GB suggests PM more sub-penetrated | DoorDash: ~10M+ subscribers as of 2021; ~40% of active customers |
| 12-month paid retention (Mar 2023 cohort) | Not publicly disclosed at this granularity | **28%** (Bloomberg Second Measure — paid only, excludes free-via-partner) |

**Why the DashPass 12-month number says retention is *understated***

Bloomberg explicitly notes the 28% rate is **paid subscribers only** — it excludes the millions of users on free DashPass via Chase / Chegg / Roku / Capital One partnerships. If those free users (who behave like subscribers) were included, retention would be materially higher. So the **true delivery-subscription stickiness** is meaningfully better than 28% — important context when we use DashPass as a benchmark for Uber One LTV in Story 3.

**Strategic implication for PM**: Uber One is Uber's biggest tool to **cross-engage PM users to UE / Rides** (the cross-platform LTV uplift in Story 3). DashPass doesn't cross categories — Uber One does. **This is a structural Uber advantage** the deck should explicitly call out.

> Sources: [Uber.com — Amex Uber One](https://www.uber.com/us/en/u/amex-uberone/); [The Points Guy — Credit cards with Uber One membership](https://thepointsguy.com/credit-cards/credit-cards-uber-one-membership/); [Bloomberg Second Measure (DashPass section)](https://secondmeasure.com/datapoints/food-delivery-services-grubhub-uber-eats-doordash-postmates/); [Latterly — DoorDash Marketing Strategy](https://www.latterly.org/doordash-marketing-strategy/)

---

## 4. Brand-sunset benchmark — Caviar / DoorDash

This is the most important parallel for our deck thesis: **DoorDash kept Caviar as a separate brand for 5+ years post-acquisition because the differentiation has structural value.**

### 4.1 Caviar acquisition

- **August 2019** announced; **November 1, 2019** closed
- DoorDash bought Caviar from Square for **$410M**
- Caviar's 2018 revenue ~$190M, projected $9M EBITDA in 2019 (vs −$10M in 2018)
- DoorDash explicitly cited **complementary geography + premium-restaurant positioning** as rationale (not consolidation)

### 4.2 Caviar's positioning

**Geographic concentration — NOT national:**
- Active in ~20 urban markets only: LA, SF Bay Area, Seattle, Chicago, Manhattan, Brooklyn, Queens, Dallas, Portland, Philadelphia, DC, Sacramento, Boston, Minneapolis
- Deliberately concentrated where the "premium delivery" cohort exists — high-density, high-income, restaurant-dense cities

**Deliberate exclusions (this is the key strategic discipline):**
- **No fast food** (no McDonald's, no Chipotle, etc.) — even though shared DoorDash backend supports it
- **No grocery / convenience** (no DashMart, no CVS) — even though DoorDash heavily promotes these on its main app
- **Only restaurants with Yelp 4+ star rating** included
- This is brand discipline: by saying NO to mass-market categories, Caviar stays credible as the "curated premium" venue

**Brand-asset partnerships unique to Caviar (UE / PM don't have these):**
- **Michelin Guide official delivery partner** (specifically for LA, SF, San Diego — the US Michelin Guide cities)
- **Zagat** partnership
- **The Infatuation** partnership (the influential restaurant editorial brand)

**Customer demographics:**
- Median user income ≈ **$79K, ~29% above national median**
- This is the "premium / in-the-know" cohort — the same audience PM's brand permission targets

### 4.3 Brand status today

- Caviar **remains a separate app** (orange branding vs DoorDash red), distinct UI
- Backend integrated: same DoorDash account works on both
- Bloomberg Second Measure tracks "DoorDash + Caviar" combined at 67% national share — meaning **Caviar is meaningful enough to not break out separately, but kept as a distinct brand for 5+ years post-acquisition**
- DoorDash spokesperson (per public reporting): "the services will remain as individual brands for the time being and the company will ultimately do the best for each brand, whether that's combining them or keeping them separate"

### 4.4 Why this is **the** parallel for our PM thesis

| Aspect | Caviar (DoorDash's premium brand) | Postmates (Uber's premium brand) |
|---|---|---|
| Acquired by mass-market platform | DoorDash 2019 ($410M) | Uber 2020 ($2.65B) |
| Backend integrated, branding separate | ✓ | ✓ |
| Premium / upscale-restaurant positioning | ✓ (Michelin / Zagat / Infatuation partnerships) | ✓ (high-AOV, 85% SMB tilt — confirmed in our data) |
| Deliberately excludes fast-food / grocery | ✓ (brand discipline) | Could / should adopt — currently maintain |
| Geographic concentration | ~20 urban premium markets | LA / Vegas / Phoenix / SoCal |
| Survives 5+ years as separate brand inside parent | ✓ | (this is the question — but parent's hiring intent suggests yes) |

**Deck framing — "1+1 > 2"** (avoid the "should PM exist" framing — Uber's hiring of intern across PM+UE signals PM is strategically committed; the right question is how the two brands coordinate):

> *"DoorDash's portfolio shows the **mass-market + premium-curated dual-brand playbook** working: DoorDash for breadth, Caviar for taste-conscious depth. Five years post-acquisition Caviar still operates as a distinct brand because it captures incremental cohorts and merchants DoorDash itself can't credibly serve.*
>
> *Uber + Postmates is the structural equivalent. UE is the mass-market workhorse; PM is the premium / SMB-curated brand whose AOV (+12% vs UE), merchant mix (85% vs 79% SMB), and brand-permission (urban / late-night / 'in-the-know') are confirmed by our data and external signal. **The question isn't whether PM should exist — it's how PM and UE should explicitly coordinate so 1+1 > 2: which cohorts each owns, which cities each leads, where each spends.**"*

This framing is also more politically apt: Uber's intern role spans PM **and** UE — meaning the team is committed to running both. Our recommendation should be how to make that portfolio work harder, not whether to have it.

> Sources: [Restaurant Dive — DoorDash acquires Caviar for $410M](https://www.restaurantdive.com/news/doordash-acquires-caviar-for-410m/560082/); [Financial Panther — Caviar vs DoorDash 2024](https://financialpanther.com/caviar-vs-doordash/); [Caviar Help — Where is Caviar delivery available](https://help.trycaviar.com/diners/s/article/Where-is-Caviar-delivery-available); [Michelin Guide — Caviar partnership in LA, SF, San Diego](https://guide.michelin.com/us/en/article/michelin-guide-ceremony/michelin-guide-delivery-in-la-sf-and-san-diego-with-caviar); [Ridester — What Is Caviar](https://www.ridester.com/caviar-food-delivery/); [Square press release](https://squareup.com/us/en/press/doordash-acquires-caviar)

---

## 5. Postmates acquisition details

- **Announced**: July 6, 2020
- **Closed**: end of November 2020 (some sources say Dec 2020)
- **Deal value**: $2.65 billion, all-stock
- **Backend integration**: completed mid-2021 (PM and UE on same tech stack)
- **Apps remained separate**: yes, both PM and UE consumer apps continue to operate

**Strategic rationale at acquisition** (per Uber statements): consolidate market share in Western US (LA, Phoenix, Vegas, San Diego) where PM was strong; gain SMB merchant relationships.

> Sources: [NPR — Uber Gobbles Up Postmates In $2.65B Bet](https://www.npr.org/sections/coronavirus-live-updates/2020/07/06/887961123/uber-gobbles-up-postmates-in-2-65-billion-bet-on-food-delivery); [Supermarket News — Uber completes purchase of Postmates](https://www.supermarketnews.com/grocery-trends-data/uber-completes-purchase-of-postmates)

---

## 6. Uber Eats merchant commission tier structure (2021-2023 era)

This is the critical structural fact behind our %SMB ↔ take rate finding.

### 6.1 Tier structure (Sept 2021 – early 2026)

| Tier | Commission | What merchant gets | Likely fits |
|---|---|---|---|
| **Lite** | **15%** | Direct search results only; no homepage placement; no Uber One member benefits | Independent SMBs prioritizing margin |
| **Plus** | **25%** | Direct search + homepage + Uber One member benefits | Mid-size local chains, some independents wanting visibility |
| **Premium** | **30%** | All of Plus + ad spend matched up to $100 | National chains in growth mode |

DoorDash launched a similar tiered model in April 2021 (15-30% range).

### 6.2 Why this drives our %SMB ↔ take rate finding

- Independents typically choose **Lite (15%)** to preserve margin → low take rate to Uber, high merchant payout share
- Chains typically choose **Plus / Premium (25-30%)** because they need volume → higher take rate to Uber
- Higher %SMB city → more 15% commissioners → **lower take rate** (matches our data)
- Higher %ENT city → more 25-30% commissioners → **higher take rate** (matches)

### 6.3 Implication for our recommendation — three concrete offsets to lower take rate

PM's structural SMB tilt (= more Lite-tier 15% commissioners) gives it a **structurally lower take rate** than UE. The deck recommendation is *not* "fix PM's take rate by chasing chains" — that erases differentiation. The recommendation is **make up the take-rate gap through three other revenue mechanics**:

**Offset 1: Restaurant ads / sponsored placement (paid search-style monetization)**
- Like UE's Premium tier mechanic ($100 ad-spend match), PM can let merchants *pay for visibility* on the PM app — sponsored search results, homepage carousel, "PM Picks" featured slots
- This is **commission-independent revenue**: SMBs pay because they want exposure to the in-the-know PM cohort; chains pay to reach a high-AOV audience they can't get on UE alone
- DoorDash already has a multi-billion-dollar ads business (DashAds) — Uber/PM have room to build similar
- For PM specifically: this is the most operationally simple monetization path because PM merchant base is willing to pay for differentiation that UE algorithm doesn't give them

**Offset 2: Subscription upsell (Uber One)**
- PM users are already more sub-penetrated (sub revenue 1.1% of GB vs UE 0.8%)
- Uber One brings **Eats + Rides + PM into one membership** — DashPass can't match this cross-category bundle
- Pushing a churning PM user into Uber One captures sub revenue + cross-uses Rides + retains PM activity simultaneously

**Offset 3: Higher AOV partially closes the per-trip net-revenue gap**
- Naive read: PM take rate 12.9% vs UE 15.1% = PM monetizes 15% worse per dollar
- Per-trip math: PM $32.57 AOV × 12.9% = **$4.20 NetRev/trip** vs UE $28.99 × 15.1% = **$4.38 NetRev/trip**
- Real per-trip gap is only **$0.18 (~4%)** — much smaller than the take-rate spread suggests
- Add ad revenue + sub revenue on top → PM per-trip economics can equal or exceed UE while staying on its differentiated track

**Combined: PM's "premium-curated" positioning is economically viable** without forcing it to look like UE.

> Sources: [Nation's Restaurant News — Uber Eats and Postmates introduce tiered commission pricing](https://www.nrn.com/news/uber-eats-and-postmates-introduce-tiered-commission-pricing-operators-starting-15)

---

## 7. CAC — handle with care

> ⚠️ **Methodology warning.** CAC is the metric in this dataset where naive aggregate comparisons most easily mislead. Multiple structural reasons require caution before drawing PM-vs-UE conclusions.

### 7.1 What our case data actually contains vs what "CAC" usually means

**Our case data**: `Incentive to New Eaters` ÷ `New Eaters` = the **promotional cost** to acquire a new user (a free-delivery credit, a $5-off coupon, etc.).

**Industry "CAC"** (the $45-85 per user benchmark) typically includes:
- Paid digital ads (Google, Meta, TikTok, etc.) — usually the biggest line item
- App-store install ads
- Brand marketing (TV, OOH, podcast)
- Referral payouts
- Onboarding funnel costs (welcome bonuses beyond the first promo)
- Allocated overhead (CRM, data ops)

These two numbers are not comparable. **Our $5.93 (PM) / $8.73 (UE) = "promotional CAC", not "total CAC".**

### 7.2 Three reasons aggregate PM-vs-UE CAC comparison is unsafe

**(a) City-level variation likely flips the headline.** Our $5.93 / $8.73 numbers are weighted across 44 cities. Hiring-manager intelligence (one-on-one): **"In Seattle, PM CAC is currently higher than UE CAC."** This single signal contradicts the aggregate direction in at least one major market. If even one large city inverts, the city-weighted average can be misleading for any specific market decision.

**(b) Cohort-level variation likely matters.** Different demographics respond to different acquisition channels. PM's cheap aggregate CAC could be driven by a small cohort of brand-affinity users (urban, taste-conscious) who convert on minimal promo, while UE's higher aggregate CAC reflects mass-market acquisition costs. Without cohort breakouts we don't know.

**(c) Time variation matters.** Our data is **Jun-22 → Jun-23**. The competitive environment evolves quickly — DoorDash's DashPass partnerships expanded materially in 2023, ad costs inflated 40-60% since 2022. Conclusions from 22-23 may not reflect 2025-26 reality. The hiring manager's Seattle anecdote refers to current state, not our case window.

### 7.3 What we can and cannot say in the deck

✅ **Defensible**: "In our 13-month aggregate data, **promotional incentive per new eater** is $5.93 (PM) vs $8.73 (UE). This is the promotional component of CAC, not total CAC. Aggregate masks city- and cohort-level variation. Hiring-manager input indicates PM CAC in Seattle currently exceeds UE — confirming aggregate is not safe to extrapolate to specific markets."

❌ **NOT defensible** (removed from earlier draft): "PM acquires users cheaper than UE", "PM brand pull lowers CAC universally", any specific city-by-city CAC claim from our data alone.

### 7.4 Strategic implication — turn the limitation into a recommendation

This becomes a Story 1 (or Q3 metrics-to-collect) bullet:

> "**Recommend collecting total CAC by city × cohort × channel.** Today we can only see the promotional sliver of CAC, and even that masks city-level inversions our team already knows exist (e.g., Seattle). Real PM-vs-UE acquisition strategy decisions need full-cost CAC at city × cohort granularity, with cohort-level LTV to compute LTV:CAC by segment."

This positions us as analytically humble + ops-aware — exactly the senior judgment a panel looks for.

### 7.5 Industry standard for sanity-checking

LTV : CAC target = **3:1** (industry rule of thumb). Even without full CAC, we can use this in Story 3 to bracket whether our LTV computations imply healthy PM unit economics:
- If PM saved-eater 24-month LTV is $X, then total CAC must be ≤ $X/3 for the engine to be ROI-positive
- If full CAC turns out to be $50+ per user, this constrains which cohorts justify retention investment

> Sources: [Medium — Why 91% of Food Delivery App Development Projects Burn $500K+](https://devin-rosario.medium.com/why-91-of-food-delivery-app-development-projects-burn-500k-in-first-year-avoid-these-5-traps-60b969d9c171); [DoorDash Merchant Blog — Comparing Restaurant CAC](https://merchants.doordash.com/en-us/blog/restaurant-customer-acquisition-cost); hiring-manager input (one-on-one round 1)

---

## 8. Postmates brand DNA — third-party signals

### 8.1 Demographics

- PM users skew **urban** (more concentrated in cities >1M population than the typical food-delivery user)
- PM users **over-index on Snapchat** (a younger-skewing platform)
- PM target: **millennials valuing time, comfort, convenience**

### 8.2 Brand positioning (qualitative)

- Operates **24/7** with strong late-night presence (orders accepted at midnight if stores are open)
- Historically the only food-delivery brand strong on "Anything" delivery (alcohol, gifts, retail, non-food convenience)
- Marketing tone: lifestyle / experiential / city-cool

### 8.3 What this confirms

The "in-the-know" / "younger-urban-taste-conscious" positioning we propose for PM in Story 1 / Section 19 isn't aspirational — it's a continuation of where PM's **existing brand permission** already sits.

> Sources: [Statista — Restaurant delivery: Postmates users in the United States](https://www.statista.com/study/76919/restaurant-delivery-postmates-users-in-the-united-states/); [Whisper Mob — Postmates: They Get It](https://medium.com/whisper-mob/postmates-they-get-it-4ed451eb7143)

---

## 9. How each benchmark plugs into our deck

| Deck claim | Benchmark anchoring it | Section in this doc |
|---|---|---|
| "Industry grew ~11% YoY in 2022-23" | Bloomberg Second Measure | 1.2 |
| "UE +17% vs industry +11% = UE taking share" | Same | 1.2 |
| "PM −11% vs industry +11% = PM losing share" | Same | 1.2 |
| "DD ~65-67%, UE ~23%, GH ~8%" | Same | 1.1 |
| "Uber's 41.9% LA share splits into ~16% PM + ~25.5% UE — PM contributes ~40% of Uber's LA position; sunsetting PM = handing LA to DoorDash" | Earnest Analytics + our case data | 1.3 |
| "L2 = LA, V1 = Vegas inference" | Statista 2021 + Uber acquisition rationale | 1.4 |
| "60% of users multi-home → PM-only churners may go to DD, not UE" | CivicScience | 2.1 |
| "Subscription retention 28% at 12mo" (LTV anchor) | Bloomberg Second Measure | 3.1 |
| "Caviar parallel: DD kept it 5 years for premium positioning" | Multiple sources | 4 |
| "PM was acquired Nov 2020 for $2.65B" | NPR / Supermarket News | 5 |
| "%SMB ↔ take rate driven by Lite (15%) vs Plus/Premium (25-30%) tier opt-in" | NRN | 6 |
| "Promo CAC $5.93/$8.73 is a subset of total CAC; aggregate masks city/cohort inversions (e.g. Seattle per hiring manager)" | Industry sources + hiring-manager input | 7 |
| "PM is urban-skewed, late-night, lifestyle brand" | Statista / Whisper Mob | 8 |

---

## 10. Open data gaps (would strengthen the deck if found)

| Want | Status | Where to get if needed |
|---|---|---|
| PM market share trajectory 2020 → 2024 by city | Partial (LA point estimates only) | Earnest Analytics paid data; Sensor Tower; Edison Trends |
| Caviar GB size today | Lumped with DD in published data | DD investor reports; private analyst estimates |
| User-level cross-app overlap (PM + UE) | Not public | Uber internal data only — flagged as deck Q3 metrics-to-collect |
| Industry retention curve (non-subscriber, just app users) | Limited public data | Sensor Tower app cohort retention; mParticle / Adjust benchmarks |
| Brand sunset / migration rates (Caviar didn't sunset; need a true sunset case) | Hard to find public data | Drizly sunset 2024 may have partial data; Uber may have internal |
| Vegas-specific food-delivery share | Generic only | Earnest / Bloomberg city-level paid data |
