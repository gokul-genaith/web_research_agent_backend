# Web Research Agent

An AI-powered research agent that can search the web, find news articles, and synthesize information from multiple sources.

## Features

- Web search functionality
- News article retrieval
- Content extraction from websites
- Information synthesis
- Clean and intuitive user interface
```
## Live Demo

Visit our live demo at: [Web Research Agent Demo](https://webresearchagentbackend-6kcsne7758ekd37pe5d7sq.streamlit.app/)

## Local Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/web-research-agent.git
cd web-research-agent
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the Streamlit app:
```bash
streamlit run app.py
```

## API Keys Required

- Google API Key (for Gemini model)
- News API Key (for news retrieval)

Get your API keys from:
- [Google AI Studio](https://makersuite.google.com/app/apikey)
- [NewsAPI](https://newsapi.org/)


## Running the Application
1. Clone the repository:
```bash
git clone https://github.com/gokulnath117/web_research_agent.git
cd web-research-agent
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. API Keys Required

- Google API Key (for Gemini model)
- News API Key (for news retrieval)

Get your API keys from:
- [Google AI Studio](https://makersuite.google.com/app/apikey)
- [NewsAPI](https://newsapi.org/)

4. Set up environment variables:
Create a `.env` file in the backend directory with:
```env
OPENAI_API_KEY=your_openai_api_key_here
NEWS_API_KEY=your_news_api_key_here
# Add any other required API keys
```

5. Start the backend server:
```bash
python api.py
```

The backend server will start running at `http://localhost:8000`

### Frontend Setup
Start the frontend:
```bash
streamlit run app.py
```

The frontend will be available at `http://localhost:3000`


### Testing the Application

1. Open your browser and navigate to `http://localhost:3000`
2. The frontend will automatically connect to the backend at `http://localhost:8000`
3. You can test API endpoints directly using the Swagger UI at `http://localhost:8000/research`


## Common Issues and Solutions

### Backend Issues
1. Port already in use:
   - Change the port in `api.py`
   - Or kill the process using the current port

2. Dependencies not found:
   - Ensure you're in the virtual environment
   - Run `pip install -r requirements.txt` again

### Frontend Issues
API connection failed:
   - Verify the backend is running
   - Check if the API URL is correctly set in `.env`

## Monitoring and Logs

### Backend Logs
- Check the terminal running the backend for real-time logs

### Frontend Logs
- Check the browser console for frontend errors

## Development Tips

1. Use the API documentation at `http://localhost:8000/research` to understand available endpoints
2. Test API endpoints using postman
3. Monitor the terminal outputs for both frontend and backend while developing