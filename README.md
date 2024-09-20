# DiaHalu
This is the repository for the paper **DiaHalu: A Dialogue-level Hallucination Evaluation Benchmark for Large Language Models** (EMNLP2024findings).
DiaHalu is the first dedicated dialogue-level hallucination evaluation benchmark for hallucination detection in LLMs.

[[ARXIV]](https://arxiv.org/abs/2403.00896)

# Overview
DiaHalu is a dialogue-level hallucination benchmark, consisting of both factuality and faithfulness hallucination, naturally generated by two API Keys of ChatGPT3.5s or GPT4s.
Then it is annotated by professional experts in academia and industry.
This benchmark covers four dialogue domains and five hallucination subtypes, extending from factuality and faithfulness hallucination.

![image](https://github.com/141forever/DiaHalu/blob/main/figures/overview.png)

The four dialogue domains are knowledge-grounded, task-oriented, chit-chat and reasoning.
About the five hallucination subtypes: Non-factual denotes factuality hallucination. Icoherence, Irrelevance, and Overreliance are extended from faithfulness hallucination, we also add reasoning errors as a kind of hallucination.


# Versions
The 1st version (corresponding to arxiv v1) can be called Diahalu_V1.xlsx. ChatGPT3.5 generates the 748 samples.

The 2nd version (corresponding to arxiv v2) of DiaHalu can be called DiaHalu_V2.xlsx. In this version, we augment the dataset from 748 to 1103 samples. 
 GPT4 generates the latest 355 samples.

# Citation
If you think this benchmark helps, welcome to cite our paper.
```
@article{DBLP:journals/corr/abs-2403-00896,
  author       = {Kedi Chen and
                  Qin Chen and
                  Jie Zhou and
                  Yishen He and
                  Liang He},
  title        = {DiaHalu: {A} Dialogue-level Hallucination Evaluation Benchmark for
                  Large Language Models},
  journal      = {CoRR},
  volume       = {abs/2403.00896},
  year         = {2024},
  url          = {https://doi.org/10.48550/arXiv.2403.00896},
  doi          = {10.48550/ARXIV.2403.00896},
  eprinttype    = {arXiv},
  eprint       = {2403.00896},
  timestamp    = {Thu, 13 Jun 2024 21:48:06 +0200},
  biburl       = {https://dblp.org/rec/journals/corr/abs-2403-00896.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}
```
