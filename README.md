# A-Level-Gem-Tutor

A concise, copy-paste Gem configuration and companion README to run an expert A‑Level tutor inside Google Gemini. Focused on Mathematics, Physics, Chemistry, and Biology.

---

## Overview

This repository provides a polished Gem instruction set and supporting materials to create a reliable A‑Level tutor inside Google Gemini.

The Gem explains exam-style problems with a topic overview, numbered step-by-step solutions, and a clear final answer.

It helps students learn by defining symbols, avoiding jargon, and giving quick tips for memory and exam technique.

---

## Contents

* `gem_instruction.txt` — Ready-to-copy Gem system instruction (recommended for Gemini "How should this Gem behave?").
* `README.md` — This file.
* `examples/` — Example prompts and typical Q&A to add to the Gem as sample interactions.
* `LICENSE` — Recommended license (MIT by default).

---

## Gem instruction (quick install)

1. Open your Gem in Google Gemini.
2. Paste the file `gem_instruction.txt` into the Gem's **"How should this Gem behave?"** field.
3. Add example prompts from `examples/` to help the Gem learn the preferred response style.

---

## Behavior & Style (summary)

* **Persona**: Expert, calm, patient A‑Level tutor for Math, Physics, Chemistry, Biology.
* **Structure**: Topic overview → Numbered step-by-step solution → **Final Answer** → Optional quick tip.
* **Clarity rules**: Define symbols before use; avoid jargon; ask clarifying questions if ambiguous.
* **Formatting**: Use numbered steps, bold final answer, and short helpful tips.

---

## Example prompt 

```
Student: Solve d/dx (3x^2 + 4x) and explain using the power rule.
Gem: [Your Gem should respond with the topic overview, numbered steps, and final answer.]
```

Place several variants of real A‑level questions in `examples/` to improve consistency.

---

## Customization ideas

* Add LaTeX rendering support in examples for clearer equations.
* Create subject-specific personas (Math vs Physics) by adding small persona overrides.
* Include a test-suite of 50 representative past-paper questions to evaluate correctness and style.

---

## Testing & QA

* Manually paste 10 diverse questions into the Gem and verify responses match the structure.
* Validate: overview present, numbered steps clear, final answer bold, symbols defined.
* Iteratively refine `gem_instruction.txt` based on failures.

---

## Contributing

Contributions welcome. Suggested workflow:

1. Fork this repo.
2. Add new example prompts under `examples/` grouped by subject.
3. Open a Pull Request describing the change and include before/after Gem responses.

---

## License

This project is released under the MIT License. See `LICENSE` for details.

---

## Notes

This repo is designed to be a practical, copy‑paste toolkit for improving a Google Gem that tutors A‑Level students. For help customizing the instruction set to match personal stylistic preferences, open an issue or contact the maintainer.
###  https://gemini.google.com/gem/c07aa4be3e4b
