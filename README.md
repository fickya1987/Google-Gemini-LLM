# Google-Gemini-LLM
🔧 Technologies Used:

Streamlit for building user-friendly web interfaces

Python for backend logic

Google Generative AI for content generation

Pillow (PIL) for image handling

dotenv for managing environment variables securely



🌟 Project 1: Gemini Image & Text Content Generator(vision.py)

🔍 How It Works:

Load Environment Variables: Securely loads the API key using the dotenv library.

Initialize Generative AI: Configures the Google Generative AI model (Gemini-1.5-flash) with the API key.

User Interface: Users can input text prompts if needed and upload images via the Streamlit app.

Generate Response: Sends the input data to the AI model, which returns a descriptive response.

Display Response: The response is displayed for users to view.

💡 Use Case: This app generates informative content or descriptions based on text and image inputs, making it a valuable tool for creative projects, educational purposes, and more!



🌟 Project 2: Gemini Q&A Application(app.py)

🔍 How It Works:

Load Environment Variables: Securely loads the API key using the dotenv library.

Initialize Generative AI: Configures the Google Generative AI model (Gemini-Pro) with the API key.

User Interface: Users can input their questions directly into the Streamlit app.

Generate Response: Sends the user's question to the AI model, which processes and generates a response.

Display Response: The response is displayed for users to read and utilize.

💡 Use Case: This Q&A app leverages the power of generative AI to provide intelligent answers to user questions, suitable for educational purposes, research, or satisfying curiosity.
