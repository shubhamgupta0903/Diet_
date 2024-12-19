# Diet Recommendation System | Llama2, PyTorch, Hugging Face, PEFT, LoRA, Quantization

## Overview
This project implements a **personalized Diet Recommendation System** using **Llama2**, a large language model, fine-tuned with **PyTorch**, **Hugging Face**, **PEFT**, **LoRA**, and **Quantization** techniques. The model provides tailored diet suggestions based on **demographic** and **behavioral** data, aiming to optimize users' diet plans for better health and well-being.

## Key Features
- **Personalized Recommendations**: Leverages demographic data and user habits to generate customized diet plans.
- **Low Latency**: Utilizes LoRA and 4-bit quantization (**QLoRA**) for efficient model fine-tuning, reducing inference latency for real-time performance.
- **Custom Dataset**: Trained on a curated dataset of **1000 rows**, ensuring broad and accurate representation for diverse dietary recommendations.
- **Real-Time Application**: Designed for quick and responsive diet suggestions, providing near-instantaneous results for users.

## Dataset
The dataset used to train the model is hosted on Hugging Face and can be accessed at:

- **[Llama2 Diet Planner Dataset](https://huggingface.co/datasets/shubhamtr/llama2_diet_planner)**

