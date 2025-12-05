Project Overview: NeuroBot is an intelligent chatbot built using Natural Language Processing (NLP) techniques and a Logistic Regression model, integrated with a Streamlit web interface. It classifies user inputs based on predefined intents and generates context-appropriate responses, offering a simple, interactive, and intelligent user experience.

Features: The app offers intent classification via TF-IDF vectorization and logistic regression, a clean Streamlit UI, custom intent configuration, randomized response generation, chat history logging to CSV with timestamps, and a sidebar for viewing chat history and accessing an "About" section.

Project Structure: The main components include app.py (Streamlit app), main.ipynb (development notebook), intents.json (list of intents, patterns, and responses), chat_log.csv (auto-generated log), requirements.txt (dependencies), and README.md (project documentation).


How It Works: The chatbot uses TF-IDF to vectorize text and a Logistic Regression model to classify it into one of the predefined intents. It then returns a randomly selected response tied to that intent. All conversations are saved in chat_log.csv with timestamps.

Example Intents: Intents are structured as objects containing a tag, patterns, and responses. For example, a greeting intent may include patterns like "Hi", "Hello", and responses like "Hey there!", "Hello!".

Logging and History: All user-bot interactions are timestamped and stored in chat_log.csv. Users can also view previous chats using the "Conversation History" tab in the Streamlit sidebar.
