# Attentive Transformer Model for Fine Grained Software Entity Extraction

This repository contains the modified huggingface transformer version-2.8.0, where we utilized an embedding level attention to extract the fine-graied software entities as proposed in the paper:  **Code and Named Entity Recognition in  StackOverflow. (ACL 2020)**.  [[Paper PDF](https://arxiv.org/pdf/2005.01634.pdf)]

The modified codes  are: [BertForTokenClassification_Soft_NER](https://github.com/jeniyat/Attentive_Transformer_NER/blob/master/src/transformers/modeling_bert.py#L1312) and [BertForTokenClassification_Seg(BertPreTrainedModel](https://github.com/jeniyat/Attentive_Transformer_NER/blob/master/src/transformers/modeling_bert.py#L1495) and can be found under `src/transformers/modeling_bert.py`.

## Installation

```
    pip install .
```

## Publication


      @inproceedings{Tabassum20acl,
          title = {Code and Named Entity Recognition in StackOverflow},
          author = "Tabassum, Jeniya and Maddela, Mounica and  Xu, Wei  and Ritter, Alan",
          booktitle = {The Annual Meeting of the Association for Computational Linguistics (ACL)},
          year = {2020}
      }

