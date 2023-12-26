# Dropbox Helper
This tool is made with the help of pathway's LLM app in order to implement a RAG (Retrieval Augmented Generation) to ensure real time data source to be used by the LLM app.
There are several steps which you can use to leverage the power of RAG based LLMs!!
step1: Clone this repository in your machine using Git clonne command.
step2: Make a .env file in the root directory and populate it with the enviroment variables.
step3: Use pip  to install all the requirements for the application to run.
step4: After the packages are installed, run command: python main.py
step5: Now separately run: streamlit run drop-app.py to launch the streamlit application which is the frontend of this app.

### Note: Use linux or MacOS since LLM app is having conflicting dependencies or use containers using docker or wsl.

.env file is like below:
OPENAI_API_TOKEN={OPENAI_API_KEY}
EMBEDDER_LOCATOR=text-embedding-ada-002
EMBEDDING_DIMENSION=1536
MODEL_LOCATOR=gpt-3.5-turbo
MAX_TOKENS=200
TEMPERATURE=0.0
DROPBOX_LOCAL_FOLDER_PATH={REPLACE_WITH_DROPBOX_RELATIVE_PATH}

make sure to change the folder path with your dropbox local path.
