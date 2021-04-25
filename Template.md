# [Paper Title or Abbreviation]

Code (and dataset) for our [Venue] [Year] paper "[Paper title]".

You can download the paper via: [[Github]](xx.pdf) [[DOI]](https://doi.org/xx/xx) [[ArXiv]](https://arxiv.org/abs/xxxx.xxxxx) [[PapersWithCode]](https://paperswithcode.com/).

## One-Sentence Summary

[Summarize your work in one sentence]

![Insert a preview image here](https://via.placeholder.com/300.jpg)

## Abstract

[Paste the abstract here]

## Requirement

- Python 3
- PyTorch 1.5.0
- …

## Preparation

### Clone

```bash
git clone https://github.com/**/***.git
```

### Create an anaconda environment [Optional]:

```bash
conda create -n [abbr]
conda activate [abbr]
pip install -r requiresments.txt
```

### Prepare the training data:

- Download the dataset files [here](https://example.com).
- Extract them to the `data` folder.
- The directory structure will be as follows:
```
data
└── sst1
   ├── train.txt
   ├── dev.txt
   └── test.txt
└── sst2
   ├── train.txt
   ├── dev.txt
   └── test.txt
```

### Download the pretrained embeddings (or models):

- Download pre-trained word vectors [here](https://nlp.stanford.edu/projects/glove/).
- Extract the [glove.840B.300d.zip](http://nlp.stanford.edu/data/glove.840B.300d.zip) to the `glove` folder.

## Usage

### Training:

```bash
python main.py --arg1 arg1 --arg2 arg2
```

### Evaluation:

```bash
python main.py --evaluate --arg1 arg1 --arg2 arg2
```

## File Specifications [Optional]

- **model.py**: Description for the model architecture.
- **data.utils.py**: Used functions for data preprocessing.
- …

## Citation

If this work is helpful, please cite as:

```bibtex
@inproceedings{[author_first_name][year][abbr],
  title={[paper title]},
  author={[authors]},
  booktitle={[venue]},
  year={[year]}
}
```

## Acknowledgments

This work is supported by [funds].

## Contact

[Email address of the corresponding contributor]

## License

[License]
