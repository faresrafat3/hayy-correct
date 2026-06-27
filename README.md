# 🌿 Hayy — Length-Aware Seq2Seq for Arabic Text Correction

> An experimental length-aware seq2seq model for Arabic morphological correction. Currently in early research phase — not yet ready for production use.

---

## 📋 Project Status

**Phase**: Pre-alpha / experimental

This repository is part of an exploratory research effort on Semitic NLP. The current focus is on a length-aware seq2seq architecture that explicitly models the input→output length transformation needed when correcting Arabic morphology (e.g., when a misspelled word of length N requires correction to a word of length M ≠ N).

The codebase is intentionally minimal at this stage. Active development has not yet started in this repo — research notes and prototypes live in a separate private workspace and will be migrated here once they reach a stable form.

---

## 🎯 Intended Direction

When development begins, the model is expected to:

- Accept Arabic text (potentially misspelled) as input.
- Predict the corrected form, with explicit handling of length mismatches.
- Be small enough to run on CPU (target: < 100k parameters for the experimental baseline).
- Report honest metrics on synthetic data, with clear caveats about generalization.

---

## 🔗 Related Repositories

This project is part of a small research stack on Semitic NLP:

- **[semitic-scattering-law](https://github.com/faresrafat3/semitic-scattering-law)** — Exploratory research on the linear decay of neural model performance as root-scatter increases in Semitic morphology.
- **[semitic-router](https://github.com/faresrafat3/semitic-router)** — Hybrid neural/symbolic router that uses the Scattering Degree to decide which correction path to take.

---

## 📅 Roadmap

| Phase | Goal |
|---|---|
| Now | Repo + README + scope definition |
| Next | Migrate research prototype + minimal reproducible training script |
| Later | Evaluation on synthetic data, write-up, sample notebooks |

If you have questions or want to collaborate, please open an issue.

---

## 📜 License

MIT (planned). No code is currently shipped.

---

## 📫 Contact

- GitHub: [@faresrafat3](https://github.com/faresrafat3)
