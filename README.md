# Soul Space - Digital Journal and Mental Health Companion
==============================================

## About the Project
Soul Space is a digital journaling platform designed to support mental well-being. 
It allows users to write journal entries, track their emotions, and receive AI-powered insights 
based on their mood patterns. With interactive tools, visual analytics, and a chatbot companion, 
Soul Space helps users gain a deeper understanding of their mental health journey.

## Features
- Secure and private digital journaling
- Emotion detection using AI
- Interactive charts for mood tracking
- Calendar-based journal entry system
- AI chatbot for mental health support
- Streak counter to encourage consistency
- Visualization of emotions over time

## Technologies Used
- StreamLit (Frontend)
- Python (Backend & AI Model)
- Hugging Face (Emotion Detection)
- Pandas (Data Processing)

## Prerequisites
- Python 3.8+
- StreamLit
- Hugging Face API Token
- Google API Key (for chatbot)

## Installation
1. Clone the repository: `git clone https://github.com/your-repo/soul-space.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Set up Hugging Face API Token: `export HF_API_TOKEN=your_api_token`
4. Set up Google API Key: `export GOOGLE_API_KEY=your_api_key`

## Usage
1. Run the application: `streamlit run Home.py`
2. Write a journal entry and submit it to detect emotions
3. View your mood calendar and track your emotions over time
4. Chat with the AI companion for mental health support

## API Documentation
The Hugging Face API is used for emotion detection. Please refer to the [Hugging Face API documentation](https://huggingface.co/docs/api) for more information.

## Testing
To test the application, run the following command: `streamlit run Home.py`

## Deployment
To deploy the application, you can use a cloud platform such as Heroku or AWS. Please refer to the [StreamLit deployment documentation](https://streamlit.io/docs/deployment) for more information.

## Chatbot Companion
The chatbot companion is powered by the Google Generative AI model. Please refer to the [Google Generative AI documentation](https://cloud.google.com/generative-ai) for more information.

## Contributing
To contribute to the project, please fork the repository and submit a pull request. Please ensure that your code is well-documented and follows the project's coding standards.

## License
The project is licensed under the MIT License. Please refer to the [LICENSE](LICENSE) file for more information.