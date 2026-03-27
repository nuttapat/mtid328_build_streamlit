# MTID328: Interactive Workshop Guide 🩺

### Build Your First AI Web App

An interactive, browser-based learning guide designed for students in **MTID328: Machine Learning & AI Technology for Healthcare** at the Faculty of Medical Technology, Mahidol University.

This guide takes students with zero prior programming experience through the complete machine learning pipeline—from setting up a local coding environment to deploying a live AI-powered web application for diabetes prediction.

## 🌟 Key Features

- **Interactive Single-Page Application (SPA)**: Built with pure HTML, Tailwind CSS, and vanilla JavaScript for easy distribution (no server required to view the guide).

- **Command-Line 101**: Includes a built-in, OS-specific terminal cheat sheet tailored for absolute beginners.

- **Dual Learning Paths**: Students can dynamically choose how they want to train their machine learning model:

  - 🐍 **Python Path**: Write ```train.py``` from scratch using ```scikit-learn``` and ```pandas```.

  - 🍊 **Orange3 Path**: Build a visual data pipeline using the Orange3 GUI and export the model to ```.pkcls```.

- **Dynamic Content**: The code blocks, Streamlit app instructions, and installation commands automatically update based on the student's chosen ML path.

- **Deployment Guide**: Step-by-step instructions for hosting the final app on Streamlit Community Cloud via GitHub.

## 📚 Workshop Structure

The workshop is divided into five core sections:

1. **Miniconda Setup & CLI 101**: Learning to navigate the terminal, creating virtual environments (```conda create```), and managing dependencies.

2. **The Model**: Loading the Pima Indians Diabetes dataset, training a Logistic Regression model, and saving the trained model locally (```.pkl``` or ```.pkcls```).

3. **The Web App**: Writing the app.py script using Streamlit to create a user-friendly frontend with interactive sliders for patient clinical data.

4. **Local Testing**: Running the app on the local machine (streamlit run ```app.py```) to verify functionality.

5. **Deployment**: Creating a ```requirements.txt file```, committing code to GitHub, and deploying the app live to Streamlit Community Cloud.

## 🚀 How to Use This Guide

1. Open this workshop guide from this URL: https://nuttapat.github.io/mtid328_build_streamlit/

2. Follow the interactive steps on-screen.

### Prerequisites for Students taking the Workshop

To complete the workshop activities, students will need:

- **Miniconda** installed on their machine (Windows or macOS).

- A text editor (e.g., VS Code, **Notepad++**, **BBEdit**).

- A free **GitHub** account.

- (Optional) **Orange3** installed if choosing the visual programming path.

## 🛠 Technologies Taught

- **Environment**: Miniconda, Command Line / Terminal

- **Languages**: Python 3.10

- **Data & ML Libraries**: Pandas, Scikit-Learn, NumPy, Orange3

- **Web Framework**: Streamlit

- **Deployment**: Git/GitHub, Streamlit Community Cloud

## 📄 License & Copyright

© 2026 Nuttapat Anuwongcharoen, Ph.D. All rights reserved.

Created for educational use at the Faculty of Medical Technology, Mahidol University.
