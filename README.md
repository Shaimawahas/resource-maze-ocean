# resource-maze-ocean
An open gameplay telemetry dataset for Big Five personality inference using a serious game (Resource Maze).
# Resource Maze – RM-OCEAN Dataset

RM-OCEAN is an open research dataset containing anonymized gameplay telemetry and behavioral features collected from *Resource Maze*, a serious game designed to study personality inference using the Big Five (OCEAN) model.

The dataset supports research in:
- Game-based personality assessment
- Behavioral modeling
- Machine learning on event logs
- Serious games and gamification

---

## Dataset Contents

- **Raw gameplay event logs**
- **Engineered behavioral features**
- **Coarsened Big Five personality labels (Low / Medium / High)**
- **Train / validation / test splits**
- **Baseline ML models for reproducibility**

---

## Game Description

Resource Maze is a single-player exploratory game in which participants navigate a maze to collect essential items and exit efficiently.  
Gameplay mechanics are designed to elicit behaviors related to exploration, persistence, risk-taking, and decision-making.

---

## Personality Measurement

Personality ground truth was obtained using a validated Big Five inventory (e.g., BFI-2 or NEO-FFI).  
To preserve privacy, personality traits are released only as categorical labels:
- Low
- Medium
- High

Raw questionnaire responses are **not** shared.

---

## Ethical Compliance

- Informed consent obtained from all participants
- No personally identifiable information is included
- No real-world timestamps or biometric data are released
- Dataset complies with GDPR-aligned open science practices

See `ETHICS_STATEMENT.md` for details.

---

## Citation

If you use this dataset, please cite it as described in `citation/CITATION.cff`.

---

## License

This dataset is released under the **Creative Commons Attribution 4.0 (CC BY 4.0)** license.
