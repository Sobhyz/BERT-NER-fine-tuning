# BERT-NER-fine-tuning
This project involves fine-tuning a BERT-NER model to identify medicine names and diagnoses within text, enabling subsequent data extraction and further operations.

# Data preperation
Before starting the fine-tuning process our data must match the data that BERT-NER model was trained on, therefor the very first step is to build the tags feature
according to BIO tags which you can find an explaination [here](https://huggingface.co/dslim/bert-base-NER).

# Fine-tuning
You can find a notebook that goes through the fine tuning process in this repo step-by-step. I recommend that you only prepare your data and change the file name in the
fine-tuning notebook.

**_NOTE:_** This project serves as a proof of concept, utilizing a small dataset. For commercial deployment, it is advisable to gather a larger dataset.

