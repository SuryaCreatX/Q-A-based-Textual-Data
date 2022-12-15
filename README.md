# Q-A-based-Textual-Data

Question Answering models can retrieve the answer to a question from a given text, which is useful for searching for an answer in a document.
Time to look at question answering! This task comes in many flavors, but the one we’ll focus on in this section is called extractive question answering. This involves posing questions about a document and identifying the answers as spans of text in the document itself.

### Create conda env

```
conda create -n tqa Python=3.8
conda activate tqa
```

### Install Depencencies

```
pip install streamlit
pip install transformers
pip install torch torchvision torchaudio
pip install torch-scatter -f https://data.pyg.org/whl/torch-1.10.0+cpu.html

```

### To run the code

```
streamlit run app.py
```
