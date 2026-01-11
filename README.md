# Youtube-Video-Summarizer

This project focuses on summarizing YouTube video content by combining video transcriptions with Large Language Models (LLMs).The goal is to help users quickly understand the key ideas, themes, and takeaways of long videos without watching them in full. Such a tool is especially useful for educational content, podcasts, lectures, tutorials, and informational videos, improving accessibility and saving time. 

<img src="hero-banner.png" >

## Prerequisites
* Python 3.9 or higher  - https://www.python.org
* Groq API key  - https://groq.com
    
## Installation


* Step 1: Clone the repository 
  * ```
    git clone https://github.com/Sivarathinam-sd/Youtube-Video-Summarizer
    cd Youtube-Video-Summarizer
    
* Step 2: Create and activate a virtual environment
  * ```
    python -m venv venv
  
  * For Mac ```source venv/bin/activate``` | For windows ```venv/Scripts/activate```
* Step 3: Install dependencies
  * ```
    pip install -r requirements.txt
* Step 4: Set up the API Key
  * Create a .env file in the root directory
  * Add the following line
    ```
    GROQ_API_KEY="your api key"
* Step 5: Run the Project
  * Open the file ```videoSummarizer.ipynb```
  * Run the cells sequentially and enter the URL of youtube video when prompted to execute the summarization.

