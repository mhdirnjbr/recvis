#  Referring Image Segmentation via Text-to-Image Diffusion Models

Diffusion models have become the new trend of generative models and have demonstrated a powerful ability of conditional synthesis, like text-to-image generation. Their ability to generate highly complex images with compositional understanding, hints towards the rich representations learned by the model. Capturing both high level (semantic) and low level (syntactic) information. If the representations can be extracted from a pre-trained Diffusion, they can further be applied to several discriminative computer vision tasks like segmentation, classification etc. But given the sequential time-dependent modeling and image-to-image autoencoding. It is not trivial to extract the representations that could be helpful for the downstream vision tasks. In this project we explore a method to extract representations from a pretrained text-to-image Diffusion model, and finetune them for downstream vision tasks.

## Reference
Zhao, Wenliang, et al. "Unleashing text-to-image diffusion models for visual perception." Proceedings of the IEEE/CVF International Conference on Computer Vision. 2023.
