# MetFuse 🔀
### Figurative Fusion between Metonymy and Metaphor

**Dataset for the paper:**
> **MetFuse: Figurative Fusion between Metonymy and Metaphor**
> [https://arxiv.org/abs/2604.12919](https://arxiv.org/abs/2604.12919)

---

## What is MetFuse?

Metonymy and metaphor are two fundamental forms of figurative language — yet they have almost always been studied in isolation. **MetFuse** is the first dataset to bring them together.

We introduce a framework that takes a **literal sentence** as input and transforms it into three figurative variants:

| Variant | What changes | Example |
|---|---|---|
| **Literal** | — | *The audience clapped when the magician entered the stage.* |
| **Metonymy** | Noun is replaced with a contiguous, in-domain referent | *The **auditorium** clapped when the magician entered the stage.* |
| **Metaphor** | Verb is mapped to another domain | *The audience **erupted** when the magician entered the stage.* |
| **Hybrid** | Both noun and verb are altered | *The **auditorium erupted** when the magician entered the stage.* |

The dataset contains **1,000 human-verified quadruplets** — 4,000 sentences in total — spanning both **common noun metonymy** (CN) and **named-entity metonymy** (NE).

---

## Dataset Format

Each instance in MetFuse contains the following fields:

| Field | Description |
|---|---|
| `sentence` | The original literal sentence |
| `target_noun` | The noun that undergoes metonymic substitution |
| `target_verb` | The verb that undergoes metaphoric mapping |
| `met_par` | The metonymic paraphrase (the replacement noun) |
| `metonymy` | The metonymic variant of the sentence |
| `metaphor` | The metaphoric variant of the sentence |
| `hybrid` | The hybrid variant (metonymic noun + metaphoric verb) |
| `category` | Type of metonymy: `CN` (common noun) or `NE` (named entity) |

### Example

```
target_noun : lawyer
target_verb : see
met_par     : law office
category    : CN

literal     : The lawyer in Lincoln saw issues.
metonymy    : The law office in Lincoln saw issues.
metaphor    : The lawyer in Lincoln beheld the behemoth of issues.
hybrid      : The law office in Lincoln beheld the behemoth of issues.
```

---

## Download

The MetFuse dataset is available in this repository:

```
metfuse.csv      ← full dataset (1,000 quadruplets / 4,000 sentences)
```

---

## Citation

If you use MetFuse in your research, please cite:

```bibtex
@misc{ghosh2026metfusefigurativefusionmetonymy,
      title={MetFuse: Figurative Fusion between Metonymy and Metaphor}, 
      author={Saptarshi Ghosh and Tianyu Jiang},
      year={2026},
      eprint={2604.12919},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2604.12919}, 
}
```

---
