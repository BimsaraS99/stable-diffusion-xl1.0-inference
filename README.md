# Text-to-Image Generation with Stable Diffusion XL (SDXL)

This project demonstrates how to generate high-quality, photorealistic images from text prompts using the **Stable Diffusion XL (SDXL)** model via Hugging Face's [`diffusers`](https://github.com/huggingface/diffusers) library. The code runs inference using the SDXL base model with optional refinement via the SDXL Refiner, and visualizes the results using `matplotlib`.

---

## 🚀 Features

- Uses `StableDiffusionXLPipeline` from 🤗 `diffusers`
- Optional second-stage refinement with `StableDiffusionXLImg2ImgPipeline`
- Customizable prompts and negative prompts
- Fully GPU-accelerated with mixed precision (fp16)
- CPU offloading support for memory-constrained environments
- Minimal dependencies — no wandb, no training, just inference
- Simple image display with `matplotlib`

---

## 🖼 Example Output

| Prompt |
|--------|
| *"Modern kitchen with dark gray shaker cabinets, white quartz countertop island, stainless steel fridge and oven, subway tile backsplash, wood flooring, pendant lights, and a window with natural light.""* |



---
