# Find Friends App

## Application Description
A web application that helps users find and connect with friends based on shared interests and location. The app uses AI to suggest potential friends, analyze user profiles, and provide a seamless experience for building social connections.

## 🛠️ Technologies Used

**Frontend & Framework:**
- **Streamlit** – main framework for building the web interface
- **HTML/CSS** – styling and layout

**Backend & AI/ML:**
- **Python 3.8+** – main programming language
- **OpenAI GPT-4o** – Large Language Model for analyzing user interests and generating suggestions

**Data Processing:**
- **Pandas** – data manipulation and analysis
- **re, json** – text and data extraction

**Configuration & Security:**
- **Python-dotenv** – environment variable management
- **Environment variables** – secure storage of API keys

## 🚀 Main Application Features

- **User profile creation**
  - Users can create and edit profiles with interests, location, and preferences

- **AI-powered friend suggestions**
  - Uses GPT-4o to analyze profiles and suggest potential friends
  - Matches users based on shared interests and proximity

- **Search and filter**
  - Search for friends by interest, location, or keywords
  - Filter results for more relevant matches

- **User-friendly interface**
  - Real-time feedback, error handling, and clear instructions
  - Simple navigation and profile management

## 💡 Example usage
```
User enters: "I love hiking, photography, and live in Warsaw. Looking for friends with similar interests."

Application:
1. Analyzes the user's profile and interests
2. Suggests friends in Warsaw who also enjoy hiking and photography
3. Displays a list of potential matches with contact options
```

## 🔧 Architecture
- **Modular structure** with separate functions for profile management, matching, and suggestions
- **Integration with OpenAI GPT-4o** for profile analysis and friend recommendations
- **Secure API key management** via environment variables
- **Automatic error handling and validation** for user input

## 🎯 Business Value
This application demonstrates how AI can enhance social networking by providing personalized, data-driven friend suggestions. It showcases the use of generative AI for real-world social and community-building scenarios.

## 🔗 Links
- **🐙 Source code:** [https://github.com/cptzbik/find_friends](https://github.com/cptzbik/find_friends)
