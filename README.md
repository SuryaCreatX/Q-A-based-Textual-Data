# Q-A-based-on-Textual-Data

Question Answering models can retrieve the answer to a question from a given text, which is useful for searching for an answer in a document. The application is provided as a Streamlit based Webapp.
This task comes in many flavors this section is called extractive question answering. This involves posing questions about a document and identifying the answers as spans of text in the document itself.
🤗 HuggingFace Transformers is backed by the three most popular deep learning libraries — Jax, PyTorch and TensorFlow — with a seamless integration between them. It's straightforward to train your models with one before loading them for inference with the other.
Streamlit’s open-source app framework to develop Web-based Application for Machine Learning and Deep Learning Projects.

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
pip install torch-scatter -f 
```

### To run the code

```
streamlit run app.py
```
