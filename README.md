# Awesome Tampered Text Detection 
A curated collection of **papers, datasets, code, and tools** for detecting tampered text and forged documents.  

## Table of Contents
1. [Papers](#papers)
2. [Key Datasets](#key-datasets)
3. [Text Tampering Methods](#text-tampering-methods)
4. [References](#references)

---

## 📚 Papers

<div style="overflow-x:auto;">
<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>Paper</th>
      <th>Year</th>
      <th>Venue</th>
      <th>Method</th>
      <th>Dataset</th>
      <th>Train. Code</th>
      <th>Val. Code</th>
      <th>Infer. Code</th>
    </tr>
  </thead>
  <tbody>

  <tr>
    <td>Yang et al. <a href="#ref1">[1]</a> : Deep Learning + ELA fusion</td>
    <td>2022</td>
    <td>ISEEIE</td>
    <td>Deep learning + ELA fusion</td>
    <td>Ali Tianchi Competition</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr>
    <td>Wang et al. <a href="#ref2">[2]</a> : SR3</td>
    <td>2022</td>
    <td>ECCV</td>
    <td>SR3</td>
    <td><a href="https://github.com/wangyuxin87/Tampered-IC13">T-IC13</a></td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr>
    <td>Qu et al. <a href="#ref3">[3]</a> : DTD</td>
    <td>2023</td>
    <td>CVPR</td>
    <td>DTD</td>
    <td><a href="https://github.com/qcf-568/DocTamper">Doc-Tamper</a></td>
    <td>✅</td>
    <td>✅</td>
    <td>✅</td>
  </tr>

  <tr>
    <td>Okamoto et al. <a href="#ref4">[4]</a> : FCN</td>
    <td>2023</td>
    <td>arXiv</td>
    <td>FCN (semantic segmentation)</td>
    <td>FD-VIED</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr>
    <td>Jain <a href="#ref5">[5]</a> : K-Means, Decision Trees, Logistic Regression</td>
    <td>2024</td>
    <td>IRJET</td>
    <td>K-Means, Decision Trees, Logistic Regression</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr>
    <td>Chen et al. <a href="#ref6">[6]</a> : FFDN</td>
    <td>2024</td>
    <td>ECCV</td>
    <td>FFDN</td>
    <td><a href="https://github.com/qcf-568/DocTamper">Doc-Tamper</a></td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr>
    <td>Qu et al. <a href="#ref7">[7]</a> : TextSleuth / Tampered Text Detective</td>
    <td>2024</td>
    <td>arXiv</td>
    <td>TextSleuth / Tampered Text Detective</td>
    <td>ETTD</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr>
    <td>Shao et al.  <a href="#ref8">[8]</a> : DTL-ARob</td>
    <td>2024</td>
    <td>ECCV</td>
    <td>DTL-ARob</td>
    <td><a href="https://github.com/qcf-568/DocTamper">Doc-Tamper</a>, <a href="https://github.com/wangyuxin87/Tampered_sroie">T-SROIE</a></td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr>
    <td>Wang et al. <a href="#ref9">[9]</a> : SherlockNet</td>
    <td>2024</td>
    <td>IEEE TMM</td>
    <td>SherlockNet</td>
    <td>EN-HA</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr>
    <td>Li et al. <a href="#ref10">[10]</a> : Dual-path framework</td>
    <td>2024</td>
    <td>arXiv</td>
    <td>Dual-path framework</td>
    <td>Suning Scene Data</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr>
    <td>Liao et al. <a href="#ref11">[11]</a> : CTP-Net</td>
    <td>2023</td>
    <td>arXiv</td>
    <td>CTP-Net</td>
    <td>Fake Chinese Trademark (FCTM)</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr>
    <td>Li et al. <a href="#ref12">[12]</a> : MA-Net</td>
    <td>2024</td>
    <td>IEEE TIFS</td>
    <td>Forgery trace enhancement + multiscale attention</td>
    <td><a href="https://github.com/nbudongli/text-image-forgery-detection">TextTamper</a></td>
    <td>✅</td>
    <td>✅</td>
    <td>✅</td>
  </tr>

  <tr>
    <td>Ren et al. <a href="#ref13">[13]</a> : EMF-Net</td>
    <td>2024</td>
    <td>Expert Systems With Applications</td>
    <td>EMF-Net</td>
    <td><a href="https://github.com/tampered816/IPM15K">TMI12K</a></td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr>
    <td>Qu et al. <a href="#ref14">[14]</a> : DAF + Text Jitter</td>
    <td>2025</td>
    <td>AAAI</td>
    <td>DAF + Text Jitter</td>
    <td><a href="https://github.com/qcf-568/OSTF">OSTF</a></td>
    <td>✅</td>
    <td>✅</td>
    <td>✅</td>
  </tr>

  <tr>
    <td>Duan et al. <a href="#ref15">[15]</a> : TTDMamba</td>
    <td>2025</td>
    <td>IJCV</td>
    <td>TTDMamba</td>
    <td><a href="https://github.com/edmundhaohao/RealDTT">RealTTD</a></td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr>
    <td>Wong et al. <a href="#ref16">[16]</a> : ADCD-Net</td>
    <td>2025</td>
    <td>ICCV</td>
    <td>ADCD-Net</td>
    <td><a href="https://github.com/qcf-568/DocTamper">Doc-Tamper</a></td>
    <td>✅</td>
    <td>✅</td>
    <td>-</td>
  </tr>

  <tr>
    <td>Li et al.  <a href="#ref17">[17]</a> : DCLNet</td>
    <td>2025</td>
    <td>Signal Processing</td>
    <td>DCLNet</td>
    <td><a href="https://github.com/qcf-568/DocTamper">Doc-Tamper</a></td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr>
    <td>Nguyen et al. <a href="#ref18">[18]</a> : TALIU</td>
    <td>2025</td>
    <td>IEEE Access</td>
    <td>TALIU</td>
    <td><a href="https://github.com/qcf-568/DocTamper">Doc-Tamper</a></td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr>
    <td>Li et al. <a href="#ref19">[19]</a> : CD-SD</td>
    <td>2025</td>
    <td>JVCIR</td>
    <td>CD-SD</td>
    <td><a href="https://github.com/qcf-568/DocTamper">Doc-Tamper</a></td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr>
    <td>Li et al. <a href="#ref20">[20]</a> : Spatial-Frequency Fusion + Swin-T</td>
    <td>2025</td>
    <td>IET</td>
    <td>Spatial-Frequency Fusion + Swin-T</td>
    <td><a href="https://github.com/qcf-568/DocTamper">Doc-Tamper</a></td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr>
    <td>George & Marcel  <a href="#ref21">[21]</a> : EdgeDoc</td>
    <td>2025</td>
    <td>arXiv</td>
    <td>EdgeDoc</td>
    <td><a href="https://zenodo.org/records/17063366">FantasyID</a></td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr>
    <td>Luo et al.  <a href="#ref26">[26]</a> : ASC-Former</td>
    <td>2025</td>
    <td>Pattern Recognition</td>
    <td>ASC-Former</td>
    <td><a href="https://github.com/DrLuo/RTM">RTM</a></td>
    <td>✅</td>
    <td>✅</td>
    <td>✅</td>
  </tr>
  </tbody>
</table>
</div>

---

## 📂 Key Datasets

### A Dataset for Forgery Detection and Spotting in Document Images (2017) <a href="#ref22">[22]</a>
- Introduction: Character-level ground truth on payslip documents with XML annotations for character bounding boxes and values; 677 images focusing on copy-paste tampering.
- Link: [Dataset Homepage](http://navidomass.univ-lr.fr/ForgeryDataset/)

### CMID — Copy-Move ID (2021) <a href="#ref23">[23]</a>
- Introduction: Pixel-level masks for copy-move forgeries on ID documents. Includes separate genuine (304) and tampered (893) images.
- Link: [Dataset Homepage](https://cmiddataset.github.io/)

### FCD — Forged Character Detection Datasets (2022) <a href="#ref24">[24]</a>
- Introduction: Bounding-box annotations for forged characters across passports, driving licences, and visa stickers; three 15K-image subsets.
- Link: [Implementation code](https://github.com/turab45/Dataset-forged-characters-detection-on-driving-licences-and-passports) | [FCD-P](https://www.kaggle.com/datasets/turabbajeer/forged-characters-detection-on-passports) | [FCD-D](https://www.kaggle.com/datasets/turabbajeer/forged-characters-detection-on-driving-licence) | [FCD-V](https://www.kaggle.com/datasets/turabbajeer/forged-character-detection-dataset-on-visa-cards)

### Tampered-IC13 (2022) <a href="#ref2">[2]</a>
- Introduction: Bounding-box annotations over ICDAR 2013 scene text images with S3R strategy; train/test splits 229/233. Tampering generated via SRNet.
- Link: [Dataset Homepage](https://github.com/wangyuxin87/Tampered-IC13)

### FSD — Forged Scanned Document (2023) <a href="#ref25">[25]</a>
- Introduction: Pixel-level segmentation masks for forged documents built on FUNSD; covers copy-move, splicing, and resampling.
- Link: [Download Link](https://drive.google.com/file/d/1mCFH41b-v4OXeYAVFB2MppSQKa-BHtLH/view)

### DocTamper (2023) <a href="#ref3">[3]</a>
- Introduction: Large-scale pixel-level dataset for document tampering localization with multiple subsets (contracts, invoices, receipts, noisy office, scanned receipts).
- Link: [Dataset Homepage](https://github.com/qcf-568/DocTamper)

### ETTD — Explainable Tampered Text Detection Dataset (2024) <a href="#ref7">[7]</a>
- Introduction: Pixel-level masks with natural language rationales for documents, IDs, and scene texts; includes ETTD-Train, ETTD-Test, and class-agnostic ETTD-CD.
- Link: Not Available

### TextTamper (2024) <a href="#ref12">[12]</a>
- Introduction: Pixel-level annotations for text tampering localization across certificates, documents, and tables; created with rule-based, Poisson, and deep image blending.
- Link: [Dataset Homepage](https://github.com/nbudongli/text-image-forgery-detection)

### OSTF — Open-set Scene Text Forensics (2025) <a href="#ref14">[14]</a>
- Introduction: Open-set benchmark on scene text with bounding boxes; evaluates multiple generation/erasure models (Derend, SRNet, STEFANN, Mostel, DiffSTE, AnyText, Textdiff, UDiffText) on ICDAR 2013, ReCTS, TextOCR, etc.
- Link: [Dataset Homepage](https://github.com/qcf-568/OSTF)

### RealDTT — Real-world Comprehensive Dataset of Tampered Text Images (2025) <a href="#ref15">[15]</a>
- Introduction: Pixel-level segmentation across scene text and documents from MARIO-LAION, FUNSD, ReCTS, LSVT, RCTW; includes Photoshop, STEFANN, MOSTEL, VATr, ViTEraser, SRNet, DiffSTE, AnyText, UDiffText, TextDiffuser subsets.
- Link: [Dataset Homepage](https://github.com/edmundhaohao/RealDTT)

### RTM — Real Text Manipulation (2025) <a href="#ref26">[26]</a>
- Introduction: Pixel-level binary masks for varied manipulations (copy-move, splicing, insertion, inpainting, coverage) across charts, receipts, certificates, scanned docs, table-heavy pages; train/test from SROIE, FUNSD, TNCR, volunteers.
- Link: [Dataset Homepage](https://github.com/DrLuo/RTM)

---

### Comparison Table

<div style="overflow-x:auto;">
<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>Datasets</th>
      <th>Language</th>
      <th>Annotation level</th>
      <th>Subset</th>
      <th>Domain</th>
  </tr>
  </thead>
  <tbody>

  <tr>
    <td>A Dataset for Forgery Detection and Spotting in Document Images <a href="#ref22">[22]</a></td>
    <td>French</td>
    <td>Character-level (XML)</td>
    <td>-</td>
    <td>Payslips</td>
  </tr>

  <tr>
    <td>CMID (Copy-Move ID) <a href="#ref23">[23]</a></td>
    <td>French</td>
    <td>Pixel-level</td>
    <td>Genuine / Tampered</td>
    <td>ID documents</td>
  </tr>

  <tr>
    <td>FCD <a href="#ref24">[24]</a></td>
    <td>English</td>
    <td>Bounding box</td>
    <td>FCD-P / FCD-D / FCD-V</td>
    <td>Passports, Driving Licences, Visa Stickers</td>
  </tr>

  <tr>
    <td>Tampered-IC13 <a href="#ref2">[2]</a></td>
    <td>English</td>
    <td>Bounding box</td>
    <td>Train / Test</td>
    <td>Scene texts</td>
  </tr>

  <tr>
    <td>FSD (Forged Scanned Document) <a href="#ref25">[25]</a></td>
    <td>English</td>
    <td>Pixel-level (segmentation)</td>
    <td>Train / Test / Authentic</td>
    <td>Scanned documents</td>
  </tr>

  <tr>
    <td>DocTamper <a href="#ref3">[3]</a></td>
    <td>English, Chinese</td>
    <td>Pixel-level (segmentation)</td>
    <td>Train / Test / DocTamper-FCD / DocTamper-SCD</td>
    <td>Contracts, Invoices, Receipts, Text pages</td>
  </tr>

  <tr>
    <td>ETTD <a href="#ref7">[7]</a></td>
    <td>English, Chinese</td>
    <td>Pixel-level + Natural language</td>
    <td>Train / Test / ETTD-CD</td>
    <td>Documents, ID cards, Scene texts</td>
  </tr>

  <tr>
    <td>TextTamper <a href="#ref12">[12]</a></td>
    <td>Chinese</td>
    <td>Pixel-level</td>
    <td>Train / Val</td>
    <td>Certificates, Documents, Tables</td>
  </tr>

  <tr>
    <td>OSTF <a href="#ref14">[14]</a></td>
    <td>Chinese</td>
    <td>Bounding box</td>
    <td>Model-specific splits</td>
    <td>Scene text</td>
  </tr>

  <tr>
    <td>RealDTT <a href="#ref15">[15]</a></td>
    <td>Various</td>
    <td>Pixel-level (segmentation)</td>
    <td>Photoshop / STEFANN / MOSTEL / VATr / ViTEraser / SRNet / DiffSTE / AnyText / UDiffText / TextDiffuser</td>
    <td>Scene text, Documents</td>
  </tr>

  <tr>
    <td>RTM <a href="#ref26">[26]</a></td>
    <td>English</td>
    <td>Pixel-level (binary masks)</td>
    <td>Train / Test</td>
    <td>Charts, Receipts, Certificates, Scanned documents, Tables</td>
  </tr>
  </tbody>
</table>
</div>

## 🛠️ Text Tampering Methods

## Overview Table for Text Tampering    
  <div style="overflow-x:auto;">
<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>Model Name</th>
      <th>Year</th>
      <th>Venue</th>
      <th>Category</th>
      <th>Key Contribution / Core Idea</th>
      <th>Architecture</th>
      <th>GitHub / Code Status</th>
      <th>Paper Link</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>SRNet <a href="#ref27">[27]</a></td>
      <td>2019</td>
      <td>ACM MM</td>
      <td>GAN-Based Editing</td>
      <td>Early GAN-based end-to-end network for text replacement.</td>
      <td>GAN-based</td>
      <td><a href="https://github.com/lksshw/SRNet">Official Repo</a></td>
      <td><a href="https://arxiv.org/pdf/1908.03047">Paper</a></td>
    </tr>
    <tr>
      <td>EnsNet <a href="#ref28">[28]</a></td>
      <td>2019</td>
      <td>ArXiv</td>
      <td>Text Editing, Inpainting, Removal</td>
      <td>An early text removal model using a feature-level attention block.</td>
      <td>GAN-based (U-Net with attention)</td>
      <td><a href="https://github.com/HCIILAB/Scene-Text-Removal">Official Repo</a></td>
      <td><a href="https://arxiv.org/abs/1812.00723">Paper</a></td>
    </tr>
    <tr>
      <td>SwapText <a href="#ref29">[29]</a></td>
      <td>2020</td>
      <td>ArXiv</td>
      <td>GAN-Based Editing</td>
      <td>Robust three-stage GAN for text replacement and background preservation.</td>
      <td>Three-stage GAN</td>
      <td>N/A</td>
      <td><a href="https://arxiv.org/pdf/2003.08152">Paper</a></td>
    </tr>
    <tr>
      <td>STEFANN <a href="#ref30">[30]</a></td>
      <td>2020</td>
      <td>CVPR</td>
      <td>Character-Level & Font-Aware</td>
      <td>Character-level editing preserving font structure and color.</td>
      <td>Two-stage GAN (FANnet + Colornet)</td>
      <td><a href="https://github.com/prasunroy/stefann">Official Repo</a></td>
      <td><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Roy_STEFANN_Scene_Text_Editor_Using_Font_Adaptive_Neural_Network_CVPR_2020_paper.pdf">Paper</a></td>
    </tr>
    <tr>
      <td>dRENDER <a href="#ref31">[31]</a></td>
      <td>2021</td>
      <td>ICCV</td>
      <td>Parametric & De-rendering</td>
      <td>Parses rendering parameters of stylized text for artifact-free re-rendering.</td>
      <td>Differentiable Text Rendering Model</td>
      <td><a href="https://github.com/CyberAgentAILab/derendering-text">Official Repo</a></td>
      <td><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Shimoda_De-Rendering_Stylized_Texts_ICCV_2021_paper.pdf">Paper</a></td>
    </tr>
    <tr>
      <td>MOSTEL <a href="#ref32">[32]</a></td>
      <td>2022</td>
      <td>AAAI</td>
      <td>Stroke-Level & Fine-Grained</td>
      <td>Stroke-level text editing using guidance maps for high glyph fidelity.</td>
      <td>Generates stroke guidance maps; Semi-supervised hybrid learning</td>
      <td><a href="https://github.com/qqqyd/MOSTEL">Official Repo</a></td>
      <td><a href="https://arxiv.org/pdf/2212.01982">Paper</a></td>
    </tr>
    <tr>
      <td>DiffUTE <a href="#ref33">[33]</a></td>
      <td>2023</td>
      <td>NeurIPS</td>
      <td>Universal Text Editing & Diffusion</td>
      <td>Self-supervised diffusion model for high-fidelity text replacement/modification.</td>
      <td>Diffusion Model with glyph/position guidance</td>
      <td><a href="https://github.com/chenhaoxing/DiffUTE">Official Repo</a></td>
      <td><a href="https://arxiv.org/pdf/2305.10825">Paper</a></td>
    </tr>
    <tr>
      <td>DiffSTE <a href="#ref34">[34]</a></td>
      <td>2023</td>
      <td>ArXiv</td>
      <td>Universal Text Editing & Diffusion</td>
      <td>Diffusion-based scene text editing to modify styles and colors while preserving structure.</td>
      <td>Diffusion Model</td>
      <td><a href="https://github.com/UCSB-NLP-Chang/DiffSTE">Official Repo</a></td>
      <td><a href="https://arxiv.org/pdf/2304.05568">Paper</a></td>
    </tr>
    <tr>
      <td>Magicremover <a href="#ref35">[35]</a></td>
      <td>2023</td>
      <td>ArXiv</td>
      <td>Text Editing, Inpainting, Removal</td>
      <td>Tuning-free text-guided image inpainting for text/object removal.</td>
      <td>Diffusion Model (Stable Diffusion)</td>
      <td>N/A</td>
      <td><a href="https://arxiv.org/pdf/2310.02848">Paper</a></td>
    </tr>
    <tr>
      <td>AnyText <a href="#ref36">[36]</a></td>
      <td>2023</td>
      <td>ArXiv</td>
      <td>Multilingual & Cross-Language</td>
      <td>Pioneering multilingual text generation/editing with an OCR-based text encoder.</td>
      <td>Diffusion Model with auxiliary latent module</td>
      <td><a href="https://github.com/tyxsspa/AnyText">Official Repo</a></td>
      <td><a href="https://arxiv.org/pdf/2311.03054">Paper</a></td>
    </tr>
    <tr>
      <td>TextDiff <a href="#ref37">[37]</a></td>
      <td>2023</td>
      <td>ArXiv</td>
      <td>Text Super-Resolution</td>
      <td>Diffusion model that sharpens text by predicting the high-frequency residual.</td>
      <td>Two-module framework: TEM + MRD (Residual Diffusion)</td>
      <td><a href="https://github.com/Lenubolim/TextDiff">Official Repo</a></td>
      <td><a href="https://arxiv.org/pdf/2308.06743">Paper</a></td>
    </tr>
    <tr>
      <td>GlyphControl <a href="#ref38">[38]</a></td>
      <td>2023</td>
      <td>NeurIPS</td>
      <td>Character-Aware Synthesis</td>
      <td>Glyph-conditional diffusion model for explicit control of text content, location, and size.</td>
      <td>Conditional Diffusion Model</td>
      <td><a href="https://github.com/AIGText/GlyphControl-release">Official Repo</a></td>
      <td><a href="https://arxiv.org/pdf/2305.18259">Paper</a></td>
    </tr>
    <tr>
      <td>UDiffText <a href="#ref39">[39]</a></td>
      <td>2023</td>
      <td>ArXiv</td>
      <td>Character-Aware Synthesis</td>
      <td>Unified framework for text synthesis and editing using a character-level text encoder.</td>
      <td>Fine-tuned Stable Diffusion with char-level encoder</td>
      <td><a href="https://github.com/ZYM-PKU/UDiffText">Official Repo</a></td>
      <td><a href="https://arxiv.org/pdf/2312.04884">Paper</a></td>
    </tr>
    <tr>
      <td>TextCtrl <a href="#ref40">[40]</a></td>
      <td>2024</td>
      <td>NeurIPS</td>
      <td>Style-Preserving & Prior-Guided</td>
      <td>Explicitly disentangles style and glyph structure priors for style preservation.</td>
      <td>Diffusion Model with Style-Structure guidance</td>
      <td><a href="https://github.com/weichaozeng/TextCtrl">Official Repo</a></td>
      <td><a href="https://arxiv.org/pdf/2410.10133">Paper</a></td>
    </tr>
    <tr>
      <td>AnyText2 <a href="#ref41">[41]</a></td>
      <td>2024</td>
      <td>ArXiv</td>
      <td>Multilingual & Cross-Language</td>
      <td>Adds customizable font/color attributes and improves speed over AnyText.</td>
      <td>Diffusion Model (WriteNet+AttnX)</td>
      <td><a href="https://github.com/tyxsspa/AnyText2">Official Repo</a></td>
      <td><a href="https://arxiv.org/pdf/2411.15245">Paper</a></td>
    </tr>
    <tr>
      <td>TextCrafter <a href="#ref42">[42]</a></td>
      <td>2024</td>
      <td>ArXiv</td>
      <td>Character-Aware Synthesis</td>
      <td>Precisely renders multiple texts with varying attributes by segmenting and rendering independently.</td>
      <td>Diffusion Model with independent region rendering</td>
      <td><a href="https://github.com/NJU-PCALab/TextCrafter">Official Repo</a></td>
      <td><a href="https://arxiv.org/pdf/2503.23461">Paper</a></td>
    </tr>
    <tr>
      <td>TextMaster <a href="#ref43">[43]</a></td>
      <td>2024</td>
      <td>ArXiv</td>
      <td>Style-Preserving & Prior-Guided</td>
      <td>Universal controllable text editing with adaptive font and style injection.</td>
      <td>Diffusion Model with Attention and Perceptual Loss</td>
      <td>N/A</td>
      <td><a href="https://arxiv.org/pdf/2410.09879">Paper</a></td>
    </tr>
    <tr>
      <td>GlyphMastero <a href="#ref44">[44]</a></td>
      <td>2025</td>
      <td>ArXiv</td>
      <td>Stroke-Level & Fine-Grained</td>
      <td>Specialized glyph encoder to guide a diffusion model for stroke-level precision.</td>
      <td>Diffusion Model + Glyph Encoder</td>
      <td>N/A</td>
      <td><a href="https://arxiv.org/pdf/2505.04915">Paper</a></td>
    </tr>
    <tr>
      <td>Qwen-Image <a href="#ref45">[45]</a></td>
      <td>2025</td>
      <td>ArXiv</td>
      <td>Character-Aware Synthesis</td>
      <td>SOTA image foundation model with excellent multilingual text rendering and editing.</td>
      <td>Multimodal DiT (MMDiT)</td>
      <td><a href="https://github.com/QwenLM/Qwen-Image">Official Repo</a></td>
      <td><a href="https://arxiv.org/pdf/2508.02324">Paper</a></td>
    </tr>
  </tbody>
</table>
</div>


## 📖 References

<a id="ref1"></a>[1] P. Yang, W. Fang, F. Zhang, L. Bai, Y. Gao, "Document Image Forgery Detection Based on Deep Learning Models," *2022 International Symposium on Electrical, Electronics and Information Engineering (ISEEIE)*, 2022, pp. 1-5, [Paper](https://ieeexplore.ieee.org/document/9853295)


<a id="ref2"></a>[2] Y. Wang, C. Liu, X. Liu, D. Peng, L. Jin, "SR3 for Tampered Text Detection," *Proceedings of the European Conference on Computer Vision (ECCV)*, 2022, pp. 1234-1245, [Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136880214.pdf)

<a id="ref3"></a>[3] C. Qu, Y. Liu, X. Liu, D. Peng, F. Guo, L. Jin, "DTD: Document Tampering Detection," *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)*, 2023, pp. 5937-5946 [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Qu_Towards_Robust_Tampered_Text_Detection_in_Document_Image_New_Dataset_CVPR_2023_paper.pdf) | [Code](https://github.com/qcf-568/DocTamper)

<a id="ref4"></a>[4] Y. Okamoto, G. Osada, I. Yahiro, R. Hasegawa, P. Zhu, H. Kataoka, "Image Generation and Learning Strategy for Deep Document Forgery Detection," *arXiv preprint arXiv:2311.03650*, Nov. 2023. [Paper](https://arxiv.org/pdf/2311.03650).

<a id="ref5"></a>[5] J. Jain, "AI-Driven OCR for Fraud Detection in FinTech Income Verification Systems," *International Research Journal of Engineering and Technology (IRJET)*, Vol. 11, Issue 12, Dec. 2024, pp. 850-854. [Paper](https://www.irjet.net/archives/V11/i12/IRJET-V11I12116.pdf)

<a id="ref6"></a>[6] Z. Chen, S. Chen, T. Yao, K. Sun, S. Ding, X. Lin, L. Cao, R. Ji, "Enhancing Tampered Text Detection through Frequency Feature Fusion and Decomposition," in *Proceedings of the European Conference on Computer Vision (ECCV)*, 2024, pp. 394-411. [Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04834.pdf)

<a id="ref7"></a>[7] C. Qu, J. Liu, H. Chen, B. Yu, J. Liu, W. Wang, L. Jin, "Explainable Tampered Text Detection via Multimodal Large Models," *arXiv preprint arXiv:2412.14816v2*, Dec. 2024. [Paper](https://arxiv.org/pdf/2412.14816v2)

<a id="ref8"></a>[8] H. Shao, Z. Qian, K. Huang, W. Wang, X. Huang, Q. Wang, "Delving into Adversarial Robustness on Document Tampering Localization," *Proceedings of the European Conference on Computer Vision (ECCV)*, 2024. [Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/08224.pdf)

<a id="ref9"></a>[9] J. Wang, L. Mou, C. Zheng, W. Gao, "Image-Based Freeform Handwriting Authentication With Energy-Oriented Self-Supervised Learning," *IEEE Transactions on Multimedia*, vol. 27, pp. 1397-1409, 2025. [Paper](https://doi.org/10.1109/TMM.2024.3521807)

<a id="ref10"></a>[10] G. Li, X. Yang, W. Ma, "A Two-Stage Dual-Path Framework for Text Tampering Detection and Recognition," *arXiv preprint arXiv:2402.13545v2*, Feb. 2024. [Paper](https://arxiv.org/pdf/2402.13545.pdf)

<a id="ref11"></a>[11] X. Liao, S. Chen, J. Chen, T. Wang, X. Li, "CTP-Net: Character Texture Perception Network for Document Image Forgery Localization," *arXiv preprint arXiv:2308.02158v1*, Aug. 2023. [Paper](https://arxiv.org/pdf/2308.02158v1)

<a id="ref12"></a>[12] B. Li, J. Xu, Y. Wang, Z. Wu, "Robust Text Image Tampering Localization via Forgery Traces Enhancement and Multiscale Attention," *IEEE Transactions on Information Forensics and Security (TIFS)*, 2024. [Paper](https://ieeexplore.ieee.org/document/10440540/) | [Code](https://github.com/nbudongli/text-image-forgery-detection)


<a id="ref13"></a>[13] R. Ren, Q. Hao, F. Gu, S. Niu, J. Zhang, M. Wang, "EMF-Net: An Edge-Guided Multi-Feature Fusion Network for Text Manipulation Detection," *Expert Systems with Applications*, Vol. 249, Part A, 2024, 123548. [Paper](https://www.sciencedirect.com/science/article/pii/S0957417424004135)

<a id="ref14"></a>[14] C. Qu, Y. Zhong, F. Guo, L. Jin, "Revisiting Tampered Scene Text Detection in the Era of Generative AI," *Proceedings of the AAAI Conference on Artificial Intelligence (AAAI)*, pp. 694–702, 2025. [Paper](https://arxiv.org/pdf/2407.21422) | [Code](https://github.com/qcf-568/OSTF)
 
<a id="ref15"></a>[15] J. Duan, H. Sun, F. Ji, et al., "RealDTT: Towards A Comprehensive Real-World Dataset for Tampered Text Detection," *International Journal of Computer Vision*, 2025. [Paper](https://link.springer.com/article/10.1007/s11263-025-02515-2)

<a id="ref16"></a>[16] K. A. Wong, J. Zhou, H. Wu, Y.-W. Si, J. Zhou, “ADCD-Net: Robust Document Image Forgery Localization via Adaptive DCT Feature and Hierarchical Content Disentanglement,” *Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)*, 2025. [Paper](https://arxiv.org/pdf/2507.16397) | [Code](https://github.com/KAHIMWONG/ADCD-Net)


<a id="ref17"></a>[17] W. Li, B. Li, K. Zheng, S. Li, H. Li, "Document image forgery detection and localization in desensitization scenarios," *Signal Processing*, vol. 238, 110123, 2025. [Paper](https://www.sciencedirect.com/science/article/pii/S0165168425002373)

<a id="ref18"></a>[18] A. D. Nguyen, H.-Y. Kim, H. N. Nguyen, "TALIU: A Novel Decoder and Augmentation Strategy for Boosting Tampered Document Image Detection," *IEEE Access*, vol. 13, pp. 70340-70351, 2025. [Paper](https://ieeexplore.ieee.org/document/10964281)  

<a id="ref19"></a>[19] L. Li, Y. Bai, S. Zhang, M. Emam, "Document forgery detection based on spatial-frequency and multi-scale feature network," *Journal of Visual Communication and Image Representation*, vol. 107, 104393, 2025. [Paper](https://www.sciencedirect.com/science/article/pii/S1047320325000070) 

<a id="ref20"></a>[20] L. Li, K. Zhang, J. Lu, S. Zhang, N. Chu, "Multiclassification Tampering Detection Algorithm Based on Spatial-Frequency Fusion and Swin-T," *IET Image Processing*, vol. 19, 2025. [Paper](https://www.researchgate.net/publication/389433177_Multiclassification_Tampering_Detection_Algorithm_Based_on_Spatial-Frequency_Fusion_and_Swin-T)

<a id="ref21"></a>[21] A. George, S. Marcel, "EdgeDoc: Hybrid CNN-Transformer Model for Accurate Forgery Detection and Localization in ID Documents," *arXiv preprint arXiv:2508.16284*, 2025. [Paper](https://arxiv.org/pdf/2508.16284)

<a id="ref22"></a>[22] N. Sidere, F. Cruz, M. Coustaty and J.-M. Ogier, "A dataset for forgery detection and spotting in document images," *Seventh International Conference on Emerging Security Technologies (EST)*, Canterbury, UK, 2017, pp. 26–31. [Paper](https://doi.org/10.1109/EST.2017.8090394)
  
<a id="ref23"></a>[23] G. Mahfoudi, F. Morain-Nicolier, F. Retraint and M. Pic, "CMID: A New Dataset for Copy-Move Forgeries on ID Documents," *IEEE International Conference on Image Processing (ICIP)*, Anchorage, AK, USA, 2021, pp. 3028–3032. [Paper](https://doi.org/10.1109/ICIP42928.2021.9506723)

<a id="ref24"></a>[24] T. Kumar, M. Turab, S. Talpur, R. Brennan and M. Bendechache, "Forged Character Detection Datasets: Passports, Driving Licences and Visa Stickers," *International Journal of Artificial Intelligence & Applications*, vol. 13, pp. 21–35, Mar. 2022. [Paper](https://doi.org/10.5121/ijaia.2022.13202)
 
<a id="ref25"></a>[25] A. K. Jaiswal, S. Singh and S. K. Tripathy, "FSD: A novel forged document dataset and baseline," *2023 14th International Conference on Computing Communication and Networking Technologies (ICCCNT)*, Delhi, India, pp. 1–6, 2023. [Paper](https://doi.org/10.1109/ICCCNT56998.2023.10306408)
  
<a id="ref26"></a>[26] D. Luo, Y. Liu, R. Yang, X. Liu, J. Zeng, Y. Zhou and X. Bai, "Toward real text manipulation detection: New dataset and new solution," *Pattern Recognition*, vol. 157, p. 110828, 2025. [Paper](https://doi.org/10.1016/j.patcog.2024.110828)  

<a id="ref27"></a>[27] L. Wu, C. Zhang, J. Liu, J. Han, J. Liu, E. Ding and X. Bai, "Editing text in the wild," in *Proceedings of the 27th ACM International Conference on Multimedia*, 2019, pp. 1500–1508. [Paper](https://arxiv.org/pdf/1908.03047) | [Code](https://github.com/lksshw/SRNet)

<a id="ref28"></a>[28] S. Zhang, Y. Liu, L. Jin, Y. Huang and S. Lai, "EnsNet: Ensconce text in the wild," in *Proceedings of the AAAI Conference on Artificial Intelligence*, vol. 33, no. 1, 2019, pp. 801–808. [Paper](https://arxiv.org/pdf/1812.00723) | [Code](https://github.com/HCIILAB/Scene-Text-Removal)


<a id="ref29"></a>[29] Q. Yang, J. Huang and W. Lin, "SwapText: Image based texts transfer in scenes," in *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 2020, pp. 14700–14709. [Paper](https://arxiv.org/pdf/2003.08152)

<a id="ref30"></a>[30] P. Roy, S. Bhattacharya, S. Ghosh and U. Pal, "STEFANN: Scene text editor using font adaptive neural network," in *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 2020, pp. 13228–13237. [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Roy_STEFANN_Scene_Text_Editor_Using_Font_Adaptive_Neural_Network_CVPR_2020_paper.pdf) | [Code](https://github.com/prasunroy/stefann)

<a id="ref31"></a>[31] W. Shimoda, D. Haraguchi, S. Uchida and K. Yamaguchi, "De-rendering stylized texts," in *Proceedings of the IEEE/CVF International Conference on Computer Vision*, 2021, pp. 1076–1085. [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Shimoda_De-Rendering_Stylized_Texts_ICCV_2021_paper.pdf) | [Code](https://github.com/CyberAgentAILab/derendering-text)

<a id="ref32"></a>[32] Y. Qu, Q. Tan, H. Xie, J. Xu, Y. Wang and Y. Zhang, "Exploring stroke-level modifications for scene text editing," in *Proceedings of the AAAI Conference on Artificial Intelligence*, vol. 37, no. 2, 2023, pp. 2119–2127. [Paper](https://arxiv.org/pdf/2212.01982) | [Code](https://github.com/qqqyd/MOSTEL)

<a id="ref33"></a>[33] H. Chen, Z. Xu, Z. Gu, Y. Li, C. Meng, H. Zhu and W. Wang, "DiffUTE: Universal text editing diffusion model," *Advances in Neural Information Processing Systems*, vol. 36, pp. 63062–63074, 2023. [Paper](https://arxiv.org/pdf/2305.10825) | [Code](https://github.com/chenhaoxing/DiffUTE)

<a id="ref34"></a>[34] J. Ji, G. Zhang, Z. Wang, B. Hou, Z. Zhang, B. Price and S. Chang, "Improving diffusion models for scene text editing with dual encoders," *arXiv preprint arXiv:2304.05568*, 2023. [Paper](https://arxiv.org/pdf/2304.05568) | [Code](https://github.com/UCSB-NLP-Chang/DiffSTE)

<a id="ref35"></a>[35] L. Yu, J. Yu, "Magicremover: Tuning-free text-guided image inpainting," *arXiv preprint arXiv:2310.14428*, 2023. [Paper](https://arxiv.org/pdf/2310.02848)

<a id="ref36"></a>[36] Y. Tuo, W. Xiang, J.-Y. He, Y. Geng and X. Xie, "AnyText: Multilingual visual text generation and editing," *arXiv preprint arXiv:2311.03054*, 2023. [Paper](https://arxiv.org/pdf/2311.03054) | [Code](https://github.com/tyxsspa/AnyText)

<a id="ref37"></a>[37] B. Liu, Z. Yang, P. Wang, J. Zhou, Z. Liu, Z. Song, Y. Liu and Y. Xiong, "TextDiff: Mask-guided residual diffusion models for scene text image super-resolution," *arXiv preprint arXiv:2308.06743*, 2023. [Paper](https://arxiv.org/pdf/2308.06743) | [Code](https://github.com/Lenubolim/TextDiff)

<a id="ref38"></a>[38] Y. Yang, D. Gui, Y. Yuan, W. Liang, H. Ding, H. Hu and K. Chen, "GlyphControl: Glyph conditional control for visual text generation," *Advances in Neural Information Processing Systems*, vol. 36, pp. 44050–44066, 2023. [Paper](https://arxiv.org/pdf/2305.18259) | [Code](https://github.com/AIGText/GlyphControl-release)

<a id="ref39"></a>[39] Y. Zhao and Z. Lian, "UDiffText: A unified framework for high-quality text synthesis in arbitrary images via character-aware diffusion models," in *Proceedings of the European Conference on Computer Vision*, 2024, pp. 217–233. [Paper](https://arxiv.org/pdf/2312.04884) | [Code](https://github.com/ZYM-PKU/UDiffText)

<a id="ref40"></a>[40] W. Zeng, Y. Shu, Z. Li, D. Yang and Y. Zhou, "TextCtrl: Diffusion-based scene text editing with prior guidance control," *Advances in Neural Information Processing Systems*, vol. 37, pp. 138569–138594, 2024. [Paper](https://arxiv.org/pdf/2410.10133) | [Code](https://github.com/weichaozeng/TextCtrl)

<a id="ref41"></a>[41] Y. Tuo, Y. Geng and L. Bo, "AnyText2: Visual text generation and editing with customizable attributes," *arXiv preprint arXiv:2411.15245*, 2024. [Paper](https://arxiv.org/pdf/2411.15245) | [Code](https://github.com/tyxsspa/AnyText2)

<a id="ref42"></a>[42] N. Du, Z. Chen, S. Gao, Z. Chen, X. Chen, Z. Jiang, J. Yang and Y. Tai, "TextCrafter: Accurately rendering multiple texts in complex visual scenes," *arXiv preprint arXiv:2503.23461*, 2025. [Paper](https://arxiv.org/pdf/2503.23461) | [Code](https://github.com/NJU-PCALab/TextCrafter) 

<a id="ref43"></a>[43] Z. Yan, J. Wang, A. Wang, Y. Li, W. Shang and R. Lin, "TextMaster: A unified framework for realistic text editing via glyph-style dual-control," *arXiv preprint arXiv:2410.09879*, 2024. [Paper](https://arxiv.org/pdf/2410.09879)

<a id="ref44"></a>[44] T. Wang, T. Liu, X. Qu, C. Wu, L. Liu and X. Hu, "GlyphMastero: A glyph encoder for high-fidelity scene text editing," in *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 2025, pp. 28523–28532. [Paper](https://arxiv.org/pdf/2505.04915)

<a id="ref45"></a>[45] C. Wu, J. Li, J. Zhou, J. Lin, K. Gao, K. Yan, S. Yin *et al.*, "Qwen-Image technical report," *arXiv preprint arXiv:2508.02324*, 2025. [Paper](https://arxiv.org/pdf/2508.02324) | [Code](https://github.com/QwenLM/Qwen-Image)

---

## 🤝 Contributing
Contributions are welcome! Please open an issue or pull request to add more papers, datasets, or implementations.

---

## ⭐ Acknowledgements
If you find this list helpful, please star ⭐ the repository to support the project.
