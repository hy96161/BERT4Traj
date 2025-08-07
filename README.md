# BERT4Traj: Transformer-Based Trajectory Reconstruction from Sparse Mobility Data

**BERT4Traj** is a deep learning model designed to reconstruct detailed human mobility trajectories from sparse Cell Phone Record (CDR) and GPS data. Inspired by BERT, this model leverages a transformer-based architecture to infer missing spatiotemporal points in trajectories using contextual information and individual-level background features.

---

## 🧠 Overview

Understanding human mobility patterns is critical for applications ranging from urban planning to infectious disease control. However, mobility data—while abundant—often suffers from data sparsity. **BERT4Traj** addresses this challenge by learning context-aware representations of mobility sequences, enabling accurate prediction of missing locations and times.

This repository includes:

- An implementation of the BERT4Traj model  
- A sample dataset including mobility data, points of interest (POIs), and user demographic information  

---

## 📌 Key Features

- **Transformer-based architecture**: Utilizes self-attention to capture complex spatiotemporal dependencies in mobility sequences.  
- **Masked trajectory modeling**: Adopts a BERT-style masked prediction strategy to reconstruct missing trajectory points.  
- **Spatiotemporal embeddings**: Incorporates location embeddings and temporal embeddings for fine-grained modeling.  
- **User background integration**: Enriches model inputs with age, gender, anchor locations, and time context embeddings.  
- **Flexible reconstruction**: Supports missing location interpolation and both full-day and partial-day trajectory inference.  

---


