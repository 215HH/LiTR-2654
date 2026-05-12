# 🎯 LiTR-2654: A Large-Scale Visual-Depth-Thermal Salient Object Detection Benchmark



## 📢 Publication Update
**🎉 We are delighted to announce that our paper has been officially accepted by IEEE Transactions on Image Processing (TIP 2026)!**

📑 **IEEE Xplore**: https://ieeexplore.ieee.org/document/11515002

---

## 📖 Introduction
Fusing Visual-Depth-Thermal (VDT) data holds immense potential for robust Salient Object Detection (SOD) in complex environments. However, current research is constrained by **dataset scarcity** and the limitations of symmetric direct fusion strategies.

To address these gaps, we construct **LiTR-2654**, a comprehensive benchmark comprising **2,654 spatially aligned VDT image triplets** captured via LiDAR and dual-modality cameras. This dataset features high diversity and reduced center bias, designed to advance practical applications of multi-modal SOD.

With this benchmark, we propose the **Asymmetric Feature Consistency Reinforcement Network (AFCRNet)**, which effectively utilizes triple-modality cues to achieve state-of-the-art SOD performance.

---

## ✨ Core Highlights
### Dataset Features
- **2,654 fully aligned image triplets**: RGB, Depth, Thermal
- **Uniform resolution**: All images are 640×480 pixels
- **High scene diversity**: Covers indoor, outdoor, day and night scenarios
- **Reduced center bias**: Objects are distributed across the entire image
- **Precise pixel-level annotations**: Manually labeled ground truth masks

### Method Contributions
- Novel "Unify-then-Integrate" asymmetric fusion strategy
- Context-guided decoder for multi-level feature alignment
- Edge supervision for accurate object contour optimization
- Superior performance on both public and self-built datasets

---

## 📊 LiTR-2654 Dataset Analysis
The dataset contains 2,654 image groups, each consisting of three modalities: RGB images, depth images, and thermal images. The proportions of different scenes and object categories are shown in the figure below.

<div align="center">
<img src="https://github.com/user-attachments/assets/1accbfbf-a0bf-41d7-b4f1-8176d087a83f" width="700" alt="Dataset Statistics">
</div>

### Dataset Access
- **Demo Subset**: This repository hosts a randomly sampled subset for demonstration and preliminary experiments
- **Complete Dataset**: Please contact the authors directly via email to request the full dataset
- **Temporary Link**: [Baidu Netdisk](https://pan.baidu.com/s/127JnwxfPTDCRP6O0CjeTYw&pwd=kk5f) (Password: kk5f)

---

## 📈 Experimental Results
We provide the prediction results of our AFCRNet on two widely used VDT-SOD benchmarks:

| Benchmark | Download Link |
|-----------|---------------|
| VDT-2048 | [Download Results](https://pan.baidu.com/s/1QYEFogPRPUllnIvYtGfvLw&pwd=we7x) (Password: we7x) |
| LiTR-2654 | [Download Results](https://pan.baidu.com/s/1X01bpWUnBUjmJxd-vj4oiQ&pwd=d99a) (Password: d99a) |

---

## 💻 Code
🚧 **The code is coming soon!**  
Thank you for your interest in our work! We are actively organizing and polishing the code to ensure its quality and readability.  
Don't forget to ⭐ Star this repo — we'll notify all stargazers as soon as the code is released!

---

## 🧪 Evaluation Metrics Toolbox
We use the standard SOD evaluation toolbox for all experiments:

👉 [PySODMetrics](https://github.com/lartpang/PySODMetrics): A simple and efficient Python implementation of SOD metrics, including MAE, S-measure, E-measure, weighted F-measure, and more.

---

## 📝 Citation
If you find our dataset or method useful in your research, please cite our paper:

```bibtex
@ARTICLE{11515002,
  author={Xu, Chang and Li, Qingwu and Zhao, Shukai and Li, Hao},
  journal={IEEE Transactions on Image Processing}, 
  title={Asymmetric Feature Consistency Reinforcement Network for Visual-Depth-Thermal Salient Object Detection and a New Benchmark}, 
  year={2026},
  volume={},
  number={},
  pages={1-1},
  keywords={Visualization;Object detection;Modeling;Educational institutions;Training;Sun;Triples (Data structure);Fuses;Modules (abstract algebra);Circuits;Visual-depth-thermal;salient object detection;feature fusion;feature consistency;LiTR-2654 dataset},
  doi={10.1109/TIP.2026.3690334}}
