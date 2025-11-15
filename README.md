[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7681302.svg)](https://doi.org/10.5281/zenodo.10794024)

<h2 align="center"> MFTCXaplin: A Multilingual Benchmark Dataset for Evaluating the Moral Reasoning of Large Language Models. </h2>  

</br>
<p align="justify"> Ensuring the moral reasoning capabilities of Large Language Models (LLMs) is a growing concern as these systems are used in socially sensitive tasks. Nevertheless, current evaluation benchmarks present two major shortcomings: a lack of annotations that justify moral classifications, which limits transparency and interpretability; and a predominant focus on English, which constrains the assessment of moral
reasoning across diverse cultural settings. To fill these relevant gaps, we introduce MFTCXplain, a multilingual benchmark dataset for evaluating the moral reasoning of LLMs via multi-hop hate speech explanations using the Moral Foundations Theory. Our results show a misalignment between LLM outputs and human annotations in moral reasoning tasks. While LLMs perform well in hate speech detection (F1 up to 0.836), their ability to predict moral sentiments is notably weak (F1 < 0.35). Furthermore, rationale alignment remains limited mainly in underrepresented languages. Our findings show the limited capacity of current LLMs to internalize and reflect human moral reasoning. </p>>
  
<p align="justify"> This repository contains the MFTCXplain dataset that comprises 3,000 tweets across Portuguese, Italian, Persian, and English, annotated with binary hate speech labels, moral categories, and text span-level rationales.

 ![SSC-logo-200x71](https://github.com/franciellevargas/franciellevargas.github.io/blob/d9f0a61b591820083c14691ffac85db460dee4d5/img/hatebr_annotation.png)


### HateBR 
<div align="center">

| class         | label | total  |
|--------------|------- |--------|
| Portuguese    |      | 3,500  |
| Italian       | 0    | 3,500  |
| Persian       | 0    | 3,500  |
| English       | 0    | 3,500  |
| **Total**    |       | **7,000** |

</div>

### HateBRXplain 

<div align="center">

| class         | label | rationales                     | total  |
|--------------|-------|--------------------------------|--------|
| offensive    | 1     | human-annotated rationales    | 3,500  |
| non-offensive | 0    | null                          | 3,500  |
| **Total**    |       |                                | **7,000** |

</div>


</br>

In addition, we also provide baseline machine learning results for both tasks: offensive language and hate speech detection. The best-obtained models are available here in .pkl files. File names are organized as `[classification (offensive or hate)_representation (ngram or tfidf)_algorithms (nb, svm, mlp or lr)]`. For example, the file *offensive_tfidf_svm.pkl* presents the model of offensive detection with tf-idf representation using the support vector machine algorithm.

</br>


<h2 align="left"> CITING / BIBTEX </h2>

Please cite our paper if you use our dataset:
```bibtex
@inproceedings{vargas-etal-2022-hatebr,
    title = "{H}ate{BR}: A Large Expert Annotated Corpus of {B}razilian {I}nstagram Comments for Offensive Language and Hate Speech Detection",
    author = "Vargas, Francielle  and
      Carvalho, Isabelle  and
      Rodrigues de G{\'o}es, Fabiana  and
      Pardo, Thiago  and
      Benevenuto, Fabr{\'\i}cio",
    booktitle = "Proceedings of the 13th Conference on Language Resources and Evaluation (LREC 2022)",
    year = "2022",
    address = "Marseille, France",
    publisher = "European Language Resources Association",
    url = "https://aclanthology.org/2022.lrec-1.777",
    pages = "7174--7183",
    }
```

```bibtex
 @article{Vargas_Carvalho_Pardo_Benevenuto_2024, 
 author={Vargas, Francielle and Carvalho, Isabelle and Pardo, Thiago A. S. and Benevenuto, Fabrício},
 title={Context-aware and expert data resources for Brazilian Portuguese hate speech detection}, 
 DOI={10.1017/nlp.2024.18}, 
 journal={Natural Language Processing},  
 year={2024}, 
 pages={435-456},
 volume{31},
 number={2},
 url={https://www.cambridge.org/core/journals/natural-language-processing/article/contextaware-and-expert-data-resources-for-brazilian-portuguese-hate-speech-detection/7D9019ED5471CD16E320EBED06A6E923#},
 }
```


```bibtex
@inproceedings{salles-etal-2025-hatebrxplain,
    title = "{H}ate{BRX}plain: A Benchmark Dataset with Human-Annotated Rationales for Explainable Hate Speech Detection in {B}razilian {P}ortuguese",
    author = "Salles, Isadora  and
      Vargas, Francielle  and
      Benevenuto, Fabr{\'i}cio",
    editor = "Rambow, Owen  and
      Wanner, Leo  and
      Apidianaki, Marianna  and
      Al-Khalifa, Hend  and
      Eugenio, Barbara Di  and
      Schockaert, Steven",
    booktitle = "Proceedings of the 31st International Conference on Computational Linguistics (COLING 2025)",
    year = "2025",
    address = "Abu Dhabi, UAE",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.coling-main.446/",
    pages = "6659--6669",
}
```

<br></br>

<h2 align="left"> FUNDING </h2>

![SSC-logo-300x171](https://github.com/franciellevargas/franciellevargas.github.io/blob/fc03a6672ab2937e413e4508a5061abed4a66098/img/google-logo-menor.png)
![SSC-logo-300x171](https://github.com/franciellevargas/franciellevargas.github.io/blob/fc03a6672ab2937e413e4508a5061abed4a66098/img/fapesp.jpg)

</br>
