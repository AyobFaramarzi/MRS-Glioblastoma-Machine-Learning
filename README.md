# MRS-Glioblastoma-Machine-Learning

## Semi-Automated Glioblastoma Tumor Detection Based on Different Classifiers Using Magnetic Resonance Spectroscopy

This repository presents a research project investigating semi-automated detection of glioblastoma tumor voxels using magnetic resonance spectroscopy (MRS) and machine learning classifiers.

The study focused on identifying metabolic features from MRS data and evaluating different classification methods for distinguishing glioblastoma tumor voxels from non-tumor voxels.

## Research Question

Can metabolic features obtained from magnetic resonance spectroscopy be used with machine learning classifiers to automatically distinguish glioblastoma tumor voxels from non-tumor voxels?

## Study Focus

- Glioblastoma multiforme (GBM)
- Magnetic resonance spectroscopy (MRS)
- Multivoxel MRS
- Medical imaging
- Machine learning
- Tumor detection
- Metabolite-based classification
- Support vector machines
- Neural networks

## Study Design

MRS data were obtained from 7 patients with glioblastoma multiforme.

A total of 293 voxels were analyzed using multivoxel proton magnetic resonance spectroscopy.

The MRS data were acquired using a 3 Tesla Siemens MAGNETOM Trio Tim MRI scanner with a Point-Resolved Spectroscopy (PRESS) sequence.

Acquisition parameters included:

- TE = 135 ms
- TR = 1570 ms

## MRS Processing

SIVIC was used for visualization and determination of the MRS voxel locations.

TARQUIN was used for water suppression, preprocessing, and metabolite quantification.

The metabolite features selected for classification included:

- Choline (Cho)
- N-Acetylaspartate (NAA)

## Machine Learning

Different machine learning and classification approaches were evaluated for glioblastoma tumor detection.

The evaluated classifiers included:

- Multilayer Perceptron (MLP)
- Linear Support Vector Machine (SVM)
- Gaussian Support Vector Machine (SVM)
- Fuzzy classification

The Gaussian SVM achieved the best classification performance, with:

- Training accuracy = 89.7%
- Testing accuracy = 87%

The fuzzy classifier using four membership functions achieved a testing accuracy of 82.5%.

## Research Workflow

```text
Multivoxel MRS
        ↓
SIVIC
        ↓
Voxel Selection
        ↓
TARQUIN Processing
        ↓
Metabolite Quantification
        ↓
Feature Selection
        ↓
Cho + NAA
        ↓
Machine Learning Classification
        ↓
MLP / Linear SVM / Gaussian SVM / Fuzzy
        ↓
Glioblastoma Tumor Detection
```

## Software and Tools

- SIVIC
- TARQUIN
- MATLAB
- Machine Learning Classifiers

## Earlier Work

An earlier study investigated glioblastoma detection using magnetic resonance spectroscopy and Support Vector Machine classification.

**Detection of Glioblastoma Multiforme Tumor in Magnetic Resonance Spectroscopy Based on Support Vector Machine**

This work represents an earlier stage of my research on MRS-based glioblastoma detection and machine learning.

## Publication

Faramarzi, A., Loghmani, N., Moqadam, R., Allahverdy, A., & Siyah Mansoory, M. (2021).

**Semi-Automated Glioblastoma Tumor Detection Based on Different Classifiers Using Magnetic Resonance Spectroscopy.**

*Frontiers in Biomedical Technologies, 8(3), 183–190.*

## Author

**Ayob Faramarzi**

Biomedical Engineering | Neuroimaging | fMRI | MRS | Brain Connectivity | Machine Learning
