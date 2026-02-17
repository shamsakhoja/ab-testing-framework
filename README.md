# A/B Testing Framework for Marketing/ Product Analytics

## Onboarding Flow Optimization

![A/B Test Results](ab_test_results.png)

## Project Overview
This project demonstrates a complete, real-world A/B testing framework 
built to optimize user onboarding flows. The analysis follows the exact 
workflow used by growth and marketing analytics teams at top tech companies.

## Business Problem
Only 35% of new users were completing onboarding and reaching their 
"aha moment". The remaining 65% dropped off before experiencing core 
product value, directly impacting revenue and growth.

## Hypothesis
**"If we simplify onboarding from 5 screens to 3 screens, then activation 
rate will increase because users reach their first key action faster 
with less friction."**

## Methodology
```
1. Define hypothesis & success criteria
2. Calculate required sample size (power analysis)
3. Run experiment (20,000 users, 2 weeks)
4. Analyze results (two-proportion z-test)
5. Visualize findings
6. Make business recommendation
```

## Key Results

| Metric | Control | Treatment | Lift |
|--------|---------|-----------|------|
| Activation Rate | 35.1% | 42.1% | **+20.0%** |
| Users Activated | 3,505 | 4,210 | +705 users |
| Statistical Significance | - | - | p < 0.001  |

## Statistical Confidence
- **P-value:** < 0.001
- **95% Confidence Interval:** [16.1%, 23.9%] relative lift
- **Z-score:** 10.9

## Business Impact
Assuming 100,000 new users per month:
- **Additional activations:** +7,020 users/month
- **Annual impact:** ~84,000 additional activated users
- **Revenue impact:** ~$4.2M additional annual revenue (at $50 LTV)

## Recommendation
SHIP the 3-screen onboarding flow**

Result is statistically significant with meaningful business impact.
Low implementation risk (UI change only, no backend changes required).

## Tools & Technologies
| Tool | Purpose |
|------|---------|
| Python | Core analysis |
| NumPy | Statistical calculations |
| Pandas | Data manipulation |
| SciPy | Hypothesis testing |
| Matplotlib/Seaborn | Visualizations |

## Files
| File | Description |
|------|-------------|
| `ab_testing_framework.ipynb` | Main analysis notebook |
| `ab_test_results.png` | Visualization of results |

## How to Run
1. Open `ab_testing_framework.ipynb` in Google Colab or Jupyter
2. Run all cells (Runtime → Run All)
3. Results and visualizations will generate automatically

## Key Concepts Demonstrated
- Hypothesis formulation
- Sample size calculation & power analysis
- Two-proportion z-test
- P-value interpretation
- Confidence interval calculation
- Statistical vs practical significance
- Executive stakeholder communication

## Author
Shamsa Khoja | MS Business Analytics, University of Louisville (2025)
www.linkedin.com/in/shamsakhoja | www.github.com/shamsakhoja7-max/ab-testing-framework
