# Multimodal AI Agent - Video Summarizer

## Overview

The **Multimodal AI Agent - Video Summarizer** is a Streamlit-based web application that leverages **Phidata (Agno) framework**, **Google Gemini 2.0 Flash Exp**, and **DuckDuckGo search tool** to analyze video content and provide AI-generated insights based on user queries.

## Features

- Upload video files (`mp4`, `mov`, `avi`) for analysis.
- AI-powered summarization and insights extraction from video content.
- Additional contextual information retrieved using DuckDuckGo search.
- User-friendly Streamlit interface for seamless interaction.
- Caching of AI agent to optimize performance.

## Tech Stack

- **Python**
- **Streamlit** for web UI
- **Phidata (Agno) framework**
- **Google Gemini 2.0 Flash Exp** for AI-powered video processing
- **DuckDuckGo search** for supplementary information retrieval
- **Google Generative AI SDK** for video file processing

## Installation

Ensure you have Python installed (Python 3.8 or higher recommended). Then, install the required dependencies:

```bash
pip install -r requirements.txt
```

### Required Dependencies

```
phidata
streamlit
python-dotenv
google-generativeai
```

## Environment Setup

Create a `.env` file and add your **Google API Key**:

```ini
GOOGLE_API_KEY=your_google_api_key_here
```

## Running the Application

Start the Streamlit app by running:

```bash
streamlit run app.py
```

## Usage

1. Upload a video file (`mp4`, `mov`, `avi`).
2. Enter a query asking for insights from the video.
3. Click **Analyze Video**.
4. The AI agent will process the video and generate insights.

## Project Structure

```
|-- app.py                # Main Streamlit application file
|-- .env                  # Environment variables (API Key)
|-- requirements.txt       # Dependencies
|-- README.md             # Project Documentation
```

## Output
Here's an image:
![My Project Logo](C:\Users\HP\Desktop)

