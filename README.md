# Awesome Revenue Algorithms

> **The practical, production-focused list** of algorithms, libraries, and techniques that have **actually driven revenue** in real businesses.

Most dynamic pricing and revenue optimization lists are heavy on academic papers and theoretical models.  
This one prioritizes **production-grade tools and approaches** used in SaaS, e-commerce, subscription, and marketplace environments.

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
- **Greedy Pricing Algorithms** — Simple, computationally efficient, interpretable rules that deliver strong revenue uplift.  
  *Murphy Street example*: Implemented a production-validated greedy algorithm to optimize pricing decisions. The approach provided clear, explainable rules that increased monetization while remaining lightweight and easy to maintain in a live system.

## Churn & Retention Optimization

- **[Lifelines](https://lifelines.readthedocs.io/)** — Survival analysis library for churn prediction and optimal retention campaign timing. (Python)
- **[scikit-learn](https://scikit-learn.org/)** + survival models — Predict churn probability to trigger targeted retention offers and reduce revenue loss. (Python)

## Recommendation & Upsell

- **[Surprise](https://surpriselib.com/)** — Easy-to-use recommender systems library focused on collaborative filtering for cross-sell and upsell opportunities. (Python)
- **[TensorFlow Recommenders](https://www.tensorflow.org/recommenders)** — Production-grade deep learning recommenders for personalized monetization.

## General Optimization Libraries

- **[Gurobi](https://www.gurobi.com/)** — Industry-leading commercial optimizer used by airlines and e-commerce for large-scale revenue management.
- **[Pyomo](https://www.pyomo.org/)** — Powerful algebraic modeling language for building custom optimization models.

## Papers & Resources

- [awesome-dynamic-pricing](https://github.com/DallasBuyer/awesome-dynamic-pricing) — Comprehensive collection of 100+ academic papers and resources.
- Contextual Bandits for Dynamic Pricing research
- Classic Revenue Management literature (Littlewood’s Rule, EMSR, etc.)

## Contributing

Thank you for considering a contribution!

**What we want**:
- Tools, algorithms, or libraries with **demonstrated revenue/monetization impact**
- Production stories, case studies, or battle-tested patterns

**How to contribute**:
1. Add your entry to the correct section
2. Use format: `**[Name](link)** — One-sentence revenue value. (Language)`
3. Commit and push to `main`

## License

CC0 1.0 Universal — Public domain.
