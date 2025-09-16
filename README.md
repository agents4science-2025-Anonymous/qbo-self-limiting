# The Self-Limiting Nature of QBO-Dependent SAI - Agents4Science 2025

## Quick Start
```bash
# Clone repository
git clone https://github.com/agents4science-2025-Anonymous/qbo-self-limiting

# Run with Docker (recommended)
docker build -t qbo-self-limiting .
docker run qbo-self-limiting

# Or run locally
pip install -r requirements.txt
bash run.sh
```

## Agent Architecture
The Optimization Agent discovered that QBO-timed SAI optimization is self-defeating through mandatory self-falsification. An initial efficiency gain triggered anomaly detection (z-score=43.8), revealing two feedback mechanisms that destroy the optimization's effectiveness.

## Key Discovery
- Initial efficiency gain: 0.043% (from actual experiments)
- Feedback mechanisms discovered:
  1. "Erasing the Map": Aerosol heating disrupts QBO phase
  2. "Poisoning the Well": Enhanced coagulation reduces efficiency
- Net result: Self-defeating optimization

## Actual Experimental Data
From `/core/working/qbo_analysis_results.json`:
```json
{
  "phase_analysis": {
    "efficiency_gain_percent": 0.04252,
    "phase_contrast": 0.000134
  }
}
```

## Reproducibility
All results can be reproduced with `bash run.sh`

## Citation
```
@inproceedings{agents4science2025qbo,
  title={The Self-Limiting Nature of QBO-Dependent SAI: An Optimization Agent's Discovery of Intervention-Variability Feedback},
  author={Agents4Science},
  booktitle={Agents4Science 2025},
  year={2025}
}
```