# diffusion_model_thesis

# Score-Based Generative Models with SDEs

This repository contains the code and research material from my Master's research internship at Université Paris Dauphine – PSL (May–July 2025), under the supervision of Yating Liu.

The project explores the theoretical and practical aspects of score-based generative models built on stochastic differential equations (SDEs), with a particular focus on time-reversal dynamics, score estimation using neural networks, and convergence guarantees such as Wasserstein bounds.

---

##  Contents

- [thesis.pdf](./Claustre_Score_Based_Diffusion_Models_2025.pdf) — Final research report (Claustre_Score_Based_Diffusion_Models_2025.pdf)
- [01-diffusion-model-swiss-roll.ipynb](./01-diffusion-model-swiss-roll.ipynb) — A complete diffusion-based generative pipeline using a contractive variance-preserving (CVP) SDE on a 2D Swiss Roll synthetic dataset.
- [02-diffusion-model-mnist.ipynb](./02-diffusion-model-mnist.ipynb) — Extension to a real-world dataset (MNIST)generation.

 ## Run on Google Colab

- **Swiss Roll Notebook**  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Arsenecl/diffusion_model_thesis/blob/main/01-diffusion-model-swiss-roll.ipynb)

- **MNIST Notebook**  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Arsenecl/diffusion_model_thesis/blob/main/02-diffusion-model-mnist.ipynb)
