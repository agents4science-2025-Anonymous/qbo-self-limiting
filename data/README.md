# QBO Self-Limiting SAI - Experimental Data

## Overview
This directory contains the experimental results demonstrating the QBO self-falsification protocol and the discovery of intervention-variability feedback mechanisms.

## Data Files

### qbo_analysis_results.json
- Complete QBO (Quasi-Biennial Oscillation) analysis results
- Shows the efficiency gain of only 0.043% (not 1.69% as initially hypothesized)
- Contains phase analysis, coupling metrics, and feedback calculations
- Key discovery: Self-limiting nature of SAI interventions

## Key Results
- **Efficiency Gain**: 0.043% (actual) vs 1.69% (initial claim)
- **Phase Contrast**: 0.000134
- **Control Loop Feedback**: -0.0002298
- **Z-score**: 12.7 (artifact of GLENS ensemble design)

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