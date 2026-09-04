# 🎨 Anima with LoRA in Google Colab

This repository contains an easy-to-use Google Colab notebook for running **Anima-Turbo v1.1** powered by ComfyUI. It allows you to generate high-quality AI images using the Qwen text encoder and VAE, with built-in support for uploading and applying custom LoRAs.

**🎥 Watch the Tutorial:** [How to Use Anima with LoRA](https://www.youtube.com/watch?v=c3UbaFYMKHM)

**🚀 Run in Colab:** [Open Google Colab Notebook](https://colab.research.google.com/drive/1H_IvWK0BcXXSRnYcNDqWh0R1ctnh7O6i?usp=sharing)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/salman02-12/Anima-with-LoRA-in-Google-Colab/blob/main/Anima-Turbo-v1.1%20%40CoinNoin.ipynb)

---

## ✨ Features Supported in this Notebook

The notebook is divided into 4 simple steps to get you generating images quickly:

1. **⚙️ Setup Environment & Download Models**: Installs ComfyUI and automatically downloads the necessary `.safetensors` files, including the Anima-Turbo v1.1 diffusion model, Qwen text encoder, and Qwen image VAE.
2. **🚀 Start Generation Engine**: Launches a ComfyUI server in the background (Port 8188) to handle the image generation.
3. **📤 Upload LoRA Files (Optional)**: A dedicated cell to easily upload custom `.safetensors` LoRA files directly into the ComfyUI models directory.
4. **🎨 Generate Image**: Generate images using a customizable workflow. Features include:
   * **Prompts**: Enter positive and negative text prompts.
   * **Dimensions & Quality**: Sliders for width, height, and steps (8 to 12 recommended).
   * **Samplers**: Choose between `er_sde`, `euler_a`, `dpmpp_2m_sde_gpu`, or `euler`.
   * **LoRA Settings**: Type your uploaded LoRA filename and adjust its strength.
   * **Auto-download**: Option to automatically download the finished image locally.

## 🛠️ How to Use

1. Click the "Open in Colab" badge above.
2. Go to **Runtime > Change runtime type** and ensure a **T4 GPU** is selected.
3. Run **Cell 1** to download all required models and dependencies.
4. Run **Cell 2** to start the ComfyUI engine. Wait for the "✅ Engine is online and ready!" message.
5. (Optional) Run **Cell 3** to upload any LoRA files you want to use.
6. Go to **Cell 4**, type your image prompt, configure your dimensions and LoRA settings, and hit Play. The image will be generated and displayed right in the notebook!

## 🤝 Credits
* **Notebook Creator:** [CoinNoin](https://www.youtube.com/@CoinNoin)
* **Base Model:** [Circlestone Labs / Anima](https://huggingface.co/circlestone-labs/Anima)
