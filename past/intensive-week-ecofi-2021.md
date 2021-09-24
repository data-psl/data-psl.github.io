---
layout: page
title: "Machine Learning and AI for Economics and Finance"
description: "PSL and Dauphine summer school"
header-img: "img/dauphine-back.jpg"
---

As part of the special "transverse program" DATA of PSL, we organize the Eco/Finance AI summer school. You want to learn: 
- How AI can interact with economics and finance ?
- How to build machine learning models from data ?
- What is the connection between causality and machine learning ? 
- What can we learn from texts (Natural Language Processing) and images (Computer Vision) ? 
The goal of this summer school is to introduced recent and important tools from data science that can  address issues in the fields of economics and finance. This week  is composed of  livestreamed lectures and lab sessions to provide participants the starter skills. 



_Important:_ Master and PhD students should check with their administration if this course can be validated within their programme. 



# Speakers  


- [Jonas Peters](http://web.math.ku.dk/~peters/) and [Sebastian Weichwald](https://sweichwald.de/) 
- [Fabrice Riva](http://www.finance.dauphine.fr/membres/fabrice-riva/)
- [Ivan Laptev](https://www.di.ens.fr/~laptev/)
- [Sylvain Benoit](https://sites.google.com/site/sylvainbenoit87/)
- [Clément Royer](https://www.lamsade.dauphine.fr/~croyer/)
- [Zoran Filipovic](https://sites.google.com/view/zoranfilipovic)
- [Arthur Mensch](https://www.amensch.fr/)
- [Syrielle Montariol](https://smontariol.github.io/)
- [Eric Benhamou](https://www.lamsade.dauphine.fr/~ebenhamou/)


# Dates and location


Dates: June 7 to 11.

Location: Virtual

# Pre-register to the Courses


[Pre-registration is free but mandatory](https://forms.gle/DgQfyCBBuhawgX1c7).

PSL students have priority if they pre-register before XXX.



# Schedule


The expected program is described below:


| :---                 |                               :----: | :----:                                      |
|----------------------|--------------------------------------|---------------------------------------------|
| Day                  |                                 Time |                                             |
|----------------------|--------------------------------------|---------------------------------------------|
| June 7 &nbsp; &nbsp; | 8:45-9:00 &nbsp; &nbsp;&nbsp; &nbsp; | Welcome  address and                        |
|                      |                                      | and week presentation                       |
|                      |                           9:00-12:00 | Introduction  to Machine Learning           |
|                      |                                      | (**Arthur Mensch**)                         |
|                      |                          14:00-16:00 | Robo-advisors  and ML                       |
|                      |                                      | for asset management  (**Eric Benhamou**)   |
|                      |                                      | (**Eric Benhamou - David Saltiel**)         |
|----------------------|--------------------------------------|---------------------------------------------|
| June 8               |                           9:00-12:00 | Causality                                   |
|                      |                                      | (**Jonas Peters and Sebastian Weichwald**) |
|                      |                          14:00-17:00 | Bankruptcy prediction - Part 1              |
|                      |                                      | (**Fabrice Riva**)                          |
|----------------------|--------------------------------------|---------------------------------------------|
| June  9              |                           9:00-12:00 | GDP  prediction and credit risk             |
|                      |                                      | (**Nicolas Woloszko and Christophe Hurlin**)|
|                      |                          14:00-16:00 | NLP  for corporate finance                  |
|                      |                                      | (**Zoran Filipovic**)                       |
|                      |                          16:00-17:00 | Derivative-Free  Optimzation (DFO)          |
|                      |                                      | (**Clément Royer**)                         |
|----------------------|--------------------------------------|---------------------------------------------|
| June  10             |                           9:00-12:00 |       Bankruptcy  prediction – Part 2       |
|                      |                                      | (**Fabrice Riva**)                          |
|                      |                          14:00-17:00 | Advanced  NLP                               |
|                      |                                      | (**Syrielle Montariol**)                    |
|----------------------|--------------------------------------|---------------------------------------------|
| June  11             |                           9:00-12:00 | Computer  vision and dimensionality         |
|                      |                                      | dimensionality  (**Ivan Laptev**)           |
|                      |                          14:00-17:00 | RL  and deep RL                             |
|                      |                                      | (**Eric Benhamou - David Saltiel**)         |
|----------------------|--------------------------------------|---------------------------------------------|


# Detailed contents

Many courses will include lab parts. All the code will rely on Python. If you want to setup your computer, you can install anaconda. This Python distribution comes with all the necessary tools. You can also use Google Colab with a Google account.


####  Bankruptcy prediction 

- Part 1 : Code from scratch a Python program, whose objective is to compute the probability that a firm goes bankrupt using logistic regressions estimated via stochastic gradient descent (SGD). The lecture will cover the following concepts:
     -  Data cleaning, feature standardization and normalization
     -  Train, validation and test sets
     -  Data balancing
     -  Online and mini-batch SGD
- Part 2 :  Introducing Scikit-learn instead of raw Python code. The functionalities offered by Scikit-learn will allow us to cover and to address new concepts including:
     - Performance metrics
     - Cross validation
     - SVM
     - Decision trees and random forests

#### GDP  prediction and credit risk

This session is co-animated by Nicolas Woloszko and Christophe Hurlin.

##### A Weekly Tracker of GDP growth  

The OECD Weekly Tracker of GDP growth provides a real-time weekly indicator of economic activity using machine learning and Google Trends data. It has a wide country coverage of OECD and G20 countries. The Tracker is well suited to assessing activity during the turbulent period of the current global pandemic. It applies a machine learning model to a panel of Google Trends data for 45 countries, and aggregates together information about search behaviour related to consumption, labour markets, housing, trade, industrial activity and economic uncertainty. The Tracker provides estimates of year-on-year growth in weekly GDP, that were used in the OECD Economic Outlook and that are released in real-time on a dedicated webpage.  

##### Credit Risk
Artificial Intelligence (AI) can systematically treat unfavourably a group of individuals sharing a protected attribute (e.g. gender, age, race). In credit scoring applications, this lack of fairness can severely distort access to credit and expose AI-enabled financial institutions to legal and reputational risks. The goal of my lecture is to show how to assess the fairness of AI algorithms used in credit markets. First, I propose an inference procedure to test various fairness metrics. Second, I present an interpretability technique, called Fairness Partial Dependence Plot, to identify the source(s) of the lack of fairness and mitigate fairness concerns. Finally, I illustrate the efficiency of this framework using a dataset of consumer loans and a series of machine-learning algorithms.

#### Robo advisors and ML for asset management
Two topics in this session animated by Eric Benhamou

- Robo advisors
  - Generation 1.0 of robo-advisors based on modern portfolio theory
  - Generation 2.0 of robo-advisors based on AI (SL, Deep and DRL)
  - AUM growth of funds managed by robo-advisors

- ML for asset management
  - Current wave of digitalization and 4th industrial revolution with artificial intelligence and robotics
  - Misconception about financial ML
  - Understanding time series
  - Testing methodology: backtesting, overfitting risk and walk forward

#### RL and deep RL
  - Introduction to Reinforcement learning, Cross validation
  - Presentation of the various algorithms: DQN, A2C, A3C
  - Next generation of Deep RL with PPO, DDPG
  - Combining Deep RL and Supervised Learning with SSA, P2A and curiosity
  - Deep RL with BBO

#### NLP for Corporate Finance


  - Overview of recent research in Corporate Finance using NLP
  - SEC EDGAR filling
     - Accessing SEC EDGAR 
     - Filing indices 
     - 8-K, 10-K download and parsing
  - Financial dictionaries
     - tone and sentiment 
     - intangible assets 
  - Application to M&As

#### Deep learning for Natural Language Processing
This session will review the main architectures used in state of the art approaches for NLP.
- Word embeddings and language models
- Recurrent architectures and LSTM
- Transformers and Contextualised embeddings (BERT, GPT)
- The essential tools (pytorch and huggingface)
- The stakes in finance: explainability, interpretability, transparency, and fairness
- The promises and the limits

# Organizers


- [Fabrice Riva](http://www.finance.dauphine.fr/membres/fabrice-riva/)
- [Bruno Bouchard](https://www.ceremade.dauphine.fr/~bouchard/bouchard.htm)
- [Sylvain Benoit](https://sites.google.com/site/sylvainbenoit87/)
- [Eric Benhamou](https://www.lamsade.dauphine.fr/~ebenhamou/)
- [Alexandre Allauzen](https://allauzen.github.io/)


