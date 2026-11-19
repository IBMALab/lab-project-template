<!--
  Copy this file into your project repo as README.md and fill every <...> field.
  Delete these comment lines when done.
-->

# <Project Title>

**Repository:** `YYYY-DEGREE-StudentName-Topic`
**Student:** <Full Name> (<BS / MS / PhD / RA>, <Batch / Year>)
**Supervisor:** Dr. Muhammad Mohsin Khan — IBMALab, PAF-IAST
**Co-supervisor:** <Name, if any>
**Group members:** <Names — for group FYPs only>
**Status:** 🟡 In progress | 🟢 Completed | 📄 Published
**Period:** <Start month/year> – <End month/year>

---

## 1. Overview
<2–4 sentences: the problem, why it matters, and your approach.>

## 2. Objectives
- <Objective 1>
- <Objective 2>
- <Objective 3>

## 3. Dataset
| Item | Details |
|------|---------|
| Name | <e.g. BCI Competition IV 2a> |
| Source / link | <URL or "lab internal"> |
| Size | <# subjects, # samples> |
| Location | <Path on lab storage / how to request access> |
| License / ethics | <license, IRB/ethics approval no.> |

> ⚠️ Data is **not** stored in this repository. See `data/README.md`.
> If the dataset is too large for GitHub, give the **download link** and **how to access it** (permission, registration, licence) and **where to place it** locally.

**Data access (for large datasets):**
- Link: <URL to shared drive / cloud folder / public source>
- Access: <who to contact, registration or data-use agreement needed>
- Download & placement: <steps or commands; e.g. put files in `data/raw/`>
- Size / version: <e.g. 45 GB, v2.1, downloaded 2026-11>

## 4. Method
<Short description of pipeline: preprocessing → features → model → evaluation. Add a diagram if helpful.>

## 5. Repository Structure
```
code/          source code
notebooks/     exploration notebooks
configs/       experiment configurations
data/          data README only
results/       figures and tables
docs/          notes, thesis drafts
```

## 6. Setup
```bash
git clone git@github.com:IBMALab/<repo-name>.git
cd <repo-name>
conda create -n <env-name> python=3.10
conda activate <env-name>
pip install -r requirements.txt
```
**Tested with:** Python <x.x> / MATLAB <R20xx>, <GPU / CUDA version>

## 7. How to Run
```bash
# Preprocess
python code/preprocessing/run_preprocess.py --config configs/default.yaml
# Train
python code/train.py --config configs/default.yaml
# Evaluate
python code/evaluate.py --checkpoint <path>
```

## 8. Results
| Model | Accuracy | F1 | <Other metric> |
|-------|----------|----|----------------|
| <Baseline> | | | |
| <Proposed> | | | |

<Key figure: `![result](results/figures/main_result.png)`>

## 9. Publications / Thesis
- <Author(s), "Title," Venue, Year. DOI/link>
- Thesis: <Title, PAF-IAST, Year>

## 10. Citation
```bibtex
@article{<key>,
  title   = {<Title>},
  author  = {<Authors>},
  journal = {<Journal>},
  year    = {<Year>}
}
```

## 11. Contact
<Student name> — <email>
Supervisor: Dr. Muhammad Mohsin Khan
