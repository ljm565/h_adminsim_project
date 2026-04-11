# H-AdminSim

**A Multi-Agent Simulator for Realistic Hospital Administrative Workflows with FHIR Integration**

Accepted at **CHIL 2026** (ACM Conference on Health, Inference, and Learning)

## Links

- **Paper**: https://arxiv.org/pdf/2602.05407
- **GitHub**: https://github.com/ljm565/H-AdminSim
- **PyPI**: https://pypi.org/project/h-adminsim/
- **Demo**: https://ljm565.github.io/medworld/
- **Project Page**: [`index.html` (this repo)](https://ljm565.github.io/h_adminsim_project/)

## About

H-AdminSim is a multi-agent simulation framework for modeling realistic hospital administrative workflows at scale. It synthesizes care level-specific patient profiles using 194 disease-symptom pairs across 9 internal medicine departments, simulates multi-turn interactions between LLM-driven staff and patient agents, and evaluates 5 LLM backends (GPT-5 Mini/Nano, Gemini 2.5 Flash, Llama 3.3 70B, Qwen 3 32B) with rubric-based scoring.

Key results: Gemini 2.5 Flash achieves 88.9% on primary care intake; tool-based scheduling reaches ~99.8% accuracy; human evaluation scores interaction quality at 4.11/5.

## Install

```bash
pip install h-adminsim
```

Requires Python 3.11 or 3.12.

## Authors

- Jun-Min Lee (KAIST)
- Meong Hi Son (Samsung Medical Center)
- Edward Choi (KAIST)
