
# Lexical Complexity Prediction Project for CMSC 516

# Installation and Requirements

# •	Requirements

o	Jupyter Notebook

o	Cuda

•	Note - All the below commands are for a Linux system
•	Clone this repository
    git clone https://github.com/sass0987/Lexical-Complexity-Prediction--CMSC-516

    cd Lexical-Complexity-Prediction--CMSC-516

Create a Virtual Environment (Highly recommended) to prevent dependency conflicts

    pip install --upgrade pip
    
Note: Ensure pip is updated in the virtual environment by executing the last command above. Some dependencies require the latest version of pip.

# Download the required dependencies
    pip install -r requirements.txt
# Download GloVE Embeddings
    wget http://nlp.stanford.edu/data/glove.6B.zip

    unzip glove*.zip

# Running the code
•	Using the best models saved during training

  o	We saved the best checkpoints during training. These models are available in the TrainedModels subdirectory.
  
  o	To run the Overall Model using the best checkpoints saved, execute the below command.
    python code.py

•	Retraining everything from scratch

 
 o	To retrain all the constitutent models and run the whole architecture from scratch, execute the below command.
 
 o	Note: Slightly different results can be obtained than reported in the report due to certain non-determinism in PyTorch computations. We tried to seed as much random number generators as possible, but some non-determinism still exists which we can't control through external arguments to PyTorch.

# Running the code (Using Google Colab Notebook)

•	The Overall solution model can also be run following the instructions in below Colab Notebook

# Experiments
•	Transformer Model with the Google Colab link is located in the BERT.py file.

# Results

