## Data Augmentation for Reliability and Fairness in Counselling Quality Classification based on Anno-MI 

```
This repository contains the source code of the project and the synthetic datasets generated from Anno-MI [Link](https://github.com/vsrana-ai/AnnoMI)
```

### Datasets Generated 

```1. Anno-MI ``` [Link](https://github.com/vsrana-ai/AnnoMI) : A Dataset of Expert-Annotated Motivational Interviewing Counselling Dialogues comprised of 133 high and low quality therapy
session transcriptions distributed over 44 topics (including smoking cessation, anxi- ety management, weight loss, etc.)  

```2. Anno-AugMI ``` : Consisting of all the therapist utterances from Anno-MI, augmented in order to balance quality proportion. Anno-AugMI creation proceeds in a topic-agnostic fashion, with the goal of obtaining a roughly balanced amount of HQ-MI and LQ-MI utterances across the entire dataset.

```3. Anno-AugMI ``` : Consisting of all the therapist utterances from Anno-MI, augmented to balance therapy quality proportion with respect to MI-topic. Anno-FairMI creation proceeds in a topic-aware fashion, with the goal of having the same amount of HQ-MI and LQ-MI utterances for each MI-topic.


### Requirements
```
Python3
Keras
PyTorch
Microsoft FairLearn
```

### Publication (Confernce IJCAI - SDAIH) 
#### Data Augmentation for Reliability and Fairness in Counselling Quality Classification 
URL: TBS

Cite as :
``` 
TBS
``` 
