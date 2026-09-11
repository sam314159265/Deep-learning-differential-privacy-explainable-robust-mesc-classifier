# Deep-learning-differential-privacy-explainable-robust-mesc-classifier

Traditional anonymization has repeatedly failed to
protect individuals in real-world data releases, raising serious
concerns for sensitive mental-health text. This work investigates
emotion classification on the MESC conversational dataset under
both utility and privacy constraints. First, several classical TF–
IDF-based models (Random Forest, KNN, MLP, SVM, Logistic
Regression) are trained and evaluated, showing that they achieve
moderate accuracy but very low macro-F1 on minority emotions
due to strong class imbalance. Next, pretrained Transformer
models (DistilBERT, BERT, RoBERTa) are fine-tuned on the
same data, yielding substantial gains in both accuracy and macro-
F1, with RoBERTa clearly outperforming the classical baselines.
Finally, differentially private stochastic gradient descent (DP–
SGD) is applied to the best-performing Transformer model to
study the privacy–utility trade-off. In our experiments, introducing
differential privacy reduces RoBERTa’s accuracy from
62.14% to 58.25%, while still preserving a large fraction of its
non-private performance. Overall, the results provide a comparative
baseline for classical and Transformer models on MESC and
illustrate how differential privacy can be integrated into mentalhealth
emotion classification with controlled, quantifiable impact
on utility.
