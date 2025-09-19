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
    <td>Yang et al. <a href="#ref1">[1]</a> : Deep Learning + ELA fusion</td>
    <td>2021</td>
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
    <td>–</td>
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
    <td>TMM</td>
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
    <td>2024</td>
    <td>AAAI</td>
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
    <td>IEEE</td>
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



## Paper List 

<a id="ref1"></a>[1] P. Yang, W. Fang, F. Zhang, L. Bai, Y. Gao, "Document Image Forgery Detection Based on Deep Learning Models," *2022 International Symposium on Electrical, Electronics and Information Engineering (ISEEIE)*, 2022, pp. 1-5, [Paper](https://ieeexplore.ieee.org/document/9853295)


<a id="ref2"></a>[2] Y. Wang, C. Liu, X. Liu, D. Peng, L. Jin, "SR3 for Tampered Text Detection," *Proceedings of the European Conference on Computer Vision (ECCV)*, 2022, pp. 1234-1245, [Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136880214.pdf)

<a id="ref3"></a>[3] C. Qu, Y. Liu, X. Liu, D. Peng, F. Guo, L. Jin, "DTD: Document Tampering Detection," *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)*, 2023, pp. 5937–5946 [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Qu_Towards_Robust_Tampered_Text_Detection_in_Document_Image_New_Dataset_CVPR_2023_paper.pdf) | [Code](https://github.com/qcf-568/DocTamper)

<a id="ref4"></a>[4] Y. Okamoto, G. Osada, I. Yahiro, R. Hasegawa, P. Zhu, H. Kataoka, "Image Generation and Learning Strategy for Deep Document Forgery Detection," *arXiv preprint arXiv:2311.03650*, Nov. 2023. [Paper](https://arxiv.org/pdf/2311.03650).

<a id="ref5"></a>[5] J. Jain, "AI-Driven OCR for Fraud Detection in FinTech Income Verification Systems," *International Research Journal of Engineering and Technology (IRJET)*, Vol. 11, Issue 12, Dec. 2024, pp. 850-854. [Paper](https://www.irjet.net/archives/V11/i12/IRJET-V11I12116.pdf)

<a id="ref6"></a>[6] Z. Chen, S. Chen, T. Yao, K. Sun, S. Ding, X. Lin, L. Cao, R. Ji, "Enhancing Tampered Text Detection through Frequency Feature Fusion and Decomposition" in *Proceedings of the European Conference on Computer Vision (ECCV)*, 2024, pp. (exact pages), [Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04834.pdf)

<a id="ref7"></a>[7] C. Qu, J. Liu, H. Chen, B. Yu, J. Liu, W. Wang, L. Jin, "Explainable Tampered Text Detection via Multimodal Large Models," *arXiv preprint arXiv:2412.14816v2*, Dec. 2024. [Paper](https://arxiv.org/pdf/2412.14816v2)

<a id="ref8"></a>[8] H. Shao, Z. Qian, K. Huang, W. Wang, X. Huang, Q. Wang, "Delving into Adversarial Robustness on Document Tampering Localization," *Proceedings of the European Conference on Computer Vision (ECCV)*, 2024. [Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/08224.pdf)

<a id="ref9"></a>[9] J. Wang, L. Mou, C. Zheng, W. Gao, "Image-based Freeform Handwriting Authentication with Energy-oriented Self-Supervised Learning," *arXiv preprint arXiv:2408.09676*, Aug. 2024. [Paper](https://arxiv.org/pdf/2408.09676)

<a id="ref10"></a>[10] G. Li, X. Yang, W. Ma, "A Two-Stage Dual-Path Framework for Text Tampering Detection and Recognition," *arXiv preprint arXiv:2402.13545v2*, Feb. 2024. [Paper](https://arxiv.org/pdf/2402.13545.pdf)

<a id="ref11"></a>[11] X. Liao, S. Chen, J. Chen, T. Wang, X. Li, "CTP-Net: Character Texture Perception Network for Document Image Forgery Localization," *arXiv preprint arXiv:2308.02158v1*, Aug. 2023. [Paper](https://arxiv.org/pdf/2308.02158v1)

<a id="ref12"></a>[12] B. Li, J. Xu, Y. Wang, Z. Wu, "Robust Text Image Tampering Localization via Forgery Traces Enhancement and Multiscale Attention," *IEEE Transactions on Information Forensics and Security (TIFS)*, 2024. [Paper](https://ieeexplore.ieee.org/document/10440540/) | [Code](https://github.com/nbudongli/text-image-forgery-detection)


<a id="ref13"></a>[13] R. Ren, Q. Hao, F. Gu, S. Niu, J. Zhang, M. Wang, "EMF-Net: An Edge-Guided Multi-Feature Fusion Network for Text Manipulation Detection," *Expert Systems with Applications*, Vol. 249, Part A, 2024, 123548. [Paper](https://www.sciencedirect.com/science/article/pii/S0957417424004135)

<a id="ref14"></a>[14] C. Qu, Y. Zhong, F. Guo, L. Jin, "Revisiting Tampered Scene Text Detection in the Era of Generative AI," *arXiv preprint arXiv:2407.21422*, 2025. [Paper](https://arxiv.org/pdf/2407.21422) | [Code](https://github.com/qcf-568/OSTF)  
 
<a id="ref15"></a>[15] J. Duan, H. Sun, F. Ji, et al., "RealDTT: Towards A Comprehensive Real-World Dataset for Tampered Text Detection," *International Journal of Computer Vision*, 2025. [Paper](https://link.springer.com/article/10.1007/s11263-025-02515-2)

<a id="ref16"></a>[16] K. Wong, J. Zhou, H. Wu, Y.-W. Si, J. Zhou, "ADCD-Net: Robust Document Image Forgery Localization via Adaptive DCT Feature and Hierarchical Content Disentanglement," *arXiv preprint arXiv:2507.16397*, 2025. [Paper](https://arxiv.org/pdf/2507.16397) | [Code](https://github.com/KAHIMWONG/ADCD-Net)


<a id="ref17"></a>[17] W. Li, B. Li, K. Zheng, S. Li, H. Li, "Document image forgery detection and localization in desensitization scenarios," *Signal Processing*, vol. 238, 110123, 2025. [Paper](https://www.sciencedirect.com/science/article/pii/S0165168425002373)

<a id="ref18"></a>[18] A. D. Nguyen, H.-Y. Kim, H. N. Nguyen, "TALIU: A Novel Decoder and Augmentation Strategy for Boosting Tampered Document Image Detection," *IEEE Access*, vol. 13, pp. 70340-70351, 2025. [Paper](https://ieeexplore.ieee.org/document/10964281)  

<a id="ref19"></a>[19] L. Li, Y. Bai, S. Zhang, M. Emam, "Document forgery detection based on spatial-frequency and multi-scale feature network," *Journal of Visual Communication and Image Representation*, vol. 107, 104393, 2025. [Paper](https://www.sciencedirect.com/science/article/pii/S1047320325000070) 

<a id="ref20"></a>[20] L. Li, K. Zhang, J. Lu, S. Zhang, N. Chu, "Multiclassification Tampering Detection Algorithm Based on Spatial-Frequency Fusion and Swin-T," *IET Image Processing*, vol. 19, 2025. [Paper](https://www.researchgate.net/publication/389433177_Multiclassification_Tampering_Detection_Algorithm_Based_on_Spatial-Frequency_Fusion_and_Swin-T)

<a id="ref21"></a>[21] A. George, S. Marcel, "EdgeDoc: Hybrid CNN-Transformer Model for Accurate Forgery Detection and Localization in ID Documents," *arXiv preprint arXiv:2508.16284*, 2025. [Paper](https://arxiv.org/pdf/2508.16284)

## 🤝 Contributing
Contributions are welcome! Please open an issue or pull request to add more papers, datasets, or implementations.

---

## ⭐ Acknowledgements
If you find this list helpful, please star ⭐ the repository to support the project.
