# awesome-tampered-text-detection
A curated collection of papers, datasets, code, and tools for detecting tampered text and forged documents.

## 📚 Papers

### 2021
- **Document Image Forgery Detection Based on Deep Learning Models**  
  *ISEEIE 2021* | Deep learning + ELA fusion | Dataset: Ali Tianchi Competition  
  🔗 *No code available*

---

### 2022
- **Detecting Tampered Scene Text in the Wild**  
  *ECCV 2022* | SR3 | Dataset: [T-IC13](https://github.com/wangyuxin87/Tampered-IC13)  
  🔗 Code: *Not available*

---

### 2023
- **Towards Robust Tampered Text Detection in Document Image: New Dataset and New Solution**  
  *CVPR 2023* | DTD | Dataset: [Doc-Tamper](https://github.com/qcf-568/DocTamper)  
  🔗 [Code](https://github.com/qcf-568/DocTamper)

- **Image Generation and Learning Strategy for Deep Document Forgery Detection**  
  *arXiv 2023* | FCN (semantic segmentation) | Dataset: FD-VIED  
  🔗 *No code available*

---

### 2024
- **AI-Driven OCR for Fraud Detection in FinTech Income Verification Systems**  
  *IRJET 2024* | K-Means, Decision Trees, Logistic Regression  
  🔗 *No dataset/code available*

- **Enhancing Tampered Text Detection through Frequency Feature Fusion and Decomposition**  
  *ECCV 2024* | FFDN | Dataset: [Doc-Tamper](https://github.com/qcf-568/DocTamper)  
  🔗 *No code available*

- **Explainable Tampered Text Detection via Multimodal Large Models**  
  *arXiv 2024* | TextSleuth / Tampered Text Detective | Dataset: ETTD  
  🔗 *No code available*

- **Delving into Adversarial Robustness on Document Tampering Localization**  
  *ECCV 2024* | DTL-ARob | Dataset: [Doc-Tamper](https://github.com/qcf-568/DocTamper), [T-SROIE](https://github.com/wangyuxin87/Tampered_sroie)  
  🔗 [Code](https://github.com/SHR-77/DTL-ARob.git)

- **Image-based Freeform Handwriting Authentication with Energy-oriented Self-Supervised Learning**  
  *TMM 2024* | SherlockNet | Dataset: [EN-HA](https://github.com/WangJingyao07/SherlockNet)  
  🔗 [Code](https://github.com/WangJingyao07/SherlockNet)

- **Two-Stage Dual-Path Framework for Text Tampering Detection and Recognition**  
  *arXiv 2024* | Dual-path framework | Dataset: Suning Scene Data  
  🔗 *No code available*

- **CTP-Net: Character Texture Perception Network for Document Image Forgery Localization**  
  *AAAI 2024* | CTP-Net | Dataset: Fake Chinese Trademark (FCTM)  
  🔗 *No code available*

- **Robust Text Image Tampering Localization via Forgery Traces Enhancement & Multiscale Attention**  
  *IEEE 2024* | Forgery trace enhancement + multiscale attention | Dataset: TextTamper  
  🔗 [Code](https://github.com/nbudongli/text-image-forgery-detection)

- **EMF-Net: Edge-Guided Multi-Feature Fusion Network for Text Manipulation Detection**  
  *Expert Systems With Applications 2024* | EMF-Net | Dataset: [TMI12K](https://github.com/tampered816/IPM15K)  
  🔗 *No code available*

---

### 2025
- **Revisiting Tampered Scene Text Detection in the Era of Generative AI**  
  *AAAI 2025* | DAF + Text Jitter | Dataset: [OSTF](https://github.com/qcf-568/OSTF)  
  🔗 [Code](https://github.com/qcf-568/OSTF)

- **RealDTT: Comprehensive Dataset for Tampered Text Detection**  
  *IJCV 2025* | TTDMamba | Dataset: [RealTTD](https://github.com/edmundhaohao/RealDTT)  
  🔗 *No code available*

- **Toward Real Text Manipulation Detection: New Dataset and New Solution**  
  *Pattern Recognition 2025* | ASC-Former | Dataset: [RTM](https://github.com/DrLuo/RTM)  
  🔗 [Code](https://github.com/DrLuo/RTM)

- **ADCD-Net: Robust Document Image Forgery Localization**  
  *ICCV 2025* | ADCD-Net | Dataset: [Doc-Tamper](https://github.com/qcf-568/DocTamper)  
  🔗 [Code](https://github.com/KAHIMWONG/ACDC-Net)

- **Document Image Forgery Detection & Localization in Desensitization Scenarios**  
  *Signal Processing 2025* | DCLNet | Dataset: DocTD  
  🔗 *No code available*


- **TALIU: Decoder & Augmentation Strategy for Tampered Document Detection**  
  *IEEE 2025* | TALIU | Dataset: [Doc-Tamper](https://github.com/qcf-568/DocTamper)  
  🔗 *No code available*

- **Generalized Document Tampering Localization via Color & Semantic Disentanglement**  
  *IEEE 2025* | CD-SD | Dataset: [Doc-Tamper](https://github.com/qcf-568/DocTamper)  
  🔗 *No code available*

- **Multiclassification Tampering Detection Algorithm via Spatial-Frequency Fusion + Swin-T**  
  *IET 2025* | Spatial-Frequency Fusion + Swin-T | Dataset: Document Tamper  
  🔗 *No code available*

- **EdgeDoc: Hybrid CNN-Transformer Model for ID Document Forgery Detection**  
  *IEEE 2025* | EdgeDoc | Dataset: [FantasyID](https://www.idiap.ch/paper/fantasyid/)  
  🔗 [Code](https://www.idiap.ch/paper/edgedoc/)

---

## 📂 Key Datasets

### DocTamper
- **Annotation:** Pixel-level segmentation  
- **Paper:** *Towards Robust Tampered Text Detection in Document Image* (CVPR 2023)  
- **Size:** 120,000 train / 30,000 test + FCD (2k), SCD (18k)  
- **Domain:** Contracts, invoices, receipts  
- **Tampering:** Copy-move, splicing, generation  

### OSTF (Open-set Scene Text Forensics)
- **Annotation:** Bounding Box  
- **Paper:** *Revisiting Tampered Scene Text Detection in the Era of Generative AI* (AAAI 2025)  
- **Size:** ~462–127k samples across SRNet, STEFANN, Mostel, DiffSTE, Anytext, Textdiff, Udifftext, TextOCR, ReCTS, ICDAR datasets  
- **Domain:** Scene text  
- **Tampering:** Rendering, conventional CNNs, GAN, diffusion models

### RealDTT
- **Annotation:** Pixel-level segmentation  
- **Paper:** *RealDTT: Towards A Comprehensive Real-World Dataset for Tampered Text Detection* (IJCV 2025)  
- **Size:** ~200k samples (Photoshop, GAN, diffusion)  
- **Domain:** Scene text, documents  
- **Tampering:** Photoshop edits, CNN, GAN, diffusion-based

### Tampered-IC13
- **Annotation:** Bounding Box  
- **Paper:** *Detecting Tampered Scene Text in the Wild* (ECCV 2022)  
- **Size:** 229 train + 233 test  
- **Domain:** Scene text  
- **Tampering:** SRNet-based neural manipulation

### ETTD
- **Annotation:** Pixel-level + natural language annotation  
- **Paper:** *TextSleuth: Towards Explainable Tampered Text Detection* (arXiv 2024)  
- **Size:** 10,400 train + 600 test + 1,000 CD  
- **Domain:** Documents, ID cards, scene texts  
- **Tampering:** Diffusion, copy-move, splicing, Photoshop

### RTM (Real Text Manipulation)
- **Annotation:** Pixel-level binary masks  
- **Paper:** *Toward Real Text Manipulation Detection: New Dataset and New Solution* (PR 2025)  
- **Size:** 5,803 train + 3,197 test  
- **Domain:** Charts, receipts, certificates, scanned docs  
- **Tampering:** Copy-move, splicing, insertion, inpainting, coverage (Photoshop)

---

## 🤝 Contributing
Contributions are welcome! Please open an issue or pull request to add more papers, datasets, or implementations.

---

## ⭐ Acknowledgements
If you find this list helpful, please star ⭐ the repository to support the project.
