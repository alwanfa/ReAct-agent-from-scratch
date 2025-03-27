# React Agent: Planet Data Analysis

## Overview
This project is a React-based AI agent utilizing Groq for retrieving and analyzing planetary data. Inspired by the tutorial [here](https://www.youtube.com/watch?v=hKVhRA9kfeM&t=1506s), the agent is designed to fetch planetary information and perform basic analysis.

## Result
![image](https://github.com/user-attachments/assets/7b3ba635-bb24-4529-aae5-fec2215f0e74)
![image](https://github.com/user-attachments/assets/c4c5196f-dea5-4507-be4c-42d98f9f916d)

## Features
- Retrieves planetary data from an API
- Provides simple analysis of planets (e.g., size, distance from the sun, habitability potential)
- Interactive chat-based interface using Groq LLM (text-based in Google Colab)
- Runs entirely in Google Colab (no UI)

## Tech Stack
- **Environment**: Google Colab (Python)
- **AI Backend**: Groq API
## Installation
### Prerequisites
- Google Colab account
- Groq API key

### Setup
1. Open the Colab notebook:
   ```
   https://colab.research.google.com/drive/1nBiAIpk-SZl1xnSFcWZhIfC8CppLWaLA?usp=sharing
   ```
2. Run the first cell to install required libraries:
   ```python
   !pip install requests pandas numpy
   ```
3. Set up environment variables in the notebook:
   ```python
   import os
   os.environ["GROQ_API_KEY"] = "your_groq_api_key_here"
   PLANET_API_URL = "https://example.com/planets"
   ```
4. Run the notebook cells to fetch and analyze planetary data.

## Usage
1. Execute each cell in order.
2. Enter a planet name when prompted.
3. The agent will fetch relevant data and provide analysis.

## Folder Structure
```
react-agent-groq/
│── colab_notebook.ipynb  # Main Colab notebook
│── data/                 # Optional dataset storage
│── README.md
```

## License
This project is licensed under the MIT License.

## Contributors
- **Alwan Fa** - Developer

