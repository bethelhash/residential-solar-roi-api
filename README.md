# Residential Solar ROI API

**Complete solar investment analysis for any US address.**  
PVWatts V8 · NASA POWER MERRA-2 · 60+ real utility tariffs · NEM 3.0 modeled correctly · 25-year cashflow.

[![RapidAPI](https://img.shields.io/badge/RapidAPI-Subscribe-0055DA?style=flat-square)](https://rapidapi.com/bethelnedi/api/residential-solar-roi-api)
[![Demo](https://img.shields.io/badge/Live_Demo-SolarTruth-FFD21E?style=flat-square)](https://solartruth.vercel.app/)

## What Makes This Different

Every other solar ROI API gives you a number with no methodology. This implements:

- **PVWatts V8** (NREL/TP-6A20-62641) — the US Dept of Energy's own production model
- **NASA POWER MERRA-2** — 22-year satellite irradiance at exact coordinates (Pro)
- **60+ real utility tariffs** — actual tiered rates from EIA Form 861 (2023)
- **NEM 3.0 modeled correctly** — California's Apr 2023 net metering change, not the old rules
- **State incentives** — cited to their actual statutory source (IRS Form 5695, DSIRE 2024)

## Quick Start
```bash
curl -X POST https://residential-solar-roi-api.p.rapidapi.com/quick-estimate \
  -H "X-RapidAPI-Key: YOUR_KEY" \
  -H "Content-Type: application/json" \
  -d '{"zip_code": "90210", "monthly_bill_usd": 180}'
```

## NEM Policy Coverage
`NEM 1.0 Full Retail` (NY, FL, OR, CO, 20+ states) · `NEM 3.0 Avoided Cost` (California post Apr 2023) · `Net Billing` (AZ, NV, UT) · `No Net Metering` (TN, AL, MS)

## Plans
| Plan | Price | NASA Data | Cashflow |
|------|-------|-----------|---------|
| Free | $0/mo | No | No |
| Pro | $49/mo | Yes | 25-year |
| Bundle | $79/mo | Yes | Yield + Structural |

## Topics
`solar-roi` `pvwatts` `nasa-power` `nem-policy` `residential-solar` `solar-incentives` `npv-irr` `lcoe` `net-metering` `eia-utility-rates` `dsire` `solar-calculator` `fastapi` `python` `rapidapi`

---
