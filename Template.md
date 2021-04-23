# [Paper Title or Abbreviation]

Code (and dataset) of our [Venue] [Year] paper "[Paper title]".

You can download the paper via: [[Github]](xx.pdf) [[DOI]](https://doi.org/xx/xx) [[ArXiv]](https://arxiv.org/abs/xxxx.xxxxx) [[PapersWithCode]](https://paperswithcode.com/).

## One-Sentence Summary

[Summarize your work in one sentence]

## Abstract

[Paste the abstract here]

## Requirement

- Python 3
- PyTorch 1.5.0
- …

## Preparation

Create anaconda environment [Optional]:

```bash
conda create -n [abbr]
conda activate [abbr]
pip install -r requiresments.txt
```

Prepare the training data:

- Download the dataset files [here](https://example.com).
- Extract them  to the `data` folder.

Download the pretrained embeddings (or models):

- Download pre-trained word vectors [here](https://github.com/stanfordnlp/GloVe#download-pre-trained-word-vectors).
- Extract the [glove.840B.300d.zip](http://nlp.stanford.edu/data/wordvecs/glove.840B.300d.zip) to the `glove` folder.

## Usage

Training:

```bash
python main.py --arg1 arg1 --arg2 arg2
```

## Citation

If this work is helpful, please cite as:

```bibtex
@inproceedings{[author's first name][abbr][year],
  title={[paper title]},
  author={[authors]},
  booktitle={[venue]},
  year={[year]}
}
```

## Acknowledgments

This work is supported by [funds].

## License

[License]
