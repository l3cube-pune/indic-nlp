# IndicSQuAD: A Multi-lingual Question Answering Dataset for Indic Languages

## Introduction

The field of Question Answering (QA) has witnessed remarkable advancements, yet these benefits have largely been concentrated in high-resource languages. Indic languages, despite their substantial native speaker populations, remain significantly underrepresented in this progress.

To address this gap, we introduce **IndicSQuAD**, a comprehensive multi-lingual extractive QA dataset encompassing nine major Indic languages. This dataset is systematically derived from the widely used SQuAD dataset, ensuring a strong foundation for cross-lingual transfer and adaptation.

Building upon the methodology established with MahaSQuAD for Marathi, our approach involves carefully adapting and extending translation techniques. This meticulous process prioritizes maintaining high linguistic fidelity and accurate answer-span alignment across the diverse grammatical structures and nuances of the included languages.

IndicSQuAD provides extensive training, validation, and test sets for each of the ten languages, offering a robust and reliable resource for the development and evaluation of QA models for these languages.

## Languages Included

IndicSQuAD currently includes the following nine major Indic languages:

* Assamese (as)
* Bengali (bn)
* Gujarati (gu)
* Hindi (hi)
* Kannada (kn)
* Malayalam (ml)
* Marathi (mr)
* Oriya (or)
* Tamil (ta)
* Telugu (te)

Each language has dedicated training, validation, and test splits.

## Dataset Details

The IndicSQuAD dataset retains the extractive QA format of the original SQuAD dataset. Each example consists of a context paragraph, a question related to the context, and the answer, which is a span of text within the context.

The dataset details and baseline results on monolingual and multilingual BERT models are provided in the <a href=""> paper </a>.

## Getting Started

The IndicSQuAD dataset is publicly available at: [drive-link](https://drive.google.com/drive/folders/1GF47J0byaXPNfDhPrYyA-0d1KklZf87x?usp=sharing)

## Citation

If you use the IndicSQuAD dataset in your research, please cite the following paper:
```
@inproceedings{ruturaj2023mahasquad,
  title={MahaSQuAD: Bridging Linguistic Divides in Marathi Question-Answering},
  author={Ruturaj, Ghatage and Ashutosh, Kulkarni Aditya and Rajlaxmi, Patil and Sharvi, Endait and Raviraj, Joshi},
  booktitle={Proceedings of the 20th International Conference on Natural Language Processing (ICON)},
  pages={497--505},
  year={2023}
}
```
