# Marine Classification and Alternate Predictions

The **Marine Classification and Alternate Predictions** system is designed to address the challenges of accurately identifying diverse fish species and tracking their precise locations. In fisheries management, misidentification or lack of real-time tracking can impede sustainable practices and disrupt ecological balance. This project introduces an **Intelligent Fish Species Identification System**, leveraging a robust dataset of fish images to train a **Convolutional Neural Network (CNN)**. Through an easy-to-use image capturing device tailored for fishermen, the system provides **real-time species identification, classification, and precise location tracking**. By integrating modern technology with traditional practices, this solution aims to enhance sustainable fisheries management and contribute to the preservation of marine ecosystems.

---

## Key Features
- **Real-Time Species Identification**: Accurately identifies fish species through CNN-powered image recognition.
- **Classification & Tagging**: Organizes fish species into categories for better data management.
- **Geospatial Analytics**: Utilizes geolocation to provide real-time tracking and mapping of fish species.
- **Alternate Predictions**: Suggests alternate classifications for uncertain cases, providing a ranked list of potential species.
- **User-Friendly Interface**: Designed specifically for fishermen to enable easy capture and classification of fish images in real-time.
- **Environmental Monitoring**: Helps monitor and predict changes in fish populations, aiding sustainable fishing practices.

---

## Setup Instructions

### 1. Prerequisites
- Ensure the following software is installed on your system:
  - [Python](https://www.python.org/) (v3.8 or higher)
  - [Node.js](https://nodejs.org/) (v14.x or higher)
  - [MongoDB](https://www.mongodb.com/) (v4.x or higher)

### 2. Download the Fish Dataset
1. **Download the Dataset:**
   - Go to [Fish Dataset](#) (link to the dataset source).
   - Download and unzip the dataset in a suitable directory within your project.

2. **Move the Dataset to Your Project Directory:**
   - Place the dataset files in the `data` directory (or specify a different path).

### 3. Setup Backend and Frontend Services
1. **Clone the Repository:**
   - Run the following commands:
   
   ```sh
   git clone https://github.com/yourusername/marine-classification.git
   cd marine-classification
   ```

2. **Install Backend Dependencies:**
   - Navigate to the backend folder and install dependencies:
   
   ```sh
   cd backend
   pip install -r requirements.txt
   ```

3. **Install Frontend Dependencies:**
   - Navigate to the frontend folder and install dependencies:
   
   ```sh
   cd ../frontend
   npm install
   ```

### 4. Run the Application
- **Start the Backend Server:**
  
  ```sh
  cd backend
  python app.py
  ```

- **Start the Frontend Server:**
  
  ```sh
  cd ../frontend
  npm start
  ```

### 5. Model Training and AI Setup
- **Train the Model** (if required):
  
  ```sh
  cd ai_model
  python train_model.py
  ```

- **Run the AI Prediction Service:**
  
  ```sh
  python predict.py
  ```

---

## Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS"/>
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Google_Maps-4285F4?style=for-the-badge&logo=google-maps&logoColor=white" alt="Google Maps"/>
</p>

---

## Contributors
<a href="https://github.com/alokillur/AUTO-FIS/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=hrithikshetty/AUTO-FIS" />
</a>

For more information, visit the [GitHub repository](https://github.com/yourusername/marine-classification).
```
