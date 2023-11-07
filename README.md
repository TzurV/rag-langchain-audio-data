# Retrieval Augmented Generation (RAG) using directly Whisper

This repo demonstrates how to perform RAG on audio data with LangChain using Whisper for transcription, HuggingFace for embeddings, Chroma as a vector database, and OpenAI's GPT 3.5 as a language model.

[Retrieval Augmentation Generation (RAG)](https://learn.microsoft.com/en-us/azure/search/retrieval-augmented-generation-overview) is an architecture that augments the capabilities of a Large Language Model (LLM) like ChatGPT by adding an information retrieval system that provides the data.

With **Retrieval_Augmented_Generation_directly_using_Whisper.ipynb** notebook OpenAI's transcription is unpacked and implemented directly using Whisper.


Setting up environment

Using [miniconda](https://docs.conda.io/projects/miniconda/en/latest/) instractions

1. Create virtual environment
   
   conda create --name rag python=3.11
   
2. Activate virtual environment
   
     conda activate rag

3. install [JutyterLab](https://jupyterlab.readthedocs.io/en/stable/index.html)
   
     conda install -c conda-forge jupyterlab
   
4. install [ipywidgets](https://ipywidgets.readthedocs.io/en/stable/)
   
     conda install -c conda-forge ipywidgets



The Notebook includes several comments and recommendations on how the solution can be improved.


Check out the original article [Retrieval Augmented Generation on audio data with LangChain](https://www.assemblyai.com/blog/retrieval-augmented-generation-audio-langchain/)

