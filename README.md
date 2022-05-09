1. topk sample

3. douban数据集评测



backbone code for "An Empirical Investigation of Pre-Trained Transformer Language Models for Open-Domain Dialogue Generation": https://arxiv.org/abs/2003.04195


#### Pre-training:

```
./prepare_data.sh
./train.sh
./inference.sh
```
#### Fine-tuning

#### Web Api:
```
./deploy.sh
```

#### Pre-trained models
- 12-layer, 768-hidden, 12-heads, Chinese (News + zhwiki, 200G) and English (Gigawords + Bookscorpus + enwiki, 60G) 

- 24-layer, 1024-hidden, 16-heads, Chinese (News + zhwiki, 200G) and English (Gigawords + Bookscorpus + enwiki, 60G)
  Note: please use transformer_preln as the main model:https://github.com/lipiji/Guyu/blob/master/biglm.py#L8

- download them: https://github.com/lipiji/Guyu/tree/master/model

#### References:
- GPT2: https://openai.com/blog/better-language-models/
- https://github.com/jcyk/BERT
- https://github.com/lipiji/Guyu
