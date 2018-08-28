
# 使用说明

## 将原来的transformer翻译模型用于智能客服QA系统的一个实践，更改了代码使之适配中文数据，使用结巴分词来处理中文文本
## 添加了在SGE集群上提交任务的脚本run.sh


# Attention is all you need: A Pytorch Implementation

This is a PyTorch implementation of the Transformer model in "[Attention is All You Need](https://arxiv.org/abs/1706.03762)" (Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Lukasz Kaiser, Illia Polosukhin, arxiv, 2017). 


A novel sequence to sequence framework utilizes the **self-attention mechanism**, instead of Convolution operation or Recurrent structure, and achieve the state-of-the-art performance on **WMT 2014 English-to-German translation task**. (2017/06/12)

> The official Tensorflow Implementation can be found in: [tensorflow/tensor2tensor](https://github.com/tensorflow/tensor2tensor/blob/master/tensor2tensor/models/transformer.py).

> To learn more about self-attention mechanism, you could read "[A Structured Self-attentive Sentence Embedding](https://arxiv.org/abs/1703.03130)".

<p align="center">
<img src="http://imgur.com/1krF2R6.png" width="250">
</p>


The project support training and translation with trained model now.

Note that this project is still a work in progress.


If there is any suggestion or error, feel free to fire an issue to let me know. :)


# Requirement
- python 3.6.5+
- pytorch 0.4.1+
- tqdm
- numpy
