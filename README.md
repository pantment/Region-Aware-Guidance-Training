# Region-Aware Guidance Training (RAGT)

[![Paper](https://img.shields.io/badge/Paper-Elsevier-blue)](https://doi.org/10.1016/j.jii.2025.100978)  
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

This is the official repository for our recent work:  
**Region-Aware Guidance Training for pipeline segmentation in complex outdoor industrial environments**  
*Pantelis Mentesidis, Vasileios Mygdalis, Ioannis Pitas*  
Published in *Journal of Industrial Information Integration*, Elsevier, 2025.

---

## 🌟 Highlights

* **Region-Aware Knowledge Distillation (RAKD):** Teaches models to focus on task-relevant regions, improving discriminative feature learning.  
* **Background-Aware Augmentation (BAUG):** Enhances robustness to diverse environments by augmenting pipeline images with varied backgrounds.  
* **Up to +8 mIoU improvement** on challenging industrial segmentation tasks, with **zero inference overhead**.  
* **Modular & model-agnostic:** Works with different state-of-the-art lightweight segmentation networks.  

---

## 🚀 Updates
- (Coming soon) Code release.
- (Oct 2025) Paper accepted and published in *Journal of Industrial Information Integration*. 🎉  

---

## 📖 Abstract
Accurate segmentation of insulated pipelines is essential for automated inspection and structural analysis in complex industrial environments. While UAV-based visual inspection is increasingly adopted, current systems often struggle with cluttered scenes and rely heavily on manual interpretation.  

This paper proposes **Region-Aware Guidance Training (RAGT)** for pipeline segmentation, a novel and modular deep neural network (DNN) training framework designed to enhance the performance and deployment readiness of state-of-the-art (SOTA) real-time region segmentation models in cluttered industrial settings.  

RAGT integrates two complementary components:  
- **Region-Augmented Knowledge Distillation (RAKD):** Guides the model to focus on task-relevant regions.  
- **Background-Aware Augmentation (BAUG):** Improves generalization by increasing background diversity during training.  

Both modules can operate independently or jointly within the unified RAGT framework. Experiments demonstrate that RAGT achieves improvements of **up to +8 mIoU** in challenging segmentation tasks.
👉 [Read the full paper here](https://doi.org/10.1016/j.jii.2025.100978)
