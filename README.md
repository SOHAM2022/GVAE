# **Graph Variational Autoencoder (GVAE)**

## **Overview**
This project implements a **Graph Variational Autoencoder (GVAE)** for **molecular graph generation**, utilizing deep learning techniques to encode and decode graph-structured data. The model is particularly useful for **drug discovery, materials science, and chemistry**, where generating new molecular structures with desired properties is a crucial task.

## **Problem Statement**
Traditional autoencoders struggle with graph-structured data due to its complex nature. The GVAE addresses this challenge by applying **Graph Neural Networks (GNNs) and Variational Autoencoders (VAEs)** to learn meaningful representations of molecular graphs, enabling the generation of novel molecules with optimized properties.

## **Key Features**
- **Graph-based Learning:** Adapts VAEs to handle graph-structured molecular data.
- **Molecular Generation & Optimization:** Learns latent representations to generate chemically valid molecular structures.
- **Efficient Representation Learning:** Uses a GNN-based encoder-decoder architecture for feature extraction and graph reconstruction.
- **Bayesian Inference:** Ensures smooth and interpretable latent space representation through VAEs.
- **Scalable & Flexible:** Utilizes **PyTorch Geometric (PyG)** for efficient graph processing.

## **Technologies Used**
- **PyTorch Geometric (PyG)** – Deep learning framework for graph data.
- **Graph Neural Networks (GNNs)** – Core model for encoding and processing graph structures.
- **Variational Autoencoder (VAE)** – Generative model for mapping molecules to a latent space.
- **Molecular Graph Representations** – Atoms as nodes, bonds as edges.
- **Latent Space Optimization** – Enables interpolation and property-based optimization of molecules.

## **Applications**
- **Drug Discovery:** Generate and optimize new drug-like molecules.
- **Materials Science:** Predict molecular structures with specific properties.
- **Chemical Property Prediction:** Assist in molecular interaction and reactivity studies.
- **Data Augmentation:** Generate synthetic molecular data for training AI models.

## **Research Paper Citation**
For more details on Graph Variational Autoencoders for molecular generation, refer to the following research paper:

> **Simon, C. M., et al. "Graph-based variational autoencoder for molecular structure generation."** *Journal of Cheminformatics*, **2019.** [**Read Here**](https://jcheminf.biomedcentral.com/track/pdf/10.1186/s13321-019-0396-x.pdf)
