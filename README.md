# End-to-End Airbnb Price Prediction

## Introduction
In today's fast-paced world, the way we travel and seek accommodations has undergone a remarkable transformation, thanks to platforms like Airbnb. This dynamic marketplace has empowered property owners and travelers, offering a diverse range of lodging options. However, one enduring challenge is setting the right price for a listing. Hosts aspire to optimize their earnings while ensuring competitive pricing, while guests seek value for their money. Balancing these interests can be intricate, and that's where the motivation for Airbnb price prediction comes in.

## Motivation 
The goal of this project is to harness the power of data science and machine learning to provide more accurate and data-driven pricing strategies for Airbnb hosts and guests. By developing predictive models that factor in myriad variables such as location, property type, and market dynamics, the objective is to help hosts maximize their income and guests find fair deals. In this exploration of Airbnb price prediction, we delve into methodologies, data sources, and emerging trends, shedding light on how technology is enhancing the overall Airbnb experience.

---

# Installation Guide

This guide provides step-by-step instructions on how to install and set up the Airbnb Price Prediction project.

## Prerequisites

Before you begin, make sure you have the following prerequisites installed on your system:

- Python (3.7 or higher recommended)
- Numpy
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn
- xgboost
- Flask
- Pillow
- Catboost
- DVC

## Installation Steps

### Option 1: Installation from GitHub (Recommended)

Follow these steps to install and set up the project directly from the GitHub repository:

1. **Clone the Repository**
   - Open your terminal or command prompt.
   - Navigate to the directory where you want to install the project.
   - Run the following command to clone the repository:
     ```bash
     git clone [https://github.com/premdeshmane-01/Air-BnB-Price-Prediction.git]
     ```

2. **Create a Virtual Environment** (Optional but recommended)
   - It is good practice to create a virtual environment to manage project dependencies.
     ```bash
     conda create -p venv python=3.8 -y
     ```

3. **Activate the Virtual Environment**
   - Activate the virtual environment:
     ```bash
     conda activate venv/
     ```

4. **Install Dependencies**
   - Navigate to the project directory:
     ```bash
     cd Air-BnB-Price-Prediction
     ```
   - Run the following command to install project dependencies:
     ```bash
     pip install -r requirements.txt
     ```

5. **Run the Project**
   - Start the application by running:
     ```bash
     python app.py
     ```

6. **Access the Application**
   - Open your web browser and navigate to the local address shown in the terminal (usually `http://127.0.0.1:5000`).

<br>

### Option 2: Docker Setup

If you prefer to use Docker, you can build and run the container locally:

1. **Build the Docker Image**
     ```bash
     docker build -t airbnb-price-prediction .
     ```

2. **Run the Docker Container**
     ```bash
     docker run -p 5000:5000 airbnb-price-prediction
     ```

---

## Troubleshooting

- If you encounter issues with library conflicts, ensure you are using a clean virtual environment.
- For any specific issues or questions, feel free to contact me at: **[Insert Your Email Here]**

---

# Contributing

We welcome contributions from the community! If you have any ideas or suggestions for improving the project, please feel free to create an issue or submit a pull request.

# Acknowledgements

This project was inspired by the Kaggle dataset on Airbnb Price Prediction and the corresponding competition. We also acknowledge the open-source Python libraries used in this project and their contributors.
