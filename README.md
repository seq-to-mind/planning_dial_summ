## Introduction
One implementation of the paper "Controllable Neural Dialogue Summarization with Personal Named Entity Planning" in EMNLP 2022.

## Package Requirements
1. pytorch==1.7.1
2. transformers==4.8.2
3. click==7.1.2
4. sentencepiece==0.1.92
5. allennlp==2.6.0
6. allennlp-models==2.6.0

## Training Data for Controllable Generation
The processed training data with the Occurrence Planning are located in `./data/SAMSum_data_OCC/`.

## Generated Summaries for SAMSum Corpus
See the predictions from the controllable summarization model of SAMSum test set in `./model_outputs/`

## Citation

```
@inproceedings{liu-chen-2021-controllable,
    title = "Controllable Neural Dialogue Summarization with Personal Named Entity Planning",
    author = "Liu, Zhengyuan and Chen, Nancy",
    booktitle = "Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing",
    month = nov,
    year = "2021",
    address = "Online and Punta Cana, Dominican Republic",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.emnlp-main.8",
    pages = "92--106",
}
```
