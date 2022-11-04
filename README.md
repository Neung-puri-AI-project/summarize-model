# summary model

## reference

`load pretrained TransformerSum models` [github](https://github.com/HHousen/TransformerSum) | [tutorial](https://transformersum.readthedocs.io/en/latest/general/getting-started.html#install)

### Model

1. `distilbert-base-uncased-ext-sum(CNN/DM): 6h 22m 32s` [model download](https://drive.google.com/uc?id=1VNoFhqfwlvgwKuJwjlHnlGcGg38cGM--)
    
    > Currently, distilbert beats bert-base-uncased by 1.0014% Since bert-base-uncased has more parameters than distilbert, this is unusual and is likely a tuning issue. This suggests that tuning the hyperparameters of bert-base-uncased can improve its performance. distilroberta matches 92.7% of the performance of roberta-base

2. `bert-base-uncased-ext-sum(CNN/DM): 12h 51m 17s` [model download](https://drive.google.com/uc?id=1yGvarxhq78Vl6m8IZgG9HFQC2qXDB-KU)

3. `mobilebert-uncased-ext-sum(CNN/DM): 8h 26m 32s` [model download](https://drive.google.com/uc?id=1R3tRH07z_9nYW8sC8eFceBmxC7u0kP_W)

    > mobilebert-uncased-ext-sum achieves 96.59%  of the performance of BertSum while containing 4.45 times fewer parameters. It achieves 94.06%  of the performance of MatchSum the current extractive state-of-the-art.

4. `distilroberta-base-ext-sum(WikiHow): 4h 27m 23s` [model download](https://drive.google.com/uc?id=1RdFcoeuHd_JCj5gBQRFXFpieb-3EXkiN)
    
    > These are the results of an extractive model, which means they are fairly good because they come close to abstractive models. The R1/R2/RL-Sum results of a base transformer model from the PEGASUS paper are 32.48/10.53/23.86. The net difference from distilroberta-base-ext-sum is +1.41/+1.57/-5.09. Compared to the abstractive SOTA prior to PEGASUS, which was 28.53/9.23/26.54, distilroberta-base-ext-sum performs +2.54/-0.27/+2.41. 
    
    However, the base PEGASUS model obtains scores of 36.58/15.64/30.01, which are much better than distilroberta-base-ext-sum, as one would expect.

5. `bert-base-uncased-ext-sum(WikiHow): 7h 29m 06s` [model download](https://drive.google.com/uc?id=1EPCaQySWJgm368XypDeCwEMdRCxB5w7Z)

### code

`check architecture, parameters` [blog](https://rabo0313.tistory.com/entry/Pytorch-%EB%AA%A8%EB%8D%B8-%EA%B5%AC%EC%A1%B0-%ED%99%95%EC%9D%B8-parameter%ED%99%95%EC%9D%B8)

### error