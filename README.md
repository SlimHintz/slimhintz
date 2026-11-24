## Hi, I'm Tim

I'm a data scientist and ML engineer who builds fraud detection end to end: entity-level features, supervised and unsupervised models, monitoring, and the write-ups that turn scores into decisions.

I'm a Data Science & Analytics Manager at Voyatek, working as a federal consultant on income-document fraud detection. The work runs on Databricks with PySpark, MLflow, Delta Lake and Unity Catalog in an air-gapped environment, so that code stays behind the wall. What's here is the work I can share.

**What I care about**

- Models that hold up in practice: reproducible inputs, drift monitoring, and catching silent bugs before they reach a decision.
- Fraud and risk problems where the entity matters more than the single transaction.
- Putting modern AI tooling to work. I run my own MCP servers on a Raspberry Pi and use them with Claude every day.

**Stack:** Python, PySpark, SQL, XGBoost, scikit-learn, PyOD, MLflow, Delta Lake, Databricks

**Background:** neuroscience at the University of Otago (BSc Hons, First Class), then Flatiron School's data science program. Kiwi, based in metro Detroit.

### Recent projects

- **[calc-tutor](https://github.com/SlimHintz/calc-tutor)**: an MCP server and web app that turn Claude into a math tutor. Answers are graded symbolically with SymPy rather than by the model, practice is scheduled with FSRS spaced repetition, and it can read handwritten work from a reMarkable tablet. 845 tests.
- **[kitchen-inventory-mcp](https://github.com/SlimHintz/kitchen-inventory-mcp)**: a household inventory MCP server where the server keeps the books and the model does the reasoning. It covers fuzzy entity matching, duplicate detection, recipe coverage scoring and first-expiring-first-out depletion, on SQLAlchemy and Alembic.
- **[garmin-strava-mcp](https://github.com/SlimHintz/garmin-strava-mcp)**: a secured MCP server and REST API over my own Garmin and Strava data (OAuth 2.1 + PKCE, rate limiting), with a SQLite training log, which I use for marathon-training analysis.
- **[rulefit](https://github.com/SlimHintz/rulefit)**: my fork of RuleFit, modularized and updated for scikit-learn 1.8, with rule extraction, benchmarks and tests. Interpretable rule models are a good fit for fraud work.

### Earlier work

- **[bait-n-switch](https://github.com/SlimHintz/bait-n-switch)**: a clickbait headline classifier (tf-idf and naive Bayes, about 90% accuracy) served through a Flask API.
- **[Pneumonia-image-classification](https://github.com/SlimHintz/Pneumonia-image-classification)**: a voting ensemble of VGG16, DenseNet121 and MobileNetV2 for pediatric chest X-rays, tuned for recall (0.99 recall, 0.90 accuracy).
- **[credit-card-default-detection](https://github.com/SlimHintz/credit-card-default-detection)**: default prediction on the UCI Taiwan credit-card data, with class rebalancing.
- **[King-County-Housing](https://github.com/SlimHintz/King-County-Housing)**: house-price regression with geohash features.
