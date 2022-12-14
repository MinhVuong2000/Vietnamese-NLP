# NLP's Ocean

- Materials: https://slds-lmu.github.io/seminar_nlp_ss20 (2020-09-08)
- Lession, discussion & Reality Practice: https://www.geeksforgeeks.org/ml-semi-supervised-learning/?ref=lbp#practice
- [Transformers HuggingFace](https://huggingface.co/docs/transformers/glossary): contains numerious spaces, dataset & models, NLP tutorials as well 


## Attention
![variants of attention](https://user-images.githubusercontent.com/46895260/208471150-8dec1c98-8b75-4c0b-90d2-f08fee53f318.png)
1. [Attention & Self-attention](https://medium.com/@angelina.yang/whats-the-difference-between-attention-and-self-attention-in-transformer-models-2846665880b6)
  - Attention (cross-attention): connect between Encoder-Decoder => Q, K, V is not the same sentence
  - Self-attention (either Encoder or Decoder): Q, K, V is the same sentence -> **self**
  - Causal self-attention: uni-directional: from left-to-right-only or right-to-left-only
  - Bi-directional Self-attention: [visualization](https://www.youtube.com/watch?v=s-JiY2LNrjY)
  
2. [Multihead](https://slds-lmu.github.io/seminar_nlp_ss20/attention-and-self-attention-for-nlp.html):
  - The multi-head attention projects the queries, keys and values `h` times instead of performing a single attention on dmodel-dim. queries and key-value pairs.
  - Operate in parallel. These self-attention blocks will not share any weights; the only thing they will share is the same input word embeddings
  - Will have n embeddings for each word -> This multi-dimensionality allows the attention mechanism to jointly attend to different information from different representation at different positions
