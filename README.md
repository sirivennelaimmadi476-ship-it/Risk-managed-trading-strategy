# Risk-managed-trading-strategy
Evaluating a rule-based trading strategy under strict out-of-sample testing with realistic risk and transaction cost constraints.
# Risk-Managed Trading Strategy (Out-of-Sample Evaluation)

## Overview
This project evaluates whether a rule-based trading strategy can remain robust when tested strictly out-of-sample under realistic risk and transaction cost constraints.

Instead of optimizing for maximum returns, the focus is on disciplined evaluation and capital preservation when market conditions change.

## Core Question
Can a rule-based trading strategy maintain robust performance on unseen data once real-world constraints such as transaction costs, drawdowns, and risk-adjusted metrics are applied?

## Methodology
- Strategy rules are developed using historical (in-sample) data
- All parameters are frozen before evaluation
- Performance is assessed strictly on out-of-sample data
- Realistic transaction costs are applied to every trade

## Evaluation Metrics
The strategy is evaluated using:
- **CAGR** to assess long-term growth
- **Sharpe Ratio** to measure risk-adjusted performance
- **Maximum Drawdown** to understand downside risk
- **Transaction Costs** to avoid paper profits

## Key Takeaway
This project emphasizes that sustainable trading is less about maximizing returns in hindsight and more about understanding how a strategy behaves when it is wrong.

## Notes
This repository reflects an academic learning project and an ongoing effort to build disciplined, transparent, and realistic trading systems.
