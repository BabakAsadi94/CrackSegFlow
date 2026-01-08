# CSF-50K: 50,000 crack image–mask pairs

CSF-50K is a 50,000-pair dataset of crack images and pixel-accurate binary masks designed for benchmarking **crack segmentation**, with emphasis on (i) **thin-structure topology** (hairline cracks), (ii) **strict mask–image alignment**, and (iii) **appearance diversity** (illumination, texture, and common confounders such as shadows, joints, stains, and markings).

This repository hosts **dataset documentation and download links** (the dataset is not stored in GitHub due to size).

---

## Paper / preprint

CSF-50K is released with the *“CrackSegFlow: Controllable Flow Matching Synthesis for Generalizable Crack Segmentation with a 50K Image–Mask Benchmark”* paper, which is **under review**.  
**Preprint:** https://arxiv.org/abs/2601.03637

---

## Download

- **CSF-50K (Google Drive, ~6 GB):**  
  https://drive.google.com/file/d/1M9ta2NYTee3KM0iLUbQxt97MCw_GO2MN/view?usp=sharing

> Recommended: the Google Drive link is a mirror/convenience link. If/when a DOI repository link is available (e.g., Mendeley Data), it should be considered the primary archival location.

---

## Quickstart (extraction)

### If the archive is `.rar`
On Linux/macOS, the simplest option is `7z`:

```bash
# Ubuntu/Debian
sudo apt-get update && sudo apt-get install -y p7zip-full

# Extract
7z x CSF-50K.rar
