# Multi Scale Texture Loss Function for CT denoising with GANs


![Screenshot 2024-12-18 at 10 32 15](https://github.com/user-attachments/assets/d2cfb70f-e2e1-4db2-aa39-4cedce988b55)



Overall framework of MSTLF. (a) MSTLF mainly includes two essential components, i.e., the Multi-Scale Texture Extractor (MSTE) and the Aggregation Module (AM). We denote the selection of the aggregation rule with the logic operators demux and mux. (b) MSTE module extracting a textural representation from the input images using a texture descriptor extracted from the GLCMs at different spatial and angular scales. (c) Dynamic aggregation by Self-Attention mechanism (SA) that combines the extracted representation into a scalar loss function
