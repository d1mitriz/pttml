# PT-t-ML
Code repository for the paper titled "From Pre-training to Meta-Learning: A Journey in Low-Resource-Language Representation Learning".

The code, datasets and instruction on how to run the experiments will be made availabe after puplication of the paper.

## Models

> The Pre-Trained Language Models (PLMs) introduced in this work are be available @ HuggingFace: [huggingface.co/dimitriz](https://huggingface.co/dimitriz)
>
> Alternatively, you can use the links below:


| PLM | Link | Publicly Available |
| --- | --- | --- |
| Greek Media BERT | [dimitriz/greek-media-bert-base-uncased](https://huggingface.co/dimitriz/greek-media-bert-base-uncased) | :heavy_check_mark: |
| Finely-Tuned Greek Media BERT (ST[^1]) | [dimitriz/st-greek-media-bert-base-uncased](https://huggingface.co/dimitriz/st-greek-media-bert-base-uncased)  | :heavy_check_mark: |
| Greek Longformer | [dimitriz/greek-longformer-base-4096](https://huggingface.co/dimitriz/greek-longformer-base-4096) | :heavy_check_mark: |
| Greek Media Longformer | [dimitriz/greek-media-longformer-4096](https://huggingface.co/dimitriz/greek-media-longformer-4096) | :heavy_check_mark: |
| Finely-Tuned Greek Media Longformer (ST[^1]) | [dimitriz/st-greek-media-longformer-4096](https://huggingface.co/dimitriz/st-greek-media-longformer-4096)  | :heavy_check_mark: |


## Datasets

> [!NOTE]
> The datasets introduced in this work will be made available @ HuggingFace: [huggingface.co/dimitriz](https://huggingface.co/dimitriz)
 
| Dataset | Link | Publicly Available |
| --- | --- | --- |
| Greek Media Domain-Adaption | [dimitriz/greek_media_texts](https://huggingface.co/datasets/dimitriz/greek_media_texts) | :x: |
| Task-Specific Classification (ATA + Custom Tasks) | [dimitriz/greek_media_cls](https://huggingface.co/dimitriz/greek_media_cls)  | :x: |
| Triplet-loss (Contrastive Learning) | [dimitriz/greek_media_st_triplets](https://huggingface.co/dimitriz/greek_media_st_triplets) | :x: |


## Citing & Authors


If you use the models, code or datasets, please cite the following:

```bibtex

@ARTICLE{10288436,
    author =  {Zaikis, Dimitrios and Vlahavas, Ioannis},
    journal = {IEEE Access},
    title =   {From Pre-training to Meta-Learning: A journey in Low-Resource-Language Representation Learning},
    year =    {2023},
    volume =  {},
    number =  {},
    pages =   {1-1},
    doi =     {10.1109/ACCESS.2023.3326337}
  }

```


[^1]: Sentence Transformer.
