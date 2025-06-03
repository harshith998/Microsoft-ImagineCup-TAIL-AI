# Microsoft-ImagineCup-TAIL-AI
Multimodal ensemble analysis tool and chatbot for doctors and patients to monitor, diagnose, and treat mental health disorders.


## Overview
This novel ensembling methodology utilizes a multiheaded approach, where all 3 inputs (questionaire, EEG, and audio signals) have seperate branches, have a contcat layer to accurately diagnose clinical mental disorders (ex: PTSD, MDD, etc). The three inputs respectively have a multi-layer perceptron, convolutional neural network, and convolutional neural network respectively.

The 3 notebooks (along with v1 for EEG models) are a part of this repo. The chatbot is another significant aspect of this project, and takes these model predictions to tune outputs to the patients, emulating a therapist that tracks condition progression through live interaction, and basing chats on novel diagnosis. However, due to proprietery reasons, it will not be included in this repo.


## Links
Below attached is a brief 5 page paper:
https://docs.google.com/document/d/1w7KysDzH5m7qeaUVdXjNEn3uBA7hny0u16twP39vpFo/edit?usp=sharing

Below is a slideshow, with a detailed architecture overview:
https://docs.google.com/presentation/d/1eHuUcduwG1TKrg2zByLzDb2a5F-aRylL/edit?usp=sharing&ouid=114547162965881187490&rtpof=true&sd=true
