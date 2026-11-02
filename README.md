# us vps price: Real US VPS Costs Compared, the Renewal Math Most Sites Skip, and Where RackNerd's $21.99/Year KVM Plans Fit In

The short answer to what a US VPS costs: a usable entry-level server runs $2 to $12 a month, and the price you see on the homepage is rarely the price you'll pay in year two. Across 174 US hosting providers tracked in September 2026, the median entry price is $6.49/mo, and the median renewal climbs to $8.20/mo. That gap is where most "cheap VPS" searches actually go wrong.

There's one mainstream exception worth knowing upfront. RackNerd sells KVM VPS plans on annual billing starting at **$21.99/year**, which works out to about $1.83/month, and its official FAQ states these special plans renew at the same rate for as long as you keep the service. For a certain kind of buyer, that changes the whole math.

> **Quick take:** If you want the cheapest credible US VPS and can commit to a year, RackNerd's 1 GB KVM plan at $21.99/year (1 vCPU, 20 GB SSD, 3 TB traffic) is the lowest confirmed recurring price among the hosts covered here, and it doesn't jump on renewal. It's unmanaged and has no money-back guarantee, so it suits people comfortable running a Linux server themselves. 👉 [Check RackNerd's current VPS specials and locations](https://bit.ly/RacKnerd)

## What does a US VPS actually cost right now?

It depends on which of three price tiers you land in, and the differences are bigger than most comparison articles suggest.

At the very bottom, aggregate pricing trackers put the cheapest US VPS at $2/month (BuyVM's Slice 512, 1 vCPU / 512 MB / 10 GB SSD, as of November 2026). DigitalOcean starts its Basic Droplets at $4/month for 512 MB, $6 for 1 GB, and $12 for 2 GB, with renewal at the same rate. IONOS advertises plans from $2/month, and AlphaVPS sells a 2 GB / 30 GB NVMe plan at $2.90/month on a one-year term.

The mid-tier is where familiar names cluster. Hostinger runs $4.99–$19.99/month for the first 24 months. Hostwinds starts at $4.99 for the first billing cycle. Namecheap's yearly-billed VPS runs $6.88–$24.88/month. Liquid Web, which sells managed hosting, starts at $11/month billed yearly.

Two things skew these numbers, and neither shows up in the headline price:

1. **Renewal increases.** Many providers advertise a first-term discount, then bill a higher rate from year two. GoDaddy's pricing applies "for the first three years." Hostinger's figure holds "for the first 24 months." If a site doesn't print a renewal price at all, that's usually the tell.
2. **Managed vs. unmanaged.** Liquid Web's $11+ includes managed service and a 100% uptime guarantee. RackNerd, DigitalOcean, and most hosts in the sub-$5 range are unmanaged: you get root access and a support channel, and everything on the server is your problem.

So when someone asks for a "US VPS price," the honest answer is: $2–$5/month gets you a small unmanaged Linux box from a budget specialist, $6–$12/month is the mainstream cloud tier, and managed hosting starts around $11 and climbs.

## RackNerd's current plans and prices

RackNerd currently sells its KVM VPS line in two tracks: fixed-price annual specials and monthly-billed standard plans. Both include full root access, one IPv4 address, a 1Gbps port, KVM virtualization, and the ctrl control panel, and both deploy immediately after payment.

Here is the complete annual specials lineup as shown on the official specials page:

| Plan | vCPU / RAM | SSD | Monthly transfer | Price (annual) | Order |
| --- | --- | --- | --- | --- | --- |
| 1 GB KVM VPS | 1 core / 1 GB | 20 GB | 3 TB | $21.99/yr | [ Order the 1 GB plan](https://my.racknerd.com/aff.php?aff=11397&pid=952) |
| 2 GB KVM VPS | 2 cores / 2 GB | 35 GB | 5 TB | $35.99/yr | [ Order the 2 GB plan](https://my.racknerd.com/aff.php?aff=11397&pid=953) |
| 4 GB KVM VPS | 3 cores / 4 GB | 60 GB | 7 TB | $59.99/yr | [ Order the 4 GB plan](https://my.racknerd.com/aff.php?aff=11397&pid=954) |
| 6 GB KVM VPS | 6 cores / 6 GB | 100 GB | 12 TB | $89.99/yr | [ Order the 6 GB plan](https://my.racknerd.com/aff.php?aff=11397&pid=955) |
| 8 GB KVM VPS | 7 cores / 8 GB | 150 GB | 20 TB | $119.99/yr | [ Order the 8 GB plan](https://my.racknerd.com/aff.php?aff=11397&pid=956) |

The monthly standard KVM line goes higher on resources and lets you pay as you go:

| Plan | vCPU / RAM | SSD | Monthly transfer | Price (monthly) |
| --- | --- | --- | --- | --- |
| 512 MB | 1 core / 512 MB | 30 GB | 500 GB | $26.99/yr |
| 1 GB Standard | 2 cores / 1 GB | 50 GB | 1 TB | $17.99/mo |
| 2 GB Standard | 3 cores / 2 GB | 75 GB | 2 TB | $20.59/mo |
| 4 GB Standard | 4 cores / 4 GB | 130 GB | 3 TB | $24.59/mo |
| 6 GB Standard | 5 cores / 6 GB | 170 GB | 4 TB | $27.59/mo |
| 8 GB Standard | 6 cores / 8 GB | 220 GB | 5 TB | $36.59/mo |
| 12 GB Standard | 7 cores / 12 GB | 300 GB | 6 TB | $55.99/mo |

One pricing trap hides in that second table: the 512 MB plan costs $26.99 **per year** for less RAM and less storage than the 1 GB special at $21.99/year. If you're entering at the bottom, the 1 GB special is simply the better buy. The 512 MB tier makes sense only if you specifically want the largest disk-to-RAM ratio for a one-off project.

## What a RackNerd plan costs you by year three

This is the part most comparison posts skip, and it's where RackNerd's model is genuinely different.

Most budget hosts use a teaser structure: a discounted first term, then a higher renewal. The industry median renewal for US VPS is $8.20/mo against a $6.49/mo entry price. RackNerd's official FAQ addresses this directly: the specials are "lifetime recurring," and you can renew at the same rate for as long as you keep the service. The annual price is the renewal price.

Run the three-year totals for the 1 GB special:

- **RackNerd 1 GB:** $21.99 × 3 = **$65.97** for three years
- **DigitalOcean 1 GB:** $6 × 36 = **$216** for three years
- **DigitalOcean 2 GB:** $12 × 36 = **$432** for three years

DigitalOcean's renewal stays flat too, to be fair, but its flat rate is roughly 3x the RackNerd equivalent on paper specs. Against providers that raise prices at renewal, the gap widens further.

The trade for that price is commitment. The specials are annual-only, you pay the full year upfront, and per RackNerd's knowledgebase there's **no money-back guarantee**; its terms of service treat payments as final, with refund requests handled case by case. Third-party reviews describe support as ticket-based with no phone or live chat, though several report replies within 20–30 minutes even at off hours. If there's any chance you'll need to bail within weeks, either start with the cheaper monthly standard line or accept that a $21.99 experiment is the most you're risking. 👉 [Lock in the 1 GB plan at $21.99/year](https://my.racknerd.com/aff.php?aff=11397&pid=952)

## How RackNerd's price compares to the big names

Here's the verified comparison, stripped of marketing. Note the refund column, because it matters more than a dollar or two of monthly price.

| Provider | Entry plan | Price | Billing | Refund policy |
| --- | --- | --- | --- | --- |
| RackNerd | 1 GB KVM special | ~$1.83/mo ($21.99/yr) | Annual | None stated; case-by-case |
| BuyVM | Slice 512 | $2/mo | Monthly | Not verified here |
| IONOS | Entry VPS | From $2/mo | Monthly | Not stated in source |
| DigitalOcean | Basic Droplet 512 MB | $4/mo | Monthly | No refund guarantee |
| AlphaVPS | C2G (2 GB / 30 GB NVMe) | $2.90/mo | 1-year term | 14-day refund |
| Hostwinds | Entry VPS | From $4.99 (first cycle) | Monthly | 3-day return policy |
| Hostinger | KVM 1 | $4.99/mo (first 24 months) | Multi-year upfront | 30-day money-back |
| Liquid Web | Entry managed VPS | $11/mo billed yearly | Annual | Managed, 100% uptime guarantee |

Where each one wins, plainly:

- **RackNerd** wins on committed annual cost. Nothing else in this table gives you 1 GB RAM, 3 TB of traffic, and a flat renewal at under $2/month equivalent.
- **DigitalOcean, IONOS, and BuyVM** win on flexibility: monthly billing, cancel anytime, no year of cash locked up. DigitalOcean also has the more mature developer ecosystem if you're building production apps.
- **AlphaVPS and Hostinger** are the picks if a refund window is non-negotiable. AlphaVPS gives 14 days, Hostinger 30.
- **Liquid Web** is a different product. If you want someone else handling server administration, its managed plans justify the higher floor.

RackNerd also runs about 20 datacenter locations, including Los Angeles, San Jose, Seattle, Dallas, Chicago, New York, Atlanta, Ashburn, and Tampa in the US, plus Toronto, Amsterdam, London, Dublin, Strasbourg, and Singapore internationally. For traffic to and from East Asia, Los Angeles is the relevant option; third-party latency tests in mid-2026 measured LA-to-Shanghai routes at roughly 150–170ms. That's fine for a proxy, a personal site, or a bot. It's not a Tokyo-grade low-latency route, and high-IOPS database workloads belong elsewhere.

## What the low price leaves out

Three limitations belong in any honest RackNerd price discussion, because they're the reasons the price is low.

**It's unmanaged.** You get root access, and RackNerd's team handles the hardware, network, and the host node. Installing software, securing the server, fixing a broken config after a bad apt upgrade: that's yours. If "SSH into a server and fix things" sounds unpleasant, the money saved won't feel worth it.

**The control panel is functional, not fancy.** The included ctrl panel covers reboot, OS reinstall, an HTML5 VNC console, firewall rules for inbound traffic, root password resets, and bandwidth graphs. One-click apps are included too, and they're the reason RAM matters in the plan you pick: OpenClaw needs at least 8 GB, Hermes Agent, AnythingLLM, Ollama, and LibreChat want 4 GB or more, and n8n or Coolify run comfortably from 2 GB. In other words, the 1 GB special runs a website or a proxy happily, but it can't host a local Ollama instance.

**Refunds aren't guaranteed.** Covered above, but it bears repeating near the checkout decision: annual specials are effectively final purchases. Small perks do soften the edges, like a free IPv4 replacement within the first 72 hours and up to 100 free IPv6 addresses in the Los Angeles and France locations on request.

## Which plan should you actually pick?

Match the plan to the workload instead of maxing out "just in case":

- **Personal site, blog, low-traffic proxy, VPN endpoint, small bot:** the 1 GB special at $21.99/year. Three TB of monthly transfer is more than most single-user projects will ever touch.
- **A couple of small services, a game server for friends, a self-hosted dashboard stack:** the 2 GB at $35.99/year or 4 GB at $59.99/year. The 4 GB tier also opens up the 4 GB one-click apps (Ollama, LibreChat, AnythingLLM).
- **Running n8n or Coolify:** 2 GB minimum per the official guidance; the 4 GB gives you headroom.
- **Trying out AI tooling on the server:** the 8 GB at $119.99/year is the entry point, since OpenClaw requires 8 GB. If that's a maybe rather than a plan, start cheaper and upgrade later; upgrades between special tiers are supported.
- **Need monthly flexibility or more than 8 GB:** the standard monthly line, from $17.99/mo (1 GB) up to $55.99/mo (12 GB).

## FAQ

**Does the $21.99/year price go up at renewal?**
No. RackNerd's FAQ states the specials are lifetime recurring and renew at the same rate for as long as you keep the service.

**Is RackNerd a real company?**
Yes. RackNerd LLC is based in Rancho Cucamonga, California, and has appeared on the Inc. 5000 list for multiple consecutive years, including 2024, 2025, and 2026.

**Can I install Windows?**
The special plans covered here are Linux KVM VPS with CentOS, Rocky Linux, AlmaLinux, Fedora, Debian, and Ubuntu available at order, plus custom ISO installs via a support ticket. Windows VPS is sold as a separate product line and wasn't part of this pricing verification.

**How do I pay?**
Payment options include PayPal, credit card, Alipay, UnionPay, and 30-plus cryptocurrencies, per third-party ordering guides.

**Is there a trial?**
No free trial and no money-back guarantee on the annual specials. The closest equivalent is the monthly standard line, which lets you test for a month before committing to a year.

## Before you click buy

Two checks will prevent most regrets. Confirm the datacenter location fits your users, since Los Angeles is the default recommendation for Asia-facing traffic and the US East locations serve American audiences better. And be sure you actually want a year of this server, because the annual special price is the deal, and it's also the commitment.

If both answers check out: running your own server for less than $2 a month is a legitimately good deal, and 👉 [RackNerd's order page](https://bit.ly/RacKnerd) will have you deployed within minutes of payment.
