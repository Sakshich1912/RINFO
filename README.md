# RINFO
Embedding-Driven Physics-Informed Neural Network for Predicting Optical Constants Across Materials

We introduce a deep learning framework for predicting the optical constants of materials, specifically the refractive index n(λ)  and the extinction coefficient k(λ), as functions of wavelength. Our model uses learnable embedding layers to encode material-specific information into a low-dimensional latent space. This embedding-driven architecture enables the network to generalize across diverse materials using only discrete material identifiers and normalized wavelengths as input. We also develop a physics-informed extension that incorporates a differentiable reflectance loss based on the Fresnel equation at normal incidence, allowing optional enforcement of physical constraints during training. Through systematic ablation studies, we find that this reflectance term has minimal impact on predictive accuracy, suggesting that the learned embeddings alone sufficiently capture essential dispersion characteristics. The proposed model offers scalability, strong generalization, and potential integration into optical simulations, high-throughput materials screening, and inverse design workflows.


Keywords: Optical constants; Embedding, Physics-informed neural networks; Reflectance regularization; Refractiveindex.info dataset
