# SLIGHT

Repository for paper: 

[**Rethinking Offensive Text Detection as a Multi-Hop Reasoning Problem**](https://arxiv.org/abs/2204.10521), by Qiang Zhang, Jason Naradowsky and Yusuke Miyao.

## Abstract
We introduce the task of implicit offensive text detection in dialogues, where a statement may have either an offensive or non-offensive interpretation, depending on the listener and context. We argue that reasoning is crucial for understanding this broader class of offensive utterances, and release SLIGHT, a dataset to support research on this task.  Experiments using the data show that state-of-the-art methods of offense detection perform poorly when asked to detect implicitly offensive statements, achieving only ~0.11 accuracy.
    
In contrast to existing offensive text detection datasets, SLIGHT features human-annotated chains of reasoning which describe the mental process by which an offensive interpretation can be reached from each ambiguous statement.   We explore the potential for a multi-hop reasoning approach by utilizing existing entailment models to score the probability of these chains, and show that even naive reasoning models can yield improved performance in most situations.  Analysis of the chains provides insight into the human interpretation process and emphasizes the importance of incorporating additional commonsense knowledge.

## Citation
If you used this dataset, please cite the paper as:
```
@misc{
  https://doi.org/10.48550/arxiv.2204.10521,
  doi = {10.48550/ARXIV.2204.10521},
  url = {https://arxiv.org/abs/2204.10521},
  author = {Zhang, Qiang and Naradowsky, Jason and Miyao, Yusuke},
  keywords = {Computation and Language (cs.CL), Artificial Intelligence (cs.AI), Human-Computer Interaction (cs.HC), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {Rethinking Offensive Text Detection as a Multi-Hop Reasoning Problem},
  publisher = {arXiv},
  year = {2022},
  copyright = {Creative Commons Attribution 4.0 International}
}

```
