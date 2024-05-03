This folder contains the source codes and report for our group project. The group project was inspired by a [Kaggle competition](https://www.kaggle.com/competitions/pii-detection-removal-from-educational-data/overview), where the dataset can be obtaiend as well.

In our project, we performed the following:

1. Loaded and preporcessed the data.
2. Experimented with two pre-trained language-models: T5 and DeBERTa.
3. Experimented with two losses: Cross-Entropy Loss and Focal Loss.
4. Experimented with Low-Rank Adaptation (LoRA) with T5.

Our evaluation metric is the F5 score, which can be calculated as:

$$ F_5 = 26*\frac{\text{precision}\cdot{\text{recall}}}{\beta^2\cdot{\text{precision}}+\text{recall}}  $$
