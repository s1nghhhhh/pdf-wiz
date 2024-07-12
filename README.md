# pdf-wiz
check it out here: <a href="https://pdf-wiz.streamlit.app"> pdf-wiz</a>

chat with multiple pdfs along with added conversational memory to maintain chat history and context

  <br>     -used streamlit for gui and python for backend 
  <br>     -integrated <a href="https://wow.groq.com/">GROQ's</a> LLM api to empower the application with advanced capabilities for processing natural language queries directly from uploaded PDF files.
  <br>     -utilized PyPDF2 package for extracting text from uploaded PDFs and splitting them into manageable chunks for processing
  <br>     -upload multiple pdfs at a time


to use it on your own system:
<br> - clone the repo
<br> - create and activate a virtual environment
<br> - install dependencies using _pip install -r requirements.txt_
<br> - create .env file
<br> - get an API key from <a href = "https://console.groq.com/keys"> GROQ CLOUD </a>
<br> - store API key in .env file using **GROQ_API_KEY_GIT** = "<i> api key goes here (without quotes)</i> "
<br> - in the terminal type _streamlit run app.py_
<br>




[pdf-wiz.webm](https://github.com/s1nghhhhh/pdf-wiz/assets/82044361/6a13aaf7-b9d7-46ff-a390-8883f62daa6f)
