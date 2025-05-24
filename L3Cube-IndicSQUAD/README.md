# IndicSQuAD: A Multi-lingual Question Answering Dataset for Indic Languages

## Introduction

The field of Question Answering (QA) has witnessed remarkable advancements, yet these benefits have largely been concentrated in high-resource languages. Indic languages, despite their substantial native speaker populations, remain significantly underrepresented in this progress.

To address this gap, we introduce **IndicSQuAD**, a comprehensive multi-lingual extractive QA dataset encompassing nine major Indic languages. This dataset is systematically derived from the widely used SQuAD dataset, ensuring a strong foundation for cross-lingual transfer and adaptation.

Building upon the methodology established with [MahaSQuAD](https://aclanthology.org/2023.icon-1.45/) for Marathi, our approach involves carefully adapting and extending translation techniques. This meticulous process prioritizes maintaining high linguistic fidelity and accurate answer-span alignment across the diverse grammatical structures and nuances of the included languages.

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

The dataset details and baseline results on monolingual and multilingual BERT models are provided in the <a href="https://arxiv.org/abs/2505.03688"> paper </a>.

## Getting Started

The IndicSQuAD dataset is publicly available at: [hugging-face](https://huggingface.co/datasets/l3cube-pune/IndicSQuAD) and [drive-link](https://drive.google.com/drive/folders/1GF47J0byaXPNfDhPrYyA-0d1KklZf87x?usp=sharing)

## HuggingFace models
| Language  | Model Link                                                                                                |
|-----------|-----------------------------------------------------------------------------------------------------------|
| Marathi   | [marathi-question-answering-squad-bert](https://huggingface.co/l3cube-pune/marathi-question-answering-squad-bert) |
| Hindi     | [hindi-question-answering-squad-bert](https://huggingface.co/l3cube-pune/hindi-question-answering-squad-bert)   |
| Bengali   | [bengali-question-answering-squad-bert](https://huggingface.co/l3cube-pune/bengali-question-answering-squad-bert) |
| Telugu    | [telugu-question-answering-squad-bert](https://huggingface.co/l3cube-pune/telugu-question-answering-squad-bert)   |
| Tamil     | [tamil-question-answering-squad-bert](https://huggingface.co/l3cube-pune/tamil-question-answering-squad-bert)   |
| Gujarati  | [gujarati-question-answering-squad-bert](https://huggingface.co/l3cube-pune/gujarati-question-answering-squad-bert) |
| Punjabi   | [punjabi-question-answering-squad-bert](https://huggingface.co/l3cube-pune/punjabi-question-answering-squad-bert)   |
| Kannada   | [kannada-question-answering-squad-bert](https://huggingface.co/l3cube-pune/kannada-question-answering-squad-bert)   |
| Oriya     | [oriya-question-answering-squad-bert](https://huggingface.co/l3cube-pune/oriya-question-answering-squad-bert)     |
| Malayalam | [malayalam-question-answering-squad-bert](https://huggingface.co/l3cube-pune/malayalam-question-answering-squad-bert) |

## Citation

If you use the IndicSQuAD dataset in your research, please cite the following papers:
```
@article{endait2025indicsquad,
  title={IndicSQuAD: A Comprehensive Multilingual Question Answering Dataset for Indic Languages},
  author={Endait, Sharvi and Ghatage, Ruturaj and Kulkarni, Aditya and Patil, Rajlaxmi and Joshi, Raviraj},
  journal={arXiv preprint arXiv:2505.03688},
  year={2025}
}
```

```
@inproceedings{ruturaj2023mahasquad,
  title={MahaSQuAD: Bridging Linguistic Divides in Marathi Question-Answering},
  author={Ruturaj, Ghatage and Ashutosh, Kulkarni Aditya and Rajlaxmi, Patil and Sharvi, Endait and Raviraj, Joshi},
  booktitle={Proceedings of the 20th International Conference on Natural Language Processing (ICON)},
  pages={497--505},
  year={2023}
}
```
