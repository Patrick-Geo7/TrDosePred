# Dose Prediction Model for Head-and-Neck Cancer (TrDosePred)

## Overview
This project aims to develop a deep learning-based **dose prediction model** for head-and-neck cancer (HNC) patients. It is inspired by the methods described in the paper **"TrDosePred: A Deep Learning Dose Prediction Algorithm Based on Transformers for Head and Neck Cancer Radiotherapy"**. The model is designed to predict radiation therapy doses using the **Open-KBP** dataset and a transformer-based architecture, similar to the approach outlined in the paper.

### Objectives
- **Primary Goal**: To predict radiation doses for head-and-neck cancer (HNC) patients.
- **Model Enhancement**: Improve model accuracy by incorporating attention mechanisms to focus on critical regions, such as the Planning Target Volume (PTV) and Organs at Risk (OARs).
- **Generalization**: Validate the model's generalizability beyond rectum cancer (original dataset), and assess its performance using the **Open-KBP** dataset.

## Table of Contents
1. [Installation](#installation)
2. [Data](#data)
3. [Model Architecture](#model-architecture)
4. [Training](#training)
5. [Evaluation](#evaluation)
6. [Results](#results)
7. [Future Work](#future-work)
8. [License](#license)

## Installation

To run this project, you need to set up the following environment:

### 1. Clone the Repository
```bash
git clone https://github.com/Patrick-Geo7/TrDosePred
cd TrDosePred
