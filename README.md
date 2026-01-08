# CSF-50K

CSF-50K is a **50,000-pair** dataset of crack images and **pixel-accurate binary masks** designed for benchmarking **crack segmentation**, with emphasis on (i) **thin-structure topology** (hairline cracks), (ii) **strict mask–image alignment**, and (iii) **appearance diversity** (illumination, texture, and common confounders such as shadows, joints, stains, and markings).

## Paper / preprint

CSF-50K is released with the *“CrackSegFlow: Controllable Flow Matching Synthesis for Generalizable Crack Segmentation with a 50K Image–Mask Benchmark”* paper, which is **under review**.  
**Preprint:** https://arxiv.org/abs/2601.03637

## Download

- **CSF-50K (Google Drive, ~6 GB):**  
  https://drive.google.com/file/d/1M9ta2NYTee3KM0iLUbQxt97MCw_GO2MN/view?usp=sharing

## Dataset structure

CSF-50K is split into **train/val/test = 40,000 / 5,000 / 5,000** with paired images and masks:

```text
CSF-50K/
  train/
    images/
    masks/
  val/
    images/
    masks/
  test/
    images/
    masks/```

Each image has a corresponding mask with the same filename stem (one-to-one pairing).

Data use policy (academic use only)

CSF-50K is released for academic research use only.
By downloading or using this dataset, you agree to:

use it only for non-commercial research and educational purposes;

not redistribute the dataset files (please share the official download link instead);

include the citation below in publications or public reports that use CSF-50K.

Citation

Please cite the arXiv preprint:

@article{asadi2026cracksegflow,
  title         = {CrackSegFlow: Controllable Flow Matching Synthesis for Generalizable Crack Segmentation with a 50K Image--Mask Benchmark},
  author        = {Asadi, Babak and Wu, Peiyang and Golparvar-Fard, Mani and Hajj, Ramez},
  journal       = {arXiv},
  year          = {2026},
  eprint        = {2601.03637},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CV}
}
