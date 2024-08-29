# RAG-pdf
Playing with pdf
Sample Example of RAG based system to train the LLM model using the local document like Pdf. Post that we can ask any questions to the model and try to see of the model can asnwer the questions based on the details available in the trained document.

Step 1: If you are running in ur local please make sure you install Ollama and make the llama2/llama3.1 is up and running.
        i) Download ollama from https://ollama.com/ and install in your machine.
        ii) pull the desired model and run the model(ollama pull llama2 , ollama run llama2)

Step 2: Create a directory in your system and open the directory using the vs code.

Step 3: Create a virtual environment and install the required packages
        $ python3 -m venv .venv
        $ source .venv/bin/activate(in case of windows use .\Scripts\activate.bat  )
        $ pip install -r requirements.txt

Step 4: Create a .env file with the following variables:
        OPENAI_API_KEY = [ENTER YOUR OPENAI API KEY HERE]
      
