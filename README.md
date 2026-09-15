# 🧬 Awesome Virtual Staining

<p align="center">
  <b>A curated collection of papers on virtual staining, digital staining, and in-silico staining.</b><br>
  <sub>Computational pathology · Label-free microscopy · Virtual H&E · Virtual IHC/IF · Stain translation · Generative AI</sub>
</p>

<p align="center">
  <a href="#reviews">Reviews</a> ·
  <a href="#label-free-h-e">Label-Free H&E</a> ·
  <a href="#virtual-ihc-if">Virtual IHC / IF</a> ·
  <a href="#stain-to-stain">Stain-to-Stain</a> ·
  <a href="#virtual-fluorescence">Virtual Fluorescence</a> ·
  <a href="#foundational">Foundational</a> ·
  <a href="#clinical-validation">Clinical Validation</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Coverage-2005--2026-405DE6?style=flat-square" alt="Coverage">
  <img src="https://img.shields.io/badge/Focus-Virtual%20Staining-7A5195?style=flat-square" alt="Focus">
  </p>

> [!NOTE]
> This repository focuses on **research papers**. The main body is organized by staining task and input/output modality rather than by publication venue.

## ✨ Table of Contents

- [Reviews](#reviews)
- [Label-Free Virtual H&E / Histological Staining](#label-free-h-e)
- [Virtual IHC / Immunofluorescence / Molecular Staining](#virtual-ihc-if)
- [Stain-to-Stain Translation / Virtual Restaining](#stain-to-stain)
- [Virtual Fluorescence / In-Silico Labeling](#virtual-fluorescence)
- [Other Early / Foundational Digital Staining](#foundational)
- [Clinical / Validation-Oriented Virtual Staining](#clinical-validation)
- [Scope & Terminology](#scope-terminology)


<a id="reviews"></a>

## 📚 Reviews

> Start here for an overview of the field, terminology, challenges, and clinical translation.

| Year | Paper | Venue |
|---|---|---|
| 2026 | [A systematic review of machine learning for digital stain processing in pathology](https://doi.org/10.1016/j.neucom.2026.133064) | *Neurocomputing* |
| 2026 | [Virtual histological staining: toward standardization and clinical translation](https://pubmed.ncbi.nlm.nih.gov/42603942/) | *Biomedical Engineering Frontiers* |
| 2025 | [Virtual staining for pathology: Challenges, limitations and perspectives](https://doi.org/10.1016/j.intonc.2025.03.005) | *Intelligent Oncology* |
| 2024 | [Virtual staining for histology by deep learning](https://doi.org/10.1016/j.tibtech.2024.02.009) | *Trends in Biotechnology* |
| 2023 | [Digital staining in optical microscopy using deep learning — a review](https://doi.org/10.1186/s43074-023-00113-4) | *PhotoniX* |
| 2023 | [Deep learning-enabled virtual histological staining of biological samples](https://doi.org/10.1038/s41377-023-01104-7) | *Light: Science & Applications* |
| 2022 | [Virtual tissue staining in pathology using machine learning](https://doi.org/10.1080/14737159.2022.2153040) | *Expert Review of Molecular Diagnostics* |
| 2020 | [Emerging advances to transform histopathology using virtual staining](https://doi.org/10.1186/s43074-020-00020-1) | *BME Frontiers* |


<a id="label-free-h-e"></a>

## Label-Free Virtual H&E / Histological Staining
> Label-free or minimally labeled imaging → H&E / histological appearance.

| Year | Paper | Venue | Input |
|---|---|---|---|
| 2026 | [High-precision label-free virtual H&E staining of 3D holotomography using DAPI-guided conditional diffusion learning](https://doi.org/10.1007/s11548-026-03651-x) | *International Journal of Computer Assisted Radiology and Surgery* | 3D holotomography |
| 2026 | [Generative AI for misalignment-resistant virtual staining to accelerate histopathology workflows](https://doi.org/10.1038/s41467-026-71038-2) | *Nature Communications* | label-free / paired tissue |
| 2026 | [ViT-Stain: Vision transformer-driven virtual staining for skin histopathology via global contextual learning](https://doi.org/10.1371/journal.pone.0341311) | *PLOS ONE* | unstained microscopy |
| 2026 | [FPM2Stain Net: physics-guided super-resolution and multi-modal virtual staining for digital histopathology](https://doi.org/10.1364/BOE.586327) | *Biomedical Optics Express* | Fourier ptychography / multimodal |
| 2026 | [Label-free whole slide virtual multi-staining using dual-excitation photon absorption remote sensing microscopy](https://doi.org/10.1038/s44303-026-00154-x) | *npj Imaging* | DE-PARS |
| 2025 | [Pixel super-resolved virtual staining of label-free tissue using diffusion models](https://doi.org/10.1038/s41467-025-60387-z) | *Nature Communications* | autofluorescence |
| 2025 | [Fast and label-free 3D virtual H&E histology via active phase modulation-assisted dynamic full-field OCT](https://doi.org/10.1038/s44303-025-00068-0) | *npj Imaging* | OCT |
| 2025 | [Pathology-aware Virtual H&E Staining of Section-free Thick Tissues with Semantic Contrastive Guidance](https://doi.org/10.1007/978-3-032-04981-0_40) | *MICCAI 2025* | fluorescence light-sheet microscopy |
| 2025 | [Deep learning based label-free virtual staining and classification of human tissues using digital slide scanner](https://doi.org/10.1016/j.media.2025.103865) | *Medical Image Analysis* | unstained bright-field |
| 2024 | [Virtual histological staining of unlabeled autopsy tissue](https://doi.org/10.1038/s41467-024-46077-2) | *Nature Communications* | autofluorescence |
| 2024 | [Deep learning-based virtual H&E staining from label-free autofluorescence lifetime images](https://doi.org/10.1038/s44303-024-00021-7) | *npj Imaging* | FLIM |
| 2024 | [Deep learning for rapid virtual H&E staining of label-free glioma tissue from hyperspectral images](https://doi.org/10.1016/j.compbiomed.2024.108958) | *Computers in Biology and Medicine* | hyperspectral |
| 2024 | [Deep learning-based virtual staining, segmentation, and classification in label-free photoacoustic histology of human specimens](https://doi.org/10.1038/s41377-024-01554-7) | *Light: Science & Applications* | photoacoustic histology |
| 2024 | [Virtual birefringence imaging and histological staining of amyloid deposits in label-free tissue using autofluorescence microscopy and deep learning](https://doi.org/10.1038/s41467-024-52263-z) | *Nature Communications* | autofluorescence |
| 2023 | [Deep learning-enabled realistic virtual histology with ultraviolet photoacoustic remote sensing microscopy](https://doi.org/10.1038/s41467-023-41574-2) | *Nature Communications* | UV-PARS |
| 2023 | [Label-free intraoperative histology of bone tissue via deep-learning-assisted ultraviolet photoacoustic microscopy](https://doi.org/10.1038/s41551-022-00940-z) | *Nature Biomedical Engineering* | UV-PAM |
| 2022 | [Deep learning enables ultraviolet photoacoustic microscopy based histological imaging with near real-time virtual staining](https://doi.org/10.1016/j.pacs.2021.100308) | *Photoacoustics* | UV-PAM |
| 2022 | [Deep-Learning-Based Virtual H&E Staining Using Total-Absorption Photoacoustic Remote Sensing (TA-PARS)](https://doi.org/10.1038/s41598-022-14042-y) | *Scientific Reports* | TA-PARS |
| 2021 | [Biopsy-free in vivo virtual histology of skin using deep learning](https://doi.org/10.1038/s41377-021-00674-8) | *Light: Science & Applications* | in-vivo microscopy |
| 2021 | [Computational tissue staining of non-linear multimodal imaging using supervised and unsupervised deep learning](https://doi.org/10.1364/BOE.415962) | *Biomedical Optics Express* | nonlinear multimodal |
| 2020 | [Deep Learning for Virtual Histological Staining of Bright-Field Microscopic Images of Unlabeled Carotid Artery Tissue](https://doi.org/10.1007/s11307-020-01508-6) | *Molecular Imaging and Biology* | bright-field |
| 2020 | [Global Pixel Transformers for Virtual Staining of Microscopy Images](https://doi.org/10.1109/TMI.2020.2968504) | *IEEE Transactions on Medical Imaging* | microscopy |
| 2020 | [Holographic virtual staining of individual biological cells](https://doi.org/10.1073/pnas.1919569117) | *PNAS* | digital holography |
| 2019 | [PhaseStain: the digital staining of label-free quantitative phase microscopy images using deep learning](https://doi.org/10.1038/s41377-019-0129-y) | *Light: Science & Applications* | QPI |
| 2019 | [Virtual histological staining of unlabelled tissue-autofluorescence images via deep learning](https://doi.org/10.1038/s41551-019-0362-y) | *Nature Biomedical Engineering* | autofluorescence |
| 2019 | [Digital staining through the application of deep neural networks to multi-modal multi-photon microscopy](https://doi.org/10.1364/BOE.10.001339) | *Biomedical Optics Express* | multiphoton |
| 2018 | [Towards Virtual H&E Staining of Hyperspectral Lung Histology Images Using Conditional Generative Adversarial Networks](https://doi.org/10.1109/ICCVW.2017.15) | *ICCV Workshops* | hyperspectral |


<a id="virtual-ihc-if"></a>

## Virtual IHC / Immunofluorescence / Molecular Staining
> Computational prediction of molecular or immunostaining channels from routine or label-free imaging.

| Year | Paper | Venue | Direction |
|---|---|---|---|
| 2026 | [PGVMS: A Prompt-Guided Unified Framework for Virtual Multiplex IHC Staining With Pathological Semantic Learning](https://doi.org/10.1109/TMI.2026.3663755) | *IEEE Transactions on Medical Imaging* | H&E → multiplex IHC |
| 2026 | [M2PL-GAN: Multi-View Multi-Level Pathology Semantic Perception Learning for H&E-to-IHC Virtual Staining](https://doi.org/10.1109/TMI.2026.3668248) | *IEEE Transactions on Medical Imaging* | H&E → IHC |
| 2026 | [Virtual Multiplex Staining for Histological Images Using a Marker-Wise Conditioned Diffusion Model](https://doi.org/10.1609/aaai.v40i10.37764) | *AAAI 2026* | H&E → multiplex IF |
| 2025 | [ODA-GAN: Orthogonal Decoupling Alignment GAN Assisted by Weakly-supervised Learning for Virtual Immunohistochemistry Staining](https://openaccess.thecvf.com/content/CVPR2025/html/Wang_ODA-GAN_Orthogonal_Decoupling_Alignment_GAN_Assisted_by_Weakly-supervised_Learning_for_CVPR_2025_paper.html) | *CVPR 2025* | unpaired H&E → IHC |
| 2025 | [Score-based Diffusion Model for Unpaired Virtual Histology Staining](https://arxiv.org/abs/2506.23184) | *arXiv* | unpaired H&E → IHC |
| 2025 | [From pixels to pathology: Restoration diffusion for diagnostic-consistent virtual IHC](https://doi.org/10.1016/j.compbiomed.2025.111264) | *Computers in Biology and Medicine* | H&E → IHC |
| 2025 | [PD-UniST: Prompt-Driven Universal Model for Unpaired H&E-to-IHC Stain Translation](https://papers.miccai.org/miccai-2025/0685-Paper1617.html) | *MICCAI 2025* | unpaired H&E → IHC |
| 2025 | [D-VST: Diffusion Transformer for Pathology-Correct Tone-Controllable Cross-Dye Virtual Staining of Whole Slide Images](https://proceedings.neurips.cc/paper_files/paper/2025/hash/048445f5e3321dc9721930b15ba9387b-Abstract-Conference.html) | *NeurIPS 2025* | cross-dye / WSI |
| 2025 | [Diffusion-based Virtual Staining from Polarimetric Mueller Matrix Imaging](https://papers.miccai.org/miccai-2025/0239-Paper3549.html) | *MICCAI 2025* | polarimetric → stain |
| 2025 | [Unpaired Multi-Domain Histopathology Virtual Staining Using Dual Path Prompted Inversion](https://doi.org/10.1609/aaai.v39i8.32949) | *AAAI 2025* | unpaired multi-domain |
| 2024 | [Virtual Immunohistochemistry Staining for Histological Images Assisted by Weakly-supervised Learning](https://openaccess.thecvf.com/content/CVPR2024/papers/Li_Virtual_Immunohistochemistry_Staining_for_Histological_Images_Assisted_by_Weakly-supervised_Learning_CVPR_2024_paper.pdf) | *CVPR 2024* | unpaired H&E → IHC |
| 2022 | [Deep learning-inferred multiplex immunofluorescence for immunohistochemical image quantification](https://doi.org/10.1038/s42256-022-00464-8) | *Nature Machine Intelligence* | H&E → multiplex IF |
| 2021 | [Deep learning-based virtual cytokeratin staining of gastric carcinomas to measure tumor-stroma ratio](https://doi.org/10.1038/s41598-021-98857-1) | *Scientific Reports* | H&E → cytokeratin |
| 2020 | [A machine learning algorithm for simulating immunohistochemistry: development of SOX10 virtual IHC and evaluation on primarily melanocytic neoplasms](https://doi.org/10.1038/s41377-020-01248-2) | *Modern Pathology* | H&E → SOX10 IHC |
| 2020 | [Effective Immunohistochemistry Pathology Microscopy Image Generation Using CycleGAN](https://doi.org/10.3389/fmolb.2020.571180) | *Frontiers in Molecular Biosciences* | stain translation |
| 2018 | [SHIFT: speedy histopathological-to-immunofluorescent translation of whole slide images using conditional generative adversarial networks](https://doi.org/10.1117/12.2293249) | *SPIE Medical Imaging* | histology → IF |
| 2018 | [In Silico Labeling: Predicting Fluorescent Labels in Unlabeled Images](https://doi.org/10.1016/j.cell.2018.03.040) | *Cell* | label-free → IF |


<a id="stain-to-stain"></a>

## Stain-to-Stain Translation / Virtual Restaining
> One histological stain → another stain or special stain.

| Year | Paper | Venue | Direction |
|---|---|---|---|
| 2026 | [Generative AI for misalignment-resistant virtual staining to accelerate histopathology workflows](https://doi.org/10.1038/s41467-026-71038-2) | *Nature Communications* | misaligned stain pairs |
| 2026 | [General Pathologists Achieve Near-Specialist Diagnostic Performance Using Deep Learning–Based Virtual Staining for Donor Kidney Assessment](https://doi.org/10.1016/j.labinv.2026.106077) | *Laboratory Investigation* | H&E → Masson's trichrome |
| 2026 | [MCS-Stain: Boosting FFPE-to-HE Virtual Staining With Multiple Cell Semantics](https://doi.org/10.1109/TMI.2025.3628174) | *IEEE Transactions on Medical Imaging* | FFPE → H&E |
| 2025 | [Virtual Histological Staining as a Tool for Extending Renal Segmentation Across Stains](https://doi.org/10.1016/j.modpat.2025.100842) | *Modern Pathology* | H&E → PAS |
| 2022 | [Virtual stain transfer in histology via cascaded deep neural networks](https://doi.org/10.1021/acsphotonics.2c00932) | *ACS Photonics* | stain → stain |
| 2022 | [Image-to-Images Translation for Multiple Virtual Histological Staining of Unlabeled Human Carotid Atherosclerotic Tissue](https://doi.org/10.1007/s11307-021-01641-w) | *Molecular Imaging and Biology* | multiple stains |
| 2021 | [Deep learning-based transformation of H&E stained tissues into special stains](https://doi.org/10.1038/s41467-021-21406-8) | *Nature Communications* | H&E → special stains |
| 2021 | [Mutual stain conversion between Giemsa and Papanicolaou in cytological images using cycle generative adversarial network](https://doi.org/10.1016/j.heliyon.2021.e06331) | *Heliyon* | Giemsa ↔ Pap |
| 2020 | [Re-staining pathology images by FCNN](https://doi.org/10.1109/MVA.2019.8886167) | *MVA 2019* | stain → stain |
| 2019 | [Stain-Transforming Cycle-Consistent Generative Adversarial Networks for Improved Segmentation of Renal Histopathology](https://proceedings.mlr.press/v102/de-bel19a.html) | *MIDL 2019* | stain transformation |
| 2017 | [Virtual staining of colon cancer tissue by label-free Raman micro-spectroscopy](https://doi.org/10.1039/C6AN02072K) | *Analyst* | Raman → histology |


<a id="virtual-fluorescence"></a>

## Virtual Fluorescence / In-Silico Labeling
> Label-free imaging → fluorescence, organelle, or molecular signal.

| Year | Paper | Venue | Input |
|---|---|---|---|
| 2025 | [Robust virtual staining of landmark organelles with Cytoland](https://doi.org/10.1038/s42256-025-01046-2) | *Nature Machine Intelligence* | label-free microscopy |
| 2025 | [DiffStain: Conditioned Diffusion-Based Semantic Virtual Staining with Mask Guidance](https://papers.miccai.org/miccai-2025/0235-Paper2432.html) | *MICCAI 2025* | label-free microscopy |
| 2022 | [Artificial confocal microscopy for deep label-free imaging](https://doi.org/10.1038/s41566-022-01140-6) | *Nature Photonics* | label-free |
| 2022 | [Fluo-Fluo translation based on deep learning](https://doi.org/10.3788/COL202220.031701) | *Chinese Optics Letters* | fluorescence → fluorescence |
| 2021 | [Single-cell cytometry via multiplexed fluorescence prediction by label-free reflectance microscopy](https://doi.org/10.1126/sciadv.abe0431) | *Science Advances* | reflectance → multiplex IF |
| 2021 | [Self-Organizing Maps for Cellular In Silico Staining and Cell Substate Classification](https://doi.org/10.3389/fimmu.2021.765923) | *Frontiers in Immunology* | label-free → fluorescence |
| 2021 | [Multiscale Assay of Unlabeled Neurite Dynamics Using Phase Imaging with Computational Specificity](https://doi.org/10.1021/acssensors.1c00100) | *ACS Sensors* | phase → fluorescence |
| 2021 | [Label-free multiplexed microtomography of endogenous subcellular dynamics using generalizable deep learning](https://doi.org/10.1038/s41556-021-00802-x) | *Nature Cell Biology* | label-free tomography |
| 2020 | [Revealing architectural order with quantitative label-free imaging and deep learning](https://doi.org/10.7554/eLife.55502) | *eLife* | label-free imaging |
| 2018 | [Label-free prediction of three-dimensional fluorescence images from transmitted-light microscopy](https://doi.org/10.1038/s41592-018-0111-2) | *Nature Methods* | transmitted light → 3D fluorescence |
| 2018 | [In Silico Labeling: Predicting Fluorescent Labels in Unlabeled Images](https://doi.org/10.1016/j.cell.2018.03.040) | *Cell* | phase → fluorescence |


<a id="foundational"></a>

## Other Early / Foundational Digital Staining
> Early computational and optical foundations of digital staining.

| Year | Paper | Venue |
|---|---|---|
| 2016 | [Pseudo-HE images derived from CARS/TPEF/SHG multimodal imaging in combination with Raman-spectroscopy as a pathological screening tool](https://doi.org/10.1186/s12885-016-2520-x) | *BMC Cancer* |
| 2016 | [Virtual Hematoxylin and Eosin Transillumination Microscopy Using Epi-Fluorescence Imaging](https://doi.org/10.1371/journal.pone.0159337) | *PLOS ONE* |
| 2015 | [Stain-less staining for computed histopathology](https://doi.org/10.13110/technology.3.1.27) | *Technology* |
| 2012 | [Digistain: a digital staining instrument for histopathology](https://doi.org/10.1364/OE.20.007290) | *Optics Express* |
| 2011 | [Digital staining for histopathology multispectral images by the combined application of spectral enhancement and spectral transformation](https://doi.org/10.1109/IEMBS.2011.6091976) | *IEEE EMBC* |
| 2005 | [Digital staining of pathological tissue specimens using spectral transmittance](https://doi.org/10.1117/12.595016) | *SPIE Medical Imaging* |
| 2005 | [Digital staining for multispectral images of pathological tissue specimens based on combined classification of spectral transmittance](https://doi.org/10.1016/j.compmedimag.2005.09.003) | *Computerized Medical Imaging and Graphics* |


<a id="clinical-validation"></a>

## Clinical / Validation-Oriented Virtual Staining
> Studies emphasizing diagnostic evaluation, robustness, and translational validation.

| Year | Paper | Venue |
|---|---|---|
| 2026 | [General Pathologists Achieve Near-Specialist Diagnostic Performance Using Deep Learning–Based Virtual Staining for Donor Kidney Assessment](https://doi.org/10.1016/j.labinv.2026.106077) | *Laboratory Investigation* |
| 2025 | [A robust and scalable framework for hallucination detection in virtual tissue staining and digital pathology](https://doi.org/10.1038/s41551-025-01421-9) | *Nature Biomedical Engineering* |
| 2024 | [Deep learning-based virtual staining, segmentation, and classification in label-free photoacoustic histology of human specimens](https://doi.org/10.1038/s41377-024-01554-7) | *Light: Science & Applications* |
| 2024 | [Virtual histological staining of unlabeled autopsy tissue](https://doi.org/10.1038/s41467-024-46077-2) | *Nature Communications* |
| 2021 | [Biopsy-free in vivo virtual histology of skin using deep learning](https://doi.org/10.1038/s41377-021-00674-8) | *Light: Science & Applications* |
| 2020 | [A machine learning algorithm for simulating immunohistochemistry: development of SOX10 virtual IHC and evaluation on primarily melanocytic neoplasms](https://pubmed.ncbi.nlm.nih.gov/32392471/) | *Modern Pathology* |


<a id="scope-terminology"></a>

## 🧭 Scope & Terminology

The literature uses overlapping terms including **virtual staining**, **digital staining**, **in-silico staining**, **virtual histology**, **virtual fluorescence**, **computational staining**, and **pseudo-H&E**.

This list follows a broad interpretation of the field and includes both:

- **Label-free → stain**: e.g. autofluorescence, QPI, OCT, photoacoustic, hyperspectral, Raman, and other optical modalities → H&E / IHC / IF / special stains.
- **Stain → stain**: e.g. H&E → IHC, IHC → IHC, or one special stain → another stain.

> The distinction between *virtual staining* and *stain translation* is not always consistent across the literature; papers are therefore grouped by their practical computational task.

## 🤝 Contributing

Contributions are welcome. Please keep entries focused on **peer-reviewed papers or high-impact recent preprints directly related to virtual staining** and follow the existing table format.

## ⭐ Star History

If this collection is useful to you, consider giving the repository a ⭐.

[![Star History Chart](https://api.star-history.com/svg?repos=diaoquesang/Awesome-Virtual-Staining&type=Date)](https://star-history.com/#diaoquesang/Awesome-Virtual-Staining&Date)

<p align="center">
  <sub>Curated for researchers in computational pathology, biomedical optics, medical image analysis, and generative modeling.</sub>
</p>
