# JSO Baseline (as of 2026-11-17)

Everything here was read from a live system or a document on 2026-11-16/17. Each fact names its source. "NOT VERIFIED" means nobody has confirmed it; "NOT FOUND" means it was looked for and is not on record. No customer, subscriber or backer names are stored in this repo.

## 1. The one-paragraph truth

JSO launched its store on Aug 31, 2026 and has **zero paid orders** so far. First real inventory (about 900 bodysuits and sleepers) arrived in late October / early November. Shopify lists 888 units for sale right now. No Children's Product Certificate, lab test report, tracking-label check or sleepwear determination is on record anywhere, so the first job is making the product legal to sell, then getting the first 100 customers. Cash is tight: bills for Shopify, Google Workspace and Meta were declined in October.

## 2. Sales and traffic (Shopify, queried 2026-11-16)

| Metric | Value | Source |
|---|---|---|
| Real paid orders, all time | 0 | `ordersCount`, ShopifyQL sales by month |
| Recorded orders | 2: a $24 test order (reversed, Aug) and a $0 free-guide download (Sep) | ShopifyQL, Gmail |
| Net sales, last 12 months | $0 | ShopifyQL `FROM sales` |
| Customer records | 94 (mostly email signups, plus spam and test entries) | `customersCount` |
| Abandoned checkouts | 7 (5 are the free guide; 2 are a single bodysuit, one of them the owner's test) | GraphQL |
| Sessions, last 90 days | 1,306 | ShopifyQL `FROM sessions` |
| Sessions in launch weeks (Aug 24 and Aug 31) | 958 | same |
| Sessions with add-to-cart, 90 days | 11 | same |
| Completed checkouts, 90 days | 1 (the $0 guide) | same |
| Device mix | 950 mobile / 275 desktop (US) | same |

Traffic by source, 90 days:

| Source | Sessions | Add-to-carts | Checkouts |
|---|---|---|---|
| Facebook | 783 | 0 | 0 |
| Direct | 377 | 10 | 1 |
| Instagram | 122 | 0 | 0 |
| Google search | 13 | 0 | 0 |
| All other | 11 | 1 | 0 |

Reading: 905 social sessions produced zero add-to-carts. During those weeks the store showed zero inventory and a "ships Dec 15, 2026" preorder note (Drive, Operational_Plan, Oct 22), so this is not a fair test of the product. It is a fair warning about paying for traffic before the store can convert.

## 3. Catalog and inventory (Shopify, 2026-11-16)

| Product | Status | Price | Units in Shopify |
|---|---|---|---|
| Organic Bodysuit (Oat, Sage; 6 sizes) | Active | $24 | 462 |
| Organic Cotton Sleeper (Oat, Sage; NB, 0-3, 3-6, 6-12, 12-18M) | Active | $32 | 426 |
| Bodysuit 2-Pack | Active | $44 | shares bodysuit stock |
| Everyday Pair (bodysuit + sleeper) | Active | $52 | shares stock |
| Starter Set (2 bodysuits + sleeper) | Active | $76 | shares stock |
| Clean Start Baby Guide | Active | $0 | digital |
| Bandana Bib, Muslin Swaddle, Toddler Play Set, Founding Box | Draft | $10 / $24 / $55 / $96 | none |
| Essential Collection, old Starter Set, Joyful Gift Box | Archived | | none |

- Retail value of stock at list price: 462 x $24 + 426 x $32 = **$24,720**.
- Store: Shopify Basic, US shipping only, no password page, Shop Pay / Apple Pay / Google Pay enabled, UPS and USPS calculated rates plus a "Free Standard Shipping" rate (threshold NOT VERIFIED; Notion plan says free over $65).
- One abandoned single-bodysuit checkout totalled $33.59 on a $24 item, so shipping and tax added about 40% (Shopify GraphQL).

**Unit count conflict (open):**

| Source | Units |
|---|---|
| Shopify inventory | 888 (462 bodysuits, 426 sleepers) |
| Manufacturer invoice, founder-pasted (Drive, Invoice_Cost_Update, Oct 22) | 900 (450 + 450) |
| Notion scope revision, Jul 15 | 410 (210 + 200) |
| Original PI 26275 and marketing copy | 800 |
| Carrier | 5 boxes delivered vs 10 cartons invoiced |

Shopify shows more bodysuits (462) than the invoice says were made (450). The Drive receiving log is empty. A physical count has not been recorded.

## 4. Cost and cash

| Item | Value | Source | Confidence |
|---|---|---|---|
| Bodysuit unit price (ex-works) | $3.55 | Drive, Invoice_Cost_Update | Founder-pasted, original not seen |
| Sleeper unit price (ex-works) | $4.95 | same | same |
| Shipping line (said to include duties) | $1,900 | same | Undocumented |
| Invoice total, 900 units | $6,011 | same | same |
| Provisional landed cost | Bodysuit $5.98, sleeper $7.38 | same | Provisional |
| Gross margin at list price | Bodysuit 75%, sleeper 77% | Computed | Before packaging, postage, fees |
| Stock value at provisional cost | about $5,900 | Computed from Shopify units | |
| Kickstarter | $1,136 pledged, 17 backers, $801.32 paid out May 14 | Gmail | Verified |
| Meta ads spend, Mar to Sep 2026 | at least $449.80 | Gmail receipts | Floor; some receipts unread |
| Family loan for UPS fee | $1,162.20, repayment dates unconfirmed | Notion | Tracker note |
| Founder capital planned | $4,500 (LiftFund budget) / $5,000 to $7,000 ceiling (Notion) | Drive, Notion | Plan, not actual |
| LiftFund loan ask $7,660; Amber Grant $10,000 | Outcomes NOT FOUND | Drive | |
| Bank balance | NOT FOUND (a low-balance alert fired Nov 2) | Gmail | |
| Books | QuickBooks connector needs re-login; the finance tracker mentions Wave + Novo | | |

Known recurring bills: Shopify $39/mo; Google Workspace (rate unconfirmed, $138.88 catch-up paid Nov 13); domain $16/yr; ManyChat $15, Claude $20, Canva $15 per the May finance tracker (current status NOT VERIFIED); Higgsfield trial ends Nov 18; Amazon Business Prime started Nov 13 (price NOT FOUND).

Payment failures: Shopify $39 bill failed Oct 3 to Oct 31, store frozen Oct 31, paid Nov 13. Google Workspace declined Oct 1 and Nov 1. Meta ad balance declined Oct 26.

## 5. Email and audience (Klaviyo, 2026-11-16)

| Metric | Value |
|---|---|
| Pre-Launch Waitlist list | 71 profiles (47 added in November 2026) |
| Kickstarter Backers list | 16 profiles |
| Joy Box Giveaway 2026 list | 0 |
| Campaigns sent, last 12 months | 10, to 22 to 66 recipients each |
| Campaign open rate | 28% to 50% on launch emails |
| Launch Day email (sent Sep 1) | 30 recipients, 15 opens, 6 clicks, 0 orders |
| Welcome flow | 112 sends, 51% open, 11% click, 0 orders |
| Abandoned checkout flow | 35 recipients, only 13 delivered (37%) |
| Revenue attributed to email | $0 |
| Unsent campaigns in Klaviyo | "Teaser" Nov 20, "Early Access" Nov 24, "Black Friday" Nov 27, "Small Business Saturday" Nov 28, "Last Call" Nov 29, "Cyber Monday" Nov 30, "Thank You" Dec 1 (draft vs scheduled NOT VERIFIED) |

Instagram: "900+ followers" in July (Notion; not re-checked, no connector). TikTok Shop seller account exists. Facebook group "Joyful Sprouts Family" planned; status NOT VERIFIED.

## 6. Promises already made

| To whom | What | Status |
|---|---|---|
| 10 Kickstarter reward backers | Gift boxes, starter sets, printed bodysuits, swaddles, bibs, totes | Funded Apr 30. Not shipped. Bibs and swaddles are not sourced. One backer asked for an update on Sep 10 and Oct 23 with no reply found. |
| A Georgia UGC creator | One gifted Starter Set in 12-18M; she owes one 20 to 30 second video, 6 months organic use, no paid-ad rights | Agreed Nov 14-15. Address received. Not shipped. |
| Swaddle supplier (Organic & More) | An answer on their 800-swaddle minimum (400 per colour) | Waiting since Sep 16 |
| A retailer inquiry (Sep 1) | Reply on where products are made and what is coming | No reply found |
| "Ships Dec 15" preorder note | Shown on the store in October | No paid preorders exist, so nobody is owed product under it. Check the wording is gone. |

## 7. Compliance status

Sources: Notion Legal + Compliance and Production tickets (state as of Aug 6), Drive Launch_Gates.csv (Oct 22), Gmail. None of these show a completed item.

| Requirement | On record |
|---|---|
| Children's Product Certificate (CPSIA) | None. Notion, Jul 14: "No CPC exists for Drop 1... Cannot legally sell Drop 1 without CPCs." Drive gate still OPEN on Oct 22. |
| Third-party lab test reports | None found |
| Tracking labels on garments | Not verified |
| Sleepwear rule for sleepers above 9 months (6-12M, 12-18M) | No measurement or determination found |
| 16 CFR 1610 general flammability | Not started |
| FTC fibre / origin / care labels | Not started |
| GOTS scope or transaction certificate | None found. Copy rule in use: "made with GOTS-certified organic cotton fabrics". |
| Product liability insurance | Not started; ticket says "Required before first sale" |
| Georgia sales tax | Registered with GA DOR Mar 27 (Gmail). At least two portal letters unread (Oct 6, Oct 22); contents unknown. Shopify tax setup ticket not started. |
| Trademark (Class 25) | Ticket says both "filed May 23" and "saved to drafts"; no serial number |
| LLC operating agreement | Generated May 23, awaiting signature |
| Store legal pages | Blocked |

## 8. Existing systems and prior agent work

- **Notion:** "JSO Launch Command Center" (last real update Aug 6) with four department ticket databases: 157 tickets, 19 done, every open one past due. "JSO Agent Pilot" (set up Nov 12) with an Operations Manager weekly review, a Sales & Inventory review (blocked) and a Content & Email draft pack. Its run log lives under "## Run log" on the Agent Pilot home page. Canonical task list: "JSO Active Launch Tasks" (10 tasks).
- **Drive:** an earlier "AI PM Operating Charter v2" (its standing constraints are carried into `CLAUDE.md`), a Black Friday planning package dated Oct 22, LiftFund budget and business plans, finance tracker, Kickstarter exports, brand guidelines.
- **House copy rules (Notion):** say "sleeper" not "romper"; no "non-toxic", "chemical-free", "hypoallergenic", "eczema-safe"; no child names; no em dashes; "made with GOTS-certified organic cotton fabrics".
- **Locked decisions on record:** prices locked May 23 (bodysuit $18, sleeper $32). Shopify today shows the bodysuit at $24. An Oct 22 working paper proposes holiday prices of $19 and $26. These three disagree and need one owner decision.

## 9. Connected tools (this session)

| Tool | State |
|---|---|
| Shopify | Working (read and write) |
| Klaviyo | Working |
| Notion, Gmail, Google Drive, Google Calendar | Working |
| GitHub | Working (this repo only) |
| Canva, Higgsfield, Airtable, Netlify | Connected, not used yet |
| QuickBooks | Needs the owner to sign in again |
| Windsor.ai (Instagram, Meta Ads, GA4, TikTok) | Connected but no accounts linked, so no social or ad data |
| Live storefront from this environment | Blocked by the environment's network settings |
