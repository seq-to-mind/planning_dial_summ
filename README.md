## Introduction
One implementation of the paper "Controllable Neural Dialogue Summarization with Personal Named Entity Planning".

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
@article{liu2021controllable,
  title={Controllable Neural Dialogue Summarization with Personal Named Entity Planning},
  author={Liu, Zhengyuan and Chen, Nancy F},
  journal={arXiv preprint arXiv:2109.13070},
  year={2021}
}
```
