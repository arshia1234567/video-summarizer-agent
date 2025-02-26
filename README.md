# Phidata Video AI Summarizer Agent 🎥🎤🖬

This project is a Streamlit-based web application that leverages a multimodal AI agent to analyze and summarize video content. The AI agent is powered by the Gemini 2.0 Flash Exp model and uses various tools to provide detailed insights based on user queries.

## Features

- Upload video files in various formats (mp4, mov, avi)
- Analyze video content and context
- Generate detailed, user-friendly, and actionable responses
- Supplementary web research using DuckDuckGo

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/arshia1234567/video-summarizer-agent.git
   cd video-summarizer-agent
   ```
2. Create a virtual environment and activate it:

   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install the required dependencies:

   ```sh
   pip install -r requirements.txt
   ```
4. Create a [.env](http://_vscodecontentref_/0) file in the root directory and add your API keys:

   ```env
   GROQ_API_KEY="your_groq_api_key"
   GOOGLE_API_KEY="your_google_api_key"
   ```

## Usage

1. Run the Streamlit application:

   ```sh
   streamlit run app.py
   ```
2. Open your web browser and navigate to `http://localhost:8501`.
3. Upload a video file and enter your query to get insights from the video content.

## Project Structure

- [app.py](http://_vscodecontentref_/1): Main application file containing the Streamlit app and AI agent logic.
- [requirements.txt](http://_vscodecontentref_/2): List of dependencies required for the project.
- [.env](http://_vscodecontentref_/3): Environment file containing API keys (not included in the repository).

## Dependencies

- Streamlit
- phidata
- python-dotenv
- yfinance
- packaging
- duckduckgo-search
- fastapi
- uvicorn
- groq
- openai
- sqlalchemy
- pgvector
- psycopg[binary]
- pypdf
- google-generativeai

## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [Phidata](https://phidata.com/)
- [DuckDuckGo](https://duckduckgo.com/)
- [Google Generative AI](https://ai.google/)
