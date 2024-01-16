# SJ-Donald/kor-hate-sentence

SJ-Donald/kor-hate-sentence is merged dataset from fllow

## Datasets

* [smilegate-ai/kor_unsmile](https://huggingface.co/datasets/smilegate-ai/kor_unsmile)
* [korean-hate-speech](https://github.com/kocohub/korean-hate-speech/tree/master)
* [Curse-detection-data](https://github.com/2runo/Curse-detection-data)
* [korean-malicious-comments-dataset](https://github.com/seongwoong/korean-malicious-comments-dataset)

Merge datasets from above and drop duplicates.

## Hugginface

[SJ-Donald/kor-hate-sentence](https://huggingface.co/datasets/SJ-Donald/kor-hate-sentence)

## How to use

```Python
from datasets import load_dataset

ds = load_dataset("SJ-Donald/kor-hate-sentence")
print(ds)

DatasetDict({
    train: Dataset({
        features: ['문장', 'hate', 'clean', 'labels'],
        num_rows: 29328
    })
    test: Dataset({
        features: ['문장', 'hate', 'clean', 'labels'],
        num_rows: 7333
    })
})

---
license: cc-by-sa-4.0
tags:
- korean
- hate-speech
- hate-sentence
---
