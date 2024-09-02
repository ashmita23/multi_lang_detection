### Multilingual Classification Using Deep Learning

### Problem Statement:
Accurately classifying text across multiple categories is a challenging task, particularly when dealing with diverse and multilingual datasets. Traditional models often struggle to capture the nuances and contextual dependencies present in such data, leading to suboptimal performance. The objective of this project was to develop and evaluate multiple neural network architectures to determine the most effective model for achieving high accuracy in text classification tasks.

### Process Employed: 
To tackle this problem, I experimented with five different types of neural network models for text classification. Among them, a combination of 1-Dimensional CNNs and Bidirectional Long Short-Term Memory (BiLSTM) networks emerged as the top performer, achieving an impressive accuracy of 93.91%. This architecture effectively captured both local features and long-range dependencies within the text. Additionally, I performed zero-shot learning using a multilingual fine-tuned LLM to extend the model's capabilities across different languages without requiring retraining on new data. The dataset used for this project was sourced from Hugging Face Datasets, ensuring a rich and diverse set of text samples for model training and evaluation.
Model comparison :

<img width="283" alt="Screenshot 2024-09-02 at 2 00 22 PM" src="https://github.com/user-attachments/assets/57949f0e-3209-4759-b021-7802ac171d5b">


Best performing model (1D-CNN BiLSTM):
<img width="392" alt="Screenshot 2024-09-02 at 2 00 09 PM" src="https://github.com/user-attachments/assets/9692497a-f8c8-4edc-9a61-70b636459105">

<img width="562" alt="Screenshot 2024-09-02 at 1 59 58 PM" src="https://github.com/user-attachments/assets/8ac3f276-434f-4c4a-9f68-9080482623f2">
