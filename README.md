Language Model for Filipino (Tagalog) Language
===========================================

This project contains relevant files for creating a language model for the Filipino language from the Filipino (Tagalog) Wikipedia corpus, Wiktionary, and Wikibooks.

Language model weights and the itos (index -> string) mapping pickle file is available for download [here]()

## Performance:
__Perplexity: 26.1997__ 

__Accuracy: 0.4403__

The RNN was trained in 4 iterations with the following learning rates:

1. 8
2. 4
3. 1.5
4. 0.2

The learning rates were determined through the plot_lr() methods of fastai.

## TODO:
- [x] Host the language model weights and itos (index -> string vocab pickle file) for the community to reuse the model directly
- [x] Add gradient clipping
- [x] Include the text generation code snippet to visually inspect language model
- [ ] Use the [sentencepiece tokenizer](https://github.com/google/sentencepiece)
- [ ] Finetune
- [ ] Use continuous cache pointer (from here: https://github.com/salesforce/awd-lstm-lm)
- [ ] Try QRNN (from here: https://github.com/salesforce/pytorch-qrnn/)
- [ ] Identify new datasets for sentiment analysis.
- [ ] Figure out if there are any summarization datasets out there.
