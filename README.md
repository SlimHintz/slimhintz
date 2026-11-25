## Hi, I'm Tim

I'm a data scientist and ML engineer who builds fraud detection end to end: entity-level features, supervised and unsupervised models, monitoring, and the write-ups that turn scores into decisions.

My approach is data-centric and interpretable. Better data usually beats a bigger model, and a fraud score is only worth acting on if someone can explain why it fired.

I'm a Data Science & Analytics Manager at Voyatek, working as a federal consultant on income-document fraud detection. The work runs on Databricks with PySpark, MLflow, Delta Lake and Unity Catalog in an air-gapped environment, so that code stays behind the wall. What's here is the work I can share.

**What I care about**

- **Data-centric ML:** most of the gains come from the data rather than the algorithm. That means clean entity resolution, point-in-time features without leakage, honest labels and reproducible inputs.
- **Interpretable models:** rule-based and additive models, SHAP explanations, and reason codes an investigator can act on and an auditor can follow. That's why I maintain a RuleFit fork and wrote transpyrancy.
- **Models that hold up in practice:** drift monitoring, and catching silent bugs before they reach a decision.
- **Entity-level fraud:** problems where the entity matters more than the single transaction.
- **Modern AI tooling:** I run my own MCP servers on a Raspberry Pi and use them with Claude every day.

**Stack:** Python, PySpark, SQL, XGBoost, scikit-learn, SHAP, PyOD, MLflow, Delta Lake, Databricks. Before Databricks: large-scale SQL on Greenplum (MPP Postgres), and a lot of work on Unix/Linux servers with bash and Docker, building custom reproducible environments.

**Background:** neuroscience at the University of Otago (BSc Hons, First Class), then Flatiron School's data science program. Kiwi, based in metro Detroit.

### Recent projects

- **[bait-n-switch](https://github.com/SlimHintz/bait-n-switch)**: a clickbait detector, rebuilt in 2026 from a 2021 capstone after an audit found label noise and test-set leakage. Fixing the training data raised F1 on human-rated Webis-17 from 0.25 to 0.60, still with a simple linear model (TF-IDF and logistic regression). The model ships in a Chrome extension as 1.5 MB of weights and gives the same scores as Python (28 tests).
- **[transpyrancy](https://github.com/SlimHintz/transpyrancy)**: SHAP explainability in one call. It auto-selects the tree, linear, kernel or deep explainer and returns per-row and global explanations with plots. 154 tests.
- **[rulefit](https://github.com/SlimHintz/rulefit)**: interpretable rule ensembles (Friedman & Popescu). I modernized it for scikit-learn 1.8, added a `get_rules` API for readable rules, and added benchmarks and tests.
- **[calc-tutor](https://github.com/SlimHintz/calc-tutor)**: an MCP math tutor with 234 topics and 652 questions. Every answer is graded symbolically with SymPy, never by the LLM. It adds FSRS spaced repetition and can read handwriting from a reMarkable tablet. 845 tests.
- **[kitchen-inventory-mcp](https://github.com/SlimHintz/kitchen-inventory-mcp)**: a household inventory MCP server with fuzzy entity matching, duplicate detection and first-expiring-first-out depletion, on SQLAlchemy and Alembic. 51 tests.
- **[garmin-strava-mcp](https://github.com/SlimHintz/garmin-strava-mcp)**: an OAuth-secured MCP server over my Garmin and Strava data, which I use every day to analyze my marathon training.

### Earlier work

- **[Pneumonia-image-classification](https://github.com/SlimHintz/Pneumonia-image-classification)**: a transfer-learning ensemble for pediatric chest X-rays, with 0.99 recall, 0.90 accuracy and 0.97 AUC on a 624-image test set.
- **[credit-card-default-detection](https://github.com/SlimHintz/credit-card-default-detection)**: default prediction on 22.5k UCI Taiwan accounts (3.5:1 imbalance), with an engineered delinquency feature and a comparison of SMOTE, Tomek links and class weighting.
- **[King-County-Housing](https://github.com/SlimHintz/King-County-Housing)**: house-price regression with 420 engineered features, including geohash location features, reaching a cross-validated R² of 0.84.
