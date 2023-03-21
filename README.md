# ChatGPT Voice Assistant

A simple ChatGPT voice assistant using OpenAI API and Gradio to provide a user interface where users can record their queries and receive spoken responses.

## Requirements

- Python 3.6 or higher
- OpenAI    
- Gradio  
- Pyttsx3  
- Soundfile  
- FFmpeg


### Installation

### 1. Clone the repository:

   ```bash
   git clone https://github.com/your-github-username/chatgpt-voice-assistant.git
   ```
### 2. Navigate to the directory:

   ```bash
   cd chatgpt-voice-assistant
   ```

### 3. Create a virtual environment:

   ```bash
   python3 -m venv venv
   ```
### 4. Activate the virtual environment:
 - #### MacOS: 
   ```bash
   source venv/bin/activate
    ```
 - #### Windows:
   ```bash
   .\venv\Scripts\activate
   ```
### 5. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```
### 6. Add OpenAI API key to config.py:
If not done already, please create a config.py file in the project folder and add the OpenAI API key you obtained from the [OpenAI Dashboard](https://platform.openai.com/account/api-keys) erhalten haben:
```bash
OPENAI_API_KEY = "your_openai_api_key_here"
```
Replace your_openai_api_key_here with your actual API key.

## Installing FFmpeg
- #### For Windows:

Download the FFmpeg binaries from the official website: [FFmpeg Download-Seite](https://ffmpeg.org/download.html)
Extract the downloaded files and add the extracted folder containing the FFmpeg exe files (usually bin) to the PATH environment variable. You can follow instructions on how to do that here: [Install FFmpeg on Windows](https://www.geeksforgeeks.org/how-to-install-ffmpeg-on-windows/)

- #### For MacOS:
```bash
brew install ffmpeg
```

- #### For Linux:
```bash
sudo apt-get update
sudo apt-get install ffmpeg
```

## Execution
To start the ChatGPT voice assistant, run the main script:
```bash
python assistant.py
```
Open your web browser and navigate to the displayed URL (usually http://localhost:7860/), to use the voice assistant interface.
   
## Author
Author: Martin Haferanke -
Original version forked by: Hacking the Markets