# BOLDLagMapping

contact: Toshihiko ASO aso.toshihiko@gmail.com / https://www.researchgate.net/profile/Toshihiko_Aso

## Extraction and removal of the sLFO with its time-lag structure in 4D blood oxygenation level dependent (BOLD) signal MRI data

![lagmaps](https://github.com/RIKEN-BCIL/BOLDLagMapping/blob/master/LagMaps.jpg)
![lagmap_anim](https://github.com/RIKEN-BCIL/BOLDLagMapping/blob/master/lagmap_anim.gif)
![sLFO_anim](https://github.com/RIKEN-BCIL/BOLDLagMapping/blob/master/Lag_model_anim100.gif)

### Dependencies
For Linux/Mac. MATLAB scripts call [FSL][] commands and [SPM12] functions.
FSL6 + niimath or FSL5's fslmaths needed for resampling in "Einsteining" scripts.
Install FSL & MATLAB then evoke MATLAB from the shell.

[FSL]: https://fsl.fmrib.ox.ac.uk/fsl/fslwiki "FSL"
[SPM12]: https://www.fil.ion.ucl.ac.uk/spm/software/spm12/

### Usage

**drLag4D** for tracking and **drDeperf** for deperfusioning.
**Einsteining** is the pipeline script.

![smoothnoisestructure](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9c/Hybrid_image_decomposition.jpg/256px-Hybrid_image_decomposition.jpg)

BOLD deperfusioning is extracting Einstein (neurovascular coupling) by removing Marilyn Monroe (perfusion structure) from this image.

### References

Recursive tracking

[Aso, T., Urayama, S., Hidenao, F., & Murai, T. (2019). Axial variation of deoxyhemoglobin density as a source of the low-frequency time lag structure in blood oxygenation level-dependent signals. PLoS ONE.](https://doi.org/10.1371/journal.pone.0222787) [(Correction here)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0225489)

[Nishida, S., Aso, T., Takaya, S., Takahashi, Y., Kikuchi, T., Funaki, T., … Miyamoto, S. (2018). Resting-state Functional Magnetic Resonance Imaging Identifies Cerebrovascular Reactivity Impairment in Patients With Arterial Occlusive Diseases: A Pilot Study. Neurosurgery, 85(5), 680-688.](https://doi.org/10.1093/neuros/nyy434)

[Aso, T., Jiang, G., Urayama, S. I., & Fukuyama, H. (2017). A resilient, non-neuronal source of the spatiotemporal lag structure detected by bold signal-based blood flow tracking. Frontiers in Neuroscience, 11(MAY), 1-13.](https://doi.org/10.3389/fnins.2017.00256)

Fixed-seed tracking

[Aso, T., Sugihara, G., Murai, T., Ubukata, S., Urayama, S., Ueno, T., Fujimoto, G., Thuy, D., Fukuyama, H., & Ueda, K. (2020). A venous mechanism of ventriculomegaly shared between traumatic brain injury and normal ageing. Brain, 143(JUN)](https://doi.org/10.1093/brain/awaa125)

[Satow, T., Aso, T., Nishida, S., Komuro, T., Ueno, T., Oishi, N., … Fukuyama, H. (2017). Alteration of venous drainage route in idiopathic normal pressure hydrocephalus and normal aging. Frontiers in Aging Neuroscience, 9(NOV), 1–10.](https://doi.org/10.3389/fnagi.2017.00387)

