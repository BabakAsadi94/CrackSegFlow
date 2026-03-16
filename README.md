# CSF-50K

CSF-50K is a **50,000-pair** dataset of crack images and **pixel-accurate binary masks** designed for benchmarking **crack segmentation**, with emphasis on (i) **thin-structure topology** and (iii) **appearance diversity** (illumination, texture, and common confounders such as shadows, joints, stains, and markings).

## Paper / preprint

CSF-50K is released with the *“CrackSegFlow: Controllable Flow Matching Synthesis for Generalizable Crack Segmentation with a 50K Image–Mask Benchmark”* paper, which is **under review**.  
**Preprint:** https://arxiv.org/abs/2601.03637

## Download

- **CSF-50K (Google Drive, ~5.5 GB):**  
https://drive.google.com/file/d/1jL6uI0LfHAQS6IoSHmeEoOuXXAXfE_MY/view?usp=sharing

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
    masks/
```

Each image has a corresponding mask with the same filename stem (one-to-one pairing).

## Data use policy (academic use only)

**CSF-50K is released for academic research use only.**  
By downloading or using this dataset, you agree to:

- use it only for non-commercial research and educational purposes;
- not redistribute the dataset files (please share the official download link instead);
- include the citation below in publications or public reports that use CSF-50K.

## Baseline models and checkpoints

The table below reports **test-set** performance on **CSF-50K** for released baseline models. We report both **volumetric metrics** (mIoU and Dice) and **topological metrics** (clDice and Betti matching error, <i>&mu;</i><sup>err</sup>). Checkpoints will be added as they are released. We appreciate users of CSF-50K sharing model performance and, when available, checkpoints, as this helps us keep the benchmark updated and maintain a broader comparison for the community.
<table>
  <thead>
    <tr>
      <th rowspan="2">Model</th>
      <th colspan="2">Volumetric (↑)</th>
      <th colspan="2">Topological</th>
      <th rowspan="2">Checkpoint</th>
    </tr>
    <tr>
      <th>mIoU</th>
      <th>Dice</th>
      <th>clDice ↑</th>
      <th><i>&mu;</i><sup>err</sup> ↓</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="">SegFlow</a></td>
      <td>NA</td>
      <td>NA</td>
      <td>NA</td>
      <td>NA</td>
      <td><a href="">Coming soon</a></td>
    </tr>
    <tr>
      <td><a href="https://arxiv.org/abs/2601.03637">U-MiT</a></td>
      <td>NA</td>
      <td>NA</td>
      <td>NA</td>
      <td>NA</td>
      <td><a href="">Coming soon</a></td>
    </tr>
    <tr>
      <td>To be completed</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
      <td>--</td>
    </tr>
  </tbody>
</table>

## Citation

Please cite the arXiv preprint:

```bibtex
@article{asadi2026cracksegflow,
  title         = {CrackSegFlow: Controllable Flow Matching Synthesis for Generalizable Crack Segmentation with a 50K Image--Mask Benchmark},
  author        = {Asadi, Babak and Wu, Peiyang and Golparvar-Fard, Mani and Hajj, Ramez},
  journal       = {arXiv},
  year          = {2026},
  eprint        = {2601.03637},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CV}
}
```
