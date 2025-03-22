# Translation Application

Welcome to the Translation Application project! This repository contains the source code, datasets, and documentation for a web-based application designed to translate Bible texts into low-resource Cameroonian languages. Our goal is to leverage advanced Natural Language Processing (NLP) techniques and community-driven research to support linguistic diversity and language preservation.

---

## Overview

The Bible Translation Application is a scalable platform that integrates **Hugging Face Transformers** and a microservice-based architecture to facilitate accurate and accessible Bible translations. The project focuses on supporting low-resource languages such as **Bafia**, **Fulfulde (Adamaoua dialect)**, **Ghomala**, **Fulfulde (Diamaré-Central dialect)**, **Bulu**, and **Tupuri**. 

Key features include:

- **Multilingual Translation:** Translates texts from English or French into two Cameroonian languages.
- **Custom Models:** Machine learning models trained specifically for each language.
- **Community Input:** Incorporates input from native speakers to ensure cultural relevance and accuracy.
- **Web-Based Interface:** A user-friendly platform for text input, translation, and output display.
- **Cloud Hosting:** Hosting models and APIs using Hugging Face and scalable cloud services.

---

## Motivation

Many low-resource languages lack digital tools to preserve and promote their use. This project aims to:

- Bridge the gap in NLP support for low-resource African languages.
- Empower communities with culturally relevant Bible translations.
- Promote linguistic diversity and language preservation.

---

## Technology Stack

- **Frontend:** React.js, HTML5, CSS3
- **Backend:** Python, Flask
- **Machine Learning:** Hugging Face Transformers, TensorFlow/PyTorch
- **Database:** MongoDB for storing user inputs and translations
- **Cloud Hosting:** Hugging Face Model Hub, Google Colab for model training
- **APIs:** RESTful APIs for integration between frontend and backend

---

## Key Components

### 1. Language Processing
- Custom tokenizers and translation models for each supported language.
- Community-validated dictionaries with over 1,200 words per language.

### 2. Backend System
- Python-based backend for preprocessing texts and interacting with translation models.
- APIs to connect frontend and machine learning models.

### 3. Frontend Interface
- A responsive and intuitive web application for users to input text, select languages, and view translations.

### 4. Cloud Infrastructure
- Hosting datasets and models on Hugging Face.
- Scalable architecture for API calls and translations.
