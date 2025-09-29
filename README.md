# Awesome Reverse Engineering of Language Models


This repository is the official collection of papers and resources for our survey: **"Towards Reverse Engineering of Language Models: A Survey"**. We aim to provide a comprehensive and up-to-date list of resources in the field of **LLM privacy** and **LLM reverse engineering**.

If you find our work helpful, please consider citing our paper and starring this repository ⭐\!

## 📜 Citation

If you find our survey or this repository useful in your research, please cite our paper:

```bibtex
@article{Ti2025Towards,
  title={Towards Reverse Engineering of Language Models: A Survey},
  author={Xinpeng Ti and Wentao Ye and Zhifang Zhang and Junbo Zhao and Chang Yao and Lei Feng and Haobo Wang},
  journal={[Journal or Conference Name, e.g., arXiv preprint arXiv:XXXX.XXXXX]},
  year={2025}
}
```

## 🌳 Taxonomy

Our taxonomy follows the structure of our paper, categorizing the reverse engineering of language models into three main areas: **Attack**, **Model Reconstruction**, and **Defense**.


## Table of Contents

  - [Attack](#attack)
      - [Data Recovery](https://www.google.com/search?q=%23-data-recovery)
          - [Training Data Extraction](https://www.google.com/search?q=%23-training-data-extraction)
          - [Input Reconstruction](https://www.google.com/search?q=%23-input-reconstruction)
          - [Membership Inference](https://www.google.com/search?q=%23-membership-inference)
          - [Property Inference](https://www.google.com/search?q=%23-property-inference)
      - [Model Reconstruction](https://www.google.com/search?q=%23-model-reconstruction)
          - [Parameter Extraction](https://www.google.com/search?q=%23-parameter-extraction)
          - [Function Imitation](https://www.google.com/search?q=%23-function-imitation)
          - [Structure Trace](https://www.google.com/search?q=%23-structure-trace)
  - [Defense](https://www.google.com/search?q=%23-defense)
      - [Preventive Defense](https://www.google.com/search?q=%23-preventive-defense)
      - [Detective Defense](https://www.google.com/search?q=%23-detective-defense)

-----
## Attack

### 📊 Data Recovery

#### ↳ Training Data Extraction

  * [USENIX Security 2021] **Extracting Training Data from Large Language Models.**
      * *Nicholas Carlini, Florian Tramer, Eric Wallace, Matthew Jagielski, Ariel Herbert-Voss, et al.*
      * [[Paper]](https://www.usenix.org/conference/usenixsecurity21/presentation/carlini-extracting) [[Code]](https://www.google.com/search?q=https://github.com/google-research/lm-extraction)
  * [ICLR 2024] **Teach LLMs to Phish: Stealing Private Information from Language Models.**
      * *Ashwinee Panda, Christopher A. Choquette-Choo, Zhengming Zhang, Yaoqing Yang, and Prateek Mittal.*
      * [[Paper]](https://www.google.com/search?q=https://openreview.net/forum%3Fid%3DvHkSMMp22J)
  * [arXiv 2024] **Special Characters Attack: Toward Scalable Training Data Extraction from Large Language Models.**
      * *Yang Bai, Ge Pei, Jindong Gu, Yong Yang, and Xingjun Ma.*
      * [[Paper]](https://arxiv.org/abs/2405.05990)
  * *... (Please continue adding from your paper's references)*

#### ↳ Input Reconstruction

  * [arXiv 2022] **Ignore Previous Prompt: Attack Techniques for Language Models.**
      * *Fábio Perez and Ian Ribeiro.*
      * [[Paper]](https://arxiv.org/abs/2211.09527) [[Code]](https://www.google.com/search?q=https://github.com/agencyenterprise/prompt-injection)
  * [ICLR 2024] **Language Model Inversion.**
      * *John X. Morris, Wenting Zhao, Justin T. Chiu, Vitaly Shmatikov, and Alexander M. Rush.*
      * [[Paper]](https://www.google.com/search?q=https://openreview.net/forum%3Fid%3DyOTB33p2c3) [[Code]](https://www.google.com/search?q=https://github.com/jxmorris12/language-model-inversion)
  * *... (Please continue adding from your paper's references)*

#### ↳ Membership Inference

  * [S\&P 2017] **Membership Inference Attacks Against Machine Learning Models.**
      * *Reza Shokri, Marco Stronati, Congzheng Song, and Vitaly Shmatikov.*
      * [[Paper]](https://ieeexplore.ieee.org/document/7958568)
  * [ACL 2023] **Membership Inference Attacks against Language Models via Neighbourhood Comparison.**
      * *Justus Mattern, Fatemehsadat Mireshghallah, Zhijing Jin, Bernhard Schölkopf, et al.*
      * [[Paper]](https://aclanthology.org/2023.findings-acl.712/) [[Code]](https://www.google.com/search?q=https://github.com/justusmattern/lm-mia-neighborhood)
  * *... (Please continue adding from your paper's references)*

#### ↳ Property Inference

  * [arXiv 2024] **Data Mixture Inference: What do BPE Tokenizers Reveal about their Training Data?**
      * *Jonathan Hayase, Alisa Liu, Yejin Choi, Sewoong Oh, and Noah A. Smith.*
      * [[Paper]](https://arxiv.org/abs/2407.16607)
  * *... (Please continue adding from your paper's references)*

### 🏗️ Model Reconstruction

#### ↳ Parameter Extraction

  * [ICML 2024] **Stealing Part of a Production Language Model.**
      * *Nicholas Carlini, Daniel Paleka, Krishnamurthy Dj Dvijotham, Thomas Steinke, et al.*
      * [[Paper]](https://www.google.com/search?q=https://openreview.net/forum%3Fid%3DgD38aI2Jhb) [[Code]](https://www.google.com/search?q=https://github.com/google-research/llm-stealing)
  * *... (Please continue adding from your paper's references)*

#### ↳ Function Imitation

  * [CVPR 2019] **Knockoff Nets: Stealing Functionality of Black-Box Models.**
      * *Tribhuvanesh Orekondy, Bernt Schiele, and Mario Fritz.*
      * [[Paper]](https://openaccess.thecvf.com/content_CVPR_2019/html/Orekondy_Knockoff_Nets_Stealing_Functionality_of_Black-Box_Models_CVPR_2019_paper.html)
  * [ICLR 2020] **Thieves on Sesame Street\! Model Extraction of BERT-based APIs.**
      * *Kalpesh Krishna, Gaurav Singh Tomar, Ankur P. Parikh, Nicolas Papernot, and Mohit Iyyer.*
      * [[Paper]](https://www.google.com/search?q=https://openreview.net/forum%3Fid%3DBJe-b34VDr) [[Code]](https://www.google.com/search?q=https://github.com/kalpeshk20/Thieves_on_Sesame_Street)
  * *... (Please continue adding from your paper's references)*

#### ↳ Structure Trace

  * *... (Please continue adding from your paper's references)*

-----

## 🛡️ Defense

### Preventive Defense

  * [ICLR 2018] **Ensemble Adversarial Training: Attacks and Defenses.**
      * *Florian Tramèr, Alexey Kurakin, Nicolas Papernot, Ian J. Goodfellow, Dan Boneh, and Patrick D. McDaniel.*
      * [[Paper]](https://www.google.com/search?q=https://openreview.net/forum%3Fid%3Drk-fX2lAZ)
  * *... (Please continue adding from your paper's references)*

### Detective Defense

  * [ICML 2023] **A Watermark for Large Language Models.**
      * *John Kirchenbauer, Jonas Geiping, Yuxin Wen, Jonathan Katz, Ian Miers, and Tom Goldstein.*
      * [[Paper]](https://proceedings.mlr.press/v202/kirchenbauer23a.html) [[Code]](https://github.com/jwkirchenbauer/lm-watermarking)
  * [NeurIPS 2024] **Huref: HUman-REadable Fingerprint for Large Language Models.**
      * *Boyi Zeng, Lizheng Wang, Yuncong Hu, Yi Xu, Chenghu Zhou, et al.*
      * [[Paper]](https://www.google.com/search?q=https://openreview.net/forum%3Fid%3DjT62jG5e78) [[Code]](https://www.google.com/search?q=https://github.com/byzeng/HUREF)
  * *... (Please continue adding from your paper's references)*

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

## Maintainers

  * [Xinpeng Ti](https://www.google.com/search?q=%5BYour_GitHub_Profile_Link%5D)
  * [Wentao Ye](https://www.google.com/search?q=%5BYour_GitHub_Profile_Link%5D)
  * [Zhifang Zhang](https://www.google.com/search?q=%5BYour_GitHub_Profile_Link%5D)

## License

This project is licensed under the [MIT License](https://www.google.com/search?q=LICENSE).
