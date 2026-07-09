# 🍽️ AI-Powered Calorie Tracker

An intelligent web application that simplifies nutrition tracking by using Computer Vision to recognize food items from images and automatically calculate their caloric and macronutrient values.

---

## 📖 Introduction
Manual nutrition logging is time-consuming and often inaccurate. **Calorie Tracker** solves this problem by allowing users to simply **take a photo of their meal**. The system automatically recognizes the food components, eliminating the friction of manual entry and boosting user consistency.

## 💡 The Hypothesis
By replacing manual text input with **automated image recognition**, the application:
- Reduces the time and effort required to track daily nutrition.
- Increases long-term user retention and engagement.
- Enhances data accuracy compared to manual estimation.

---

## 🏗️ Architecture & System Workflow
The application is built upon a modular three-tier architecture:

1. **Frontend (Client Layer):** An intuitive user interface for image uploads and interactive data visualization.
2. **Backend API (Logic Layer):** Handles image processing, coordinates communication with the ML model, and fetches data from nutritional databases.
3. **ML Model (Intelligence Layer):** A deep learning component trained specifically for food classification.

---

## 🛠️ Tech Stack & Methodology

### 💻 Technologies Used
- **Backend:** Python (Flask / FastAPI)
- **Frontend:** React, HTML5, CSS3
- **Version Control:** Git, GitHub

### 🧠 Machine Learning & Data Methodology
- **Model Architecture:** Convolutional Neural Network (CNN) optimized for image classification.
- **Dataset:** Trained on benchmark datasets (e.g., *Food-101*).
- **Nutritional Database:** Integrates external APIs / datasets like [USDA FoodData Central](https://usda.gov) to fetch precise ingredient data.

---

## 🧩 Features & API Specifications

### Key Features
- **Instant Food Classification:** Upload standard image formats (JPEG/PNG) for automated detection.
- **Nutrient Calculation:** Real-time breakdown of total calories and macronutrients (proteins, carbs, fats).
- **Interactive UI:** Clean, visual dashboard rendering the analytical breakdown to the user.

### 🔍 API Endpoints Summary

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `POST` | `/analyze` | Accepts meal image payload; returns classified food label and nutrition matrix. |
| `GET` | `/food/{name}` | Fetches nutritional reference values directly by food item name. |

---

## 📊 Results & Conclusion
- **Results:** The CNN model successfully classifies core food categories and estimates nutritional profiles within an acceptable margin of error.
- **Conclusion:** This project successfully demonstrates how combining Computer Vision with verified nutritional data creates a high-utility tool that promotes healthier lifestyle habits through technology.

## 🚀 Future Roadmap
- [ ] Implement multi-object detection to analyze complex, multi-item meals from a single photo.
- [ ] Add user authentication and personalized daily caloric intake recommendations.
- [ ] Transition the frontend architecture into a cross-platform mobile application.

---

## 👩‍💻 Author
- **Katarina Pilić** - *univ. bacc. inf. et techn. Katarina Pilić*
