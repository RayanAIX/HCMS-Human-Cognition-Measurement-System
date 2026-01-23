![Python](https://img.shields.io/badge/Python-3.x-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Research%20Prototype-orange)
![AI](https://img.shields.io/badge/Focus-Human--Centered%20AI-purple)

# 🧠 Human Cognition Measurement System (HCMS)

---

📄 **Preprint (DOI-backed)**
**Beyond Correctness: Measuring Cognitive Stability and Confidence Calibration in Human Understanding**
Zenodo (v1.0): [https://doi.org/10.5281/zenodo.18269740](https://doi.org/10.5281/zenodo.18269740)

---

## 📑 Citation

If you use or reference this work, please cite:

**Shahid, M. R. (2026).**
*Beyond Correctness: Measuring Cognitive Stability and Confidence Calibration in Human Understanding.*
Zenodo. [https://doi.org/10.5281/zenodo.18269740](https://doi.org/10.5281/zenodo.18269740)

```bibtex
@article{shahid2026hcms,
  title={Beyond Correctness: Measuring Cognitive Stability and Confidence Calibration in Human Understanding},
  author={Shahid, Muhammad Rayan},
  year={2026},
  publisher={Zenodo},
  doi={10.5281/zenodo.18269740}
}
```

---

**An AI-driven framework for measuring human understanding, confidence calibration, and cognitive stability.**

The **Human Cognition Measurement System (HCMS)** is a research-grade cognitive assessment framework designed to move beyond right-or-wrong evaluation. Rather than treating intelligence as a static score, HCMS models **how a learner thinks**, **how confident they are**, **how consistent their reasoning remains**, and **how well-calibrated their understanding truly is**.

This repository represents **a consolidated research system representing the current validated stage of HCMS development**, spanning **Phases 1–15** of structured investigation.

---

## 🧾 Abstract

Traditional assessment systems equate correctness with understanding, overlooking metacognitive alignment and reasoning stability. This work introduces the **Human Cognition Measurement System (HCMS)**, a cognition-aware assessment framework that models understanding as a multidimensional construct integrating accuracy, confidence calibration, repeated-trial consistency, and robustness under controlled perturbation.

Controlled experiments demonstrate that learners with comparable accuracy profiles can exhibit substantially different cognitive stability and confidence–accuracy alignment. Notably, confidence miscalibration is shown to predict degradation in reasoning consistency under perturbation—patterns that static test scores fail to capture. HCMS is presented as a diagnostic measurement instrument emphasizing interpretability, reproducibility, and cognitive validity.

---

## ✨ Core Capabilities

HCMS evaluates cognition across multiple, interdependent dimensions:

* **Understanding Level** — Depth, structure, and correctness of conceptual grasp
* **Confidence Calibration** — Alignment between self-reported confidence and actual performance
* **Consistency** — Stability of reasoning across attempts and conditions
* **Misconception Detection** — Rule-based and statistical identification of cognitive errors
* **Adaptive Feedback** — Targeted remediation and reinforcement strategies
* **Robustness Analysis** — Resistance to noisy, incomplete, or adversarial inputs
* **Explainability** — Transparent decision tracing and feature-level attribution

---

## 🧩 System Architecture

```text
HCMS_Final/
│
├── phases/                    # Complete research history (Phases 4–12)
│
├── cognition_ai/              # Final integrated system layer
│   ├── run_full_system.py     # End-to-end execution entry point
│   ├── config.json            # System configuration
│   ├── outputs/
│   │   └── final_learner_report.json
│   └── paper/                 # Research paper (Markdown)
│       ├── abstract.md
│       ├── introduction.md
│       ├── related_work.md
│       ├── methodology.md
│       ├── experiments.md
│       ├── results.md
│       └── conclusion.md
│
└── README.md
```

The **`phases/`** directory preserves scientific rigor, traceability, and experimental evolution.
The **`cognition_ai/`** directory represents the deployable system and final research artifact.

---

## 🚀 How to Run the System

### 1️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

### 2️⃣ Run the Full Cognitive Pipeline

```bash
python cognition_ai/run_full_system.py
```

### 3️⃣ Output

After execution, a finalized learner cognition profile is generated at:

```text
cognition_ai/outputs/final_learner_report.json
```

---

## 📊 Example Output (Simplified)

```json
{
  "Understanding Level": "Partial",
  "Calibration": "Miscalibrated",
  "Consistency Score": 0.83,
  "System Verdict": "Needs targeted remediation"
}
```

This output reflects **how a learner thinks**, not merely whether an answer was correct.

---

## 🧪 Research Foundation

HCMS was developed through **15 structured research phases**, including:

* **Controlled experiments** — Testing core cognitive behaviors
* **Validation & consistency checks** — Ensuring reliability across trials
* **Confidence–accuracy correlation analysis** — Measuring self-awareness of understanding
* **Stress testing** — Evaluating performance under noise and adversarial conditions
* **Explainability & decision tracing** — Transparent reasoning analysis
* **Adaptive feedback systems** — Personalized remediation and reinforcement
* **Full system integration** — Cohesive end-to-end framework assembly

> *Each phase builds upon the previous, maintaining strict scientific continuity.*

---

## 🔬 Research Contributions

This work makes the following contributions:

1. Introduces **cognitive stability** as a measurable dimension of human understanding beyond correctness.
2. Demonstrates that **confidence–accuracy misalignment** predicts reasoning degradation under perturbation.
3. Provides a **diagnostic measurement framework** rather than a predictive scoring model.
4. Offers interpretable, reproducible assessment signals suitable for educational and cognitive research.

---

## 📄 Research Paper

The **complete research paper** is available at:

```text
cognition_ai/paper/
```

### Included Sections

1. Abstract
2. Introduction
3. Related Work
4. Methodology
5. Experiments
6. Results
7. Conclusion

All files are written in **clean Markdown**, ensuring academic readability and publishing compatibility.

---

## 🎯 Use Cases

HCMS is designed for **scalable, intelligent assessment** across educational and research domains:

* Education Technology (EdTech)
* Adaptive Learning Platforms
* AI-driven Assessment Systems
* Cognitive Science Research
* Personalized Skill Evaluation
* Intelligent Tutoring Systems

> *Scales from individual learners to institution-level assessment.*

---

## 🧠 Why HCMS Is Different

Traditional assessments ask:

> *Did the student get it right?*

HCMS asks:

> *Do they truly understand — and do they know that they understand?*

This distinction enables:

* Deeper learning outcomes
* Early misconception detection
* Personalized intervention strategies
* Fairer and more meaningful evaluation

---

## 📌 Project Status

* ✅ Research complete
* ✅ System consolidated
* ✅ Final product operational
* ✅ Paper drafted
* ✅ Ready for publication, demonstration, or extension

---

## 🔭 Future Work

Planned extensions include:

* Longitudinal cognitive stability analysis
* Cross-task understanding transfer
* Refined perturbation modeling
* Expanded validation across learner populations

---

## 👤 Author

**Muhammad Rayan Shahid**
Independent AI Researcher
Founder — **ByteBrilliance AI**

---

## 🌟 Acknowledgment

This project represents a **deep exploration into human cognition, AI alignment, and meaningful assessment**, developed with rigor, patience, and purpose.

> *“Not everything that can be measured matters — but understanding how humans think, does.”*
