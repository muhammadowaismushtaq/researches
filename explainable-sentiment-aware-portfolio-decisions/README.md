# Explainable, Sentiment-Aware Portfolio Decisions

**Research plan (draft) · Muhammad Owais Mushtaq**

> This is a working plan, not finished research. It will change as the literature review and early experiments progress.

---

## Motivation

Portfolio rebalancing engines in wealth management mostly follow fixed rules on fundamentals and risk. They can't see market sentiment: after events such as COVID or a war, investors may panic-sell even when a company's fundamentals are strong. At the same time, advisors and their clients need a clear reason for every decision, which many AI models can't provide.

## Research questions

1. Does adding market sentiment to a fundamentals-based rebalancing signal improve decisions during event-driven market shocks?
2. How can such recommendations be explained so that advisors and clients understand and trust them?
3. Where should the human stay in the loop, and how much should the model be allowed to adjust a rule-based decision?

## Planned approach

1. **Baseline:** a rule-based rebalancing signal built on fundamentals and risk.
2. **Sentiment:** score financial news and market text with a finance-specific language model such as FinBERT.
3. **Similar past events:** find historical events that resemble the current one and how markets reacted.
4. **Combination:** use sentiment and past-event evidence to adjust the baseline signal, not replace it.
5. **Explanation:** show each factor's contribution (e.g. SHAP) alongside references to the similar past events behind a recommendation.

## Evaluation

- **Backtesting** against the rule-based baseline, especially around major market events.
- **Metrics:** returns, volatility, maximum drawdown and risk-adjusted return.
- **Explanation quality:** feedback from practitioners on whether the explanations are clear and useful.

## Risks and considerations

- Sentiment does not always move prices, so the model may overfit to past events.
- News data is noisy and may have licensing limits.
- Financial recommendations are regulated, so this work stays at the research and decision-support level.

## Tentative milestones

| Phase | Focus |
|---|---|
| 1 | Literature review; data sources for prices, fundamentals and news |
| 2 | Sentiment pipeline and event-similarity search |
| 3 | Combined model and backtesting against the baseline |
| 4 | Explanation layer and practitioner feedback |
| 5 | Write-up |
