# Introduction to AI

![요약](../sketchnotes/ai-intro.png)

> Sketchnote by [Tomomi Imura](https://twitter.com/girlie_mac)

## [사전 퀴즈](https://red-field-0a6ddfd03.1.azurestaticapps.net/quiz/101)

**인공지능**은 사람처럼 지능적인 행동을 하는 컴퓨터를 구현하는 것을 목적으로 연구하는 학문입니다. 

최초의 컴퓨터는 수학자 [찰스 배비지 (Charles Babbage)](https://ko.wikipedia.org/wiki/%EC%B0%B0%EC%8A%A4_%EB%B0%B0%EB%B9%84%EC%A7%80)에 의해 수를 잘 짜여진 절차, 알고리즘에 의해 연산하기 위하여 발명되었습니다. 처음과 비교하여 기술이 엄청나게 발전한 근대의 컴퓨터도 절차에 따라 계산하는 것은 동일했습니다. 그래서 만약 우리가 목적을 달성하기 위한 정확한 절차를 알고 있다면, 컴퓨터를 프로그래밍하는 것이 가능합니다. 


![사람 사진](images/dsh_age.png)

> Photo by [Vickie Soshnikova](http://twitter.com/vickievalerie)

> ✅ 사진을 보고 사람의 나이를 알아차리는 것은 정확하게 프로그래밍할 수 없는 일입니다. 우리가 사람을 보고 나이를 떠올려도 어떻게 그러는 지 모르기 때문입니다. 

---

하지만 우리가 어떻게 풀어야 하는지 알 수 없는 문제들도 있습니다. 사진을 보고 나이를 알아차리는 문제를 생각해보세요. 사람은 살면서 다양한 나이의 많은 사람을 본 경험을 떠올려 어떻게든 나이를 알 수도 있습니다. 하지만 어떻게 그 사람의 나이를 정하는지 정확하게 설명할 수 없습니다. 따라서 컴퓨터에 프로그래밍하는 일 또한 불가능하죠. 이것이 바로 **인공지능**, AI가 관심을 가지는 종류의 작업입니다. 

✅ AI로 인해 컴퓨터에게 떠넘길만한 일들을 생각해보세요. 오늘날 금융, 의료, 예술 분야는 AI에게서 어떠한 도움을 받고 있나요?

## 약한 AI와 강한 AI

약한 AI | 강한 AI
---------------------------------------|-------------------------------------
약한 AI는 특정한 작업을 위해 만들어진 AI를 의미합니다.|강한 AI는 범용인공지능(AGI)으로도 불리우며 사람 수준의 지능과 사람처럼 이해가 가능하여 다양한 일을 수행할 수 있는 AI를 의미합니다.
지능을 가지고 있다고 여겨지지 않습니다. 이해나 인지 없이 그저 미리 정해진 일을 수행할 뿐입니다.|사람이 할 수 있는 어떠한 지능적인 일을 수행할 수 있습니다. 다양한 분야에 적응하고 자기인지와 의식을 지니고 있습니다. 
시리나 알렉사와 같은 비서 AI, 음악 스트리밍 사이트의 추천 음악, 온라인 쇼핑몰의 챗봇 등이 예시입니다.| 강한 AI를 만드는 것이 AI분야의 궁극적인 목표입니다.
약한 AI는 특정 분야에 특화되어 사람과 같은 인지능력과 다양한 분야에서의 문제해결을 가지지 못합니다.|강한 AI는 아직 이론적인 개념에 불과하며 이정도 수준에 도달한 AI는 없습니다.

더 자세한 내용은 **[Artificial General Intelligence(영문위키)](https://en.wikipedia.org/wiki/Artificial_general_intelligence)**를 참고하세요.

## 인공지능의 정의와 튜링테스트

**[지능](https://ko.wikipedia.org/wiki/%EC%A7%80%EB%8A%A5)**을 다룰 때의 문제 중 하나는 명확한 정의가 없다는 것입니다. 혹자는 지능이 **추상적 사고**나 **자기 인식**이라고 주장하지만, 이를 명확하게 정의할 수는 없습니다.

![고양이 사진](images/photo-cat.jpg)

> [Photo](https://unsplash.com/photos/75715CVEJhI) by [Amber Kipp](https://unsplash.com/@sadmax) from Unsplash

*지능*의 모호함을 보기 위하여 "고양이는 지능을 가지는가?"에 대해서 생각해봅시다. 증명하기 위한 국제적인 테스트가 없어 알 수 없다고 생각하십니까? 고양이에게 IQ테스트를 시켜볼까요? 이를 어떻게 판단할 수 있을까요?

✅ 잠시 지능을 어떻게 정의할 지 생각해보세요. 미로를 풀어 먹이를 찾는 까마귀는 지능을 가지고 있나요? 어린아이는 지능을 가지고 있나요?

---

만약 범용인공지능을 만들어도 그것이 진짜 지능적인 AI인지 확인할 방법이 필요합니다. [앨런 튜링 (Alan Turing)](https://ko.wikipedia.org/wiki/%EC%95%A8%EB%9F%B0_%ED%8A%9C%EB%A7%81)은 **[튜링 테스트](https://ko.wikipedia.org/wiki/%ED%8A%9C%EB%A7%81_%ED%85%8C%EC%8A%A4%ED%8A%B8)**라는 것을 만들어서 기계의 지능을 판단할 방법을 고안하였습니다. 지능을 가진 사람이 상대가 컴퓨터인지 다른 사람인지 모르는 상황에서 문자로 대화를 하며 상대방을 구분할 수 없다면 컴퓨터가 지능을 가지고 있다고 간주한다는 것입니다.

> 상트페테르부르크에서 개발된 [Eugene Goostman(유진 구스트만, 영문위키)](https://en.wikipedia.org/wiki/Eugene_Goostman)라는 챗봇은 2014년에 영리하게 챗봇의 인격을 만드는 방법으로 튜링테스트 통과에 근접하였습니다. 이 챗봇은 자신을 13살의 우크라이나 소년이라고 소개하며 지식의 부족함과 문맥의 어색함을 설명하였습니다. 판단자들과의 5분동안 대화를 나눈 뒤 30퍼센트나 사람이라는 반응을 얻었습니다. 하지만 이것이 지능적인 AI를 만들었거나 컴퓨터가 사람을 속였다고 이해해서는 안됩니다. AI가 사람을 속인 것이 아닌 AI를 만든 사람이 판잔자를 속였을 뿐입니다.

✅ 챗봇과 대화하면서 상대가 사람이라고 속은 적이 있나요? 어떠한 방식으로 속았나요?

## AI에 대한 다양한 접근법

사람과 같이 행동하는 컴퓨터를 원한다면, 어떻게든 컴퓨터에게 사람이 생각하는 방식을 알려줘야합니다. 결과적으로 어떻게 사람이 지능을 가지는 지 알아야 합니다. 

> To be able to program intelligence into a machine, we need to understand how our own processes of making decisions work. If you do a little self-introspection, you will realize that there are some processes that happen subconsciously – eg. we can distinguish a cat from a dog without thinking about it - while some others involve reasoning.

> 기계에게 지능을 프로그래밍하기 위해서는, 우리의 의사결정 절차를 알아야 합니다. 우리는 별 생각 없이 고양이과 강아지를 구분할 수 있습니다. 그 과정을 의식해서 돌아보면 잠재의식 속에서의 여러 절차 이외의 무엇인가가 추론에 관여하고 있다고 깨달을 수 있습니다.

There are two possible approaches to this problem:

Top-down Approach (Symbolic Reasoning) | Bottom-up Approach (Neural Networks)
---------------------------------------|-------------------------------------
A top-down approach models the way a person reasons to solve a problem. It involves extracting **knowledge** from a human being, and representing it in a computer-readable form. We also need to develop a way to model **reasoning** inside a computer. | A bottom-up approach models the structure of a human brain, consisting of huge number of simple units called **neurons**. Each neuron acts like a weighted average of its inputs, and we can train a network of neurons to solve useful problems by providing **training data**.

There are also some other possible approaches to intelligence:

* An **Emergent**, **Synergetic** or **multi-agent approach** are based on the fact that complex intelligent behaviour can be obtained by an interaction of a large number of simple agents. According to [evolutionary cybernetics](https://en.wikipedia.org/wiki/Global_brain#Evolutionary_cybernetics), intelligence can *emerge* from more simple, reactive behaviour in the process of *metasystem transition*.

* An **Evolutionary approach**, or **genetic algorithm** is an optimization process based on the principles of evolution.

We will consider those approaches later in the course, but right now we will focus on two main directions: top-down and bottom-up.

### The Top-Down Approach

In a **top-down approach**, we try to model our reasoning.  Because we can follow our thoughts when we reason, we can try to formalize this process and program it inside the computer. This is called **symbolic reasoning**.

People tend to have some rules in their head that guide their decision making processes. For example, when a doctor is diagnosing a patient, he or she may realize that a person has a fever, and thus there might be some inflammation going on inside the body. By applying a large set of rules to a specific problem a doctor may be able to come up with the final diagnosis.

This approach relies heavily on **knowledge representation** and **reasoning**. Extracting knowledge from a human expert might be the most difficult part, because a doctor in many cases would not know exactly why he or she is coming up with a particular diagnosis. Sometimes the solution just comes up in his or her head without explicit thinking. Some tasks, such as determining the age of a person from a photograph, cannot be at all reduced to manipulating knowledge.

### Bottom-Up Approach

Alternately, we can try to model the simplest elements inside our brain – a neuron. We can construct a so-called **artificial neural network** inside a computer, and then try to teach it to solve problems by giving it examples. This process is similar to how a newborn child learns about his or her surroundings by making observations.

✅ Do a little research on how babies learn. What are the basic elements of a baby's brain?

> | What about ML?         |      |
> |--------------|-----------|
> | Part of Artificial Intelligence that is based on computer learning to solve a problem based on some data is called **Machine Learning**. We will not consider classical machine learning in this course - we refer you to a separate [Machine Learning for Beginners](http://aka.ms/ml-beginners) curriculum. |   ![ML for Beginners](images/ml-for-beginners.png)    |

## A Brief History of AI

Artificial Intelligence was started as a field in the middle of the twentieth century. Initially, symbolic reasoning was a prevalent approach, and it led to a number of important successes, such as expert systems – computer programs that were able to act as an expert in some limited problem domains. However, it soon became clear that such approach does not scale well. Extracting the knowledge from an expert, representing it in a computer, and keeping that knowledgebase accurate turns out to be a very complex task, and too expensive to be practical in many cases. This led to so-called [AI Winter](https://en.wikipedia.org/wiki/AI_winter) in the 1970s.

<img alt="Brief History of AI" src="images/history-of-ai.png" width="70%"/>

> Image by [Dmitry Soshnikov](http://soshnikov.com)

As time passed, computing resources became cheaper, and more data has become available, so neural network approaches started demonstrating great performance in competing with human beings in many areas, such as computer vision or speech understanding. In the last decade, the term Artificial Intelligence has been mostly used as a synonym for Neural Networks, because most of the AI successes that we hear about are based on them.

We can observe how the approaches changed, for example, in creating a chess playing computer program:

* Early chess programs were based on search – a program explicitly tried to estimate possible moves of an opponent for a given number of next moves, and selected an optimal move based on the optimal position that can be achieved in a few moves. It led to the development of the so-called [alpha-beta pruning](https://en.wikipedia.org/wiki/Alpha%E2%80%93beta_pruning) search algorithm.
* Search strategies work well toward the end of the game, where the search space is limited by a small number of possible moves. However, at the beginning of the game, the search space is huge, and the algorithm can be improved by learning from existing matches between human players. Subsequent experiments employed so-called [case-based reasoning](https://en.wikipedia.org/wiki/Case-based_reasoning), where the program looked for cases in the knowledge base very similar to the current position in the game.
* Modern programs that win over human players are based on neural networks and [reinforcement learning](https://en.wikipedia.org/wiki/Reinforcement_learning), where the programs learn to play solely by playing a long time against themselves and learning from their own mistakes – much like human beings do when learning to play chess. However, a computer program can play many more games in much less time, and thus can learn much faster.

✅ Do a little research on other games that have been played by AI.

Similarly, we can see how the approach towards creating “talking programs” (that might pass the Turing test) changed:

* Early programs of this kind such as [Eliza](https://en.wikipedia.org/wiki/ELIZA), were based on very simple grammatical rules and the re-formulation of the input sentence into a question.
* Modern assistants, such as Cortana, Siri or Google Assistant are all hybrid systems that use Neural networks to convert speech into text and recognize our intent, and then employ some reasoning or explicit algorithms to perform required actions.
* In the future, we may expect a complete neural-based model to handle dialogue by itself. The recent GPT and [Turing-NLG](https://turing.microsoft.com/) family of neural networks show great success in this.

<img alt="the Turing test's evolution" src="images/turing-test-evol.png" width="70%"/>

> Image by Dmitry Soshnikov, [photo](https://unsplash.com/photos/r8LmVbUKgns) by [Marina Abrosimova](https://unsplash.com/@abrosimova_marina_foto), Unsplash

## Recent AI Research

The huge recent growth in neural network research started around 2010, when large public datasets started to become available. A huge collection of images called [ImageNet](https://en.wikipedia.org/wiki/ImageNet), which contains around 14 million annotated images, gave birth to the [ImageNet Large Scale Visual Recognition Challenge](https://image-net.org/challenges/LSVRC/).

![ILSVRC Accuracy](images/ilsvrc.gif)

> Image by [Dmitry Soshnikov](http://soshnikov.com)

In 2012, [Convolutional Neural Networks](../4-ComputerVision/07-ConvNets/README.md) were first used in image classification, which led to a significant drop in classification errors (from almost 30% to 16.4%). In 2015, ResNet architecture from Microsoft Research [achieved human-level accuracy](https://doi.org/10.1109/ICCV.2015.123).

Since then, Neural Networks demonstrated very successful behaviour in many tasks:

---

Year | Human Parity achieved
-----|--------
2015 | [Image Classification](https://doi.org/10.1109/ICCV.2015.123)
2016 | [Conversational Speech Recognition](https://arxiv.org/abs/1610.05256)
2018 | [Automatic Machine Translation](https://arxiv.org/abs/1803.05567) (Chinese-to-English)
2020 | [Image Captioning](https://arxiv.org/abs/2009.13682)

Over the past few years we have witnessed huge successes with large language models, such as BERT and GPT-3. This happened mostly due to the fact that there is a lot of general text data available that allows us to train models to capture the structure and meaning of texts, pre-train them on general text collections, and then specialize those models for more specific tasks. We will learn more about [Natural Language Processing](../5-NLP/README.md) later in this course.

## 🚀 Challenge

Do a tour of the internet to determine where, in your opinion, AI is most effectively used. Is it in a Mapping app, or some speech-to-text service or a video game? Research how the system was built.

## [Post-lecture quiz](https://red-field-0a6ddfd03.1.azurestaticapps.net/quiz/201)

## Review & Self Study

Review the history of AI and ML by reading through [this lesson](https://github.com/microsoft/ML-For-Beginners/tree/main/1-Introduction/2-history-of-ML). Take an element from the sketchnote at the top of that lesson or this one and research it in more depth to understand the cultural context informing its evolution.

**Assignment**: [Game Jam](assignment.md)
