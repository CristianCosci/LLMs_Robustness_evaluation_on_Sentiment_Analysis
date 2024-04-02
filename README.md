# Large Language Models (LLMs) Robustness Evaluation on Sentiment Analysis task

## Overview
This project aims to assess the robustness of several Large Language Models (LLMs) in the task of Sentiment Analysis. The evaluation is conducted on various models, including ***GPT-J-6B***, ***FLAN-T5-small***, ***FLANT-T5-base***, and ***FLANT-T5-xl***. 
The evaluation process involves assessing these models on the ***IMDB dataset*** and its [contrastive set](https://arxiv.org/abs/2004.02709) available at [allenai/contrast-sets](https://github.com/allenai/contrast-sets).

## Project Structure
- `FLAN-T5_eval.ipynb`: Colab notebook with scripts for evaluating FLAN models.
- `GPT-J-6B_eval.ipynb`: Colab notebook with scripts for evaluating GPT-J-6B model.
- There is a folder associated with each evaluation.
- `Dataset`: This folder contains the original and contrast sample for the evaluation.
- `Plots`: This folder contains various comparison plots generated during the evaluation process.

## Evaluation Methodology
The models are evaluated under zero-shot, 1-shot, 3-shot, and 5-shot settings. 
The evaluation scripts assess the models' performance on the IMDB dataset and its contrastive set to gauge their robustness in sentiment analysis tasks.

## How to Use
1. Clone the repository to your local machine.
2. Navigate to the evaluation notebooks.
3. Execute the evaluation scripts.
4. View the evaluation results in the notebook.
5. Explore comparison plots in the `Plots` folder to analyze the performance of different models.
