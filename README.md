# slogan-generator
A simple slogan generator built by fine-tuning GPT-2 on ~10,000 company and product taglines.

This repository uses the HuggingFace Transformers library to easily download and finetune GPT2.

## How to train the model

You must have PyTorch and the Transformers library installed:

    pip install torch transformers

Just open the "GPT2_finetuning.ipynb" Jupyter notebook and run all cells to download a pretrain version of GPT2 (distilled version) and finetune on the slogans dataset.

You can then use PyTorch or the Transformers library's included methods to export the model to use in production.

## Acknowledgement

The slogans in the csv file were exported from the [TextArt.ru](http://www.textart.ru/database/slogan/list-advertising-slogans.html) database.
