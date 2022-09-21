<div align="center">
<a href="https://www.python.org/">
    <img src="https://img.shields.io/badge/built%20with-Python3-green.svg" alt="built with Python3"/>
</a>
<a href="https://github.com/Sharif-SLPL/Attentionist-a-novel-solution-for-structured-sentiment-analysis">
    <img src="https://github.com/aleen42/badges/raw/master/src/github.svg" alt="hosted on Github"/>
</a>
<a href="https://colab.research.google.com/github/Sharif-SLPL/Attentionist-a-novel-solution-for-structured-sentiment-analysis/blob/master/Attentionist_SSA.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Document"/>
</a>
</div>

# Attentionist | A novel solution for Structured Sentiment Analysis

This is the code of my dissertation supervised by Prof. Hossein Sameti at CS@Sharif University of Technology and also the code of my solution submitted to SemEval 2022 workshop.

Data folder includes [SemEval 2022 Task 10](https://github.com/jerbarnes/semeval22_structured_sentiment) data and SemEval 2014-2015 (Pontiki et al. 2014, 2015) data annotated by (Wang et al. 2016, 2017). The latter one is on Targeted Sentiment Analysis task and I obtained it from (Chen et Qian 2020) [github repo](https://github.com/NLPWM-WHU/RACL).

Three notebooks are provided by this repository. Each one is explained below.

## `Attentionist_SSA.ipynb`
This is my proposed solution for SemEval 2022 Task 10 Subtask 1 (Structured Sentiment Analysis). It includes training, evaluation and all experiments.

## `baselines.ipynb`
Running and evaluating SemEval 2022 Task 10 baselines using its codebase in order to reproduce the results and compare my solution with them.

## `Karimi_et_al_2020.ipynb`
My implementation of [a baseline](https://github.com/IMPLabUniPr/BERT-for-ABSA) for ABSA (Aspect-Based Sentiment Analysis) task. This notebook includes training and evaluation of the baseline. I used the same data that this baseline used which is available in its repo. This baseline is not among my solution baselines but I implemented it as a part of my literature study step.
