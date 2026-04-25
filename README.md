# Awesome Revenue Algorithms

> **Battle-tested algorithms, libraries, and techniques** that have **actually driven revenue** in production environments: dynamic pricing, monetization optimization, churn reduction, upsell/cross-sell, yield management, and more.

Unlike academic paper collections, this list focuses on tools and approaches with **clear business impact** — production usage, case studies, benchmarks, or proven revenue lift.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Table of Contents
- [Dynamic / Algorithmic Pricing](#dynamic--algorithmic-pricing)
- [Churn & Retention Optimization](#churn--retention-optimization)
- [Recommendation & Upsell](#recommendation--upsell)
- [General Optimization Libraries](#general-optimization-libraries)
- [Papers & Resources](#papers--resources)
- [Contributing](#contributing)

## Dynamic / Algorithmic Pricing

- **[PuLP](https://coin-or.github.io/pulp/)** — Linear programming solver widely used for optimal pricing and resource allocation in production revenue systems. (Python)
- **[OR-Tools](https://developers.google.com/optimization)** — Google's full constraint programming suite for complex pricing and yield optimization problems. (Python, C++, Java)
- **[Nevergrad](https://facebookresearch.github.io/nevergrad/)** — Derivative-free optimization library from Facebook Research. Excellent for black-box pricing experiments. (Python)
- **[contextualbandits](https://github.com/david-cortes/contextualbandits)** — Efficient contextual bandit algorithms (LinUCB, etc.) for personalized real-time pricing. (Python)
- **Greedy Pricing Heuristics** — Simple, fast, interpretable rules that deliver strong revenue uplift.  
  *Murphy Street example*: Implemented a greedy algorithm to optimize pricing decisions in production. The approach provided clear, explainable rules that increased monetization while remaining computationally lightweight and easy to maintain.

## Churn & Retention Optimization

- **[Lifelines](https://lifelines.readthedocs.io/)** — Survival analysis library for churn prediction and optimal retention campaign timing. (Python)
- **[scikit-learn](https://scikit-learn.org/)** + survival models — Predict churn probability to trigger targeted retention offers and reduce revenue loss. (Python)

## Recommendation & Upsell

- **[Surprise](https://surpriselib.com/)** — Easy-to-use recommender systems library focused on collaborative filtering for cross-sell and upsell opportunities. (Python)
- **[TensorFlow Recommenders](https://www.tensorflow.org/recommenders)** — Production-grade deep learning recommenders for personalized monetization.

## General Optimization Libraries

- **[Gurobi](https://www.gurobi.com/)** — Industry-leading commercial optimizer used by airlines and e-commerce companies for large-scale revenue management.
- **[Pyomo](https://www.pyomo.org/)** — Powerful algebraic modeling language for building custom optimization models.

## Papers & Resources

- [awesome-dynamic-pricing](https://github.com/DallasBuyer/awesome-dynamic-pricing) — Comprehensive collection of 100+ academic papers and resources (great reference).
- Contextual Bandits for Dynamic Pricing research
- Classic Revenue Management literature (Littlewood’s Rule, EMSR, etc.)

## Contributing

Thank you for considering a contribution!

**What we want**:
- Tools, algorithms, or libraries with **demonstrated revenue/monetization impact** (production usage, case studies, benchmarks)
- Clear, concise entries in the standard format
- High-signal only — we keep this list focused and valuable

**How to contribute**:
1. Add your entry to the correct section in `README.md`
2. Use the format: `**[Name](link)** — One-sentence revenue value. (Language)`
3. Commit and push to `main` (or open a PR)

## License

This list is dedicated to the public domain under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).

