# 💖 CardioScope AI - Heart Risk Predictor

🌌 **Welcome to CardioScope AI**, an intelligent, galaxy-themed web tool that predicts the **risk of heart attack**. Tool is designed using IBM Watson AutoAI data science, health analytics and deployed as an interactive web application. This project uses health-related data to analyze and predict the risk of a heart attack using an AutoML pipeline.

---

## 🚀 Live Project Links

| 🌐 Resource | 🔗 Link |
|------------|--------|
| 🧠 Try the Predictor | [CardioScope Web App](https://vaibhavidhankhar.github.io/IBM_CardioScope-AutoAI/#walkthrough) |
| 📊 Google Colab Notebook | [Colab Notebook](Heart_attack_prediction.ipynb) |
| 📽️ PPT Presentation | [View Presentation](CardioScope_Project_Presentation.pptx) |
| 🌐 PPT Images  | [View images](Presentation_Images)  |
| 📸 Project Walkthrough | [Walkthrough Screens](walkthrough) |
| 🏠 Homepage | [GitHub Pages Site](https://github.com/Vaibhavidhankhar/IBM_CardioScope-AutoAI.git) |

---

## 🧠 Project Overview

**CardioScope AI** is an ML-powered web application that predicts a person’s heart attack risk using critical health indicators. It combines:

- ✅ Dataset-driven model built via **IBM Watson AutoAI**
- ✅ Dataset from Kaggle: Heart Attack Prediction
- ✅ Intuitive web interface with **dark galaxy theme + ambient piano audio**
- ✅ Google Colab notebook for **full model analysis + visualization** with full ML pipeline
- ✅ Data preprocessing, feature selection, and model optimization
- ✅ PPT-style **interactive presentation and project walkthrough**
- ✅ Auto-calculated BMI, stress levels, and user-friendly interface
- ✅ Deployment using GitHub Pages
---

## 📊 Dataset & Model

📁 **Dataset Used**: [Heart Attack Prediction Dataset (Kaggle)](https://www.kaggle.com/datasets/iamsouravbanerjee/heart-attack-prediction-dataset)

🔍 **AutoAI Features:**
- Auto preprocessing + feature selection
- Best model pipeline recommendation
- Evaluation metrics like AUC, ROC, accuracy
- Deployed using Watson Machine Learning

---

## 🎯 Features at a Glance

✅ Built with IBM Watson Studio AutoAI  
✅ Auto-generated API used in web interface  
✅ Galaxy-themed front end using HTML/CSS/JS  
✅ Audio background with 🎹 ambient music  
✅ Input fields for age, cholesterol, diabetes, lifestyle habits  
✅ BMI calculation + sleep + stress levels  
✅ Probability-based risk result: *Low Risk* or *High Risk*

---

## 🧪 Technologies Used

- **IBM Watson Studio (AutoAI)**
- **Python / Google Colab**
- **HTML / CSS / JS**
- **GitHub Pages**
- **Orbitron / Open Sans fonts**
- **Galaxy-style dark theme + animation**
  
---

## 🧪 Tech Stack

| Area | Tools Used |
|------|------------|
| 👨‍💻 Machine Learning | IBM AutoAI, Watson Studio, Python |
| 🗂️ Dataset | Kaggle CSV |
| 🌐 Frontend | HTML, CSS, JavaScript |
| 🌐 Backend | Python |
| 🎨 UI Theme | Galaxy-style with Orbitron, Open Sans fonts |
| 📦 Deployment | GitHub Pages |
| 📄 Docs | Colab Notebook, PPT, Walkthrough |

---

## 🗂️ Repository Structure
📦 IBM_CardioScope-AutoAI/
│
├── index.html # Landing page with buttons
├── CardioScopeWebApp/
│ ├── cardioscope.html # AI web app interface
│ ├── piano.mp3 # Background audio
│ ├── assets/ # Images, screenshots, banner
├── CardioScope_Model_Code.ipynb # Colab notebook with analysis
├── README.md # Project documentation

---

## 🧭 Project Walkthrough

📽️ The GitHub page includes an **embedded presentation** that walks through:
- How AutoAI was used
- Dataset insights and preprocessing
- Model selection and accuracy
- Deployment flow
- Code + UI + API integration

You’ll also find multiple **screenshots** of model evaluation and app output for clear understanding.

---

## Related Links

* [Simplify your AI lifecycle with AutoAI](https://developer.ibm.com/series/explore-autoai/)

---

# Generate Python notebook for pipeline models using AutoAI

## Summary

In this code pattern, we will learn how to automatically generate a Jupyter notebook that will contain Python code of a machine learning model using AutoAI. We will explore, modify and retrain this model pipeline using python code. Lastly, we will deploy this model in Watson Machine Learning using WML APIs.

## Description

AutoAI is a graphical tool available within Watson Studio that analyzes your dataset, generates several model pipelines  and ranks them based on the metric chosen for the problem. This code pattern shows extended features of AutoAI. More basic AutoAI exploration for the same dataset is covered in the [Generate machine learning model pipelines to choose the best model for your problem](https://developer.ibm.com/tutorials/generate-machine-learning-model-pipelines-to-choose-the-best-model-for-your-problem-autoai/) article.

When you have completed this code pattern, you will understand how to:

* Run an AutoAI experiment.
* Generate and save a Python notebook.
* Execute notebook and analyse results.
* Make changes and retrain model using Watson Machine Learning SDKs.
* Deploy model using Watson Machine Learning from within notebook .

## Architecture components

![architecture](doc/source/images/architecture.png)

## Flow

1. The user submits an AutoAI experiment using default settings.
1. Multiple pipeline models are generated. A pipeline model of choice from the leaderboard is saved as Jupyter notebook.
1. The Jupyter notebook is executed and a modified pipeline model is generated within the notebook.
1. Pipeline model is deployed in Watson Machine Learning using WML APIs.

## Included components

* [IBM Watson Studio](https://cloud.ibm.com/catalog/services/watson-studio) - IBM Watson® Studio helps data scientists and analysts prepare data and build models at scale across any cloud.
* [IBM Watson Machine Learning](https://cloud.ibm.com/catalog/services/machine-learning) - IBM Watson® Machine Learning helps data scientists and developers accelerate AI and machine-learning deployment.

## Featured Technologies

* [Machine Learning](https://developer.ibm.com/articles/introduction-to-machine-learning/) - Science of predicting values by analysing historic data.
* [Python](https://www.python.org/) - Python is an interpreted, object-oriented, high-level programming language.
* [Jupyter notebook](https://jupyter.org/) - Open-source web application to help build live code.
* [scikit-learn](https://scikit-learn.org/stable/) - Python based machine learning library.
* [lale](https://github.com/IBM/lale) - Python library compatible with scikit-learn for semi-automated data science used in AutoAI SDK

## Prerequisites

* [IBM Cloud account](https://tinyurl.com/y4mzxow5) This code pattern assumes you have an **IBM Cloud** account. Sign up for a no-charge trial account - no credit card required.

> Instructions to get through the list of prerequistes are covered in [this](https://developer.ibm.com/technologies/artificial-intelligence/tutorials/generate-machine-learning-model-pipelines-to-choose-the-best-model-for-your-problem-autoai/) prequel.

* Create a Cloud Object Storage service instance.
* Create a Watson Studio service instance.
* Create a Watson Machine Learning service instance.
* Create a Watson Studio project and load data.

---


## 🙋‍♀️ About the Creator

Made with 💻 + 💖 by **Vaibhavi Dhankhar**  
🎓 IBM SkillsBuild Project  
🌐 [View Portfolio or GitHub Profile](https://github.com/Vaibhavidhankhar)

---

## 📬 Contact

If you have questions or suggestions:

📧 **Email**: vbhavi7677@gmail.com  
🔗 **GitHub**: [@Vaibhavidhankhar](https://github.com/Vaibhavidhankhar)

---

## 📜 License

MIT License. Free to use, share, and modify with credits.

---

> “Your heart matters. Predict it before it reacts.” – *CardioScope AI*


