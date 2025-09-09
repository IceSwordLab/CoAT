# CoAT

<p align="center">
📑 <a href="https://arxiv.org/abs/2502.02390">Paper</a>
</p>

The official realease of EMNLP 2025 Finding "CoAT: Chain-of-Associated-Thoughts Framework for Enhancing Large Language Models Reasoning" by Jianfeng Pan, Senyou Deng, and Shaomang Huang.

## Dataset
The Comprehensive Reasoning Benchmark (CRB) dataset contains 205 professionally reviewed questions, each accompanied by its corresponding evaluation rules and total score, which together constitute the final evaluation entries. The data entry in the CRB is structured referring to the design principles of subjective questions in the Chinese Gaokao examination. Specifically, each entry consists of three components: the Question, the Judge Rules, and the Score. The Judge Rules outline a series of fundamental key points that must be addressed to provide an adequate response. Each key point corresponds to a specific score, and the inclusion of these key points in an answer results in the allocation of the corresponding score. Additionally, the Judge Rules incorporate higher-level criteria as bonus points. The Score assigned to each data entry represents the maximum attainable score for that entry.

## Citation
If you think this work is useful for your research, please cite the following paper.
```bibtex
@article{pan2025coat,
  title={Coat: Chain-of-associated-thoughts framework for enhancing large language models reasoning},
  author={Pan, Jianfeng and Deng, Senyou and Huang, Shaomang},
  journal={arXiv preprint arXiv:2502.02390},
  year={2025}
}
```