# Streamlit App Readme

This readme file provides instructions for running the Streamlit app "Stream Chat" and highlights the steps required to set up the application environment. Please follow the guidelines below to get the app up and running on your local machine.

## Prerequisites

Before running the Streamlit app, ensure you have the following components installed:

1. Python 3.6 or later
2. pip (Python package manager)

## Setup

1. Clone the repository:

```bash
git clone https://github.com/zshancs/stream-chat.git
cd stream-chat
```

2. Create a virtual environment (optional but recommended):

```bash
# On macOS and Linux
python3 -m venv venv

# On Windows
python -m venv venv
```

3. Activate the virtual environment:

```bash
# On macOS and Linux
source venv/bin/activate

# On Windows
venv\Scripts\activate
```

4. Install required dependencies:

```bash
pip install -r requirements.txt
```

## Environment Variable

The Streamlit app relies on a secret named `OPENAI_API_KEY`, which is required for authentication purposes. Before running the app, you need to set this environment variable. In the .streamlit/secrets.toml file add: 

```bash
OPENAI_API_KEY=your_openai_api_key
```

Replace `your_openai_api_key` with the actual API key provided by OpenAI.

## Running the Streamlit App

Once you have completed the setup and set the `OPENAI_API_KEY` environment variable, you can run the Streamlit app:

```bash
streamlit run main.py
```

This will start the app, and you should be able to access it by opening your web browser and navigating to the provided URL (usually `http://localhost:8501`).

## Additional Information

- The Streamlit app is configured to use the `OPENAI_API_KEY` environment variable for security purposes. Please ensure that you keep this key confidential and avoid sharing it with others.


Enjoy using "Stream Chat" with Streamlit! If you have any feedback or suggestions, we'd love to hear from you: email at mahmad.zeeshan72@gmail.com .
"# stream-chat" 
