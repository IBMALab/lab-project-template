# Data

> ⚠️ **Do NOT commit data to this repository.** Everything in `data/` except this README is ignored by `.gitignore`.
> Patient data, medical images, raw EEG and any identifiable data must never be pushed to GitHub.

Fill in the sections below so anyone in the lab can get the exact same data.

## 1. Dataset
| Item | Details |
|------|---------|
| Name | <e.g. BCI Competition IV 2a> |
| Description | <what the data contains: modality, subjects, classes> |
| Size | <e.g. 45 GB, 9 subjects, 288 trials each> |
| Version / date obtained | <e.g. v2.1, downloaded 2026-11> |
| License / ethics | <license, IRB / ethics approval no., data-use agreement> |

## 2. Where the data is (link)
- **Link:** <URL to shared drive / cloud folder / public source (PhysioNet, OpenNeuro, Kaggle, ...)>
- **Lab storage path (if any):** <e.g. \\lab-server\datasets\EEG\BCI-IV-2a>

## 3. How to get access
- <Who to contact for permission (PI / data owner)>
- <Registration, login or data-use agreement required>
- <Any restrictions: lab computers only, no copying outside the lab, etc.>

## 4. How to download and where to put it
```bash
# Example
mkdir -p data/raw
# download / copy the files into data/raw/
```
Expected layout after download:
```
data/
├── README.md        ← this file (the only file committed)
├── raw/             ← original data, never modified
└── processed/       ← created by code/preprocessing scripts
```

## 5. Integrity check (optional)
- Checksum: <e.g. SHA-256 of the archive>
