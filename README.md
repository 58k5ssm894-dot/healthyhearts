# healthyhearts

Educational clinical decision support for **urgent care and primary care** clinicians ordering (or deferring) resting echocardiography when echo capacity is limited.

## Tools

### Ambulatory Echo Stewardship (default)

Safety gate → presentation-based path → recommendation with:

- **At this encounter**
- **Next test / pathway** (resting TTE, exercise ECG, stress imaging/CCTA, PE pathway, or no imaging)
- **Avoid**
- **Rationale** (AUC / guideline anchors)
- **If clinical picture changes**

Collegial CDS tone for physicians and APPs — not patient-facing copy.

### Echo Stewardship (AUC v1)

Prior decision tree kept for comparison (also frozen on branch `archive/v1-auc-stewardship` / tag `v1-auc-stewardship`).

## Sources

Simplified educational map (not a complete AUC catalog):

- 2011 Multisociety AUC for Echocardiography  
- 2019 Multimodality AUC (nonvalvular heart disease)  
- 2021 AHA/ACC Chest Pain Guideline  
- 2023 Multimodality AUC for Chronic Coronary Disease  

## Use

Open `index.html` or the GitHub Pages site. For qualified professionals only — supplement to clinical judgment and local protocol.
