
# SemEval Task 1 - Lexical Complexity Prediction (https://arxiv.org/abs/2106.02340) 

# Installation and Requirements 

Python 3.6 (Tested in this environment) Cuda 

Note - All the below commands are for a Linux system

Create a Virtual Environment (Highly recommended to prevent dependency conflicts) python3 -m venv venv

source venv/bin/activate

# On Windows - venv\Scripts\activate

pip install --upgrade pip

Note: Ensure pip is updated in the virtual enviroment by executing the last command above. Some dependencies require the latest version of pip.
Please ensure to execute all the 3 commands above

** Download the required dependencies pip install -r requirements.txt Download GloVE Embeddings wget http://nlp.stanford.edu/data/glove.6B.zip **

unzip glove*.zip


Running the code (Using Google Colab Notebook) The Overall solution model can also be run following the instructions in this Colab Notebook Experiments Transformer Models and the Neighbourhood Aggregate Model with the Google Colab links are located in the Experiments subdirectory.
