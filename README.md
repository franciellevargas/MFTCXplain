[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7681302.svg)](https://doi.org/10.5281/zenodo.10794024)

<h2 align="center"> MFTCXaplin: A Multilingual Benchmark Dataset for Evaluating the Moral Reasoning of Large Language Models. </h2>  

</br>
<p align="justify"> Ensuring the moral reasoning capabilities of Large Language Models (LLMs) is a growing concern as these systems are used in socially sensitive tasks. Nevertheless, current evaluation benchmarks present two major shortcomings: a lack of annotations that justify moral classifications, which limits transparency and interpretability; and a predominant focus on English, which constrains the assessment of moral
reasoning across diverse cultural settings. To fill these relevant gaps, we introduce MFTCXplain, a multilingual benchmark dataset for evaluating the moral reasoning of LLMs via multi-hop hate speech explanations using the Moral Foundations Theory. Our results show a misalignment between LLM outputs and human annotations in moral reasoning tasks. While LLMs perform well in hate speech detection (F1 up to 0.836), their ability to predict moral sentiments is notably weak (F1 < 0.35). Furthermore, rationale alignment remains limited mainly in underrepresented languages. Our findings show the limited capacity of current LLMs to internalize and reflect human moral reasoning. </p>
  
<p align="justify"> This repository contains the MFTCXplain dataset that comprises 3,000 tweets across Portuguese, Italian, Persian, and English, annotated with binary hate speech labels, moral categories, and text span-level rationales. Below is an example annotation for the Moral Foundations Theory (MFT) categories.</p>

 ![SSC-logo-200x71](https://github.com/franciellevargas/franciellevargas.github.io/blob/b120e8a4b589cded34bcac18819e10dc493c4691/img/MFT-ex.png)


### MFTCXplain Statistics
<div align="center">

| Language   | Hate Speech | Non-Hate Speech | Total |
|----------- |-------------|-----------------|-------|
| English (EN)   | 310 | 394 | 704 |
| Italian (IT)   | 300 | 321 | 621 |
| Persian (PE)   | 302 | 306 | 608 |
| Portuguese (PO) | 541 | 526 | 1,067 |
| **All Languages** | **1,453** | **1,547** | **3,000** |


![SSC-logo-200x71](https://github.com/franciellevargas/franciellevargas.github.io/blob/45c7c339a940bc8020a69b3ec9d3b27a5b2190aa/img/mft-cross-lang.png)

</div>

</br>
If you have any questions, feel free to contact me at: franciellealvargas@gmail.com.

</br>


<h2 align="left"> CITING / BIBTEX </h2>

Please cite our paper if you use our dataset:
```bibtex
@inproceedings{trager-etal-2025-mftcxplain,
    title = "{MFTCX}plain: A Multilingual Benchmark Dataset for Evaluating the Moral Reasoning of {LLM}s through Multi-hop Hate Speech Explanation",
    author = "Trager, Jackson  and
      Vargas, Francielle  and
      Alves, Diego  and
      Guida, Matteo  and
      Ngueajio, Mikel K.  and
      Agrawal, Ameeta  and
      Daryani, Yalda  and
      Malekabadi, Farzan Karimi  and
      Plaza-del-Arco, Flor Miriam",
    editor = "Christodoulopoulos, Christos  and
      Chakraborty, Tanmoy  and
      Rose, Carolyn  and
      Peng, Violet",
    booktitle = "Findings of the Association for Computational Linguistics: EMNLP 2025",
    month = nov,
    year = "2025",
    address = "Suzhou, China",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.findings-emnlp.851/",
    doi = "10.18653/v1/2025.findings-emnlp.851",
    pages = "15709--15740",
    ISBN = "979-8-89176-335-7",
    abstract = "Ensuring the moral reasoning capabilities of Large Language Models (LLMs) is a growing concern as these systems are used in socially sensitive tasks. Nevertheless, current evaluation benchmarks present two major shortcomings: a lack of annotations that justify moral classifications, which limits transparency and interpretability; and a predominant focus on English, which constrains the assessment of moral reasoning across diverse cultural settings. In this paper, we introduce MFTCXplain, a multilingual benchmark dataset for evaluating the moral reasoning of LLMs via multi-hop hate speech explanations using the Moral Foundations Theory. MFTCXplain comprises 3,000 tweets across Portuguese, Italian, Persian, and English, annotated with binary hate speech labels, moral categories, and text span-level rationales. Our results show a misalignment between LLM outputs and human annotations in moral reasoning tasks. While LLMs perform well in hate speech detection (F1 up to 0.836), their ability to predict moral sentiments is notably weak (F1 {\ensuremath{<}} 0.35). Furthermore, rationale alignment remains limited mainly in underrepresented languages. Our findings show the limited capacity of current LLMs to internalize and reflect human moral reasoning."
}

```


<br></br>

<h2 align="left"> FUNDING </h2>

![SSC-logo-300x171](https://github.com/franciellevargas/franciellevargas.github.io/blob/fc03a6672ab2937e413e4508a5061abed4a66098/img/google-logo-menor.png)
![SSC-logo-300x171](https://github.com/franciellevargas/franciellevargas.github.io/blob/fc03a6672ab2937e413e4508a5061abed4a66098/img/fapesp.jpg)

</br>
