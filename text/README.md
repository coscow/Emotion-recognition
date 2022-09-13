RoBERTa models represent an entire sequence using the first unique token called CLS (stands for classification). Using the fact that the mechanism of self-attention in BERT-based models is bidirectional the CLS token, which is the first token of the sequence, is encoded with all information to its right, which is the future sequence. Therefore, we can use this token as a concise representation to solve classification tasks like emotion recognition. 

Dataset: https://ai.googleblog.com/2021/10/goemotions-dataset-for-fine-grained.html
