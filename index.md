# Transparency and Explainability of Federated Learning

## 🎯 Overview

This research project focuses on **Transparency and Explainability of Federated Learning**, addressing critical challenges in making federated learning systems more interpretable, cost-aware, and adaptable to domain shifts. The work is conducted by research teams at Tan Tao University (Vietnam) and National Institute of Information and Communications Technology (Japan).

### 🌟 Research Highlights

Our research tackles fundamental challenges in explainable and transparent federated learning:

- **Cost-Performance Analysis**: Framework for evaluating trade-offs between training costs and model performance
- **Privacy-Preserving Contribution Measurement**: Quantifying client contributions without accessing raw datasets
- **Intelligent Client Selection**: Algorithms that balance performance gains with training expenses
- **Domain Adaptation with Server Feedback**: Lightweight feedback mechanisms (Grad-CAM, SHAP) for better generalization
- **Modality-Specific Data Generation**: TVAE for tabular data, diffusion models for images, LLMs for text

---

## 🚀 Key Features

### 1. **Explainable Cost-Performance Framework**

Comprehensive transparency in federated learning economics:

- **Four-Component Cost Model**: Data usage, market context, model improvement, resource consumption
- **Privacy-Preserving Measurement**: Analyzes model behavior via Wasserstein distance, not raw data
- **Interpretable Dashboards**: Visual analytics for cost distribution and performance ratios
- **Real-Time Monitoring**: Tracks contributions and expenses throughout training

### 2. **Intelligent Client Selection**

Strategic optimization for Quality of Training:

- **Two-Phase Approach**: Clustering (K-Means + K-Medoids) followed by greedy selection
- **Alternating Criteria**: Balances performance and cost across training rounds
- **Fairness Mechanism**: Penalty function ensures all clients get opportunities
- **Proven Results**: 8-32% cost reduction, 7-26% time savings while maintaining accuracy

### 3. **Domain Adaptation with Server Feedback**

Novel approach for handling distributional shifts:

- **Server-Side Analysis**: Detects domain shifts and identifies misclassified samples
- **Lightweight Feedback**: Grad-CAM (images) and SHAP (tabular) signals without raw data access
- **Client-Side Adaptation**: Targeted training guided by interpretable feedback
- **Significant Gains**: Up to 10% accuracy improvement under domain shift

### 4. **Multi-Modal Data Generation**

Privacy-preserving synthetic data augmentation:

- **Tabular**: TVAE with feedback-guided feature injection
- **Image**: Diffusion models conditioned on Grad-CAM regions
- **Text**: LLM-based generation with validation criteria
- **Enhanced Performance**: Outperforms baselines across all modalities

---

## 📚 Publications

### Published Papers

#### 1. Client Selection of Federated Learning by Cost-Performance Analysis

> **Authors**: Tien-Dung Cao, Hoang-Duc Le  
> **Venue**: 20th International Conference on Intelligent Systems and Knowledge Engineering (ISKE 2025)  
> **Pages**: 209-216  
> **Publisher**: IEEE

**Keywords**: Federated Learning, Client Selection, Cost Model, Quality of Training, Explainable AI

---

#### 2. Domain Adaptation of Federated Learning by Data Generation and Server Feedback

> **Authors**: Phuong-Anh Vu, Kim-Tinh Phan, Cao-Dien Nguyen, Tien-Dung Cao, Le Trieu Phong, Ngoc-Thai Nguyen  
> **Venue**: Multi-disciplinary International Workshop on Artificial Intelligence (MIWAI 2025)  
> **Series**: Lecture Notes in Artificial Intelligence (LNAI), vol 16354  
> **Pages**: 272-283  
> **DOI**: [10.1007/978-981-95-4960-3_22](https://doi.org/10.1007/978-981-95-4960-3_22)  
> **Publisher**: Springer Nature Singapore

**Keywords**: Federated Learning, Server Feedback, Data Generation, Knowledge Distillation, Domain Adaptation

---

### Research Impact

- **Publications**: 2 conference papers (2025)
- **Venues**: IEEE ISKE, Springer MIWAI (LNAI)

---

## 👥 Research Team

### Principal Investigator

**Tien-Dung Cao, PhD**  
Dean, School of Information Technology  
Tan Tao University, Vietnam  
📧 dung.cao@ttu.edu.vn

---

### Collaborators

**Le Trieu Phong, PhD**  
National Institute of Information and Communications Technology (NICT), Tokyo, Japan  
📧 phong@nict.go.jp

**Ngoc-Thai Nguyen**  
Viettel Solutions, Ho Chi Minh City, Vietnam

**Hoang-Duc Le**  
Faculty of Mathematics & Computer Science, University of Science, VNU-HCMC, Vietnam  
📧 lhduc@hcmus.edu.vn

---

### Students

**Phuong-Anh Vu**, **Kim-Tinh Phan**, **Cao-Dien Nguyen**  
School of Information Technology, Tan Tao University, Vietnam

---

## 🙏 Acknowledgments

This research is supported by:

- **Tan Tao University Foundation for Science and Technology Development**  
  Grant No. TTU.RS.25.102.003

- **JST CREST, Japan**  
  Grant No. JPMJCR21M1 (for work of L. T. Phong)

---

## 📜 License

This project is licensed under the MIT License.

---

## 📞 Contact & Resources

### Contact
📧 dung.cao@ttu.edu.vn  
🏛️ Tan Tao University, Long An, Vietnam

### Resources
- 📖 [Flower Framework](https://flower.ai/)
- 📖 [Grad-CAM](https://arxiv.org/abs/1610.02391)
- 📖 [SHAP](https://github.com/slundberg/shap)

---

## 🔖 Citation

```bibtex
@inproceedings{cao2025client,
  title={Client Selection of Federated Learning by Cost-Performance Analysis},
  author={Cao, Tien-Dung and Le, Hoang-Duc},
  booktitle={2025 20th International Conference on Intelligent Systems and Knowledge Engineering (ISKE)},
  pages={209--216},
  year={2025},
  organization={IEEE}
}

@inproceedings{vu2025domain,
  title={Domain Adaptation of Federated Learning by Data Generation and Server Feedback},
  author={Vu, Phuong-Anh and Phan, Kim-Tinh and Nguyen, Cao-Dien and Cao, Tien-Dung and Phong, Le Trieu and Nguyen, Ngoc-Thai},
  booktitle={Multi-disciplinary International Workshop on Artificial Intelligence},
  pages={272--283},
  year={2025},
  organization={Springer}
}
```

---

<div align="center">
  <p><strong>Transparency and Explainability of Federated Learning</strong></p>
  <p>Making Federated Learning More Interpretable, Cost-Aware, and Adaptable</p>
  <p><em>Research by Tan Tao University and Collaborators</em></p>
</div>
