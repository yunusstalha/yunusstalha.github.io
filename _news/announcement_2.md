---
layout: post
title: Our paper MobileUNETR has been accepted to ECCV 2024 BioImage Computing Workshop (ORAL)
date: 2024-09-29 16:11:00-0400
inline: false
related_posts: false
---

# MobileUNETR: A Lightweight Hybrid CNN-Transformer Model for Skin Lesion Segmentation

Skin cancer segmentation poses a significant challenge in medical image analysis. Numerous existing solutions, predominantly **CNN-based**, face issues related to a lack of global contextual understanding. Alternatively, some approaches resort to **large-scale Transformer models** to bridge the global contextual gaps, but at the expense of model size and computational complexity. Furthermore, many Transformer-based approaches rely primarily on **CNN-based decoders**, overlooking the benefits of Transformer-based decoding models.

## Our Contribution
Recognizing these limitations, we introduce **MobileUNETR**, an efficient and lightweight segmentation model that overcomes the performance constraints associated with both CNNs and Transformers while minimizing model size. MobileUNETR presents a **promising stride towards efficient image segmentation** with the following key features:

### 🔹 Key Features:
1. **Hybrid CNN-Transformer Encoder**  
   - Balances local and global contextual feature extraction in an efficient manner.

2. **Novel Hybrid Decoder**  
   - Simultaneously utilizes **low-level** and **global features** at different resolutions within the decoding stage for **accurate mask generation**.

3. **Superior Performance & Efficiency**  
   - Outperforms large and complex architectures with just **3 million parameters** and a computational complexity of **1.3 GFLOP**.  
   - Achieves **10× and 23×** reduction in parameters and FLOPs, respectively.

## Experimental Validation
Extensive experiments have been conducted to validate the effectiveness of our proposed method on **four publicly available skin lesion segmentation datasets**, including:
- **ISIC 2016**
- **ISIC 2017**
- **ISIC 2018**
- **PH2 datasets**

Moreover we have also obtained competitive performances on **Cityscapes**, **Postdam**, and **Vaihingen** datasets.

## 📌 Code Availability
The code will be publicly available at:  
🔗 **[GitHub Repository](https://github.com/osupcvlab/mobileunetr)**
