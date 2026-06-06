# Awesome Regularization-by-Denoising (RED) for Inverse Problems 🚀

A curated list of awesome papers, codes, and resources focusing on the evolution of **Regularization by Denoising (RED)** frameworks—from classical energy-based methods to modern operator topologies (RED-PRO, Pseudo-Contractive) and generative diffusion priors in imaging inverse problems.

---

## 📌 Technical Roadmap & Evolution Tree

Before diving into the papers, here is the quick evolutionary trajectory of the RED paradigm:
1. **Classical RED (2017)**: Energy-based, strict idealistic assumptions (Jacobian symmetry, homogeneity).
2. **RED-PRO (2021)**: Fixed-point projection geometric framework, demicontractive operators, unification with PnP.
3. **Spectral & Pseudo-Contractive RED (2024+)**: Relaxes boundaries via holomorphic calculus, maximizing deep network expressiveness.
4. **Probabilistic & Generative RED (2025+)**: Bayesian Langevin sampling, unquantified uncertainty, and multi-scale Diffusion extensions.

---

## 📚 Milestone Literature & Chronology

### 📚 Publications (First Author)
| Year | Title | Venue | Link |
| :--- | :--- | :--- | :--- |
| 2026 | *Dual-Domain Regularization by Denoising: Taming Spectral Bias in Unsupervised Image Restoration* |Pattern Recognition(CCF-B)-UR| [📄 PDF] |
| 2026 | *Net2Net: A Dual-Network Prior Framework for Image Restoration via Regularization by Denoising* |Neural Networks(CCF-B)-UR| [📄 PDF](https://arxiv.org/pdf/2510.02733) |
| 2025 | *Image restoration driven by dual-scale prior* | Neural Networks(CCF-B)| [📄 PDF](https://www.sciencedirect.com/science/article/pii/S0893608025010184) |
| 2025 | *Guided image filtering-conventional to deep models: A review and evaluation study* | Computer Vision and Image Understanding(CCF-B)| [📄 PDF](https://www.sciencedirect.com/science/article/pii/S1077314225000013) |
| 2024 | *Weighted side-window based gradient guided image filtering* | Pattern Recognition(CCF-B)| [📄 PDF](https://www.sciencedirect.com/science/article/pii/S0031320323007033) |
| 2024 | *Simultaneous image denoising and completion through convolutional sparse representation and nonlocal self-similarity* | Computer Vision and Image Understanding(CCF-B)| [📄 PDF](https://www.sciencedirect.com/science/article/pii/S1077314224002972) |
| 2024 | *Mixed degradation image restoration via deep image prior empowered by deep denoising engine* | International Joint Conference on Neural Networks (IJCNN)(CCF-C)| [📄 PDF](https://ieeexplore.ieee.org/document/10650215) |
| 2023 | *Guided image filtering: A survey and evaluation study* | Proceedings of the 5th ACM International Conference on Multimedia in Asia Workshops| [📄 PDF](https://dl.acm.org/doi/abs/10.1145/3611380.3629544) |
| 2021 | *Efficient local stereo matching algorithm based on fast gradient domain guided image filtering* | Signal Processing: Image Communication(CCF-C)| [📄 PDF](https://www.sciencedirect.com/science/article/pii/S0923596521001181) |
| 2019 | *Sgm-based disparity estimation under radiometric variations* | Chinese Conference on Image and Graphics Technologies| [📄 PDF](https://link.springer.com/chapter/10.1007/978-981-13-9917-6_37) |

### 🌟 Phase 1: The Dawn of RED (Energy-Based Foundations)
*The foundational era that established explicit objective functions using denoising residuals.*

* **[SIAMS 2017] Regularization by Denoising (RED): The General Framework**
  * *Authors*: Yaniv Romano, Michael Elad, Peyman Milanfar
  * *Paper*: [Link to SIAMS] | *Code*: [MATLAB Official]
  * *Key Contribution*: Introduced the explicit prior $\frac{1}{2}\mathbf{x}^T[\mathbf{x}-f(\mathbf{x})]$ and simplified the gradient to $\mathbf{x}-f(\mathbf{x})$ under 4 strict patch assumptions.
* **[IEEE TIP 2019] Online Regularization-by-Denoising with Applications to Image Restoration**
  * *Key Contribution*: Extended RED to streaming data and stochastic gradient descent variants.

### 🌟 Phase 2: The Geometric Revolution (Fixed-Point & Projections)
*The era acknowledging that deep networks break classical assumptions, shifting the paradigm to operator theory.*

* **[SIAMS 2021] RED-PRO: Regularization by Denoising via Fixed-Point Projection**
  * *Authors*: Regev Cohen, Michael Elad, et al.
  * *Paper*: [Link to SIAMS] | *Code*: [GitHub]
  * *Key Contribution*: Replaced the concept of energy minimization with **geometric projection** onto the fixed-point set of a **demicontractive denoiser** using the Krasnosel'skii-Mann (KM) iteration. Formally unified PnP and RED.

### 🌟 Phase 3: Unleashing Network Freedom (Spectral & Weak Constraints)
*Modern optimization theories that allow the usage of extremely expressive, non-expansive deep neural architectures.*

* **[ICML 2024] Learning Pseudo-Contractive Denoisers for Inverse Problems**
  * *Authors*: Comprehensive team on spectrum constraints.
  * *Key Contribution*: Further relaxed the operator constraint from demicontractive to **pseudo-contractive (PC)** via holomorphic calculus, preventing over-smoothing and capturing extreme high-frequency details.

### 🌟 Phase 4: Probabilistic, Generative & Untrained Integration (Current Frontiers)
*The cutting-edge integration of RED with generative models, Bayesian statistics, and self-supervised structures.*

* **[IEEE TIP 2025] Regularization by Denoising: Bayesian Model and Langevin-Within-Split Gibbs Sampling**
  * *Authors*: Faye et al.
  * *Key Contribution*: Formulated a probabilistic counterpart of RED, leveraging Langevin MCMC within a split Gibbs sampler to quantify reconstruction uncertainty.
* **[Preprint/Ongoing 2026] Untrained Network Priors meeting RED-PRO / Net2Net-PRO**
  * *Context*: Merging Deep Image Prior (DIP) with structural spectrum/fixed-point projections for zero-shot generalization without external training data. (Placeholder for your future work! 😉)
* **[2024-2026 Trends] Diffusion Models as Multi-Scale RED Priors**
  * *Key Papers*: (Include papers linking Score-matching / DPS with RED fixed-point dynamics).

---

## 🛠️ Comprehensive Surveys (Must-Read)
* **[IEEE SPM 2023] Plug-and-Play Methods for Integrating Physical and Learned Models in Computational Imaging: Theory, algorithms, and applications**
  * *Authors*: Ulugbek S. Kamilov, Charles A. Bouman, Gregery T. Buzzard, Brendt Egon Wohlberg.
  * *Note*: The absolute bible for understanding the macro-landscape of both PnP and RED branches.

---

## 🤝 Contribution & Maintenance
If you find any missing landmark papers regarding the RED paradigm, feel free to open an issue or pull request!
