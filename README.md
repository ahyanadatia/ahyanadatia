### hi, I'm Ahyan. I build things.

CS + AI at the University of Nottingham. I like software that does real work and can show its working: agents whose claims carry citations, forecasts held to significance tests, scores computed from evidence.

```text
dealscreen        agentic due diligence, every fact cited       python · claude
equity-forecast   does an LSTM beat the baselines? (no)         python · tensorflow
forge             a builder's track record, from evidence       typescript · next.js
yuzu              a goals league for one flat                   javascript · postgres
```

**[dealscreen](https://github.com/ahyanadatia/dealscreen)**: give it a company name and get back a first-pass investment memo where every claim links to a source it actually retrieved. It finds the company on Companies House, a Claude agent researches the web, and Python, not the model, computes the final score and the red flags. A human signs off on every screening.

**[equity-forecast](https://github.com/ahyanadatia/equity-forecast)**: six forecasting models, walk-forward folds, Diebold-Mariano tests and a backtest with trading costs. On real market data, none of them beat "tomorrow's return is zero" with statistical significance, and the repo says so.

**[Forge](https://github.com/ahyanadatia/Forge)**: a track record for builders, computed from what they actually shipped: deterministic scoring with anti-gaming checks, plus live probes against their deployments and GitHub. Built with one collaborator.

**[Yuzu](https://github.com/ahyanadatia/yuzu)**: a goals league for my flat. Plain JavaScript, Postgres functions as the entire API, and row level security on the tables.

**Now:** checking whether any model does better when markets are volatile (equity-forecast), hardening Forge's security, and co-leading Wove, an AI styling and wardrobe app (private).

<sub>TypeScript · Python · SQL · Next.js · FastAPI · Postgres / Supabase · Anthropic API · pandas · statsmodels · TensorFlow · pytest · Vitest · GitHub Actions</sub>
