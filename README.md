# Private-AI
A hybrid approach to privacy preserving AI

## Abstract

Machine learning algorithms based on Deep Neural Networks (NN) have achieved remarkable results
and are being extensively used in diﬀerent domains. A crucial enabler for Artificial Intelligence is the
quantum of data, and these models are as good as the quality of data that is used to train them.
However, gathering data and using them to prognosticate behaviours presents great challenges to the
privacy of individuals and organisations, such as data breaches, privacy loss, and the corresponding
financial and reputational damages.
Privacy-preserving machine learning (PPML) aims at bridging the gap between preserving privacy
and reaping the benefits of ML. It is a key enabler for privatising collected data and complying with
data protection regulations.
Therefore, the goal of our project is to implement a hybrid approach to Privacy Preserving AI by
using these three Privacy Preserving techniques namely: Federated Learning, Differential Privacy,
and Homomorphic Encryption to achieve maximum user data privacy while not affecting the overall
accuracy of the predictions and computations made by the AI model.

## Scope

Traditional ML approach uses centralised learning which puts user data at risk.
Further, decentralised approaches like vanilla Federated Learning also has its cons.

Aim: To design and implement a hybrid approach to protect sensitive user data combining multiple privacy preservation techniques.

Tackling the Problem splitting it into 3 parts:

<img width="865" alt="Screenshot 2025-04-19 at 1 18 34 PM" src="https://github.com/user-attachments/assets/5cc67255-aaea-4d1b-b346-436502bc940a" />

## A High Level Architectural View of the Hybrid approach components

<img width="868" alt="Screenshot 2025-04-19 at 1 19 32 PM" src="https://github.com/user-attachments/assets/0b886eda-1df1-4786-af30-211b75e47cac" />


## High Level Architecture Diagram of the Implementation

<img width="466" alt="Screenshot 2025-04-19 at 1 12 40 PM" src="https://github.com/user-attachments/assets/d36a49f0-03d4-48af-a373-64612c4302a5" />


## Conclusion:

1. This technique offers a private and secure approach to training ML models.
2. It is a combination of three PPML techniques which have yielded best privacy guarantees. Hence users can confidently use their data in the field of artificial intelligence.
3. It provides protection against third party attack vectors, reverse engineering attacks, inference attacks, MITM etc
4. The only drawback of this approach is the tradeoff with accuracy. 


