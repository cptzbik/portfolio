
# Insurance Cost Estimator

## Application Description
An intelligent web application that predicts health insurance costs based on user data and provides personalized, AI-powered suggestions to reduce premiums. The app supports both manual and voice input, calculates BMI, and explains how to lower your insurance costs.

## 🛠️ Technologies Used

**Frontend & Framework:**
- **Streamlit** – main framework for building the web interface
- **HTML/CSS** – styling and layout

**Backend & AI/ML:**
- **Python 3.8+** – main programming language
- **PyCaret** – library for automating machine learning
- **OpenAI GPT-4o** – Large Language Model for generating suggestions
- **Whisper** – speech-to-text transcription

**Audio & Data Processing:**
- **audiorecorder** – voice recording in the browser
- **Pandas** – data manipulation and analysis

**Configuration & Security:**
- **Python-dotenv** – environment variable management
- **Environment variables** – secure storage of API keys

## 🚀 Main Application Features

- **Health insurance cost prediction**
	- Predicts insurance costs using a trained machine learning model
	- Supports both manual and voice (audio) input

- **BMI calculation**
	- Calculates and displays BMI based on user input
	- Provides feedback on BMI value

- **Personalized suggestions**
	- Uses OpenAI GPT-4o to generate actionable tips for lowering insurance costs
	- Compares current and improved scenarios (e.g., lower BMI, non-smoker)

- **Speech-to-text transcription**
	- Converts voice notes to text using Whisper
	- Extracts relevant data from natural language

- **User-friendly interface**
	- Real-time feedback and clear error messages
	- Sidebar for voice input and quick calculations

## 💡 Example usage
```
User enters or records: "I am a 40-year-old man, BMI 29, 2 children, smoker, living in the southeast."

Application:
1. Extracts: age=40, sex=male, bmi=29, children=2, smoker=yes, region=southeast
2. Predicts insurance cost using the ML model
3. Suggests improvements (e.g., lower BMI, quit smoking)
4. Shows potential savings and actionable tips
```

## 🔧 Architecture
- **Modular structure** with separate functions for prediction, transcription, and data extraction
- **Integration with OpenAI GPT-4o and Whisper** for suggestions and speech-to-text
- **Secure API key management** via environment variables
- **Automatic error handling and validation** for user input

## 🎯 Business Value
This application demonstrates how AI and machine learning can be used to personalize health insurance cost predictions and provide actionable, user-specific advice. It showcases the integration of speech recognition, data extraction, and generative AI in a real-world scenario.

## 🔗 Links
- **🐙 Source code:** [https://github.com/cptzbik/insurance](https://github.com/cptzbik/insurance)
