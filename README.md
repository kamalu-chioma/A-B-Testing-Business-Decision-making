# 📌 A/B Testing for Business Decision-Making
By: Chioma Kamalu

## 📍 Project Overview
Traditional A/B testing often stops at statistical significance, overlooking business impact. This project integrates Frequentist analysis, Monte Carlo simulations, and Bayesian inference to determine whether a marketing campaign should be deployed based on both statistical reliability and financial viability.

I analyzed the impact of a promotional campaign for a fast-food chain, evaluating whether the observed increase in sales justified a full-scale rollout. Instead of a simple hypothesis test, Monte Carlo simulations were used to estimate the probability distribution of future sales outcomes, providing a data-driven approach to risk assessment and return on investment (ROI).

## 📊 Key Features
✅ Frequentist A/B Testing – Uses t-tests and confidence intervals to determine significance.

✅ Monte Carlo Simulations – Models potential future sales, providing probabilistic forecasts.

✅ Bayesian Inference – Updates beliefs dynamically to support flexible decision-making.

✅ Business-Oriented Framework – Ensures marketing spend is optimized based on both statistical and financial considerations.

## 🚀 Bootstrapping for Standard Error Estimation
Standard errors in regression typically assume normality and homoskedasticity, but bootstrapping offers a more robust alternative by resampling the dataset to estimate variability. This allows for a more reliable assessment of uncertainty in A/B test results.

## Next Steps: Implementing Bootstrapping for A/B Testing

1️⃣ Generate 10,000 resampled datasets by sampling with replacement.

2️⃣ Run the regression model on each resampled dataset.

3️⃣ Extract and store the coefficient on Promotion across all iterations.

4️⃣ Analyze the distribution of coefficients to estimate confidence intervals and assess campaign impact.

By leveraging bootstrapping, businesses can make more informed decisions with greater statistical confidence.

## 🔬 Bayesian Approach: A More Probabilistic Perspective
Rather than relying on fixed-sample hypothesis tests, Bayesian inference quantifies uncertainty and continuously updates beliefs about the campaign's effectiveness, offering a flexible, real-time decision-making framework.

### Comparison to Frequentist Methods

✔ Frequentist: Binary decision-making (significant vs. not significant).

✔ Bayesian: Provides probability distributions for expected outcomes, allowing for nuanced risk assessment.

This approach ensures that businesses can adapt to new data dynamically, reducing uncertainty in campaign performance.

## 📈 Business Impact

✔ Optimizes marketing ROI by balancing statistical confidence with financial feasibility.

✔ Reduces financial risk by modeling uncertainty using Monte Carlo simulations.

✔ Supports adaptive decision-making through Bayesian inference for continuous learning.

By integrating Frequentist, Bayesian, and bootstrapping techniques, this project delivers a comprehensive framework for data-driven business decisions.

📢 For collaboration, contributions, or feedback, feel free to connect! 🚀
