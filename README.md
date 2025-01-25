# ChatBot

This project is a simple backend implementation for a ChatGPT clone using OpenAI's GPT API. The backend is built with Node.js and Express, providing an API endpoint to handle user queries and return responses from the GPT model.

Features
API endpoint to send messages to OpenAI's GPT-3.5/4 model.

**Getting Started**
Follow these steps to set up and run the project locally:

**1.Setting Up OpenAI API**
To access the OpenAI API, you need to obtain an API key from the OpenAI platform:

Visit the OpenAI API platform at https://platform.openai.com/.
You may be prompted to create an OpenAI account or log in if you already have one. Follow the instructions accordingly.
In order to use the OpenAI API, you need to set up a paid account on https://platform.openai.com/account/billing/overview
Once you're done, navigate to https://platform.openai.com/account/api-keys.
Click on the "Create new secret key" button to generate your unique API key.
Copy the API key and make sure to keep it secure. Treat it like a password, as it provides access to your OpenAI API resources.
Remember, the API key is sensitive information and should not be shared publicly or with unauthorized individuals, keep it safe!

**2. Clone the Repository**
git clone https://github.com/DhruvaPatel14/ChatBot.git

**3. Install Dependencies**
pip install openai

**4. Set Up Environment Variables**
Create an environment variable to store your OpenAI API key. There are several ways to do this:

For Linux/MacOS (Temporary)
export OPENAI_API_KEY='your-api-key-here'

For Windows Command Prompt (Temporary)
set OPENAI_API_KEY=your-api-key-here

For Windows PowerShell (Temporary)
$env:OPENAI_API_KEY="your-api-key-here"

**5. Finally, run main**
python3 main.py
