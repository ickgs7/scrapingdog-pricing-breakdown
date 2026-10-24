# scrapingdog pricing：Every Plan and Credit Cost Explained, and How It Stacks Up Against ScraperAPI

Scrapingdog's pricing starts at a free tier with 100 credits, then jumps to **$40/month for the Lite plan** with 200,000 credits and 5 concurrent requests. Above that, Standard runs $90 for 1 million credits, Pro $200 for 3 million, and the ladder keeps climbing to Business Plus at $1,000 for 19 million credits — with more than twenty additional high-volume tiers stretching up to $30,000/month for 1.1 billion credits.

That's the headline. But if you're comparing it against other scraping APIs before committing, the sticker price only tells half the story, because both Scrapingdog and every serious competitor bill in credits, and what one credit actually buys differs a lot between platforms. This breakdown covers every published Scrapingdog tier, how its credit system behaves once you start scraping, the annual billing math, and a side-by-side look at one of its main competitors, ScraperAPI, so you can see where each one wins.

> **Quick take:** If you need roughly 1 million credits a month with 50 concurrent requests, Scrapingdog's Standard plan at $90 is the entry point — and its annual billing works out to 10 months for 12. If you'd rather test before paying anything, ScraperAPI gives new accounts 1,000 free credits a month plus a 7-day trial with 5,000 credits, no card required. 👉 [see ScraperAPI's current plans and trial options](https://www.scraperapi.com/pricing?fp_ref=coupons)

## Scrapingdog's full plan list

Scrapingdog publishes its tiers openly, and the structure is simple: every paid plan unlocks all 40+ APIs, and the only things that change as you go up are credits and concurrency. Here are the tiers you'll actually be choosing between at the start:

| Plan | Monthly price | Credits | Concurrency | Support |
| --- | --- | --- | --- | --- |
| Free | $0 | 100 | 1 | Community |
| Lite | $40 | 200,000 | 5 | Email |
| Standard | $90 | 1,000,000 | 50 | Priority email |
| Pro | $200 | 3,000,000 | 100 | Priority email + team |
| Premium | $350 | 6,000,000 | 150 | Priority email + team |
| Business | $500 | 9,000,000 | 200 | Priority email + team |
| Business Plus | $1,000 | 19,000,000 | 250 | Priority email + team |

Beyond Business Plus, the published ladder continues in fixed steps — a Business Pro tier at 90 million credits with 500 concurrency, Enterprise Plus at 120 million, and eventually NOVA PRO at $30,000/month for 1.1 billion credits and 2,200 concurrent requests. From the Enterprise tier upward you also get a dedicated account manager. For most readers searching for scrapingdog pricing, though, the real decision lives between Lite and Pro.

Two things worth knowing about the free plan. First, the 100 credits are a starting allowance, not a monthly renewal — it's meant to let you test the service end to end before picking a tier. Second, there's no credit card required, so trying it costs nothing but a signup.

## What one credit actually buys on Scrapingdog

Scrapingdog's credits are shared across every API on your plan, and here's the detail that flat "per-request" marketing numbers hide: each API has its own credit cost, published in their documentation. A Google Search request and an Amazon request don't drain your balance at the same rate.

The company is upfront about this — the full per-API cost list lives in their docs, not the pricing page. So when you're doing the math on whether 200,000 credits is enough, multiply your expected request mix by the right per-API rate, not by 1.

Three billing rules work in your favor:

- **Failed, blocked, and timed-out requests are automatically credited back.** You only pay for data you successfully receive. On a plan like Lite where you're hitting sites that might block you, this matters more than a dollar or two of list price.
- **Over-limit behavior is a hard stop, not a surprise bill.** Once credits run out, API requests return an over-limit response until the balance resets on your next billing date. Nothing gets charged behind your back.
- **Upgrades take effect immediately.** Change plans from the dashboard and new credits are available right away. On an upgrade, unused credits roll over to the new plan; on a downgrade, they reset to the new plan's allowance — the FAQ is explicit that neither direction is prorated.

## Annual billing: the "2 months free" math

Scrapingdog prices annual billing at ten months for twelve — effectively two months free on every plan, which works out to about a 16.7% discount. Toggle the Monthly/Annual switch on their pricing page and each tier drops accordingly: Lite effectively becomes about $33.33/month, Standard about $75, Pro about $166.67.

That's a slightly better annual discount than what ScraperAPI offers (a flat 10% off), worth factoring in if you're committing for a year either way.

## ScraperAPI: the full plan table, for comparison

Since you're likely pricing Scrapingdog against alternatives, here's ScraperAPI's entire published plan structure. Every paid plan includes the same feature set — JavaScript rendering, premium residential and mobile IPs, CAPTCHA and anti-bot bypass, structured data endpoints, DataPipeline, crawler access, and unlimited bandwidth — so the tiers differ only in credits, concurrency, and geotargeting precision.

| Plan | Monthly price | Annual (per month) | Credits | Concurrency | Link |
| --- | --- | --- | --- | --- | --- |
| Free | $0 | — | 1,000/month | 5 | [ Try the free plan](https://www.scraperapi.com/pricing?fp_ref=coupons) |
| Hobby | $49 | $44.10 | 100,000 | 20 | [ Start with Hobby](https://www.scraperapi.com/pricing?fp_ref=coupons) |
| Startup | $149 | $134.10 | 1,000,000 | 50 | [ View Startup](https://www.scraperapi.com/pricing?fp_ref=coupons) |
| Business | $299 | $269.10 | 3,000,000 | 100 | [ View Business](https://www.scraperapi.com/pricing?fp_ref=coupons) |
| Scaling | $475 | $427.50 | 5,000,000 | 200 | [ View Scaling](https://www.scraperapi.com/pricing?fp_ref=coupons) |
| Professional | $975 | $877.50 | 10,500,000 | 300 | [ View Professional](https://www.scraperapi.com/pricing?fp_ref=coupons) |
| Advanced | $1,975 | $1,777.50 | 21,500,000 | 500 | [ View Advanced](https://www.scraperapi.com/pricing?fp_ref=coupons) |
| Enterprise | Custom | — | 22,000,000+ | 500+ | [ Talk to sales](https://www.scraperapi.com/pricing?fp_ref=coupons) |

New accounts get a 7-day trial with 5,000 credits on top of the free plan, no credit card needed — one review of the service notes it also comes with a 7-day no-questions-asked refund on paid plans, so the trial window carries into a paid month. 👉 [start the 7-day trial with 5,000 free credits](https://www.scraperapi.com/pricing?fp_ref=coupons)

## Which one is actually cheaper for your workload

Here's where the comparison gets interesting, because the two platforms price the same-size workload differently.

At the 1-million-credit level, Scrapingdog's Standard plan costs $90 with 50 concurrency; ScraperAPI's equivalent Startup plan costs $149, also at 50 concurrency. Drop to per-credit terms and Scrapingdog is running about $0.09 per thousand credits against ScraperAPI's $0.149 — Scrapingdog is roughly 40% cheaper at that tier.

| Monthly volume | Scrapingdog option | Scrapingdog cost | ScraperAPI option | ScraperAPI cost |
| --- | --- | --- | --- | --- |
| ~100k credits | Lite | $40 | Hobby | $49 |
| ~1M credits | Standard | $90 | Startup | $149 |
| ~3M credits | Pro | $200 | Business | $299 |
| ~5M credits | Premium | $350 | Scaling | $475 |

Scrapingdog's own comparison content puts its Premium tier at $0.058 per 1,000 credits against ScraperAPI's Scaling at $0.095 — and the arithmetic checks out from the official list prices, though it's worth remembering the source is the vendor itself.

Where ScraperAPI pushes back is on what a credit does. Its credit costs are published and stackable: a standard page costs 1 credit, Amazon 5, Google and Bing 25, LinkedIn 30, and protected domains (Cloudflare, Datadome, PerimeterX) add 10 credits per request when bypassed — third-party reviewers have documented cases reaching 75 credits for a single hard request. Scrapingdog also varies credit costs per API; the difference is that its "failed requests refunded" policy and generally lower list prices soften the blow.

One structural difference worth flagging: geotargeting. Scrapingdog includes geotargeting on all its paid plans from Lite up. ScraperAPI restricts it to US and EU regions until you reach Business ($299/month), where country-level targeting unlocks. If your targets need non-US/EU locations and your budget is under $300, that's a real constraint on the ScraperAPI side.

## Limits neither pricing page leads with

A few operational details sit in FAQs and help docs rather than pricing tables, and they change how the plans behave in practice:

- **What happens at over-limit.** Scrapingdog hard-stops with an over-limit response until your billing date resets. ScraperAPI also pauses by default, but gives you two opt-in escape hatches: auto-upgrade (on Hobby through Professional, your account moves to the next plan automatically when credits run out) and pay-as-you-go (on Scaling and above, you keep scraping at a fixed per-credit rate under a monthly cap you set). If your scraping volume spikes unpredictably, that flexibility is worth something.
- **Concurrency overruns cost nothing but patience.** ScraperAPI returns a 429 and asks you to retry within your plan's limit — no queueing, no extra charge. Scrapingdog's concurrency caps similarly just gate throughput; going over doesn't bill you extra.
- **Unused credits don't roll over month to month on either platform.** ScraperAPI's credits reset at renewal, and Scrapingdog resets at the billing date — the only rollover is when you upgrade plans mid-cycle.
- **Concurrency is the hidden lever.** Scrapingdog's Standard tier gives 50 concurrent requests for $90, while the same concurrency on ScraperAPI costs $149 (Startup). If you're running parallel jobs, concurrency-per-dollar often matters more than credits-per-dollar.

## FAQ

**Does Scrapingdog have a free plan?**
Yes — 100 free credits with 1 concurrency and full API access, no credit card required. It's a starting balance for testing rather than a renewable monthly allowance.

**Is Scrapingdog's "$0.0002 per request" the real price?**
Not reliably. That figure only holds for standard 1-credit requests on a high-volume plan; each API has its own credit cost, and harder targets consume more. Price your workload against the per-API credit list, not the marketing number.

**Which platform is better for anti-bot-heavy targets?**
Both charge premium rates for protected domains. Independent tests of ScraperAPI's bypass rates on systems like Akamai, DataDome, and PerimeterX have shown low single-digit to low double-digit success percentages — but those figures come from a competing provider's own comparison page, so treat them as one data point rather than settled fact. If most of your targets sit behind heavy bot protection, run a trial on whichever platform you're considering before buying a year of credits.

**Can I change plans later?**
Yes, on both. Scrapingdog lets you upgrade or downgrade anytime (upgrades roll over unused credits, downgrades reset them, neither is prorated). ScraperAPI allows plan changes anytime from the billing page, with auto-upgrade and pay-as-you-go as additional buffers on higher tiers.

## Where to put your money

The decision breaks down cleanly by workload:

- **Mostly plain HTML pages, predictable volume, tight budget** → Scrapingdog's Lite at $40 (200k credits) or Standard at $90 (1M credits) is the cheaper entry, with failed requests refunded on top.
- **Mixed workload with lots of Google/LinkedIn/Amazon endpoints** → per-credit costs will dominate either way; ScraperAPI's Domain Cost Estimator lets you price any URL before you commit, and its structured data endpoints may save you parsing work that offsets the higher list price.
- **Spiky, hard-to-predict volume** → ScraperAPI's pay-as-you-go and auto-upgrade options mean a busy month doesn't stall your pipeline the way a hard over-limit stop does.
- **Just experimenting** → both free tiers cost nothing. ScraperAPI's is simply bigger (1,000 monthly credits plus a 5,000-credit trial vs. 100 one-time), which makes it the better sandbox before you spend anything.

Before you pay for anything, do one thing: take your five most-scraped URLs and check their actual credit cost on whichever platform you pick. The list price comparison above assumes a standard page; your real cost depends on your targets. When you're ready to commit, 👉 [open ScraperAPI's pricing page and pick your plan](https://www.scraperapi.com/pricing?fp_ref=coupons) — the 7-day trial means you can verify the math on your own workload before the first charge lands.
