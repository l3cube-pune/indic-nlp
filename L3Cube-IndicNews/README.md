# L3Cube-IndicNews

L3Cube-IndicNews, is a multilingual text classification corpus aimed at curating a high-quality dataset for Indian regional languages, with a specific focus on news headlines and articles. We have centered our work on 11 prominent Indic languages, including Hindi, Bengali, Marathi, Telugu, Tamil, Gujarati, Kannada, Odia, Malayalam, Punjabi and English. Each of these news datasets comprises
10 or more classes of news articles. <br> <br> L3Cube-IndicNews offers 3 distinct datasets tailored to handle different document lengths that are classified as: Short Headlines Classification (SHC) dataset containing the news headline and news category, Long Document Classification (LDC) dataset containing the whole news article and the news category, and Long Paragraph Classification (LPC) containing sub-articles of the news and the news category. We maintain consistent labeling across all 3 datasets for in-depth length-based analysis. <br>
Dataset details and baseline experiments are described in our <a href="https://arxiv.org/abs/2401.02254"> paper </a>.
The model trained on the Hindi IndicNews corpus is shared <a href="https://huggingface.co/l3cube-pune/hindi-topic-all-doc"> here </a>. Links of models for different languages can be found on the same page.

## Citing
```
@article{mirashi2024l3cube,
  title={L3Cube-IndicNews: News-based Short Text and Long Document Classification Datasets in Indic Languages},
  author={Mirashi, Aishwarya and Sonavane, Srushti and Lingayat, Purva and Padhiyar, Tejas and Joshi, Raviraj},
  journal={arXiv preprint arXiv:2401.02254},
  year={2024}
}
```
