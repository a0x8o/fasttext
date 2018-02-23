---
id: english-vectors
title: English word vectors
---

This page gathers several pre-trained word vectors trained using fastText.

### Download pre-trained word vectors

Pre-trained word vectors learned on different sources can be downloaded below:

1. [wiki-news-300d-1M.vec.zip](https://s3-us-west-1.amazonaws.com/fasttext-vectors/wiki-news-300d-1M.vec.zip): 1 million word vectors trained on Wikipedia 2017, UMBC webbase corpus and statmt.org news dataset (16B tokens).
2. [wiki-news-300d-1M-subword.vec.zip](https://s3-us-west-1.amazonaws.com/fasttext-vectors/wiki-news-300d-1M-subword.vec.zip): 1 million word vectors trained with subword infomation on Wikipedia 2017, UMBC webbase corpus and statmt.org news dataset (16B tokens).
3. [crawl-300d-2M.vec.zip](https://s3-us-west-1.amazonaws.com/fasttext-vectors/crawl-300d-2M.vec.zip): 2 million word vectors trained on Common Crawl (600B tokens).

### Format

The first line of the file contains the number of words in the vocabulary and the size of the vectors.
Each line contains a word followed by its vectors, like in the default fastText text format.
Each value is space separated. Words are ordered by descending frequency.

### License

These word vectors are distributed under the [*Creative Commons Attribution-Share-Alike License 3.0*](https://creativecommons.org/licenses/by-sa/3.0/).

### References

If you use these word vectors, please cite the following paper:

T. Mikolov, E. Grave, P. Bojanowski, C. Puhrsch, A. Joulin. [*Advances in Pre-Training Distributed Word Representations*](https://arxiv.org/abs/1712.09405)

```markup
@inproceedings{mikolov2018advances,
  title={Advances in Pre-Training Distributed Word Representations},
  author={Mikolov, Tomas and Grave, Edouard and Bojanowski, Piotr and Puhrsch, Christian and Joulin, Armand},
  booktitle={Proceedings of the International Conference on Language Resources and Evaluation (LREC 2018)},
  year={2018}
}
```
