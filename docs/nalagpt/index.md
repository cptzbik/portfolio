 # NalaGPT - Chatbot Application with OpenAI

## Application Description

**NalaGPT** is an intelligent chatbot based on OpenAI technology that simulates a conversation with a cat. The application allows users to have conversations with AI, which are saved and can be reloaded later.

## Main Features

### 🐱 Cat Personality Chatbot
- **Default personality**: The chatbot behaves like a cat – meows, asks for treats
- **Customizable personality**: The user can change the chatbot's personality in the sidebar
- **Conversation memory**: The bot remembers previous messages (last 25)

### 💬 Conversation Management
- **Create new conversations**: Ability to start a new conversation thread
- **Switch between conversations**: Load previous conversations
- **Naming**: Each conversation can have its own name
- **History**: All messages are saved locally

### 💰 Cost Tracking
- **Token calculation**: Counts input/output tokens
- **Costs in USD and PLN**: Converts according to the current rate (1 USD = 3.97 PLN)
- **AI models**: Supports GPT-4o and GPT-4o-mini with different prices

### 🔐 Secure API Key Management
- **.env file**: Automatically loads the key from the environment file
- **Fallback UI**: If there is no .env file, the user can enter the key
- **Session state**: The key is saved in Streamlit session memory

## Technologies

### 🐍 Backend
- **Python 3.x**: Main programming language
- **Streamlit**: Framework for building web applications
- **OpenAI API**: Integration with GPT language models

### 📁 Database
- **JSON**: Stores conversations in JSON files
- **File-based storage**: Local files instead of a database
- **Directory structure**:
  - `naszgpt_db/` - main database directory
  - `conversations/` - conversation files
  - `current.json` - currently active conversation

### 📚 Libraries and Dependencies
```python
streamlit          # User interface
openai            # OpenAI API client
python-dotenv     # Loading environment variables
pathlib           # File path operations
json              # Data serialization
```

### 🌐 Architecture
- **Single-page application**: Everything in one Streamlit file
- **Session management**: User state management
- **File I/O**: File operations for data storage
- **Error handling**: API error handling and data validation

## Code Structure


### 1. Configuration and Pricing
- Definition of AI model prices
- Currency rate configuration
- Default settings

### 2. API Key Management
- Function `get_openai_api_key()`
- Checking the .env file
- Fallback UI for the user

### 3. Chatbot
- Function `get_chatbot_reply()`
- Integration with OpenAI API
- Message system handling

### 4. Conversation Database
- `load_current_conversation()` - loads the current conversation
- `save_current_conversation_messages()` - saves messages
- `create_new_conversation()` - creates a new conversation
- `switch_conversation()` - switches between conversations

### 5. User Interface
- Main chat with message history
- Sidebar with controls and statistics
- Conversation management

## Security

- **API keys**: Never committed to Git (thanks to .gitignore)
- **Data validation**: Checks JSON file correctness
- **Error handling**: Graceful error handling without crashing
- **Session isolation**: Each user has their own session

## Extension Possibilities

- **More AI models**: Add other OpenAI models
- **Conversation export**: PDF, TXT, JSON
- **Search**: Search conversation history
- **Multiple users**: Login and authorization system
- **Backup**: Cloud synchronization

## Launch

```bash
# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py
```

The application will automatically create the necessary directories and files on first launch.

## 🔗 Links

- **🚀 App demo:** [https://nalagpt.streamlit.app/](https://nalagpt.streamlit.app/)
- **🐙 Source code:** [https://github.com/cptzbik/nalagpt](https://github.com/cptzbik/nalagpt)

