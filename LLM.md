# LLM学习记录

## 一些网址记录

python cookbook https://python3-cookbook.readthedocs.io/zh_CN/latest/

LLM综述 https://zhuanlan.zhihu.com/p/612181615

pytorch dataloader https://zhuanlan.zhihu.com/p/270028097

便宜vpn https://xn--5hqx9equq.com/#/plan

clash https://github.com/wanhebin/clash-for-linux
每次使用必须先shutdown再start

解决容器克隆gitpull 问题 https://www.jianshu.com/p/cc544715dc17

## 阅读LLM综述

### NLP

针对上游标注数据难搞（记作「短板一」），另一方面因为针对特定任务训练，所以下游使用时只能对特定任务起作用（记作「短板二」）。

#### pre-train和fine-tune学习范式

- NLP的解决思路就是把学习分成两个阶段：pre-train预训练+fine-tune微调。

#### 自监督学习Self-Supervised Learning

- 利用文本生成任务，免除大量标注训练模型，一句话做截断，前面部分就是x，后面部分就是y，天然可以作为文本生成的训练数据。这种在语料库自己自己构建标记数据的方法叫自监督学习。

#### 预训练-提示prompt学习范式

- 
