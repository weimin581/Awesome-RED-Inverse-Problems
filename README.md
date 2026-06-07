# Awesome Regularization-by-Denoising (RED) for Inverse Problems 🚀

A curated list of awesome papers, codes, and resources focusing on the evolution of **Regularization by Denoising (RED)** frameworks—from classical energy-based methods to modern operator topologies (RED-PRO, Pseudo-Contractive) and generative diffusion priors in imaging inverse problems.

---

## 📚 Milestone Literature & Chronology

### 📚 Publications
| Year | Title | Venue | Link |
| :--- | :--- | :--- | :--- |
| 2017 | *The Little Engine That Could: Regularization by Denoising (RED)* |SIAM journal on imaging sciences| [📄 PDF](https://epubs.siam.org/doi/abs/10.1137/16M1102884) |
| 2019 | *Regularization by Denoising: Clarifications and New Interpretations* |IEEE Transactions on Computational Imaging| [📄 PDF](https://ieeexplore.ieee.org/document/8528509) |
| 2019 | *Block Coordinate Regularization by Denoising* |Advances in neural information processing systems| [📄 PDF](https://proceedings.neurips.cc/paper/2019/file/9872ed9fc22fc182d371c3e9ed316094-Paper.pdf) |
| 2021 | *Regularization by Denoising via Fixed-Point Projection (RED-PRO)* |SIAM journal on imaging sciences| [📄 PDF](https://epubs.siam.org/doi/abs/10.1137/20M1337168) |
| 2021 | *Async-RED: A provably convergent asynchronous block parallel stochastic method using deep denoising priors* |International Conference on Learning Representations (ICLR)| [📄 PDF](https://arxiv.org/pdf/2010.01446#page=1.00&gsr=0) |




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
