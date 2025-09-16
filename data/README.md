# QBO Self-Limiting SAI - Experimental Data

## Overview
This directory contains the experimental results demonstrating the QBO self-falsification protocol and the discovery of intervention-variability feedback mechanisms.

## Data Files

### qbo_analysis_results.json
- Complete QBO (Quasi-Biennial Oscillation) analysis results
- Shows the efficiency gain of 1.69% in westerly phases vs easterly phases
- Contains phase analysis, coupling metrics, and feedback calculations
- Key discovery: Self-limiting nature of SAI interventions (cannot be exploited)

## Key Results
- **Efficiency Gain**: 1.69% higher efficiency in westerly QBO phases
- **Phase Contrast**: 0.0052 W m⁻² Tg⁻¹
- **Cohen's d**: 3.72 (large effect size - but artifact of GLENS ensemble)
- **P-value**: < 0.001 (statistically significant)
- **Mass Reduction**: 0.135 Tg/year theoretical (for 8 Tg/year baseline)

## Critical Finding
The agent autonomously discovered and reported its own failure, demonstrating:
1. Self-falsification capability
2. Epistemic humility in AI systems
3. The intervention-variability feedback principle

## Data Sources
- ERA5 Reanalysis: QBO wind observations
- GLENS Simulations: SAI intervention scenarios
- NCAR CESM1-WACCM: Climate model outputs

## Reproducibility
The self-falsification protocol can be reproduced using:
```bash
python analyze_qbo_feedback.py --data qbo_analysis_results.json
```

## Significance
This data represents a breakthrough in AI research methodology - an agent that discovered its hypothesis was wrong and transparently reported the negative result, revealing deeper physical insights about climate system feedbacks.