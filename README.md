# TubeTalk
An intelligent video assistant that helps you extract knowledge from YouTube content without watching the entire video. By leveraging advanced AI technology, TubeTalk processes video transcripts to create an interactive experience where you can ask questions, get summaries, and explore content through natural conversation.

# Key Features:

1. Instant Video Summarization: Get concise summaries of any YouTube video with just a URL.
2. Interactive Q&A: Ask specific questions about the video content and receive accurate answers.
3. Timestamp Navigation: Easily find specific moments in videos through conversation.
4. Related Content Discovery: Discover similar videos based on your interests.
5. Time-Saving: Extract key information without watching hours of content.
6. Download the summary and the chat history in text format.

# How It Works:

1. Paste any YouTube URL.
2. Our AI processes the video transcript.
3. Get an immediate summary of key points along with timestamps.
4. Start chatting with the content - ask anything about the video.
5. Receive intelligent responses with relevant timestamps.

   [![Video Placeholder]](https://github.com/user-attachments/assets/45ab4dba-1f1d-4235-887f-6e1591585a97)

# How to Run the Streamlit App Locally

This guide will walk you through the steps to run the Streamlit application on your local machine.

## Prerequisites

Before you begin, ensure you have the following installed:

* **Python:** Streamlit is a Python library, so you'll need Python installed on your system. It's recommended to use Python 3.8 or later. You can download it from [python.org](https://www.python.org/downloads/).
* **pip:** pip is the package installer for Python. It usually comes bundled with your Python installation. You'll need it to install the necessary Python libraries.
* **Git (Optional but Recommended):** If you haven't already cloned the repository, you'll need Git installed to do so. You can download it from [git-scm.com](https://git-scm.com/downloads).

## Steps to Run Locally

Follow these steps to get the Streamlit app running on your computer:

1.  **Clone the Repository:**

    If you haven't already, clone this repository to your local machine using Git. Open your terminal or command prompt and navigate to the directory where you want to save the project, then run:

    ```bash
    git clone https://github.com/NPriyankaDS/TubeTalk.git
    ```


2.  **Navigate to the Repository Directory:**

    Once the repository is cloned, change your current directory in the terminal to the newly created repository folder:

    ```bash
    cd <repository_name>
    ```

    Replace `<repository_name>` with the name of the repository you just cloned.

    *Example:*
    ```bash
    cd your-repository
    ```

3.  **Install Dependencies:**

    This project likely has a `requirements.txt` file that lists all the necessary Python libraries. It's crucial to install these dependencies before running the app. Use pip to install them:

    ```bash
    pip install -r requirements.txt
    ```

    This command will read the `requirements.txt` file and install all the listed packages, including Streamlit.

4.  **Run the Streamlit App:**

    Identify the main Python script that contains the Streamlit application (it often has a name like `app.py`, `main.py`, `streamlit_app.py`, or something similar). Once you've found it, run the app using the `streamlit run` command followed by the script's filename:

    ```bash
    streamlit run app.py
    ```

    
5.  **View the App in Your Browser:**

    After running the command, Streamlit will automatically open a new tab in your default web browser with the running application. If it doesn't open automatically, check your terminal for the local URL where the app is running (it's usually `http://localhost:8501`). Open this URL in your browser to access the Streamlit app.

Now you should be able to interact with the Streamlit application running locally on your machine!

Whether you're a student researching topics, a professional gathering information, or simply curious about a video's content before investing your time, TubeTalk provides a smarter way to interact with YouTube content.
Transform passive video watching into active knowledge exchange with TubeTalk - Turning Monologues into Conversations"
