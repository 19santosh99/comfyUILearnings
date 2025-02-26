# ComfyUI Workflows

This repository contains a collection of pre-configured workflows for ComfyUI, a powerful node-based interface for Stable Diffusion. These workflows are designed to help you quickly get started with various image generation and manipulation tasks.

## Available Workflows

### 1. Text to Image (`TxtToImageWorkflow.json`)
A basic workflow for generating images from text descriptions using Stable Diffusion.

### 2. Image to Image (`ImageToImageWorkflow.json`)
Transform existing images using Stable Diffusion. This workflow allows you to:
- Load an existing image as input
- Apply text prompts to guide the transformation
- Uses the flux1-schnell-fp8 model for generation
- Configurable parameters like steps (20) and CFG scale (0.9)

### 3. Image or Text to Image (`ImageOrTextToImage.json`)
A flexible workflow that can handle both text-to-image and image-to-image generation in a single setup.

### 4. Upscale Text to Image (`upScaleTextToImage.json`)
Generate high-resolution images from text descriptions with built-in upscaling capabilities.

## Usage

1. Install [ComfyUI](https://github.com/comfyanonymous/ComfyUI) if you haven't already
2. Clone this repository or download the workflow JSON files
3. In ComfyUI:
   - Click the "Load" button
   - Navigate to and select the desired workflow JSON file
   - The workflow will be loaded with all nodes and connections pre-configured

## Requirements

- ComfyUI installation
- Required models:
  - flux1-schnell-fp8.safetensors (for Image to Image workflow)
  - Other workflows may require additional models as specified in their configurations

## Tips

- Each workflow is optimized for specific use cases but can be modified to suit your needs
- Adjust parameters like seed, steps, and CFG scale to fine-tune results
- Make sure to have the required models installed in your ComfyUI models directory

## Contributing

Feel free to submit issues, fork the repository, and create pull requests for any improvements.
