# High-Resolution Motion Synthesis Using LDM and Image-Based Rendering  

This repository showcases a high-resolution motion synthesis pipeline combining Latent Diffusion Models (LDM) and image-based rendering to predict realistic future frames from static images and motion trajectories.  

## Overview  
- **Training Data**: Utilized every 5th frame from input sequences to compute optical flow using a coarse-to-fine flow method.  
- **LDM Training**: Leveraged U-Net for downsampling (noise addition) and upsampling (noise reduction) to generate motion trajectories.  
- **Frame Prediction**: Integrated motion trajectories with input images to generate future frames via an image-based rendering pipeline with ResNet-34 for feature extraction.  
- **Optimization**: Enhanced resolution, speed, and memory efficiency for real-time applications.  

## Key Features  
- Motion extraction using optical flow and Latent Diffusion Models.  
- Future frame generation through image-based rendering.  
- ResNet-34 for feature extraction and frame synthesis.  
- Optimized for high-resolution, real-time performance.  

## Technologies Used  
- **Programming Language**: Python  
- **Deep Learning Frameworks**: PyTorch  
- **Architectures**: Latent Diffusion Models (LDM), U-Net, ResNet-34  
- **Techniques**: Optical Flow, Image-Based Rendering  

## Results  
This approach generates realistic future frames with accurate motion synthesis, achieving high-resolution outputs suitable for real-time applications.  
