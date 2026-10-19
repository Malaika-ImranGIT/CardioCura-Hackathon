# CardioCura

## AI-Powered Cardiovascular Health Assessment & Awareness Platform

CardioCura is an AI-powered digital health platform designed to make cardiovascular health assessment and awareness more accessible, understandable, and user-friendly. The platform brings together intelligent health assessment, an interactive conversational interface, and digital cardiovascular analysis within a unified application.

## Overview

Cardiovascular diseases are a major health concern, yet early awareness and access to appropriate health information can remain challenging for many people.

CardioCura aims to provide users with an accessible first step toward understanding their cardiovascular health. The platform allows users to interact with the system, provide relevant health information, and receive AI-assisted cardiovascular risk insights and health guidance.

CardioCura is designed as a research and prototype project and is intended to support awareness and preliminary assessment. It is **not a replacement for professional medical diagnosis, clinical evaluation, or treatment**.

## Key Features

* AI-assisted cardiovascular health assessment
* Interactive conversational health interface
* Symptom and health-information based assessment
* Cardiovascular risk awareness and preliminary insights
* Support for an accessible and user-friendly digital experience
* Web-based interface for convenient interaction
* Multilingual-oriented design for improved accessibility
* Integration of intelligent analysis within a unified platform

## Problem Statement

Cardiovascular health assessment can be difficult to access or understand, particularly when people face barriers such as limited awareness, delayed screening, language differences, or difficulty interpreting health information.

Many individuals may not know when their symptoms or risk factors require further medical attention.

CardioCura addresses this gap by providing an accessible digital platform that can assist users in understanding cardiovascular risk indicators and encourage appropriate follow-up with qualified healthcare professionals.

## Proposed Solution

CardioCura uses artificial intelligence and machine-learning technologies to process relevant cardiovascular health information and provide preliminary risk insights through an easy-to-use interface.

The platform is designed around a user-centered workflow:

1. The user interacts with the CardioCura platform.
2. Relevant health information is provided through the available interface.
3. The system processes the information using its intelligent assessment components.
4. CardioCura presents the resulting preliminary insights in an understandable format.
5. Users are encouraged to seek professional medical advice when appropriate.

The implementation details of the underlying models and training resources are intentionally not included in this public repository.

## Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript
* Responsive web interface

### Backend

* Python
* Flask

### Artificial Intelligence

* Machine Learning
* Natural Language Processing
* AI-assisted health assessment

### Development Tools

* Visual Studio Code
* Git
* GitHub

## Target Users

CardioCura is designed primarily for:

* Individuals seeking greater awareness of cardiovascular health
* People interested in preliminary cardiovascular risk assessment
* Users who may face accessibility or language barriers
* Students and researchers exploring AI applications in healthcare

The platform is designed as an assistive and awareness-oriented system and does not replace healthcare professionals.

## Social Impact

CardioCura aims to contribute to improved cardiovascular health awareness by making digital health information and preliminary assessment more accessible.

The project is aligned with:

**UN Sustainable Development Goal 3 — Good Health and Well-being**

The project supports the broader goal of improving health awareness and encouraging timely engagement with appropriate healthcare services.

# AI Models and APIs Used
**1. MobileNetV2 — Deep Learning**
- Framework: TensorFlow/Keras.
- Role: ECG image classification.
- Implementation: TensorFlow's MobileNetV2 architecture and image preprocessing utilities.

**2. Random Forest Classifier — Machine Learning**
- Library: scikit-learn.
- Role: Classification based on structured input features for the implemented cardiovascular assessment task.

**3. Additional ML components**
- XGBoost: Imported for gradient-boosting classification; include as an active model only if it is used in the submitted prediction pipeline.
- SMOTE: Available through imbalanced-learn for addressing class imbalance during model training, if applied.

**External AI prediction APIs:** No external AI APIs are used for the MobileNetV2 or Random Forest prediction components.

**Translation and transliteration:** The application imports GoogleTranslator through deep_translator and the Aksharamukha transliteration library for language-related functionality. GoogleTranslator may call an external translation service; it should not be described as a locally hosted translation model.

# CardioCura — Team Member Contribution
**Team Member**
Malaika Imran — Sole Developer
**Contributions**
 Project concept and development
 Frontend and backend implementation
 AI/ML/DL integration
 Symptom-based and clinical assessment implementation
 ECG analysis integration
 Four-language interface
 Testing, debugging, and project documentation
 Presentation and project demonstration
Team Structure: Individual Project

## Project Structure

A simplified version of the application structure is provided below:

```text
CardioCura/
│
├── app.py
├── requirements.txt
├── README.md
│
├── templates/
│   └── Web interface templates
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
└── Other application components
```

Certain datasets, trained models, training resources, credentials, and other private development materials are intentionally excluded from this public repository.

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/Malaika-ImranGIT/CardioCura-Hackathon.git
cd CardioCura-Hackathon
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure environment variables

If environment variables are required, create a local `.env` file using the required variable names.

**Do not upload `.env` files, API keys, passwords, or other credentials to GitHub.**

### 6. Run the application

```bash
python app.py
```

Then open the local address displayed by the application in your browser.

## Project Status

CardioCura is an evolving research and prototype project. The version submitted for the hackathon represents the current implementation available for demonstration.

## Privacy & Security

This public repository intentionally excludes private datasets, trained model files, credentials, and other sensitive development resources.

No confidential credentials or private user information should be committed to this repository.

## Medical Disclaimer

CardioCura is a technology research and prototype project intended for educational, research, and health-awareness purposes.

The information or assessment provided by the application should not be considered a medical diagnosis, medical advice, or a substitute for consultation with a qualified healthcare professional.

Users experiencing concerning or emergency symptoms should seek appropriate professional medical care.

## Acknowledgment

CardioCura was developed as a technology project exploring the application of artificial intelligence to cardiovascular health awareness and preliminary assessment.

---

**CardioCura — Making Cardiovascular Health Awareness More Accessible Through AI**
