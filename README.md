# Medical Visual Question Answering (Med-VQA) on VQA-RAD Dataset

Authors
Chang Kai Xin (23109141)
Yoong Jia Yin (24065194)

----
A comparative study of CNN-LSTM baseline and Transformer-based (ViT + ClinicalBERT) architectures for Medical Visual Question Answering using the VQA-RAD dataset.

**Overview**
This project implements and compares two multimodal architectures for answering natural language questions about medical images:

CNN-LSTM Baseline: ResNet-50 + LSTM with attention fusion

ViT + ClinicalBERT (Proposed): Vision Transformer + ClinicalBERT with cross-attention fusion

----

**Acknowledgements**

VQA-RAD Dataset - Lau et al.
Vision Transformer - Google Research
ClinicalBERT - Emily Alsentzer

----

**REFERENCES**

@article{lau2018dataset,
  title={A dataset of clinically generated visual questions and answers about radiology images},
  author={Lau, Jason J and Gayen, Soumya and Ben Abacha, Asma and Demner-Fushman, Dina},
  journal={Scientific data},
  volume={5},
  number={1},
  pages={1--10},
  year={2018}
}

@article{dosovitskiy2020image,
  title={An image is worth 16x16 words: Transformers for image recognition at scale},
  author={Dosovitskiy, Alexey and others},
  journal={arXiv preprint arXiv:2010.11929},
  year={2020}
}

@article{alsentzer2019publicly,
  title={Publicly available clinical BERT embeddings},
  author={Alsentzer, Emily and others},
  journal={arXiv preprint arXiv:1904.03323},
  year={2019}
}
