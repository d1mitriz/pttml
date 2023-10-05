# PT-t-ML
Code repository for the paper titled "From Pre-training to Meta-Learning: A journey in Low-Resource-Language Representation Learning".

The code, datasets and instruction on how to run the experiments will be made availabe after puplication of the paper.


> [!NOTE]
> The Pre-Trained Language Models (PLMs) and datasets introduced in this work are/will be available @ HuggingFace: [huggingface.co/dimitriz](https://huggingface.co/dimitriz)


| PLM | Link | Publicly Available |
| --- | --- | --- |
| Greek Media BERT | [dimitriz/greek-media-bert-base-uncased](https://huggingface.co/dimitriz/greek-media-bert-base-uncased) | :heavy_check_mark: |
| Finely-Tuned Greek Media BERT (ST[^1]) | [dimitriz/st-greek-media-bert-base-uncased](https://huggingface.co/dimitriz/st-greek-media-bert-base-uncased)  | :heavy_check_mark: |
| Greek Longformer | [dimitriz/greek-longformer-base-4096](https://huggingface.co/dimitriz/greek-longformer-base-4096) | :x: |
| Greek Media Longformer | [dimitriz/greek-media-longformer-4096](https://huggingface.co/dimitriz/greek-media-longformer-4096) | :x: |
| Finely-Tuned Greek Media Longformer (ST[^1]) | [dimitriz/st-greek-media-longformer-4096](https://huggingface.co/dimitriz/st-greek-media-longformer-4096)  | :x: |


| Dataset | Link | Publicly Available |
| --- | --- | --- |
| Greek Media Domain-Adaption | [dimitriz/greek_media_texts](https://huggingface.co/datasets/dimitriz/greek_media_texts) | :x: |
| Task-Specific Classification (ATA + Custom Tasks) | [dimitriz/greek_media_cls](https://huggingface.co/dimitriz/greek_media_cls)  | :x: |
| Triplet-loss (Contrastive Learning) | [dimitriz/greek_media_st_triplets](https://huggingface.co/dimitriz/greek_media_st_triplets) | :x: |





> Authors: _Dimitrios Zaikis_ and _Ioannis Vlahavas_


[^1]: Sentence Transformer.
