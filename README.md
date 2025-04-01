## BiGRU-based Named Entity Recognition (NER) using GloVe Embeddings

This project implements a BiGRU-based Named Entity Recognition (NER) model using pre-trained GloVe embeddings. The model is trained to recognize named entities in text and classify them into categories such as person, location, organization, etc. The project is part of an NLP course offered at the University of Rochester.


In this project, we train a Bi-directional Gated Recurrent Unit (BiGRU) model for Named Entity Recognition (NER). We leverage pre-trained GloVe embeddings to initialize word representations and use them as input to the BiGRU model. Fine-tuning of embeddings is allowed during training for better performance. The model is evaluated on a test dataset with standard evaluation metrics.

Key steps involved in the project: 


- Data Preprocessing: Tokenizing text and creating features (including capitalization).

- Model Building: Implementing a BiGRU-based architecture for sequence labeling.
- Training: Training the model with a dataset and pre-trained embeddings.
- Evaluation: Evaluating the model's performance on the test set.

  
**Requirements**
- Python 3.x
- PyTorch
- TorchText
- GloVe embeddings
- sklearn
- seqeval (for NER evaluation)


Acknowledgments
This project is part of the NLP course offered at the University of Rochester.
The model uses GloVe embeddings, which are publicly available.
Special thanks to the course instructors and teaching assistants for their guidance.
