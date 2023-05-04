# A Benchmark Study of Contrastive Learning for Arabic Social Meaning


This repo contains the codes for [A Benchmark Study of Contrastive Learning for Arabic Social Meaning](https://aclanthology.org/2022.wanlp-1.7/).

We provided jupyter notebook implementation on a sample dataset for each method discussed in the paper.


## 1. Requirements:

Please run the following commands:</br>
```diff
pip install numpy
pip install pandas
pip install torch
pip install sklearn
pip install tqdm
pip install transformers
pip install datasets
pip install nltk
pip install spacy
pip install matplotlib
```


## 2. Methods:

1. Supervised Contrastive Learning (SCL): [[Code]](SCL.ipynb)
2. Contrastive Adversarial Training (CAT): [[Code]](CAT.ipynb)
3. Token-level Adversarial Contrastive Training (TACT): [[Code]](TACT.ipynb)
4. Label-Aware Contrastive Loss (LCL): [[Code]](LCL.ipynb)
5. Token Adversarial LCL (TLCL): [[Code]](TLCL.ipynb)


## 3. Citation

```diff
@inproceedings{khondaker-etal-2022-benchmark,
    title = "A Benchmark Study of Contrastive Learning for {A}rabic Social Meaning",
    author = "Khondaker, Md Tawkat Islam  and
      Nagoudi, El Moatez Billah  and
      Elmadany, AbdelRahim  and
      Abdul-Mageed, Muhammad  and
      Lakshmanan, V.S., Laks",
    booktitle = "Proceedings of the The Seventh Arabic Natural Language Processing Workshop (WANLP)",
    month = dec,
    year = "2022",
    address = "Abu Dhabi, United Arab Emirates (Hybrid)",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.wanlp-1.7",
    pages = "63--75",
}
```

## 4. Contact

If you have any queries, please feel free to contact at: tawkat@cs.ubc.ca
