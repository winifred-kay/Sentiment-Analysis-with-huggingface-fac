# Project : Natural Language Processing

##Introduction
Sentiment analysis has become a key tool for businesses and organizations to comprehend the attitudes and opinions expressed by individuals regarding their products, services, or content in an increasingly digitalized world. Sentiment analysis provides effective extraction of sentiment patterns from user-generated content on social media platforms, online reviews, and discussion forums, allowing organizations to make data-driven decisions. This post will highlight a machine learning study that uses fine-tuning approaches on the Hugging Face platform to classify emotion as positive, negative, or neutral.

## Project Flow
###### Understanding Sentiment Analysis:
Sentiment analysis, also known as opinion mining, is the computer process of determining the sentiment expressed in a piece of text, whether that content be a sentence, paragraph, or an entire document. Sentiment analysis identifies these texts as positive, negative, or neutral using machine learning algorithms, providing enterprises with important insights into public opinion.

###### Fine-Tuning with Hugging Face:
Hugging Face is a popular NLP (Natural Language Processing) library that provides a rich ecosystem of pre-trained transformer models. These models, such as BERT (Bidirectional Encoder Representations from Transformers) and GPT-2 (Generative Pre-trained Transformer 2), have been trained on vast amounts of text data and possess remarkable language understanding capabilities. We can leverage these pre-trained models and fine-tune them for specific tasks like sentiment analysis.

###### Data Collection and Preprocessing:
About Data
The datasets used for this project have the column below
safe text : 
label :

## Setup
Install the required packages to be able to run the evaluation locally.

You need to have [`Python3`](https://www.python.org/) on your system. Then you can clone this repo and being at the repo's root (`root :: repo_name> ...`)  follow the steps below:

- Windows:
        
        python -m venv venv; venv\Scripts\activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt  

- Linux & MacOs:
        
        python3 -m venv venv; source venv/bin/activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt  

The both long command-lines have a same structure, they pipe multiple commands using the symbol **;** but you may manually execute them one after another.

1. **Create the Python's virtual environment** that isolates the required libraries of the project to avoid conflicts;
2. **Activate the Python's virtual environment** so that the Python kernel & libraries will be those of the isolated environment;
3. **Upgrade Pip, the installed libraries/packages manager** to have the up-to-date version that will work correctly;
4. **Install the required libraries/packages** listed in the `requirements.txt` file so that it will be allow to import them into the python's scripts and notebooks without any issue.

**NB:** For MacOs users, please install `Xcode` if you have an issue.

## Ressources
1. [Quick intro to NLP](https://www.youtube.com/watch?v=CMrHM8a3hqw)
1. [Getting Started With Hugging Face in 15 Minutes](https://www.youtube.com/watch?v=QEaBAZQCtwE)
1. [Fine-tuning a Neural Network explained](https://www.youtube.com/watch?v=5T-iXNNiwIs)
1. [Fine-Tuning-DistilBert - Hugging Face Transformer for Poem Sentiment Prediction | NLP](https://www.youtube.com/watch?v=zcW2HouIIQg)
1. [Introduction to NLP: Playlist](https://www.youtube.com/playlist?list=PLM8wYQRetTxCCURc1zaoxo9pTsoov3ipY)
<!-- 1. [](https://www.youtube.com/)
1. [](https://www.youtube.com/) -->
![image](https://github.com/winifred-kay/Sentiment-Analysis-with-huggingface-fac/assets/74463676/5e1c3d37-8dc6-4b1a-81d8-dbb67cc2e53e)
![image](https://github.com/winifred-kay/Sentiment-Analysis-with-huggingface-fac/assets/74463676/2715854a-7ea7-47b1-9cbf-50bf88edd1d3)

