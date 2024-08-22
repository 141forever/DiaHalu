# DiaHalu
This is the repository for the paper **DiaHalu: A Dialogue-level Hallucination Evaluation Benchmark for Large Language Models**.
DiaHalu is the first dedicated dialogue-level hallucination evaluation benchmark for hallucination detection in LLMs.

[[ARXIV]](https://arxiv.org/abs/2403.00896)

# Oveview
DiaHalu is a dialogue-level hallucination benchmark, consisting of both factuality and faithfulness hallucination, naturally generated by two API Keys of ChatGPT3.5s or GPT4s.
Then it is annotated by professional experts in academia and industry.
This benchmark covers four dialogue domains and five hallucination subtypes, extending from factuality and faithfulness hallucination.

![image](https://github.com/141forever/DiaHalu/blob/main/figures/overview.png)

The four dialogue domains are knowledge-grounded, task-oriented, chit-chat and reasoning.
About the five hallucination subtypes: Non-factual denotes factuality hallucination, Icoherence, Irrelevance, and Overreliance are extended from faithfulness hallucination, we also add reasoning errors as a kind of hallucination.


# Versions
The 1st version (corresponding to arxiv v1) can be called Diahalu_V1.xlsx. ChatGPT3.5 generates the 748 samples.

The 2nd version (corresponding to arxiv v2) of DiaHalu can be called DiaHalu_V2.xlsx. In this version, we augment the dataset from 748 to 1103 samples. 
 GPT4 generates the latest 355 samples.

