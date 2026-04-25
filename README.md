# Awesome Revenue Algorithms

> Curated list of algorithms, libraries, frameworks, and **battle-tested techniques** for monetization optimization, dynamic pricing, revenue management, churn reduction, upsell/cross-sell, and systems that drive real business impact.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![GitHub stars](https://img.shields.io/github/stars/IainAmosMelchizedek/awesome-revenue-algorithms)

## Table of Contents

- [Dynamic / Algorithmic Pricing](#dynamic--algorithmic-pricing)
- [Revenue Management & Yield Optimization](#revenue-management--yield-optimization)
- [Recommendation & Personalization Engines](#recommendation--personalization-engines)
- [Churn Prediction & Retention Optimization](#churn-prediction--retention-optimization)
- [A/B Testing & Experimentation](#ab-testing--experimentation)
- [General Optimization Libraries](#general-optimization-libraries)
- [Papers & Case Studies](#papers--case-studies)
- [Contributing](#contributing)

## Dynamic / Algorithmic Pricing

### Core Techniques & Battle-Tested Examples
- **Greedy Pricing Heuristics** — Simple, fast, interpretable rules with proven revenue lift in production.  
  *Example (Murphy Street)*: Used a greedy algorithm to optimize pricing decisions that increased monetization. (Full details and code example coming in next steps)
- Contextual Bandits (LinUCB, Thompson Sampling) for personalized real-time pricing
- Dynamic Programming / Revenue Management models (classic airline/hotel yield management adapted to SaaS and e-commerce)

### Libraries (by language)

**Python**
- [PuLP](https://coin-or.github.io/pulp/) — Linear programming for price optimization
- [Pyomo](https://www.pyomo.org/) — Modeling optimization problems
- [Nevergrad](https://facebookresearch.github.io/nevergrad/) — Derivative-free optimization (great for pricing experiments)
- [scikit-learn](https://scikit-learn.org/) — For churn prediction and recommendation systems tied to monetization

**JavaScript / TypeScript**
- [ml.js](https://github.com/mljs/ml) — Lightweight ML for browser-based pricing models

*(More languages and tools will be added)*

## General Optimization Libraries
- [OR-Tools](https://developers.google.com/optimization) — Google's powerful optimization suite
- [Gurobi](https://www.gurobi.com/) — High-performance commercial solver (excellent for large-scale revenue problems)

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) — high-signal, revenue-impact focused additions welcome.

## License

[CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) — Public domain.
