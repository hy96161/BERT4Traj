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
## 📚 Citation
This work has been accepted and published at GIScience 2025:Hao Yang, Angela Yao, Christopher C. Whalen, and Gengchen Mai. BERT4Traj: Transformer-Based Trajectory Reconstruction for Sparse Mobility Data. In 13th International Conference on Geographic Information Science (GIScience 2025). Leibniz International Proceedings in Informatics (LIPIcs), Volume 346, pp. 8:1-8:9, Schloss Dagstuhl – Leibniz-Zentrum für Informatik (2025) https://doi.org/10.4230/LIPIcs.GIScience.2025.8

