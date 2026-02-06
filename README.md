# RAD-IQMRI: A Benchmark for MRI Image Quality Assessment

Official repository for the RAD-IQMRI radiologist-rated MRI image quality assessment benchmark dataset and related documentation.

## 📄 Paper

Yueran Ma, Jianxun Lou, Jean-Yves Tanguy, Padraig Corcoran, Hantao Liu  
RAD-IQMRI: A Benchmark for MRI Image Quality Assessment  
Neurocomputing, 2024

Journal page:
https://www.sciencedirect.com/science/article/pii/S0925231224010634

DOI:
https://doi.org/10.1016/j.neucom.2024.128292

---

## Overview

RAD-IQMRI is a radiologist-rated MRI image quality assessment (IQA) benchmark designed for perceptual image quality research in medical imaging.

The dataset was constructed through a fully controlled psychovisual experiment in which radiologists evaluated MRI images with systematically simulated artifacts. The dataset provides Mean Opinion Scores (MOS) that support benchmarking and development of objective IQA algorithms in clinically relevant MRI scenarios.

This repository provides dataset description, citation information, and controlled access instructions.

---

## Dataset Characteristics

RAD-IQMRI contains:

- 8 pristine MRI reference images
- 112 distorted MRI images
- 4 simulated artifact types:
  - ghosting
  - edge ghosting
  - white noise
  - colored noise
- 2 distortion energy levels (low and high)
- Multiple anatomical regions:
  - brain
  - liver
  - breast
  - fetus
  - hip
  - knee
  - spine

Artifacts were added to anatomical object regions rather than background areas.

---

## Subjective Quality Experiment

Subjective quality scores were obtained via a controlled radiologist study:

- 13 radiologists participated
- Conducted in a clinical radiology reading room
- Simultaneous Double Stimulus (SDS) protocol
- Reference and distorted images shown side-by-side
- Continuous quality scale from 0 to 100
- Training phase performed before formal scoring
- No zoom or window-level adjustment allowed
- Outlier rejection applied
- Z-score normalization applied across observers
- Final labels provided as Mean Opinion Scores (MOS)

---

## Intended Research Use

RAD-IQMRI is intended for:

- MRI image quality assessment research
- Objective IQA algorithm benchmarking
- Medical perceptual quality modeling
- Transfer learning from natural image IQA to medical IQA
- Radiologist perception and observer-study research

---

## Dataset Access

Due to controlled-use and ethical requirements, the dataset is **not directly distributed via GitHub**.

Access is provided upon request for academic non-commercial research.

### Request Procedure

1. Download and complete the agreement form:

📄 **[Download Data Usage Agreement](agreement/RAD-IQMRI_Data_Usage_Agreement_v1.0.pdf)**

2. Sign the form

3. Send the signed PDF to:

   **[mayueranmyr@gmail.com]**

4. Approved applicants will receive dataset access instructions.

---

## Usage Restrictions

Permitted:

- Academic research use
- Non-commercial use
- Method development and benchmarking

Not permitted:

- Commercial use
- Dataset redistribution
- Public mirroring
- Clinical decision making
- Re-identification attempts

All images are de-identified.

---

## Citation

If you use the RAD-IQMRI dataset, please cite:

@article{ma2024rad,
  title={RAD-IQMRI: A benchmark for MRI image quality assessment},
  author={Ma, Yueran and Lou, Jianxun and Tanguy, Jean-Yves and Corcoran, Padraig and Liu, Hantao},
  journal={Neurocomputing},
  volume={602},
  pages={128292},
  year={2024}
}

---

## Data Availability Statement

Consistent with the published paper:

Data will be made available on request.

---

## Ethical Notes

- Images are de-identified
- No personal health information is included
- Released for research purposes only
- Not for clinical use

---

## Contact

Dataset access requests and questions:

[Yueran Ma]  
[mayueranmyr@gmail.com]
