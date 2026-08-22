# The Rundown (therundown)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The Rundown is a sports betting data API platform providing real-time odds, lines, scores, and results across 30+ sports leagues including NFL, NBA, MLB, NHL, WNBA, MLS, college football and basketball, and international soccer, tennis, cricket, and Formula 1. The API aggregates data from 16+ sportsbooks including DraftKings, FanDuel, BetMGM, and Pinnacle, as well as prediction markets like Kalshi and Polymarket, normalizing everything into a single unified schema with 600+ market types. Developers can access data via REST endpoints or WebSocket streaming for sub-second real-time updates, with historical odds data and line movement tracking available on higher tiers.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/therundown/refs/heads/main/apis.yml
- Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=therundown-api-evangelist&utm_content=repo

## Tags

Sports, Betting, Odds, NFL, NBA, MLB, NHL, Soccer, Real-Time, Sports Data, Sportsbook

## APIs

### TheRundown Sports Odds API

RESTful API providing real-time sports betting odds, lines, scores, schedules, team stats, and player props from 16+ sportsbooks normalized into a single schema. Supports 600+ market types across 30+ leagues including NFL, NBA, MLB, NHL, college sports, and international competitions. Also offers WebSocket streaming for sub-second updates and historical line movement data on higher-tier plans.

- Human URL: https://therundown.io/api
- Base URL: https://therundown.io/api/v2

## Plans / Rate Limits / FinOps

| Plan | Price | Data Points | Rate Limit | Delay |
|------|-------|-------------|-----------|-------|
| Free | $0/mo | 20K/day | 1 req/sec | 5 min |
| Starter | $49/mo | 5M/mo | 2 req/sec | 60 sec |
| Pro | $149/mo | 25M/mo | 5 req/sec | 30 sec |
| Ultra | $399/mo | 100M/mo | 10 req/sec | Real-time |
| Super | $649/mo | 250M/mo | 15 req/sec | Real-time |
| Mega | $999/mo | 500M/mo | 20 req/sec | Real-time |
| Max | $2,499/mo | 2.5B/mo | 50 req/sec | Real-time |
| Enterprise | Custom | Custom | Custom | Real-time |

- Plans: [plans/therundown-plans-pricing.yml](plans/therundown-plans-pricing.yml)
- Rate Limits: [rate-limits/therundown-rate-limits.yml](rate-limits/therundown-rate-limits.yml)
- FinOps: [finops/therundown-finops.yml](finops/therundown-finops.yml)

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common

| Type | URL |
|------|-----|
| Website | https://therundown.io |
| Documentation | https://docs.therundown.io/introduction |
| GitHub Org | https://github.com/TheRundown |
| LinkedIn | https://www.linkedin.com/company/therundowninc |
| Blog | https://blog.therundown.io |
| Pricing | https://therundown.io/pricing/api |
| Status Page | https://therundown.instatus.com/ |
| X | https://x.com/therundownio |

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
