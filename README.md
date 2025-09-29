# Awesome Reverse Engineering of LLMs 🤖


This repository is the official collection of papers and resources for our survey: **"Towards Reverse Engineering of Language Models: A Survey"**. We aim to provide a comprehensive and up-to-date list of resources in the field of **_LLM privacy_** or **_LLM reverse engineering_**.

If you find our work helpful, please consider citing our paper and starring this repository ⭐\!

## 📜 Citation

If you find our survey or this repository useful in your research, please cite our paper:

```bibtex
@article{Ti2025Towards,
  title={Towards Reverse Engineering of Language Models: A Survey},
  author={Xinpeng Ti and Wentao Ye and Zhifang Zhang and Junbo Zhao and Chang Yao and Lei Feng and Haobo Wang},
  journal={EMNLP},
  year={2025}
}
```

## 🚩 Our GOAL
With the continuous development of language models and the widespread availability of various types of accessible interfaces, LLMs have been applied to an increasing number of fields. However, due to the vast amounts of data and computational resources required for model development, _protecting the model's parameters and training data has become an urgent and crucial concern_. Due to the revolutionary training and application paradigms of LLMs, many new attacks on language models have emerged in recent years. In this paper, we define these attacks as _reverse engineering_ (RE) techniques on LMs and aim to provide an in-depth analysis of reverse engineering of language models. We illustrate various methods of reverse engineering applied to different aspects of a model, while also providing an introduction to existing protective strategies. On the one hand, it demonstrates the vulnerabilities of even black box models to different types of attacks; on the other hand, it offers a more holistic perspective for the development of new protective strategies for models.

## 🌳 Taxonomy

Our taxonomy follows the structure of our paper, categorizing the reverse engineering of language models into three main areas: **Attack**, **Model Reconstruction**, and **Defense**.
<img width="1345" height="1132" alt="intro2" src="https://github.com/user-attachments/assets/f63c5d3e-cb47-4b1f-9476-ea5def37cc9c" />


## Table of Contents

  - [Attack](#attack)
      - [Data Recovery](#data-recovery)
          - [Training Data Extraction](training-data-extraction)
          - [Input Reconstruction](input-reconstruction)
          - [Membership Inference](membership-inference)
          - [Property Inference](#property-inference)
      - [Model Reconstruction](#model-reconstruction)
          - [Parameter Extraction](#parameter-extraction)
          - [Function Imitation](#function-imitation)
          - [Structure Trace](#structure-trace)
  - [Defense](#defense)
      - [Preventive Defense](#preventive-defense)
      - [Detective Defense](#detective-defense)

-----
## Attack

### Data Recovery

#### Training Data Extraction

  * [USENIX Security 2021] **Extracting Training Data from Large Language Models.** [[Paper]](https://www.usenix.org/conference/usenixsecurity21/presentation/carlini-extracting)
      * *Nicholas Carlini, Florian Tramer, Eric Wallace, Matthew Jagielski, Ariel Herbert-Voss, et al.*
      
  * [ICLR 2024] **Teach LLMs to Phish: Stealing Private Information from Language Models.**[[Paper]](https://www.usenix.org/conference/usenixsecurity21/presentation/carlini-extracting)
      * *Ashwinee Panda, Christopher A. Choquette-Choo, Zhengming Zhang, Yaoqing Yang, and Prateek Mittal.*
  * [arXiv 2024] **Special Characters Attack: Toward Scalable Training Data Extraction from Large Language Models.**[[Paper]](https://www.usenix.org/conference/usenixsecurity21/presentation/carlini-extracting)
      * *Yang Bai, Ge Pei, Jindong Gu, Yong Yang, and Xingjun Ma.*

#### Input Reconstruction

  * [arXiv 2022] **Ignore Previous Prompt: Attack Techniques for Language Models.**[[Paper]](https://www.usenix.org/conference/usenixsecurity21/presentation/carlini-extracting)
      * *Fábio Perez and Ian Ribeiro.*
  * [ICLR 2024] **Language Model Inversion.**[[Paper]](https://www.usenix.org/conference/usenixsecurity21/presentation/carlini-extracting)
      * *John X. Morris, Wenting Zhao, Justin T. Chiu, Vitaly Shmatikov, and Alexander M. Rush.*

#### Membership Inference

  * [S\&P 2017] **Membership Inference Attacks Against Machine Learning Models.**[[Paper]](https://www.usenix.org/conference/usenixsecurity21/presentation/carlini-extracting)
      * *Reza Shokri, Marco Stronati, Congzheng Song, and Vitaly Shmatikov.*
  * [ACL 2023] **Membership Inference Attacks against Language Models via Neighbourhood Comparison.**[[Paper]](https://www.usenix.org/conference/usenixsecurity21/presentation/carlini-extracting)
      * *Justus Mattern, Fatemehsadat Mireshghallah, Zhijing Jin, Bernhard Schölkopf, et al.*

#### Property Inference

  * [arXiv 2024] **Data Mixture Inference: What do BPE Tokenizers Reveal about their Training Data?**[[Paper]](https://www.usenix.org/conference/usenixsecurity21/presentation/carlini-extracting)
      * *Jonathan Hayase, Alisa Liu, Yejin Choi, Sewoong Oh, and Noah A. Smith.*

### Model Reconstruction

#### Parameter Extraction

  * [ICML 2024] **Stealing Part of a Production Language Model.**[[Paper]](https://www.usenix.org/conference/usenixsecurity21/presentation/carlini-extracting)
      * *Nicholas Carlini, Daniel Paleka, Krishnamurthy Dj Dvijotham, Thomas Steinke, et al.*

#### Function Imitation

  * [CVPR 2019] **Knockoff Nets: Stealing Functionality of Black-Box Models.**[[Paper]](https://www.usenix.org/conference/usenixsecurity21/presentation/carlini-extracting)
      * *Tribhuvanesh Orekondy, Bernt Schiele, and Mario Fritz.*
  * [ICLR 2020] **Thieves on Sesame Street\! Model Extraction of BERT-based APIs.**[[Paper]](https://www.usenix.org/conference/usenixsecurity21/presentation/carlini-extracting)
      * *Kalpesh Krishna, Gaurav Singh Tomar, Ankur P. Parikh, Nicolas Papernot, and Mohit Iyyer.*

#### Structure Trace

  * *... (Please continue adding from your paper's references)*

-----

## Defense

### Preventive Defense

  * [ICLR 2018] **Ensemble Adversarial Training: Attacks and Defenses.**[[Paper]](https://www.usenix.org/conference/usenixsecurity21/presentation/carlini-extracting)
      * *Florian Tramèr, Alexey Kurakin, Nicolas Papernot, Ian J. Goodfellow, Dan Boneh, and Patrick D. McDaniel.*
  * *... (Please continue adding from your paper's references)*

### Detective Defense

  * [ICML 2023] **A Watermark for Large Language Models.**[[Paper]](https://www.usenix.org/conference/usenixsecurity21/presentation/carlini-extracting)
      * *John Kirchenbauer, Jonas Geiping, Yuxin Wen, Jonathan Katz, Ian Miers, and Tom Goldstein.*
  * [NeurIPS 2024] **Huref: HUman-REadable Fingerprint for Large Language Models.**[[Paper]](https://www.usenix.org/conference/usenixsecurity21/presentation/carlini-extracting)
      * *Boyi Zeng, Lizheng Wang, Yuncong Hu, Yi Xu, Chenghu Zhou, et al.*

-----

## 🤝 Contributing

Contributions are welcome\! If you would like to add or update resources on this list, please follow these steps:

1.  **Fork** this repository.
2.  Create a new branch (`git checkout -b your-feature-branch`).
3.  Add your changes to the appropriate section, maintaining the existing format.
4.  Commit your changes (`git commit -m 'Add some feature'`).
5.  **Push** to your branch (`git push origin your-feature-branch`).
6.  Create a **Pull Request**.

We will review and merge your contributions as quickly as possible.

## License

This project is licensed under the [MIT License](https://www.google.com/search?q=LICENSE).
