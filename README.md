# Arabic-LLM-Benchmarks
This repo provides a list of existing Arabic benchmarks and evaluation efforts that were reported in this [work](https://arxiv.org/abs/2507.15850)

## Table of Contents
* [Abstract](#abstract)
* [citation](#citations)
* [Taxonomy](#taxonmoy)
    1. [STEM & Domain Knowledge](#STEM_DOM)
        - [STEM](#STEM)
        - [Domain Knowledge](#DOM)
    3. [NLP Tasks](#NLP)
    4. [Culture & Dialects](#cult)
    5. [Specific-Targets](#target)


# <a name='abstract'></a> Abstract
This survey provides the first systematic review of Arabic LLM benchmarks, analyzing 40 evaluation frameworks across NLP tasks, knowledge domains, cultural understanding, and specialized capabilities. We propose a taxonomy organizing benchmarks into four categories: Knowledge and STEM, NLP Tasks, Culture and Dialects, and Target-Specific evaluations. Our analysis reveals significant progress in benchmark diversity while identifying critical gaps: limited temporal evaluation, insufficient multi-turn dialogue assessment, and cultural misalignment in translated datasets. We examine three primary approaches: native collection, translation, and synthetic generation discussing their trade-offs regarding authenticity, scale, and cost. This work serves as a comprehensive reference for Arabic NLP researchers, providing insights into benchmark methodologies, reproducibility standards, and evaluation metrics while offering recommendations for future development.

#  <a name='citations'></a>Citation

```
@misc{alarabic bench,
      title={Evaluating Arabic Large Language Models: A Survey of Benchmarks, Methods, and Gaps}, 
      author={author names},
      year={2025},
      eprint={2501.02189},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2501.02189}, 
}
```

#  <a name='taxonmoy'></a>Taxonmoy

##  <a name='STEM_DOM'></a>STEM & Domain Knowledge
###  <a name='STEM'></a>STEM
| Paper/Benchmark | Links  |
|----------------|---------|
|Measuring Massive Multitask Language Understanding| [[paper](https://arxiv.org/abs/2009.03300)] [[data](https://huggingface.co/datasets/MBZUAI/ArabicMMLU)] [[lighteval](https://github.com/huggingface/lighteval/blob/main/community_tasks/arabic_evals.py)]|
|EXAMS: A Multi-Subject High School Examinations Dataset for Cross-Lingual and Multilingual Question Answering| [[paper](https://arxiv.org/abs/2011.03080)] [[data](https://huggingface.co/datasets/OALL/Arabic_EXAMS)] [[lighteval](https://github.com/huggingface/lighteval/blob/main/community_tasks/arabic_evals.py)]|
|ArabicMMLU: Assessing Massive Multitask Language Understanding in Arabic| [[paper](https://arxiv.org/abs/2402.12840)] [[data](https://huggingface.co/datasets/MBZUAI/ArabicMMLU)] [[repo](https://github.com/mbzuai-nlp/ArabicMMLU)]|
|A bilingual benchmark for evaluating large language models | [[paper](https://peerj.com/articles/cs-1893/)]|
|The Qiyas Benchmark: Measuring ChatGPT Mathematical and Language Understanding in Arabic | [[paper](https://arxiv.org/abs/2407.00146)]|
|GATmath and GATLc: Comprehensive benchmarks for evaluating Arabic large language models| [[paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0329129#:~:text=We%20created%20the%20GATmath%2C%20a,benchmark%20dataset%20named%20the%20GATLc.)] [[data](https://www.kaggle.com/datasets/c1adf50de06a2d0ecce0141840f602d4de7d838e81224d9a7fc2af4f357e216c)] |
|3LM: Bridging Arabic, STEM, and Code through Benchmarking| [[paper](https://arxiv.org/abs/2507.15850)] [[data](https://huggingface.co/collections/tiiuae/3lm-arabic-benchmark-687de9629072871e702d35e1)] [[repo](https://github.com/tiiuae/3LM-benchmark)] |
###  <a name='DOM'></a>Domain Knowledge
| Paper/Benchmark | Links  |
|----------------|---------|
##  <a name='NLP'></a>NLP Tasks
##  <a name='cult'></a> Culture & Dialects
##  <a name='target'></a> Specific-Targets
