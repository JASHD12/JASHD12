# Jashdeep Singh

**Software engineer · M.Sc. Data Science, Philipps-Universität Marburg**

I came to data science from backend engineering. I’m interested in what happens when a model has to beat a simple baseline, work on later data, or fit on a CPU. My projects include the code and results so you can check what held up.

Based in Germany. Open to **working-student roles (Werkstudent) in AI/ML and data science** and **full-time applied ML engineering roles**.

## Featured projects

### [Forecast Arena](https://github.com/JASHD12/forecast-arena) · Forecasting and LLM evaluation

A public benchmark where baselines, ML models and LLM agents publish probabilities before the outcomes are known. An append-only ledger records the forecasts for scoring and audit.

- **365-day electricity-price backtest.** Gradient boosting achieved a Brier score of **0.1930**, compared with **0.2205** for the persistence baseline (lower is better). [Backtest results](https://jashd12.github.io/forecast-arena/backtests.html)
- **276 held-out questions.** I compared a QLoRA-tuned language model with its 4-bit CPU export. The export lost most of the improvement over the original model.

[Live benchmark](https://jashd12.github.io/forecast-arena/) · [Code tour](https://github.com/JASHD12/forecast-arena/blob/main/docs/CODE_TOUR.md) · [Fine-tuning study](https://github.com/JASHD12/forecast-arena/blob/main/docs/lab/qlora-r1.md) · [Forecast audit case](https://jashd12.github.io/forecast-arena/audit.html)

### [DataPilot](https://github.com/JASHD12/datapilot) · Applied ML and retrieval

A workbench for exploring data, comparing models and checking answers against source evidence. You can train small models in the browser on historical Olist orders and evaluate them on later orders.

- **Review classification.** On 6,548 final-period reviews with wording unseen in earlier splits, the classifier scored **0.6475 macro-F1**, compared with **0.2605** for the majority baseline.
- **Multilingual retrieval.** I compared TF-IDF, multilingual E5 embeddings and reciprocal-rank fusion, then documented ranking errors and limitations.

[Try the demo](https://jashdeep-datapilot.pages.dev/) · [Review study](https://github.com/JASHD12/datapilot/blob/main/docs/REVIEW_STUDY.md) · [Retrieval study](https://github.com/JASHD12/datapilot/blob/main/docs/RETRIEVAL_STUDY.md)

## Software engineering experience

- **Paytm Money · Software Engineer** · Jan 2025 – Sep 2026  
  Java and Spring Boot services for 100K+ monthly portfolio syncs and 50K+ monthly orders. Added retry handling and built Kafka ingestion and validation across 5M accounts.
- **MAQ Software · Software Engineer 1** · Nov 2023 – Nov 2024  
  Built a Python and FastAPI document assistant and evaluated answers against source passages. Automated reporting with SQL Server, Azure and Databricks, saving about 15 hours a week.
- **Advantage Club · Software Developer** · Jul – Sep 2023  
  Built React survey forms and improved responsiveness on lower-end devices.
- **Advantage Club · Software Development Intern** · Jan – Jun 2023  
  Integrated an HR dashboard with third-party systems and cut award email processing time by 60%.

I specified and directed Forecast Arena and used AI coding agents for implementation. Its figures are generated from the public record.
