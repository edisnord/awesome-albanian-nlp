# Awesome NLP Resources for Albanian
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/edisnord/awesome-albanian-nlp)
[![Check Links](https://github.com/edisnord/awesome-albanian-nlp/actions/workflows/link-checker.yml/badge.svg)](https://github.com/edisnord/awesome-albanian-nlp/actions/workflows/link-checker.yml)

## Notation used

- 👌 Easy to install and use
- 🚀 Commercial-friendly license
- 💯 Pretrained models are available or not needed

## Tools
### Morphology
- [uniparser-morph](https://github.com/timarkh/uniparser-morph)'s [Albanian](https://github.com/timarkh/uniparser-grammar-albanian) extension 🚀💯
    - Rule-based morphological analysis tool and lemmatizer supporting Albanian
        - Requires [cg3](https://github.com/GrammarSoft/cg3) for disambiguating some analysis variants, which is a program not available on all linux distros' package managers.
- [Simplemma](https://github.com/adbar/simplemma) 👌🚀💯
    - simple multilingual lemmatizer for Python, its Albanian coverage is a bit low at the moment, but it's there

## Datasets
### Large corpora for unsupervised training
- [CulturaX](https://huggingface.co/datasets/uonlp/CulturaX) 🚀
    - Massive multilingual webcrawled dataset which includes Albanian text, 3,648,893,215 tokens (largest Albanian corpus to date)
- [mC4](https://huggingface.co/datasets/allenai/c4) 🚀
    - 14GB of text
- [OSCAR](https://oscar-project.org/) 🚀
    - 462,694,599 tokens of text (3.2 GB)