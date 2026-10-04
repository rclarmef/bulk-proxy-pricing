# buy bulk proxies: how to compare per-IP vs per-GB pricing, size your order, and stop paying for traffic you never use

Bulk proxy buying is a unit-conversion problem before it is anything else. Two vendors can both advertise cheap residential IPs and still bill you wildly different amounts for the same week of work, because one sells addresses and the other sells gigabytes. Pick the wrong unit on a 50,000-IP order and you have handed over four figures for headroom you will never touch.

9Proxy is a decent case study for this, mostly because it sells both units from one dashboard. Per-IP packages come with unlimited bandwidth, per-GB packages are metered, and the bundles mix the two. The published ladder runs from 100 IPs at $24 up to 500,000 IPs at $8,625, with 20M+ residential IPs across 90+ countries behind it, so it covers the range where bulk buyers actually operate.

## Every 9Proxy package on the pricing page right now

Here is the whole board, including the tiers most reviews skip because they are too big for a casual user. Prices are in USD.

| Package | What you get | Price | Validity / billing | Purchase |
| --- | --- | --- | --- | --- |
| 100 IPs | 100 residential IPs, unlimited bandwidth each | $24 ($0.24/IP) | Balance-based, IPs don't expire | [Buy 100 IPs](https://bit.ly/9-Proxy) |
| 500 IPs | As above | $72 ($0.144/IP) | IPs don't expire | [Buy 500 IPs](https://bit.ly/9-Proxy) |
| 1,000 IPs + 500 bonus | 1,500 residential IPs total | $126 ($0.084/IP) | IPs don't expire | [Buy the 1,000 IP pack](https://bit.ly/9-Proxy) |
| 2,500 IPs | 2,500 residential IPs | $210 ($0.084/IP) | IPs don't expire | [Buy 2,500 IPs](https://bit.ly/9-Proxy) |
| 5,000 IPs | 5,000 residential IPs | $360 ($0.072/IP) | IPs don't expire | [Buy 5,000 IPs](https://bit.ly/9-Proxy) |
| 15,000 IPs | 15,000 residential IPs | $720 ($0.048/IP) | IPs don't expire | [Buy 15,000 IPs](https://bit.ly/9-Proxy) |
| 25,000 IPs | 25,000 residential IPs | ≈$863 (≈$0.035/IP) | IPs don't expire | [Buy 25,000 IPs](https://bit.ly/9-Proxy) |
| 50,000 IPs | 50,000 residential IPs | ≈$1,438 (≈$0.029/IP) | IPs don't expire | [Buy 50,000 IPs](https://bit.ly/9-Proxy) |
| 100,000 IPs (Business) | 100,000 residential IPs | $2,300 ($0.023/IP) | IPs don't expire | [Buy 100,000 IPs](https://bit.ly/9-Proxy) |
| 200,000 IPs (Business) | 200,000 residential IPs | ≈$4,140 (≈$0.021/IP) | IPs don't expire | [Buy 200,000 IPs](https://bit.ly/9-Proxy) |
| 500,000 IPs (Business) | 500,000 residential IPs | $8,625 ($0.018/IP) | IPs don't expire | [Buy 500,000 IPs](https://bit.ly/9-Proxy) |
| 5 GB | Traffic balance, unlimited endpoints, sticky or rotating | $15 ($3.00/GB) | 180 days | [Buy 5 GB](https://bit.ly/9-Proxy) |
| 50 GB + 5 GB bonus | 55 GB traffic | $105 ($2.10/GB) | 180 days | [Buy the 50 GB pack](https://bit.ly/9-Proxy) |
| 100 GB | 100 GB traffic | $150 ($1.50/GB) | 180 days | [Buy 100 GB](https://bit.ly/9-Proxy) |
| 200 GB | 200 GB traffic | $200 ($1.00/GB) | 180 days | [Buy 200 GB](https://bit.ly/9-Proxy) |
| 1,000 GB | 1,000 GB traffic | $800 ($0.80/GB) | 180 days | [Buy 1,000 GB](https://bit.ly/9-Proxy) |
| 2,000 GB | 2,000 GB traffic | $1,500 ($0.75/GB) | 180 days | [Buy 2,000 GB](https://bit.ly/9-Proxy) |
| ≈10,000 GB | 10,000 GB traffic | ≈$6,800 ($0.68/GB) | 180 days | [Buy the 10,000 GB tier](https://bit.ly/9-Proxy) |
| Starter bundle | 100 IPs + 5 GB | $30 | IPs don't expire, traffic 180 days | [Buy the Starter bundle](https://bit.ly/9-Proxy) |
| Popular bundle | 1,500 IPs + 50 GB | $180 | IPs don't expire, traffic 180 days | [Buy the Popular bundle](https://bit.ly/9-Proxy) |
| Pro bundle | 5,000 IPs + 500 GB | $720 | IPs don't expire, traffic 180 days | [Buy the Pro bundle](https://bit.ly/9-Proxy) |
| Enterprise (GB) | High-volume traffic, unlimited validity, team mode (1 owner + 5 members), per-member traffic controls | Price on request (VIP pricing) | Unlimited | [Request Enterprise pricing](https://bit.ly/9-Proxy) |

Two things about that list. First, IP-based and bundle prices went up on 1 June 2026 — the first adjustment in the company's history — while GB packages were left untouched. Second, the rows marked ≈ come from published 2026 price tables rather than a screenshot I can hand you, so if you are about to spend four or five figures, confirm the exact number on the live pricing page before you check out.

## Per-IP or per-GB: which side of the fence your workload sits on

The two models behave nothing alike, and the difference is not marketing fluff.

|  | Residential by IP | Residential by GB |
| --- | --- | --- |
| What you buy | a fixed number of addresses | a traffic balance |
| Bandwidth | unlimited per IP while it's live | metered, every byte counts |
| Rotation | generate endpoints, rotate at set intervals | rotate per request or hold a sticky session |
| Shelf life | IPs sit in your balance and never expire; an individual IP stays live from a few hours to about 24h | 180 days, unlimited on Enterprise |
| Best fit | few addresses, heavy traffic, long sessions | many addresses, light traffic, high rotation |
| Where it wastes money | buying IPs you barely use | heavy pages at per-GB rates |

A quick piece of arithmetic to show why the unit matters more than the headline rate. Say your job pushes 5 GB through each of 100 addresses. That's 500 GB of traffic. Bought as bandwidth at the $1.50/GB tier, 500 GB costs $750. Bought as 100 IPs with unlimited bandwidth, it costs $24. Now flip the scenario: 100 GB spread across thousands of rotating addresses. On the GB model that's $150, and you never think about how many IPs you burned. On the per-IP model you would be paying for addresses that see a handful of requests each before they drop.

Neither example is a benchmark result, just how the pricing structures behave. If your traffic is unpredictable or your pages are fat, unlimited bandwidth per IP is the cheaper shape. If your traffic is thin but your IP count is enormous, buy gigabytes.

## Where the bulk discount actually comes from

The spread on the IP ladder is roughly 13x: $0.24 per IP at 100 addresses down to $0.018 at 500,000. Most of that fall happens early. Going from 100 to 500 IPs cuts your per-IP cost by 40%, and the 1,000-IP tier throws in 500 bonus IPs, which is why it lands at $0.084. Past 15,000 IPs each step saves cents rather than dollars, and you need a real reason — a reseller operation, a platform-level workload — to be shopping up there.

The GB ladder behaves the same way but flatter. $3.00/GB at the 5 GB entry point, $1.00/GB at 200 GB, and $0.68/GB at the top. If you only need a few gigs for testing, do not buy 200 GB to chase the better rate; the 180-day clock starts the moment you pay, and unused gigabytes are the one thing on this pricing page that genuinely turns into dust.

## Bundles: cheaper than buying the two pieces separately

The bundle math is straightforward once you have the individual prices.

- Starter: $30 for 100 IPs + 5 GB. Bought separately, 100 IPs ($24) plus 5 GB ($15) is $39.
- Pro: $720 for 5,000 IPs + 500 GB. Separately, 5,000 IPs ($360) plus 500 GB at $1.50/GB ($750) is $1,110.

That gap is the whole pitch. Bundles suit mixed workloads where some tasks need a stable address for hours and others just need to rotate cheaply, and they keep both balances in one account instead of forcing you to guess the split in advance.

## Five checks before you wire a four-figure amount

**Expiry asymmetry.** IP-based purchases never expire. GB purchases do, at 180 days, unless you are on Enterprise. On a large bandwidth order you are buying a deadline, not just data.

**Replacement policy.** 9Proxy documents an auto-refresh that detects and replaces offline IPs within about 60 seconds rather than charging you again, plus a "Today List" feature that lets you reuse addresses from the previous 24 hours at no extra cost. Worth verifying in your own workflow, but it matters on bulk orders where a handful of dead IPs can stall a queue.

**Protocol and tool support.** HTTP/HTTPS and SOCKS5. Anti-detect browsers and most automation tools take host:port:user:pass, so there is no protocol conversion to fight with.

**Targeting depth.** Country, state, city, ZIP, and ISP level. ISP-level targeting is the difference between "a Los Angeles IP" and "an AT&T Los Angeles IP", and it is usually what separates a working geo-check from a failed one.

**Payment and access.** Cards, crypto (USDT, BTC, ETH, LTC, DOGE), bank cards, Alipay, Apple Pay, Google Pay, plus local payment options. Access runs through a Windows client that routes traffic at the OS layer, a browser-based Proxy2Web option, a public API, and sub-accounts for teams.

One more, specific to this vendor: the invite code on the sign-up link takes 5% off your purchases. On a $2,300 order that is real money, and it applies to later orders too.

## How to place the order

1. 👉 [Create your account with the invite code already attached](https://bit.ly/9-Proxy) so the discount applies from the first purchase.
2. Pick your model — by IP, by GB, or a bundle — and choose the package size. There is no subscription; you top up a balance.
3. Open the Proxy Generator in the dashboard. Choose authentication (username/password or IP whitelisting), select country, state, city, ZIP or ISP, pick sticky or rotating sessions, and export endpoints as .txt or .csv. Ready-made code samples are included.
4. Drop the credentials into whatever is making the requests.

## Questions that come up before a large order

**Do unused IPs expire?** No. They sit in your balance until you forward them. Individual IPs do have a natural lifespan once active, anywhere from a few hours to about 24 hours.

**How long do gigabytes last?** 180 days for standard GB packages, unlimited on Enterprise.

**What is the smallest order?** 100 IPs at $24, or 5 GB at $15. You do not have to commit to volume to test the network.

**Can I resell?** Reseller and Share Code arrangements exist, and wholesale pricing is available on request through 9Proxy's own reseller materials. That is the audience for the 100,000+ IP tiers.

**Is there a trial?** 9Proxy has periodically handed out trial packages to new users depending on availability. Ask support before you assume one is on the table.

**How is support handled?** 24/7 across Telegram, email, and a ticket system, which is not nothing when a bulk order misbehaves at 3am.

## The short version

If your jobs keep a small number of addresses busy, buy IPs — the 100-IP pack at $24 with unlimited bandwidth is close to impossible to beat on cost per gigabyte, and nothing expires. If your jobs spray thin requests across thousands of addresses, buy gigabytes and start at 100 GB rather than the 5 GB tier. If you genuinely do both, the Starter bundle at $30 costs less than its parts and gives you an account that can do either.

The expensive mistake in bulk proxy buying is not picking the wrong vendor. It is buying 200 GB when you needed 20, or 50,000 IPs when 5,000 would have carried the same load. 👉 [Check the current package ladder, apply the invite code, and buy only the size you actually have work for](https://bit.ly/9-Proxy).
