# 🎨 Generative AI — Hands-on Notebooks

Eleven practical notebooks covering the core of generative AI: autoencoders, VAEs, GANs (and how they fail), StyleGAN latent space, style transfer, bias in text-to-image models, and fine-tuning GPT-2.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white)

## Notebooks

| # | Notebook | Topic | Key tools |
|---|---|---|---|
| 1 | `Gen_AI_Assignment_1.ipynb` | **Discriminative vs generative models** — a classifier vs an autoencoder that generates new digits, on MNIST 0/1 | TensorFlow / Keras |
| 2 | `Gen_AI_Assignement_2.ipynb` | **Text-generation parameters** — how temperature, top-k, top-p and others change GPT-2 output | Hugging Face Transformers |
| 3 | `GenAI_Assignment_3.ipynb` | **Bias in generative AI** — occupation prompts in Stable Diffusion v1.5, with an observation table on gender, skin tone and age patterns | Diffusers |
| 4 | `DCGAN_Gen_AI_4.ipynb` | **DCGAN from scratch** on Fashion-MNIST, following the original paper's settings | PyTorch |
| 5 | `GEN_AI_ASSIGNMENT_5.ipynb` | **StyleGAN2 latent space** — face interpolation GIF and single-dimension edits (FFHQ) | StyleGAN2-ADA |
| 6 | `GEN_AI_ASSIGNMENT_6.ipynb` | **Style transfer** — CycleGAN (photo→Monet) vs VGG19 neural style transfer on the same photo | PyTorch, TorchVision |
| 7 | `GEN_AI_Assignment_7.ipynb` | **Mode collapse** — deliberately breaking a DCGAN, measuring diversity, then fixing it with separate learning rates | PyTorch |
| 8 | `GEN_AI_ASSIGNMENT_8.ipynb` | **GAN in TensorFlow** — generator/discriminator on Fashion-MNIST with a fixed noise vector to track progress | TensorFlow |
| 9 | `Assignment9_GenAI.ipynb` | **VAE for compression & denoising** — compression ratio, reconstruction MSE, latent sizes 2 / 16 / 32 | PyTorch |
| 10 | `GEN_AI_ASSIGNMENT_10.ipynb` | **VAE in Keras** — compression, reconstruction, denoising and latent-dimension comparison | TensorFlow / Keras |
| 11 | `GEN_AI_Assignment_11_GPT2_Fine_Tuning.ipynb` | **Fine-tuning GPT-2** on 250 cleaned lines of Shakespeare and comparing output with the base model | Transformers, Datasets |

## Run them

Most notebooks are designed for **Google Colab with a GPU runtime** (Runtime → Change runtime type → T4 GPU). Open a notebook in Colab and choose *Runtime → Run all*. Required packages are installed in the first cells.

---
Coursework · Generative AI, BCA (AI/ML) Semester V, Alliance University

**Dakshraj Singh Chandawat** · [GitHub](https://github.com/DakshrajKurki) · [LinkedIn](https://www.linkedin.com/in/dakshraj-singh-chandawat-0a6349314)
