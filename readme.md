# MCQ-Mismatch_data



Data repository for our paper "["My Answer is C": First-Token Probabilities Do Not Match Text Answers in Instruction-Tuned Language Models](https://arxiv.org/abs/2402.14499)"

This repo contains the annotated data we used for training our evaluator in `labeled_model_output`, and the model output with mapping result in `outputs`.

## Classifier
<a href="https://huggingface.co/mainlp/MCQ-Classifier-MMLU-EFG"><img alt="HuggingFace Model" src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Model-8A2BE2"></a>

We also released the classifiers we trained on huggingface. Please try them out. 

## Cite
If you find this repository useful or our work is related to your research, please kindly cite it:

```latex
@inproceedings{wang-etal-2024-answer-c,
    title = "{``}My Answer is {C}{''}: First-Token Probabilities Do Not Match Text Answers in Instruction-Tuned Language Models",
    author = {Wang, Xinpeng  and
      Ma, Bolei  and
      Hu, Chengzhi  and
      Weber-Genzel, Leon  and
      R{\"o}ttger, Paul  and
      Kreuter, Frauke  and
      Hovy, Dirk  and
      Plank, Barbara},
    editor = "Ku, Lun-Wei  and
      Martins, Andre  and
      Srikumar, Vivek",
    booktitle = "Findings of the Association for Computational Linguistics ACL 2024",
    month = aug,
    year = "2024",
    address = "Bangkok, Thailand and virtual meeting",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.findings-acl.441",
    doi = "10.18653/v1/2024.findings-acl.441",
    pages = "7407--7416",
}
```
