# summarize
Summarize model for makes summary from news articles 
# spacy-summary

A work-in-progress test summarizer that uses [spacy.io](https://spacy.io/).

## Usage

To get started, install the dependencies:

```bash
# Using virtualenv
virtualenv .env
source .env/bin/activate

# Install python libraries
pip install -r requirements.txt
python -m spacy download en
python --version = 2.7
```

The program takes the text file to summarize and the number of sentences to include in the summary:
# Reads and summarizes document.txt in 3 sentences
python main.py 

# Steps for execute the program
cd spacy-summary ``` #navigate to root folder using conda terminal\n ```
conda activate py27 ``` #if the current python version 2.7 in conda terminal, then ignore this step\n ```
python main.py ``` #start the python server using flask and waiting for POST request\n ```
