# Hunter Energy Analytics — NSW SME Electricity Dashboard

**Live demo:** [imakshat96.github.io/hunter-energy-analytics-dashboard](https://imakshat96.github.io/hunter-energy-analytics-dashboard)

---

## Why I built this

I work in energy analytics in Newcastle, NSW. Every week I see small businesses — cafes, bakeries, restaurants — paying electricity bills they don't fully understand, on plans they've never reviewed.

NSW small businesses pay among the highest electricity bills in Australia. Most are on default standing offers — the most expensive plans available — and many don't know their tariff type or whether a better option exists.

This dashboard pulls together publicly available data to show the scale of the problem locally. It's the first piece of a broader project: **Hunter Energy Analytics**, focused on helping Hunter Valley businesses understand and reduce their energy costs.

---

## What the dashboard shows

- Average annual SME electricity bills by state (NSW vs national)
- NSW electricity generation mix in 2024
- Potential savings available from switching to a competitive market offer
- The Hunter Transmission Project and what it means for local businesses.

---

## Data sources

All data is publicly available and cited in `data.js`:

| Stat | Source |
|------|--------|
| SME annual bills by state | [Energy Consumers Australia — SME Retail Tariff Tracker, June 2024](https://energyconsumersaustralia.com.au/projects/retail-tariff-tracker) |
| NSW price rise July 2025 | [PSC Energy / energy.gov.au](https://www.pscenergy.com.au/blog/nsw-energy-prices-up-feed-in-tariffs-down-is-it-time-to-add-a-battery-in-2025/) |
| 25% savings — market vs standing offer | [AER reference price data via comparable.com.au](https://comparable.com.au/energy/cheapest-electricity-providers-nsw-2025/) |
| NSW generation mix 2024 | [Australian Energy Statistics, energy.gov.au](https://www.energy.gov.au/publications/australian-energy-statistics-table-o-electricity-generation-fuel-type-2023-24-and-2024) |
| Hunter Transmission Project | [EnergyCo NSW (Nov 2023)](https://www.energyco.nsw.gov.au) |

---

## Tech stack

Built with zero frameworks — just HTML, CSS, and [Chart.js](https://www.chartjs.org/). One `index.html` file, one `data.js` file. Deployable on GitHub Pages in under 2 minutes.

---

## How to deploy on GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your dashboard will be live at `https://yourusername.github.io/repo-name`

---

## About Hunter Energy Analytics

Hunter Energy Analytics helps Newcastle and Hunter Valley businesses understand, analyse and reduce their electricity costs. Services include free bill reviews, tariff analysis, and energy strategy consulting.

📧 hello@hunterenergyanalytics.com.au
🌐 [hunterenergyanalytics.com.au](https://hunterenergyanalytics.com.au)

---

*Data last updated: May 2026*
