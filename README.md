# IMDb reviews classification using BERT

If you want to read this notebook, please open it in [google colab](https://colab.research.google.com/notebooks/intro.ipynb#recent=true) (you can use hyperlinks on functions and classes there)  
You can also open it in [nbviewer](https://nbviewer.jupyter.org) if you have a intermittent GitHub jupyter notebooks error "Sorry, something went wrong. Reload?"

### [BertForSequenceClassification](https://huggingface.co/transformers/model_doc/bert.html#transformers.BertForSequenceClassification) is used for [IMDb rewievs](https://pytorchnlp.readthedocs.io/en/latest/source/torchnlp.datasets.html#torchnlp.datasets.imdb_dataset) classification. Batch accumulation is used for more stable fine-tuning.

### Final accuracy on test sample: 93.576 %
