# YouTube GPT Creator LangChain

Welcome to the YouTube GPT Creator. This application, uses the power of GPT-3 provided by OpenAI to generate YouTube video titles and scripts based on user-provided prompts.

## Overview

The application leverages GPT-3's natural language understanding capabilities to create engaging and relevant video content. The user inputs a prompt of their choice, and the application performs the following tasks:

- Generates a YouTube video title
- Fetches relevant information from Wikipedia
- Generates a video script incorporating the title and the Wikipedia content

## Application Flow

1. **User Input**: The user inputs a prompt into the application.

2. **Title Generation**: Using the user's prompt, the application generates a YouTube video title.

3. **Wikipedia Research**: The application uses the prompt to fetch relevant information from Wikipedia.

4. **Script Generation**: The application uses the generated title and the Wikipedia content to create a script for the video.

At each stage, the application displays the results, giving the user an opportunity to see how the title, Wikipedia content, and script are formulated.

## Installation and Usage

The application is built using Streamlit. To run the application locally, you'll need to install the necessary dependencies.

### Prerequisites

- Python 3.6 or later
- pip
- OpenAI API Key

### Installation Steps

Clone the repository:

```bash
git clone https://github.com/vivek7208/langchain_app.git
cd langchain_app
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Enter your OpenAI API Key in the `apikey.py` file:

```python
apikey = 'your OpenAI API key here'
```

Run the application:

```bash
streamlit run app.py
```

The application should now be running on your local machine.
---
