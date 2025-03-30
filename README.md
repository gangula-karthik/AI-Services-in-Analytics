# 🤖 AI Services in Analytics Assignment

## 📋 Project Overview
This project focuses on enhancing airport security through AI-powered X-ray image analysis. Using AutoML and computer vision techniques, we develop models to detect dangerous items like guns, blades, shurikens, and knives in baggage scans. With global airports handling approximately 4.5 billion passengers and 6.75 billion pieces of luggage annually, this solution aims to improve security efficiency while reducing human error rates that can reach up to 20%.

## ✨ Features
- 🧹 Data preprocessing and cleaning of X-ray baggage images
- 🔌 Integration with Google Cloud Vertex AI for AutoML vision models
- 📊 Detection and visualization of dangerous items
- 📈 Model performance analysis and reporting
- 🎯 Support for detecting guns, blades, shurikens, and knives
- 📉 Real-time threat detection with 70-90% accuracy improvement

## 🛠️ Technologies Used
- 🐍 Python
- 📊 Data Visualization Tools (e.g., Matplotlib, Seaborn)
- 🖼️ Image Processing Libraries (openCV, skimage)
- ☁️ Cloud AI Services (Google Cloud Vertex AI)
- 🤖 AutoML Vision API

## 💻 Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/gangula-karthik/AI-Services-in-Analytics.git
    ```
2. Navigate to the project directory:
    ```bash
    cd AI_Services_in_Analytics_Assignment/
    ```

## 🚀 Usage
1. Place X-ray baggage images in the `dataset/threat_items_dataset` folder
2. Run the data preparation notebook:
    ```bash
    jupyter notebook DataPreparation.ipynb
    ```
3. Execute the AutoML training notebook:
    ```bash
    jupyter notebook AutoML.ipynb
    ```
4. View results in the Threat-Detection-1 folder

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙌 Acknowledgments
- **Instructor**: Dr Brandon Ooi
- **Institution**: Nanyang Polytechnic