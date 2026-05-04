[![DOI](https://img.shields.io/badge/DOI-10.82901%2Fnemar.nm000124-blue)](https://doi.org/10.82901/nemar.nm000124)

# SSVEP fatigue dataset with two frequency paradigms

SSVEP fatigue dataset with two frequency paradigms.

## Dataset Overview

- **Code**: Han2024Fatigue
- **Paradigm**: ssvep
- **DOI**: 10.1109/TNSRE.2024.3380635
- **Subjects**: 24
- **Sessions per subject**: 2
- **Events**: 8=1, 8.5=2, 9=3, 9.5=4, 10=5, 10.5=6, 11=7, 11.5=8, 12=9, 12.5=10, 13=11, 13.5=12, 14=13, 14.5=14, 15=15, 15.5=16, 25.5=17, 26=18, 26.5=19, 27=20, 27.5=21, 28=22, 28.5=23, 29=24, 29.5=25, 30=26, 30.5=27, 31=28, 31.5=29, 32=30, 32.5=31, 33=32
- **Trial interval**: [0.14, 2.14] s
- **File format**: MAT

## Acquisition

- **Sampling rate**: 1000.0 Hz
- **Number of channels**: 64
- **Channel types**: eeg=64
- **Channel names**: Fp1, Fpz, Fp2, AF3, AF4, F7, F5, F3, F1, Fz, F2, F4, F6, F8, FT7, FC5, FC3, FC1, FCz, FC2, FC4, FC6, FT8, T7, C5, C3, C1, Cz, C2, C4, C6, T8, M1, TP7, CP5, CP3, CP1, CPz, CP2, CP4, CP6, TP8, M2, P7, P5, P3, P1, Pz, P2, P4, P6, P8, PO7, PO5, PO3, POz, PO4, PO6, PO8, CB1, O1, Oz, O2, CB2
- **Montage**: standard_1005
- **Hardware**: Synamps2 (Neuroscan)
- **Reference**: Cz
- **Ground**: midway between Fz and FPz
- **Line frequency**: 50.0 Hz
- **Online filters**: {'bandpass_hz': [0.15, 200.0]}
- **Impedance threshold**: 10 kOhm

## Participants

- **Number of subjects**: 24
- **Health status**: healthy
- **Age**: min=18, max=26
- **Gender distribution**: male=12, female=12

## Experimental Protocol

- **Paradigm**: ssvep
- **Task type**: gaze-shifting
- **Number of classes**: 32
- **Class labels**: 8, 8.5, 9, 9.5, 10, 10.5, 11, 11.5, 12, 12.5, 13, 13.5, 14, 14.5, 15, 15.5, 25.5, 26, 26.5, 27, 27.5, 28, 28.5, 29, 29.5, 30, 30.5, 31, 31.5, 32, 32.5, 33
- **Trial duration**: 2.0 s
- **Feedback type**: none
- **Stimulus type**: JFPM visual flicker
- **Stimulus modalities**: visual
- **Primary modality**: visual
- **Synchronicity**: synchronous
- **Mode**: offline
- **Training/test split**: True

## HED Event Annotations

Schema: HED 8.4.0 | Browse: https://www.hedtags.org/hed-schema-browser

```
  8
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/8

  8.5
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/8_5

  9
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/9

  9.5
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/9_5

  10
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/10

  10.5
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/10_5

  11
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/11

  11.5
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/11_5

  12
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/12

  12.5
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/12_5

  13
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/13

  13.5
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/13_5

  14
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/14

  14.5
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/14_5

  15
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/15

  15.5
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/15_5

  25.5
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/25_5

  26
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/26

  26.5
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/26_5

  27
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/27

  27.5
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/27_5

  28
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/28

  28.5
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/28_5

  29
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/29

  29.5
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/29_5

  30
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/30

  30.5
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/30_5

  31
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/31

  31.5
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/31_5

  32
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/32

  32.5
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/32_5

  33
    ├─ Sensory-event
    ├─ Experimental-stimulus
    ├─ Visual-presentation
    └─ Label/33

```
## Paradigm-Specific Parameters

- **Detected paradigm**: ssvep
- **Stimulus frequencies**: [8.0, 8.5, 9.0, 9.5, 10.0, 10.5, 11.0, 11.5, 12.0, 12.5, 13.0, 13.5, 14.0, 14.5, 15.0, 15.5, 25.5, 26.0, 26.5, 27.0, 27.5, 28.0, 28.5, 29.0, 29.5, 30.0, 30.5, 31.0, 31.5, 32.0, 32.5, 33.0] Hz
- **Frequency resolution**: 0.5 Hz

## Data Structure

- **Trials**: 960 per frequency band (16 targets x 60 blocks)
- **Blocks per session**: 60
- **Trials context**: 6 training + 24 fatigue blocks per frequency condition

## Preprocessing

- **Data state**: epoched

## Signal Processing

- **Classifiers**: TRCA
- **Spatial filters**: TRCA

## BCI Application

- **Environment**: lab
- **Online feedback**: False

## Tags

- **Pathology**: healthy
- **Modality**: visual
- **Type**: perception

## Documentation

- **DOI**: 10.1109/TNSRE.2024.3380635
- **License**: CC BY 4.0
- **Investigators**: Yuheng Han, Yufeng Ke, Ruiyan Wang, Tao Wang, Dong Ming
- **Senior author**: Dong Ming
- **Institution**: Tianjin University
- **Department**: Academy of Medical Engineering and Translational Medicine, Tianjin University
- **Country**: CN
- **Repository**: Zenodo
- **Data URL**: https://zenodo.org/records/10507229
- **Publication year**: 2024
- **Funding**: National Key Research and Development Program of China (Grant 2021YFF1200603); National Natural Science Foundation of China (Grants 62276184, 61806141)
- **Ethics approval**: Research Ethics Committee of Tianjin University
- **Keywords**: SSVEP, BCI, fatigue, dynamic stopping, EEG

## References

Y. Han, Y. Ke, R. Wang, T. Wang, and D. Ming, "Enhancing SSVEP-BCI Performance Under Fatigue State Using Dynamic Stopping Strategy," IEEE Trans. Neural Syst. Rehab. Eng., vol. 32, pp. 1407-1415, 2024. DOI: 10.1109/TNSRE.2024.3380635
Appelhoff, S., Sanderson, M., Brooks, T., Vliet, M., Quentin, R., Holdgraf, C., Chaumon, M., Mikulan, E., Tavabi, K., Hochenberger, R., Welke, D., Brunner, C., Rockhill, A., Larson, E., Gramfort, A. and Jas, M. (2019). MNE-BIDS: Organizing electrophysiological data into the BIDS format and facilitating their analysis. Journal of Open Source Software 4: (1896). https://doi.org/10.21105/joss.01896

Pernet, C. R., Appelhoff, S., Gorgolewski, K. J., Flandin, G., Phillips, C., Delorme, A., Oostenveld, R. (2019). EEG-BIDS, an extension to the brain imaging data structure for electroencephalography. Scientific Data, 6, 103. https://doi.org/10.1038/s41597-019-0104-8

---
Generated by MOABB 1.4.3 (Mother of All BCI Benchmarks)
https://github.com/NeuroTechX/moabb
