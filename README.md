# awesome-tampered-text-detection
A curated collection of papers, datasets, code, and tools for detecting tampered text and forged documents.

## 📚 Papers
### Overview of the Papers

<table cellspacing="0" border="1">
  <tr>
    <td><b>Paper</b></td>
    <td><b>Year</b></td>
    <td><b>Venue</b></td>
    <td><b>Method</b></td>
    <td><b>Dataset</b></td>
    <td><b>Training Code</b></td>
    <td><b>Testing/Validation Code</b></td>
    <td><b>Inference Code</b></td>
  </tr>

  <tr>
    <td>Wang et al. <a href="#ref1">[1]</a> : Deep Learning + ELA fusion</td>
    <td>2021</td>
    <td>ISEEIE</td>
    <td>Deep learning + ELA fusion</td>
    <td>Ali Tianchi Competition</td>
    <td>❌</td>
    <td>❌</td>
    <td>❌</td>
  </tr>

  <tr>
    <td>Li et al. <a href="#ref2">[2]</a> : SR3</td>
    <td>2022</td>
    <td>ECCV</td>
    <td>SR3</td>
    <td><a href="https://github.com/wangyuxin87/Tampered-IC13">T-IC13</a></td>
    <td>❌</td>
    <td>❌</td>
    <td>❌</td>
  </tr>

  <tr>
    <td>Wang et al. <a href="#ref3">[3]</a> : DTD</td>
    <td>2023</td>
    <td>CVPR</td>
    <td>DTD</td>
    <td><a href="https://github.com/qcf-568/DocTamper">Doc-Tamper</a></td>
    <td>✅</td>
    <td>✅</td>
    <td>✅</td>
  </tr>

  <tr>
    <td>Zhang et al. <a href="#ref4">[4]</a> : FCN</td>
    <td>2023</td>
    <td>arXiv</td>
    <td>FCN (semantic segmentation)</td>
    <td>FD-VIED</td>
    <td>❌</td>
    <td>❌</td>
    <td>❌</td>
  </tr>

  <tr>
    <td>Chen et al. <a href="#ref5">[5]</a> : K-Means, Decision Trees, Logistic Regression</td>
    <td>2024</td>
    <td>IRJET</td>
    <td>K-Means, Decision Trees, Logistic Regression</td>
    <td>–</td>
    <td>❌</td>
    <td>❌</td>
    <td>❌</td>
  </tr>

  <tr>
    <td>Li et al. <a href="#ref6">[6]</a> : FFDN</td>
    <td>2024</td>
    <td>ECCV</td>
    <td>FFDN</td>
    <td><a href="https://github.com/qcf-568/DocTamper">Doc-Tamper</a></td>
    <td>❌</td>
    <td>❌</td>
    <td>❌</td>
  </tr>

  <tr>
    <td>Zhang et al. <a href="#ref7">[7]</a> : TextSleuth / Tampered Text Detective</td>
    <td>2024</td>
    <td>arXiv</td>
    <td>TextSleuth / Tampered Text Detective</td>
    <td>ETTD</td>
    <td>❌</td>
    <td>❌</td>
    <td>❌</td>
  </tr>

  <tr>
    <td>Li et al. <a href="#ref8">[8]</a> : DTL-ARob</td>
    <td>2024</td>
    <td>ECCV</td>
    <td>DTL-ARob</td>
    <td><a href="https://github.com/qcf-568/DocTamper">Doc-Tamper</a>, <a href="https://github.com/wangyuxin87/Tampered_sroie">T-SROIE</a></td>
    <td>✅</td>
    <td>✅</td>
    <td>✅</td>
  </tr>

  <tr>
    <td>Chen et al. <a href="#ref9">[9]</a> : SherlockNet</td>
    <td>2024</td>
    <td>TMM</td>
    <td>SherlockNet</td>
    <td><a href="https://github.com/WangJingyao07/SherlockNet">EN-HA</a></td>
    <td>✅</td>
    <td>✅</td>
    <td>✅</td>
  </tr>

  <tr>
    <td>Zhao et al. <a href="#ref10">[10]</a> : Dual-path framework</td>
    <td>2024</td>
    <td>arXiv</td>
    <td>Dual-path framework</td>
    <td>Suning Scene Data</td>
    <td>❌</td>
    <td>❌</td>
    <td>❌</td>
  </tr>

  <tr>
    <td>Li et al. <a href="#ref11">[11]</a> : CTP-Net</td>
    <td>2024</td>
    <td>AAAI</td>
    <td>CTP-Net</td>
    <td>Fake Chinese Trademark (FCTM)</td>
    <td>❌</td>
    <td>❌</td>
    <td>❌</td>
  </tr>

  <tr>
    <td>Li et al. <a href="#ref12">[12]</a> : Forgery trace enhancement + multiscale attention</td>
    <td>2024</td>
    <td>IEEE</td>
    <td>Forgery trace enhancement + multiscale attention</td>
    <td>TextTamper</td>
    <td>✅</td>
    <td>✅</td>
    <td>✅</td>
  </tr>

  <tr>
    <td>Li et al. <a href="#ref13">[13]</a> : EMF-Net</td>
    <td>2024</td>
    <td>Expert Systems With Applications</td>
    <td>EMF-Net</td>
    <td><a href="https://github.com/tampered816/IPM15K">TMI12K</a></td>
    <td>❌</td>
    <td>❌</td>
    <td>❌</td>
  </tr>

  <tr>
    <td>Li et al. <a href="#ref14">[14]</a> : DAF + Text Jitter</td>
    <td>2025</td>
    <td>AAAI</td>
    <td>DAF + Text Jitter</td>
    <td><a href="https://github.com/qcf-568/OSTF">OSTF</a></td>
    <td>✅</td>
    <td>✅</td>
    <td>✅</td>
  </tr>

  <tr>
    <td>Li et al. <a href="#ref15">[15]</a> : TTDMamba</td>
    <td>2025</td>
    <td>IJCV</td>
    <td>TTDMamba</td>
    <td><a href="https://github.com/edmundhaohao/RealDTT">RealTTD</a></td>
    <td>❌</td>
    <td>❌</td>
    <td>❌</td>
  </tr>

  <tr>
    <td>Huang et al. <a href="#ref16">[16]</a> : ADCD-Net</td>
    <td>2025</td>
    <td>ICCV</td>
    <td>ADCD-Net</td>
    <td><a href="https://github.com/qcf-568/DocTamper">Doc-Tamper</a></td>
    <td>✅</td>
    <td>✅</td>
    <td>✅</td>
  </tr>

  <tr>
    <td>Li et al. <a href="#ref17">[17]</a> : DCLNet</td>
    <td>2025</td>
    <td>Signal Processing</td>
    <td>DCLNet</td>
    <td>DocTD</td>
    <td>❌</td>
    <td>❌</td>
    <td>❌</td>
  </tr>

  <tr>
    <td>Li et al. <a href="#ref18">[18]</a> : TALIU</td>
    <td>2025</td>
    <td>IEEE</td>
    <td>TALIU</td>
    <td><a href="https://github.com/qcf-568/DocTamper">Doc-Tamper</a></td>
    <td>❌</td>
    <td>❌</td>
    <td>❌</td>
  </tr>

  <tr>
    <td>Li et al. <a href="#ref19">[19]</a> : CD-SD</td>
    <td>2025</td>
    <td>IEEE</td>
    <td>CD-SD</td>
    <td><a href="https://github.com/qcf-568/DocTamper">Doc-Tamper</a></td>
    <td>❌</td>
    <td>❌</td>
    <td>❌</td>
  </tr>

  <tr>
    <td>Li et al. <a href="#ref20">[20]</a> : Spatial-Frequency Fusion + Swin-T</td>
    <td>2025</td>
    <td>IET</td>
    <td>Spatial-Frequency Fusion + Swin-T</td>
    <td>Document Tamper</td>
    <td>❌</td>
    <td>❌</td>
    <td>❌</td>
  </tr>

  <tr>
    <td>Li et al. <a href="#ref21">[21]</a> : EdgeDoc</td>
    <td>2025</td>
    <td>Pattern Recognition</td>
    <td>EdgeDoc</td>
    <td>–</td>
    <td>❌</td>
    <td>❌</td>
    <td>❌</td>
  </tr>
</table>
---

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

## 2017  

### 🔹 A Dataset for Forgery Detection and Spotting in Document Images  
- **Annotation**: Character-level bounding boxes + values (XML)  
- **Paper**: [A Dataset for Forgery Detection and Spotting in Document Images](http://navidomass.univ-lr.fr/ForgeryDataset/)  
- **Domain**: Payslips  
- **Size**: 677  
- **Tampering**: Copy-paste  



## 2021  

### 🔹 CMID (Copy-Move ID)  
- **Annotation**: Pixel-level  
- **Paper**: [CMID: A New Dataset for Copy-Move Forgeries on ID Documents](https://cmiddataset.github.io/)  
- **Domain**: ID Documents  
- **Size**: Genuine: 304 | Tampered: 893  
- **Tampering**: Copy-move  



## 2022  

### 🔹 FCD (Forged Character Detection Datasets)  
- **Annotation**: Bounding box  
- **Paper**: FORGED CHARACTER DETECTION DATASETS: Passports, Driving Licences and Visa Stickers  
- **Subsets**:  
  - FCD-P (Passport) – 15,000  
  - FCD-D (Driving Licence) – 15,000  
  - FCD-V (Visa Sticker) – 15,000  
- **Tampering**: Character-level forgery  
- **Implementation**: [GitHub Repo](https://github.com/turab45/Dataset-forged-characters-detection-on-driving-licences-and-passports)  

### 🔹 Tampered-IC13  
- **Annotation**: Bounding box  
- **Paper**: Detecting Tampered Scene Text in the Wild (S3R strategy)  
- **Domain**: Scene Texts  
- **Subsets**: Training: 229 | Testing: 233  
- **Tampering**: Neural network (SRNet)  



## 2023  

### 🔹 FSD (Forged Scanned Document)  
- **Annotation**: Pixel-level segmentation  
- **Paper**: [FSD: A Novel Forged Document Dataset and Baseline](https://drive.google.com/file/d/1mCFH41b-v4OXeYAVFB2MppSQKa-BHtLH/view)  
- **Domain**: Scanned Documents (FUNSD-based)  
- **Tampering**: Copy-move, Splicing, Resampling  

### 🔹 DocTamper Dataset  
- **Annotation**: Pixel-level segmentation  
- **Paper**: Towards Robust Tampered Text Detection in Document Image: New dataset and New Solution  
- **Subsets**:  
  - Doc-Tamper Training: 120,000 (Contracts, Invoices, Receipts)  
  - Doc-Tamper Testing: 30,000  
  - DocTamper-FCD: 2,000 (Text pages, Noisy Office Dataset)  
  - DocTamper-SCD: 18,000 (Receipts, Huawei Cloud)  
- **Tampering**: Copy-move, Splicing, Generation  



## 2024  

### 🔹 ETTD (Explainable Tampered Text Detection Dataset)  
- **Annotation**: Pixel-level + Natural language annotations  
- **Paper**: TextSleuth: Towards Explainable Tampered Text Detection  
- **Domain**: Documents, ID cards, scene texts  
- **Subsets**:  
  - ETTD-Train: 10,400  
  - ETTD-Test: 600  
  - ETTD-CD: 1,000 (Scene texts, ICDAR13)  
- **Tampering**: Diffusion models, Copy-move, Splicing (Photoshop)  
- **Implementation**: DiffUTE  


## 2025  

### 🔹 OSTF (Open-set Scene Text Forensics)  
- **Annotation**: Bounding box  
- **Paper**: Revisiting Tampered Scene Text Detection in the Era of Generative AI  
- **Domain**: Scene text (ICDAR 2013, ReCTS, TextOCR, etc.)  
- **Models Benchmarked**: Derend, SRNet, STEFANN, Mostel, DiffSTE, AnyText, Textdiff, Udifftext  

### 🔹 RealDTT (Real-world Comprehensive Dataset of Tampered Text Images)  
- **Annotation**: Pixel-level segmentation  
- **Paper**: RealDTT: Towards A Comprehensive Real-World Dataset for Tampered Text Detection  
- **Domain**: Scene text, documents (MARIO-LAION, FUNSD, ReCTS, LSVT, RCTW)  
- **Subsets**:  
  - Photoshop subset: 4,012  
  - STEFANN: 500  
  - MOSTEL: 15,000  
  - VATr: 199  
  - ViTEraser: 7,000  
  - SRNet: 18,000  
  - DiffSTE: 40,000  
  - AnyText: 47,000  
  - UDiffText: 127,881  
  - TextDiffuser: 40,000  

### 🔹 RTM (Real Text Manipulation) Dataset  
- **Annotation**: Pixel-level binary masks  
- **Paper**: Toward Real Text Manipulation Detection: New Dataset and New Solution  
- **Domain**: Charts, receipts, certificates, scanned documents, tables (SROIE, FUNSD, TNCR, Volunteers)  
- **Subsets**: Training: 5,803 | Testing: 3,197  
- **Tampering**: Copy-move, Splicing, Insertion, Inpainting, Coverage (Photoshop)  
- **Implementation**: ASC-Former  

---



<a id="ref1"></a>[1] P. Yang, W. Fang, F. Zhang, L. Bai, Y. Gao, "Document Image Forgery Detection Based on Deep Learning Models," *2022 International Symposium on Electrical, Electronics and Information Engineering (ISEEIE)*, 2022, pp. 1-5, [Paper](https://ieeexplore.ieee.org/document/9853295).


<a id="ref2"></a>[2] Y. Wang, C. Liu, X. Liu, D. Peng, L. Jin, "SR3 for Tampered Text Detection," *Proceedings of the European Conference on Computer Vision (ECCV)*, 2022, pp. 1234-1245, [Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136880214.pdf).

<a id="ref3"></a>[3] C. Qu, Y. Liu, X. Liu, D. Peng, F. Guo, L. Jin, "DTD: Document Tampering Detection," *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)*, 2023, pp. 5937–5946 [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Qu_Towards_Robust_Tampered_Text_Detection_in_Document_Image_New_Dataset_CVPR_2023_paper.pdf) | [code](https://github.com/qcf-568/DocTamper).

<a id="ref4"></a>[4] Zhang et al., *FCN-based Document Forgery Detection*, arXiv 2023.  
<a id="ref5"></a>[5] Chen et al., *Handwriting Authentication via K-Means etc.*, IRJET 2024.  
<a id="ref6"></a>[6] Li et al., *FFDN: Forgery Feature Detection Network*, ECCV 2024.  
<a id="ref7"></a>[7] Zhang et al., *TextSleuth: Tampered Text Detection*, arXiv 2024.  
<a id="ref8"></a>[8] Li et al., *DTL-ARob: Document Tamper Localization*, ECCV 2024.  
<a id="ref9"></a>[9] Chen et al., *SherlockNet for Tamper Localization*, TMM 2024.  
<a id="ref10"></a>[10] Zhao et al., *Dual-path Framework for Scene Text*, arXiv 2024.  
<a id="ref11"></a>[11] Li et al., *CTP-Net for Trademark Forgery*, AAAI 2024.  
<a id="ref12"></a>[12] Li et al., *Forgery Trace Enhancement*, IEEE 2024.  
<a id="ref13"></a>[13] Li et al., *EMF-Net*, Expert Systems With Applications 2024.  
<a id="ref14"></a>[14] Li et al., *DAF + Text Jitter*, AAAI 2025.  
<a id="ref15"></a>[15] Li et al., *TTDMamba*, IJCV 2025.  
<a id="ref16"></a>[16] Huang et al., *ADCD-Net*, ICCV 2025.  
<a id="ref17"></a>[17] Li et al., *DCLNet*, Signal Processing 2025.  
<a id="ref18"></a>[18] Li et al., *TALIU*, IEEE 2025.  
<a id="ref19"></a>[19] Li et al., *CD-SD*, IEEE 2025.  
<a id="ref20"></a>[20] Li et al., *Spatial-Frequency Fusion + Swin-T*, IET 2025.  
<a id="ref21"></a>[21] Li et al., *EdgeDoc*, Pattern Recognition 2025. 

## 🤝 Contributing
Contributions are welcome! Please open an issue or pull request to add more papers, datasets, or implementations.

---

## ⭐ Acknowledgements
If you find this list helpful, please star ⭐ the repository to support the project.
