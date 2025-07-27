# Upscaling
Super resolution and upscaling pictures
<p align="justify"> I used ComfyUI with the Flux model to change clothing in an image, I start by setting up a node-based workflow that allows me to feed a reference image into Flux’s garment transfer system. I choose a source image with the person whose outfit I want to change, and pair it with either a target image or a detailed text prompt describing the new clothing style. In ComfyUI, I connect nodes like FluxModelLoader, ImagePreprocessor, and GarmentMapper, and link them to a TextPrompt or another visual reference. Once the pipeline is built, I generate the output and fine-tune it by adjusting texture realism, fit accuracy, and lighting to make sure the new clothes blend seamlessly with the original image. It’s a hands-on, creative way for me to design virtual outfit changes with precision and flair. </p>

# Samples Results
<p align="center">
  <img src="https://github.com/user-attachments/assets/2c9a3357-4f58-4a72-bc03-e81db01e30ea" width="350" height = "700" title="Original Image">
  <img src="https://github.com/user-attachments/assets/dfdcfde9-c6f7-41ed-931c-832f5e20a477" width="350" height = "700" title="Upscaled Image">
</p>

# Model's links:
FLUX GGUF fill: https://huggingface.co/city96/FLUX.1-dev-gguf


Clip Tensor: https://huggingface.co/comfyanonymous/flux_text_encoders/blob/main/clip_l.safetensors


VAE Model: https://huggingface.co/stabilityai/sd-vae-ft-mse/tree/main
