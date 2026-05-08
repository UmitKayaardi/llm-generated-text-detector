# LLM-Generated Text Detector & Analytics 🤖✍️

## Project Overview
In the era of rapidly advancing Large Language Models (LLMs), distinguishing between human-written and machine-generated content has become a fundamental challenge for digital trust and information integrity. This project develops a scalable analytics pipeline to identify the "digital fingerprints" of various AI models including **GPT-4, Llama-Chat, and Cohere**. 

Using the **RAID (Real-world AI Detection)** benchmark dataset, this repository demonstrates how big data tools can be leveraged for robust text classification and forensic linguistic analysis.

## Key Technical Features
- **Scalable Big Data Pipeline:** Implemented using **PySpark** to ensure the architecture can handle high-volume text datasets that exceed traditional memory limits.
- **Cross-Model Benchmarking:** Comparative analysis of text generation styles across multiple state-of-the-art LLMs vs. human authors.
- **Advanced Feature Engineering:** Development of statistical features such as lexical density, word count distributions, and text complexity metrics.
- **Statistical Visualization:** Deep-dive Exploratory Data Analysis (EDA) using Seaborn and Matplotlib to uncover structural differences in AI writing.

## Tech Stack
- **Core Engine:** Apache Spark (PySpark)
- **Programming:** Python
- **Natural Language Processing:** NLTK
- **Data Visuals:** Seaborn, Matplotlib
- **Data Architecture:** Parquet-based processing for optimized I/O

## Dataset Insights
The project utilizes the **RAID dataset**, a comprehensive benchmark for AI detection.
- **Diversity:** Covers multiple generation models and diverse human-written sources.
- **Scalability:** Processed in a distributed environment to maintain performance during heavy computational tasks like tokenization and feature extraction.

## Methodology
1. **Data Orchestration:** Efficiently loading and partitioning large-scale Parquet files.
2. **Preprocessing & Filtering:** Selective filtering of specific model architectures (Llama, GPT, etc.) to analyze unique model signatures.
3. **Feature Construction:** Engineering numerical representations of text for classification readiness.
4. **Analysis & Insights:** Validating detection patterns through robust statistical visualizations.

---
*Developed as a professional case study in Scalable Machine Learning and AI Content Integrity.*
