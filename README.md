**####Prompt to Image Generator**

This project uses Stable Diffusion and Gradio to generate AI images from text prompts. It enables users to enter any imaginative prompt and receive images generated using cutting-edge deep learning models.

**Overview**
1.Generates images from text prompts using Stable Diffusion (version 2) via the Diffusers library.
2.Provides a user-friendly web interface using Gradio for easy prompt input and image display.​

**Features**
1.Enter a text prompt and select the number of desired images (1-5).
2.Example prompts and instant image gallery.
3.Custom-styled interface for improved aesthetics and usability.
4.Saves generated images locally for download or reuse.​

**Requirements**
1.Python 3.x
2.diffusers
3.torch
4.gradio

**Install required Python packages with:
bash**
1.pip install diffusers torch gradio
2.A supported NVIDIA GPU is required for optimal performance.​

**Usage**
1.Model setup: The script loads Stable Diffusion 2 with an Euler Discrete Scheduler.
2.Run interface: Launch the Gradio demo by executing the notebook. Enter your prompt and number of images, then press "Generate."
3.Generated images: Images are saved locally (e.g., generatedimage1.png, generatedimage2.png, etc.).
4.Colab support: You can run this notebook on Google Colab, including GPU acceleration.​

**Example Prompts**
1."realistic photo of 3d cartoon style of a cat in a space suit with milky way background"
2."futuristic cyberpunk cityscape at night with neon signs"
3."serene mountain landscape with crystal clear lake"​

**Customization**
1.Modify CSS and JavaScript for your own UI theme.
2.Adjust model parameters for different image styles.

**NOTE: While Accessing this code try to run in this Google Colab because it is connected to T4-GPU(not supported for jupyter notebook).**
