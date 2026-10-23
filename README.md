# Paywall Audit — BetterSleep

**Live:** https://bterzic123.github.io/bettersleep-paywall-audit/

Prepared for the BetterSleep team by Adapty. Four ranked paywall ideas, each backed by a number from
State of Paywalls 2026, and a clickable rebuild of the BetterSleep paywall and what happens when
someone cancels Apple's purchase sheet (Today / Proposed).

## The ideas

| # | Idea | Report anchor | Potential outcome |
| :-- | :-- | :-- | :-- |
| 1 | Turn “Transaction canceled” into a second chance | 4.5: only 4% of apps show a second paywall after close; it converts at 0.88× the main one and beats it in 45% of apps | ARPU +10–15% (based on Adapty data) |
| 2 | Show how the 7 free nights work | 3.4: 24% of trial paywalls show a timeline; 5.2: trial changes win 60% of LTV tests | ARPU +12–36% (observed in winning A/B tests) |
| 3 | Answer their quiz in the headline | 3.5: only 2% of top paywalls personalize the headline | CR +8–17% (observed in winning A/B tests) |
| 4 | Bring your proof onto the paywall | 3.1: only 27% of top paywalls show social proof; 3.4: 20% of trial paywalls show awards or press | CR +10–30% (observed in winning A/B tests) |

**Benchmark slice:** Health & Fitness (App Store category), US (biggest storefront by ratings).
App Store data, Oct 2025–Sep 2026.

**Full report:** [State of Paywalls 2026](https://adapty.io/state-of-paywalls/?utm_source=paywall-audit&utm_medium=github-pages&utm_campaign=sop_2026&utm_content=bettersleep)

## Grounding

Every price, rating and claim on the page comes from BetterSleep's own App Store listing and in-app
screens: the yearly price of 59,99 € and the 7-day trial on the store sheet, 4.7 from 391K
ratings on the US App Store, App of the Day and 65M+ users from the onboarding. No discount is shown,
because BetterSleep does not publish one. Impact ranges are observed lifts from winning A/B tests in
State of Paywalls 2026 and Adapty's own data, not measured results for BetterSleep.

## Run locally

```
python3 -m http.server 8000
```

Add `?open=proto` to open on the prototype.
