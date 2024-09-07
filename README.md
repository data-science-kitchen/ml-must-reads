# Important Machine Learning Papers

This repository contains a collection of the most important and influential papers in the field of machine learning, sorted by various categories.

## Learning Path

This section contains a curated collection of learning paths on various important topics in the field of machine learning. Each learning path guides you through the basics, advanced concepts, and current developments of a specific topic.

### 1. Transformers

- [General Machine Learning](./topics/general.md)
- [Transformers Learning Path](./topics/transformers.md)
- ...

## Categories

### 1. Computer Vision (CV)

| Paper | Year | Description |
|-------|------|--------------|
| [AlexNet](https://arxiv.org/abs/1803.01164) | 2012 | AlexNet was the first major convolutional neural network that won the ImageNet image classification task by a significant margin. It demonstrated that deep neural networks with many layers can effectively process large image datasets. |
| [VGGNet](https://arxiv.org/abs/1409.1556) | 2014 | VGGNet introduced deeper networks with very small (3x3) convolutions, leading to a significant improvement in image classification performance. It showed that network architecture, especially depth, is crucial for performance. |
| [ResNet](https://arxiv.org/abs/1512.03385) | 2015 | ResNet (Residual Networks) addressed the problem of diminishing accuracy in very deep networks by introducing residual connections, making it easier to train deep networks and improving their performance. |
| [Faster R-CNN](https://arxiv.org/abs/1506.01497) | 2015 | Faster R-CNN is a framework for object detection that introduced Region Proposal Networks (RPNs) to significantly speed up region-based detection and enable real-time object detection. |

### 2. Natural Language Processing (NLP)

| Paper | Year | Description |
|-------|------|--------------|
| [Word2Vec](https://arxiv.org/abs/1301.3781) | 2013 | Word2Vec is a model that enables efficient computation of word representations in vector space. It uses a technique where words with similar meanings receive similar vector representations, facilitating many NLP tasks. |
| [Attention is All You Need](https://arxiv.org/abs/1706.03762) | 2017 | This paper introduced the Transformer model, which is based entirely on attention mechanisms and does not rely on recurrent or convolutional layers. It revolutionized the NLP landscape by significantly improving translation and other sequence-to-sequence tasks. |
| [BERT](https://arxiv.org/abs/1810.04805) | 2018 | BERT (Bidirectional Encoder Representations from Transformers) is a pre-trained language model that understands bidirectional contexts in texts. It set new benchmarks in numerous NLP tasks by capturing deeper language representations. |
| [ELMo](https://arxiv.org/abs/1802.05365) | 2018 | ELMo (Embeddings from Language Models) generates contextualized word representations by using deep bidirectional language models. It improves performance in various NLP tasks by considering the context of words within a sentence. |
| [GPT-3](https://arxiv.org/abs/2005.14165) | 2020 | GPT-3 (Generative Pre-trained Transformer 3) is a large language model capable of generating human-like text and learning new tasks with few examples. It impresses with its versatility and the quality of the generated texts. |

### 3. Reinforcement Learning (RL)

| Paper | Year | Description |
|-------|------|--------------|
| [DQN](https://arxiv.org/abs/1312.5602) | 2015 | The Deep Q-Network (DQN) introduced deep reinforcement learning that reached human-level performance in playing video games. It combines Q-learning with deep neural networks to learn directly from raw pixels. |
| [A3C](https://arxiv.org/abs/1602.01783) | 2016 | Asynchronous Advantage Actor-Critic (A3C) is a framework for deep reinforcement learning that uses asynchronous methods to train multiple copies of the agent in parallel. This leads to more stable and faster training processes. |
| [AlphaGo](https://arxiv.org/abs/1712.01815) | 2016 | AlphaGo is known for its victory against human Go champions. It combines deep neural learning with Monte Carlo tree search and was trained on a large number of Go games to develop strategic game understanding. |
| [DDPG](https://arxiv.org/abs/1509.02971) | 2016 | Deep Deterministic Policy Gradient (DDPG) is an algorithm for continuous control tasks in reinforcement learning. It combines DQN with an actor-critic approach, enabling learning in high-dimensional action spaces. |
| [PPO](https://arxiv.org/abs/1707.06347) | 2017 | Proximal Policy Optimization (PPO) is a modern algorithm in the field of reinforcement learning that provides stable and efficient policy updates and is often used as a standard method. |

### 4. Generative Models

| Paper | Year | Description |
|-------|------|--------------|
| [GANs](https://arxiv.org/abs/1406.2661) | 2014 | Generative Adversarial Networks (GANs) consist of two neural networks, a generator and a discriminator, which are trained against each other. GANs have significantly improved the ability to generate realistic-looking data. |
| [VAEs](https://arxiv.org/abs/1312.6114) | 2013 | Variational Autoencoders (VAEs) are a class of generative models based on probabilistic density estimation. They allow for the generation of new data points that are similar to those in the training dataset and are particularly useful for image and text generation. |
| [PixelRNN](https://arxiv.org/abs/1601.06759) | 2016 | Pixel Recurrent Neural Networks (PixelRNN) are generative models that generate images pixel by pixel. They use recurrent neural networks to model the dependencies between pixels in an image, enabling the generation of high-resolution images. |

### 5. Graph Neural Networks (GNNs)

| Paper | Year | Description |
|-------|------|--------------|
| [GCN](https://arxiv.org/abs/1609.02907) | 2016 | Graph Convolutional Networks (GCNs) are a method for semi-supervised classification of nodes in graphs. They extend convolutional neural networks to graph data, enabling efficient processing and analysis of networks and relational data. |
| [GraphSAGE](https://arxiv.org/abs/1706.02216) | 2017 | GraphSAGE (Graph Sample and AggregatE) is a method for inductive learning on large graphs. It uses sampling and aggregation techniques to learn representative node features that can be used to predict new nodes without having to retrain on the entire graph. |

### 6. Fairness, Accountability, and Transparency in AI (FAccT)

| Paper | Year | Description |
|-------|------|--------------|
| [The Mythos of Model Interpretability](https://arxiv.org/abs/1606.03490) | 2016 | This paper discusses the misconceptions and challenges surrounding model interpretability. It provides a critical analysis of what it means to make a model interpretable and which approaches can contribute to this goal. |
| [Fairness and Abstraction in Sociotechnical Systems](https://www.researchgate.net/publication/330264946_Fairness_and_Abstraction_in_Sociotechnical_Systems) | 2017 | This paper explores the concepts of fairness and abstraction in sociotechnical systems. It emphasizes the importance of considering social and technical factors in designing fair and transparent algorithms. |

### 7. Bayesian Optimization

| Paper | Year | Description |
|-------|------|--------------|
| [Practical Bayesian Optimization of Machine Learning Algorithms](https://arxiv.org/abs/1206.2944) | 2012 | This paper describes how Bayesian optimization can be used to efficiently optimize the hyperparameters of machine learning models. It presents practical algorithms and implementations. |
| [A Tutorial on Bayesian Optimization](https://arxiv.org/abs/1807.02811) | 2018 | This tutorial offers a comprehensive introduction to Bayesian optimization. It covers the theoretical foundations and demonstrates how this method can be applied to optimize complex and expensive functions. |

## Contributing

Contributions to this repository are welcome. If you know of an important paper that should be included here, please submit a pull request.


## Lizenz

MIT License

Copyright (c) 2024 Data Science Kitchen

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.