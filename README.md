# Text-Based Emotion Detection: Fine-tuning BERT with GoEmotions

In this project, we conduct an exploratory analysis of Google's GoEmotions corpus, a dataset of 58k reddit comments labeled with 28 possible emotions.. We attempt to improve upon the original researcher's classification performance. We try unexplored model architectures. Lastly, we verfiy the claims made in the GoEmotions paper. [**GoEmotions Blog.**](https://ai.googleblog.com/2021/10/goemotions-dataset-for-fine-grained.html)

>This project was completed for the Deep Learning course (DS 6050) in the University of Virginia's Masters of Science in Data Science Program.
>
>*Group 5*  
> Alice Bogdan, Brooks Anderson, Trey Briggs

---
This repository contains our code notebooks as well as some small filesof results.

## File Organization

 + The `transfer_learning_results` folder contains outpufiles from our transfer learning experiments

+ Notebooks beginning with `GoEmotions_DS6050` contain candidate models
    + BERT baseline model
    + improved BERT
    + RoBERTA
    + PRADO
    + Transfer Learning Experiment

+ `EmoTweets.csv` and `SSECTweets0.66.csv` are benchmark datasets of tweets and emotion labels.
