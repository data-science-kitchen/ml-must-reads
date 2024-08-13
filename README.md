# Wichtige Machine Learning Paper

Dieses Repository enthält eine Sammlung der wichtigsten und einflussreichsten Paper im Bereich des Machine Learnings, sortiert nach verschiedenen Kategorien.

## Learning Path

Dieser Abschnitt enthält eine kuratierte Sammlung von Lernpfaden zu verschiedenen wichtigen Themen im Bereich des Machine Learnings. Jeder Lernpfad führt dich durch die Grundlagen, fortgeschrittene Konzepte und aktuelle Entwicklungen eines spezifischen Themas.

### 1. Transformers

- [Transformers Learning Path](./transformers.md)
- ...

## Kategorien

### 1. Computer Vision (CV)

| Paper | Jahr | Beschreibung |
|-------|------|--------------|
| [AlexNet](https://arxiv.org/abs/1803.01164) | 2012 | AlexNet war das erste große Convolutional Neural Network, das die ImageNet-Bildklassifizierungsaufgabe mit erheblichem Abstand gewann. Es zeigte, dass tiefe neuronale Netzwerke mit vielen Schichten effektiv große Bilddatensätze verarbeiten können. |
| [VGGNet](https://arxiv.org/abs/1409.1556) | 2014 | VGGNet führte tiefere Netzwerke mit sehr kleinen (3x3) Faltungen ein, was zu einer signifikanten Verbesserung der Bildklassifikationsleistung führte. Es zeigte, dass die Netzwerkarchitektur, insbesondere die Tiefe, entscheidend für die Leistung ist. |
| [ResNet](https://arxiv.org/abs/1512.03385) | 2015 | ResNet (Residual Networks) löste das Problem der abnehmenden Genauigkeit in sehr tiefen Netzwerken durch die Einführung von Residualverbindungen, die das Training tiefer Netzwerke erleichtern und deren Leistung verbessern. |
| [Faster R-CNN](https://arxiv.org/abs/1506.01497) | 2015 | Faster R-CNN ist ein Framework für Objekterkennung, das Region Proposal Networks (RPNs) einführt, um regionsbasierte Erkennung erheblich zu beschleunigen und Echtzeit-Objekterkennung zu ermöglichen. |


### 2. Natural Language Processing (NLP)

| Paper | Jahr | Beschreibung |
|-------|------|--------------|
| [Word2Vec](https://arxiv.org/abs/1301.3781) | 2013 | Word2Vec ist ein Modell, das effiziente Berechnungen von Wortrepräsentationen im Vektorraum ermöglicht. Es nutzt eine Technik, bei der Wörter mit ähnlicher Bedeutung ähnliche Vektorrepräsentationen erhalten, was viele NLP-Aufgaben erleichtert. |
| [Attention is All You Need](https://arxiv.org/abs/1706.03762) | 2017 | Dieses Paper führte das Transformer-Modell ein, das ausschließlich auf Aufmerksamkeit (Attention) basiert und ohne rekurrente oder konvolutionale Schichten auskommt. Es revolutionierte die NLP-Landschaft durch signifikante Verbesserungen bei Übersetzungs- und anderen Sequenz-zu-Sequenz-Aufgaben. |
| [BERT](https://arxiv.org/abs/1810.04805) | 2018 | BERT (Bidirectional Encoder Representations from Transformers) ist ein vortrainiertes Sprachmodell, das bidirektionale Kontexte in Texten versteht. Es setzte neue Maßstäbe in zahlreichen NLP-Aufgaben durch seine Fähigkeit, tiefere Sprachrepräsentationen zu erfassen. |
| [ELMo](https://arxiv.org/abs/1802.05365) | 2018 | ELMo (Embeddings from Language Models) erzeugt kontextualisierte Wortrepräsentationen, indem es tiefe bidirektionale Sprachmodelle verwendet. Es verbessert die Leistung in verschiedenen NLP-Aufgaben, indem es den Kontext von Wörtern in einem Satz berücksichtigt. |
| [GPT-3](https://arxiv.org/abs/2005.14165) | 2020 | GPT-3 (Generative Pre-trained Transformer 3) ist ein großes Sprachmodell, das in der Lage ist, menschenähnlichen Text zu generieren und wenige Beispiele zu verwenden, um neue Aufgaben zu lernen. Es beeindruckt durch seine Vielseitigkeit und Qualität der generierten Texte. |

### 3. Reinforcement Learning (RL)

| Paper | Jahr | Beschreibung |
|-------|------|--------------|
| [DQN](https://arxiv.org/abs/1312.5602) | 2015 | Das Deep Q-Network (DQN) führte tiefes Reinforcement Learning ein, das menschliches Niveau in der Steuerung von Videospielen erreichte. Es kombiniert Q-Learning mit tiefen neuronalen Netzwerken, um direkt aus Rohpixeln zu lernen. |
| [A3C](https://arxiv.org/abs/1602.01783) | 2016 | Asynchronous Advantage Actor-Critic (A3C) ist ein Framework für tiefes Reinforcement Learning, das asynchrone Methoden nutzt, um mehrere Kopien des Agenten parallel zu trainieren. Dies führt zu stabileren und schnelleren Trainingsprozessen. |
| [AlphaGo](https://arxiv.org/abs/1712.01815) | 2016 | AlphaGo ist bekannt für seinen Sieg gegen menschliche Go-Meister. Es kombiniert tiefes neuronales Lernen mit Monte-Carlo-Baumsuche und trainierte auf einer großen Menge an Go-Partien, um strategisches Spielverständnis zu entwickeln. |
| [DDPG](https://arxiv.org/abs/1509.02971) | 2016 | Deep Deterministic Policy Gradient (DDPG) ist ein Algorithmus für kontinuierliche Steuerungsaufgaben im Reinforcement Learning. Es kombiniert DQN mit einem Actor-Critic-Ansatz und ermöglicht das Lernen in hochdimensionalen Aktionsräumen. |
| [PPO](https://arxiv.org/abs/1707.06347) | 2017 | Proximal Policy Optimization (PPO) ist ein moderner Algorithmus im Bereich des Reinforcement Learnings, der eine stabile und effiziente Aktualisierung der Politik bietet und oft als Standardmethode verwendet wird. |


### 4. Generative Modelle

| Paper | Jahr | Beschreibung |
|-------|------|--------------|
| [GANs](https://arxiv.org/abs/1406.2661) | 2014 | Generative Adversarial Networks (GANs) bestehen aus zwei neuronalen Netzwerken, einem Generator und einem Diskriminator, die gegeneinander trainiert werden. GANs haben die Fähigkeit, realistisch aussehende Daten zu generieren, erheblich verbessert. |
| [VAEs](https://arxiv.org/abs/1312.6114) | 2013 | Variational Autoencoders (VAEs) sind eine Klasse von generativen Modellen, die auf der Wahrscheinlichkeitsdichte-Schätzung basieren. Sie ermöglichen es, neue Datenpunkte zu generieren, die denen im Trainingsdatensatz ähnlich sind, und sind besonders nützlich für die Bild- und Textgenerierung. |
| [PixelRNN](https://arxiv.org/abs/1601.06759) | 2016 | Pixel Recurrent Neural Networks (PixelRNN) sind generative Modelle, die Pixel für Pixel Bilder erzeugen. Sie nutzen rekurrente neuronale Netzwerke, um die Abhängigkeiten zwischen den Pixeln in einem Bild zu modellieren und ermöglichen so die Generierung hochauflösender Bilder. |


### 5. Graph Neural Networks (GNNs)

| Paper | Jahr | Beschreibung |
|-------|------|--------------|
| [GCN](https://arxiv.org/abs/1609.02907) | 2016 | Graph Convolutional Networks (GCNs) sind eine Methode zur semi-supervisierten Klassifikation von Knoten in Graphen. Sie erweitern konvolutionale neuronale Netzwerke auf Graphdaten und ermöglichen so die effiziente Verarbeitung und Analyse von Netzwerken und relationalen Daten. |
| [GraphSAGE](https://arxiv.org/abs/1706.02216) | 2017 | GraphSAGE (Graph Sample and AggregatE) ist eine Methode für induktives Lernen auf großen Graphen. Sie verwendet sampling und aggregating Techniken, um repräsentative Knotenfeatures zu lernen, die für die Vorhersage neuer Knoten verwendet werden können, ohne den gesamten Graphen erneut trainieren zu müssen. |

### 6. Fairness, Accountability, and Transparency in AI (FAccT)

| Paper | Jahr | Beschreibung |
|-------|------|--------------|
| [The Mythos of Model Interpretability](https://arxiv.org/abs/1606.03490) | 2016 | Dieses Paper diskutiert die Missverständnisse und Herausforderungen rund um die Interpretierbarkeit von Modellen. Es bietet eine kritische Analyse dessen, was es bedeutet, ein Modell interpretierbar zu machen, und welche Ansätze dazu beitragen können. |
| [Fairness and Abstraction in Sociotechnical Systems](https://www.researchgate.net/publication/330264946_Fairness_and_Abstraction_in_Sociotechnical_Systems) | 2017 | Dieses Paper untersucht die Konzepte von Fairness und Abstraktion in soziotechnischen Systemen. Es betont die Bedeutung der Berücksichtigung sozialer und technischer Faktoren bei der Gestaltung fairer und transparenter Algorithmen. |

### 7. Bayesian Optimization

| Paper | Jahr | Beschreibung |
|-------|------|--------------|
| [Practical Bayesian Optimization of Machine Learning Algorithms](https://arxiv.org/abs/1206.2944) | 2012 | Dieses Paper beschreibt, wie Bayesianische Optimierung genutzt werden kann, um die Hyperparameter von Machine Learning Modellen effizient zu optimieren. Es stellt praktische Algorithmen und Implementierungen vor. |
| [A Tutorial on Bayesian Optimization](https://arxiv.org/abs/1807.02811) | 2018 | Dieses Tutorial bietet eine umfassende Einführung in die Bayesianische Optimierung. Es deckt die theoretischen Grundlagen ab und zeigt, wie diese Methode zur Optimierung komplexer und teurer Funktionen angewendet werden kann. |

## Beitrag leisten

Beiträge zu diesem Repository sind herzlich willkommen. Wenn du ein wichtiges Paper kennst, das hier aufgenommen werden sollte, erstelle bitte einen Pull-Request.

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