# L3Cube-IndicNLP
The L3Cube's IndicNLP project is an effort to improve NLP resources for Indic languages. We have created monolingual BERT models for 10 Indic languages. We have also released monolingual and multilingual (cross-lingual) Sentence BERT models. These models provide state-of-the-art results on downstream tasks.

### Monolingual BERT models for Indic languages
More details about these models can be found in <a href="https://arxiv.org/abs/2211.11418"> paper </a>

|Model|Link|
|:--------:|:----:|
|Marathi BERT|<a href='https://huggingface.co/l3cube-pune/marathi-bert-v2'> model </a>|
|Hindi BERT|<a href='https://huggingface.co/l3cube-pune/hindi-bert-v2'> model </a>|
|Dev BERT (Hindi + Marathi)|<a href='https://huggingface.co/l3cube-pune/hindi-marathi-dev-bert'> model </a>|
|Kannada BERT|<a href='https://huggingface.co/l3cube-pune/kannada-bert'> model </a>|
|Telugu BERT|<a href='https://huggingface.co/l3cube-pune/telugu-bert'> model </a>|
|Malayalam BERT|<a href='https://huggingface.co/l3cube-pune/malayalam-bert'> model </a>|
|Tamil BERT|<a href='https://huggingface.co/l3cube-pune/tamil-bert'> model </a>|
|Gujarati BERT|<a href='https://huggingface.co/l3cube-pune/gujarati-bert'> model </a>|
|Oriya BERT|<a href='https://huggingface.co/l3cube-pune/odia-bert'> model </a>|
|Bengali BERT|<a href='https://huggingface.co/l3cube-pune/bengali-bert'> model </a>|
|Punjabi BERT|<a href='https://huggingface.co/l3cube-pune/punjabi-bert'> model </a>|
|Assamese BERT|<a href='https://huggingface.co/l3cube-pune/assamese-bert'> model </a>|

### Indic Sentence BERT models
More details about these models can be found in <a href="https://arxiv.org/abs/2304.11434"> paper </a>

|Similarity Model|Sentence BERT|
|:--------:|:--------:|
|<a href='https://huggingface.co/l3cube-pune/marathi-sentence-similarity-sbert'> Marathi Similarity </a> |<a href='https://huggingface.co/l3cube-pune/marathi-sentence-bert-nli'> Marathi SBERT</a>|
|<a href='https://huggingface.co/l3cube-pune/hindi-sentence-similarity-sbert'> Hindi Similarity </a> |<a href='https://huggingface.co/l3cube-pune/hindi-sentence-bert-nli'> Hindi SBERT</a>|
|<a href='https://huggingface.co/l3cube-pune/kannada-sentence-similarity-sbert'> Kannada Similarity </a> |<a href='https://huggingface.co/l3cube-pune/kannada-sentence-bert-nli'> Kannada SBERT</a> |
|<a href='https://huggingface.co/l3cube-pune/telugu-sentence-similarity-sbert'> Telugu Similarity </a> |<a href='https://huggingface.co/l3cube-pune/telugu-sentence-bert-nli'> Telugu SBERT</a>|
|<a href='https://huggingface.co/l3cube-pune/malayalam-sentence-similarity-sbert'> Malayalam Similarity </a> |<a href='https://huggingface.co/l3cube-pune/malayalam-sentence-bert-nli'> Malayalam SBERT</a>|
|<a href='https://huggingface.co/l3cube-pune/tamil-sentence-similarity-sbert'> Tamil Similarity </a> |<a href='https://huggingface.co/l3cube-pune/tamil-sentence-bert-nli'> Tamil SBERT</a>|
|<a href='https://huggingface.co/l3cube-pune/gujarati-sentence-similarity-sbert'> Gujarati Similarity </a> |<a href='https://huggingface.co/l3cube-pune/gujarati-sentence-bert-nli'> Gujarati SBERT</a>|
|<a href='https://huggingface.co/l3cube-pune/odia-sentence-similarity-sbert'> Oriya Similarity </a> |<a href='https://huggingface.co/l3cube-pune/odia-sentence-bert-nli'> Oriya SBERT</a>|
|<a href='https://huggingface.co/l3cube-pune/bengali-sentence-similarity-sbert'> Bengali Similarity </a> |<a href='https://huggingface.co/l3cube-pune/bengali-sentence-bert-nli'> Bengali SBERT</a>|
|<a href='https://huggingface.co/l3cube-pune/punjabi-sentence-similarity-sbert'> Punjabi Similarity </a> |<a href='https://huggingface.co/l3cube-pune/punjabi-sentence-bert-nli'> Punjabi SBERT</a>|
|<a href='https://huggingface.co/l3cube-pune/indic-sentence-similarity-sbert'> Indic Similarity (multilingual)</a> |<a href='https://huggingface.co/l3cube-pune/indic-sentence-bert-nli'> Indic SBERT (multilingual)</a>|

## License

All the resources are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>. The datasets are released to the community for research purposes only and the group is not responsible for any misuse of these datasets.

## Citing
```
@article{joshi2022l3cube_hind,
  title={L3Cube-HindBERT and DevBERT: Pre-Trained BERT Transformer models for Devanagari based Hindi and Marathi Languages},
  author={Joshi, Raviraj},
  journal={arXiv preprint arXiv:2211.11418},
  year={2022}
}
```
```
@article{deode2023l3cube,
  title={L3Cube-IndicSBERT: A simple approach for learning cross-lingual sentence representations using multilingual BERT},
  author={Deode, Samruddhi and Gadre, Janhavi and Kajale, Aditi and Joshi, Ananya and Joshi, Raviraj},
  journal={arXiv preprint arXiv:2304.11434},
  year={2023}
}

```
## Publications
```
Joshi, Raviraj. "L3Cube-HindBERT and DevBERT: Pre-Trained BERT Transformer models for Devanagari based Hindi and Marathi Languages." arXiv preprint arXiv:2211.11418 (2022).
Deode, Samruddhi, et al. "L3Cube-IndicSBERT: A simple approach for learning cross-lingual sentence representations using multilingual BERT." arXiv preprint arXiv:2304.11434 (2023).
Kowtal, Nidhi, Tejas Deshpande, and Raviraj Joshi. "Chain-of-Translation Prompting (CoTR): A Novel Prompting Technique for Low Resource Languages." Proceedings of the 38th Pacific Asia Conference on Language, Information and Computation. 2024.
Mirashi, Aishwarya, et al. "L3Cube-IndicNews: News-based Short Text and Long Document Classification Datasets in Indic Languages." arXiv preprint arXiv:2401.02254 (2024).
Rohera, Pritika, et al. "L3Cube-IndicQuest: A Benchmark Question Answering Dataset for Evaluating Knowledge of LLMs in Indic Context." arXiv preprint arXiv:2409.08706 (2024).
Rohera, Pritika, et al. "Better To Ask in English? Evaluating Factual Accuracy of Multilingual LLMs in English and Low-Resource Languages." arXiv preprint arXiv:2504.20022 (2025).
Endait, Sharvi, et al. "IndicSQuAD: A Comprehensive Multilingual Question Answering Dataset for Indic Languages." arXiv preprint arXiv:2505.03688 (2025).
```

This project is led by <a href='https://www.linkedin.com/in/ravirajoshi/'> Raviraj Joshi </a> under L3Cube Labs, Pune. For any queries contact ravirajoshi@gmail.com .
