# STRR

This is the official repository for our paper, titled ["Beyond Fertility: Analyzing STRR as a Metric for Multilingual Tokenization Evaluation,"](https://arxiv.org/abs/2510.09947) published at the [NeurIPS 2025 Workshop](https://sites.google.com/view/llm-eval-workshop/home) on Evaluating the Evolving LLM Lifecycle: Benchmarks, Emergent Abilities, and Scaling.


## Abstract

> Tokenization is a crucial but under-evaluated step in large language models (LLMs). The standard metric, fertility (the average number of tokens per word), captures compression efficiency but obscures how vocabularies are allocated across languages and domains. We analyze six widely used tokenizers across seven languages and two domains, finding stable fertility for English, high fertility for Chinese, and little domain sensitivity. To address fertility's blind spots, we propose the Single Token Retention Rate (STRR), which measures the proportion of words preserved as single tokens. STRR reveals systematic prioritization of English, strong support for Chinese, and fragmentation in Hindi, offering an interpretable view of cross-lingual fairness. Our results show that STRR complements fertility and provides practical guidance for designing more equitable multilingual tokenizers.


---

## Citation Information

If you use any of the resources or it's relevant to your work, please cite our [NeurIPS 2025 Workshop paper](https://arxiv.org/abs/2510.09947). 

```
@misc{nayeem2025fertilityanalyzingstrrmetric,
      title={Beyond Fertility: Analyzing STRR as a Metric for Multilingual Tokenization Evaluation}, 
      author={Mir Tafseer Nayeem and Sawsan Alqahtani and Md Tahmid Rahman Laskar and Tasnim Mohiuddin and M Saiful Bari},
      year={2025},
      eprint={2510.09947},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2510.09947}, 
}
```