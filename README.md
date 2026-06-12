# The Rundown (therundown)

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
