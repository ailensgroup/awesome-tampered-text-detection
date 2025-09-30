# Awesome Tampered Text Detection 
A curated collection of **papers, datasets, code, and tools** for detecting tampered text and forged documents.  

## Table of Contents
1. [Papers](#papers)
2. [Key Datasets](#key-datasets)
3. [Text Tampering Methods](#text-tampering-methods)
4. [References](#references)

---

## 📚 Papers
<table>
  <tr>
    <td><b>Paper</b></td>
    <td><b>Year</b></td>
    <td><b>Venue</b></td>
    <td><b>Method</b></td>
    <td><b>Dataset</b></td>
    <td><b>Train. Code</b></td>
    <td><b>Val. Code</b></td>
    <td><b>Infer. Code</b></td>
  </tr>

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
    <td>Wang et al.<a href="#ref2">[2]</a> : SR3</td>
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
    <td>IEEE</td>
    <td>SherlockNet</td>
    <td><a href="https://github.com/WangJingyao07/SherlockNet">EN-HA</a></td>
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
    <td>Li et al.  <a href="#ref12">[12]</a> : MA-Net</td>
    <td>2024</td>
    <td>IEEE</td>
    <td>Forgery trace enhancement + multiscale attention</td>
    <td>TextTamper</td>
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
    <td>Nguyen et al.  <a href="#ref18">[18]</a> : TALIU</td>
    <td>2025</td>
    <td>IEEE</td>
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
    <td>Pattern Recognition</td>
    <td>EdgeDoc</td>
    <td>FantasyID</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>
</table>

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
- Link: [Dataset Home page](https://github.com/DrLuo/RTM)

---

### Comparison Table

<table>
  <tr>
    <td><b>Datasets</b></td>
    <td><b>Language</b></td>
    <td><b>Annotation level</b></td>
    <td><b>Subset</b></td>
    <td><b>Domain</b></td>
  </tr>

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
</table>

## 🛠️ Text Tampering Methods

### DiffUTE — Universal Text Editing Diffusion Model
- Diffusion-based universal text-editing; replaces or modifies words while preserving style and background. Great for diffusion-driven text replacement and high-fidelity edits.
- Link: [GitHub](https://github.com/chenhaoxing/DiffUTE)


### MOSTEL — Stroke-level Scene Text Editing
- Stroke-aware editing at the stroke level for better glyph/edge fidelity; minimizes disruption to stroke structure for realistic tampering.
- Link: [GitHub](https://github.com/qqqyd/MOSTEL)


### SRNet (SRNet / SwapText family)
- GAN-based word/region-level editing preserving background context and font style; classical baseline for quick experiments.
- Link: [GitHub](https://github.com/lksshw/SRNet)


### dRENDER / De-rendering Stylized Text
- Parses rendering parameters of stylized text to de-render and re-render with precise, style-preserving control.
- Link: [GitHub](https://github.com/CyberAgentAILab/derendering-text)

### STEFANN — Scene Text Editor using Font-Adaptive Neural Network
- Character-level font-adaptive editor (FANnet + Colornet) preserving font structure and color; good for per-character edits and synthesis.
- Link: [GitHub](https://github.com/prasunroy/stefann)


### AnyText / AnyText2
- Diffusion-based multilingual text generation and editing; AnyText2 improves speed and multilingual quality.
- Link: [GitHub](https://github.com/tyxsspa/AnyText)


### TextCtrl — Diffusion-based Scene Text Editing with Prior Guidance Control
- Disentangles style and glyph structure with prior guidance for faithful style preservation; strong modern diffusion baseline.
- Link: [GitHub](https://github.com/weichaozeng/TextCtrl)


### TextDiff — Mask-Guided Residual Diffusion Models for Scene Text
- Mask-guided residual diffusion for scene text; enables residual editing instead of full-image generation.
- Link: [GitHub](https://github.com/microsoft/unilm/tree/master/textdiffuser)

### UDiffText (UDiff / UDiffText)
- Unified character-aware diffusion for high-quality text synthesis in arbitrary images; precise character-level control and scalable generation.
- Link: [GitHub](https://github.com/ZYM-PKU/UDiffText)

---

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
  

---

## 🤝 Contributing
Contributions are welcome! Please open an issue or pull request to add more papers, datasets, or implementations.

---

## ⭐ Acknowledgements
If you find this list helpful, please star ⭐ the repository to support the project.
