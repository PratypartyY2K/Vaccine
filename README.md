# 💉 COVID-19 Vaccination Enrollment and Prioritization System

**Project Description:** A full-stack web application designed to manage the enrollment and optimized slot allocation for a COVID-19 vaccination program. The core feature is a proprietary Machine Learning algorithm that analyzes user-provided health data to automatically prioritize high-risk individuals, ensuring equitable and efficient distribution of limited resources.

## ✨ Key Architectural Highlights

* **AI-Driven Core Logic:** Integrated a custom Machine Learning model built with **Scikit-Learn** and **Random Forest** directly into the backend to execute rapid, high-accuracy risk assessment upon enrollment.
* **Monolithic Reliability (Django):** Built on the stable, secure **Django** framework, providing a robust, full-featured backend for managing user accounts, authentication, data persistence, and all business logic.
* **Optimized Resource Allocation:** The platform goes beyond simple FIFO (First-In, First-Out) queuing by applying a **Pandas**-based prioritization algorithm, dynamically adjusting slot allocation to optimize for public health impact.
* **Modern Data Handling:** Utilized the **Pandas** library for complex data manipulation, feature engineering, and pipeline execution before feeding data to the ML model.

## 🛠️ Technology Stack

| Layer | Technology | Details |
| :--- | :--- | :--- |
| **Backend Framework** | **Django (Python)** | Handles user authentication, data models, and RESTful API routing. |
| **Machine Learning** | **Scikit-Learn, Random Forest** | Core ML libraries used to develop the high-risk individual prioritization model. |
| **Data Processing** | **Pandas** | Used for data cleaning, transformation, and processing large data inputs efficiently. |
| **Frontend** | **HTML/CSS, JavaScript (ES6)** | Develops a responsive, client-side interface for user enrollment and dashboard views. |
| **APIs** | **RESTful** | Interface for the frontend to securely interact with Django models and the ML prediction endpoint. |

## 🚀 Quantified Impact

The system achieved **85% accuracy** in identifying high-risk individuals based on a predictive model, demonstrating a direct, measurable improvement in public health-focused resource distribution.
