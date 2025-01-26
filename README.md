# AIxOncoCare: Revolutionizing Cancer Care with AI

## Overview

**AIxOncoCare** is an AI-powered platform designed to revolutionize oncology by integrating **radiomics**, **genomics**, and **conversational AI**. The platform empowers clinicians and patients with personalized, data-driven insights for cancer care. This project leverages cutting-edge technologies to predict survival outcomes, optimize therapies, and enhance access to groundbreaking cancer research.

## Team
# AIxOncoCare Team

| ![Team Picture 1](https://i.imgur.com/x4oITT8.jpg) | ![Team Picture 2](https://i.imgur.com/Bm7tBCp.jpg) |



## Project Components

### 1. **Radiomics-Based Survival Prediction Models**

**Goal:**  
Predict survival outcomes for cancer patients, especially for neuro-oncologists working with brain metastases imaging.

**How it's Built:**  
- **Data Used:** We used medical imaging data, specifically for brain metastases, to extract radiomic features such as texture, shape, and intensity from 2D/3D images of tumors.
- **Model Development:**  
  - Developed machine learning models that analyze radiomic features to predict survival outcomes based on patient imaging data.
  - Trained models using labeled data to provide neuro-oncologists with actionable insights.
  
- **Technologies & Tools:**  
  - **Python Libraries:** `scikit-learn`, `SimpleITK` for image processing.
  - **Model Training:** Utilized machine learning algorithms to train survival prediction models from extracted radiomic features.

### 2. **Genomics and Drug-Response Integration**

**Goal:**  
Process complex genomic datasets and predict therapy effectiveness, enabling personalized treatment recommendations.

**How it's Built:**  
- **Data Used:** Utilized genomic data, such as DNA sequencing and mutation profiles, along with drug response data.
- **Data Processing:**  
  - Preprocessed genomic datasets and identified key mutations that affect drug efficacy.
  - Analyzed genomic data to predict how individual patients will respond to various cancer therapies.
  
- **Model Development:**  
  - Built a personalized treatment recommendation framework by integrating genomic data with historical drug response data.
  - Trained models to output personalized therapy suggestions based on genomic profiles.

- **Technologies & Tools:**  
  - **Libraries:** `Pandas`, `NumPy` for data manipulation.
  - **Machine Learning:** `TensorFlow`, `Keras` for creating predictive models.
  - **Techniques:** Genomic variant calling and statistical analysis for identifying key mutations.

### 3. **CancerChat AI – Interactive Research Assistant**

**Goal:**  
Create a conversational AI assistant to help clinicians and patients explore relevant cancer research and make informed treatment decisions.

**How it's Built:**  
- **Base Model:** Built on **Falcon 180B**, a large language model, with custom layers to tailor it to oncology-specific content such as drug recommendations and research findings.
- **Features:**  
  - Allows users to query cancer treatment options, research articles, and clinical trial information using natural language.
  - Provides actionable insights based on the latest cancer research and clinical data.
  
- **Technologies & Tools:**  
  - **NLP Libraries:** `Hugging Face Transformers` for natural language processing tasks.
  - **Web Framework:** `Flask` for deploying the chatbot as a web app.
  - **Cloud Databases:** Integrated with cancer research and clinical trial databases to provide real-time, up-to-date information.

## Technology Stack

- **Programming Languages:**  
  - Python, JavaScript (for frontend interaction)
  
- **Key Libraries & Frameworks:**  
  - Machine Learning: `scikit-learn`, `TensorFlow`, `Keras`
  - Image Processing: `SimpleITK`, `OpenCV`
  - Natural Language Processing: `Hugging Face Transformers`, `Flask`
  - Data Analysis: `Pandas`, `NumPy`

- **Cloud/Deployment:**  
  - Google Cloud for model training, storage, and hosting the AI assistant through Netlify.

## Conclusion

AIxOncoCare integrates AI-driven models for predicting cancer survival outcomes, personalized therapy recommendations based on genomic data, and an interactive research assistant using conversational AI. By combining these cutting-edge technologies, we aim to empower clinicians and patients with data-driven insights that can significantly improve cancer treatment decision-making.

---
