# Transformer-Text-Coherence
 Fine-Tuning Five Types of Transformers on the GCDC Dataset for Coherence Evaluation and Incorporating Syntactic Features into BERT for Coherence Measurement
 
## Models
**Bertsem**: a fine-tuned version of the original BERT model.<br/>

**XLNetsem**: a fine-tuned variant of XLNet.<br/>

  **GPTsem**: a fine-tuned version of the GPT2.<br/>
  
  **Robertasem**: a fine-tuned version of RoBERTa.<br/>
  
  **DistilBERT**: a fine-tuned version of DistilBert<br/>
  
  **BERTSyn1**:  a modified version of the BERT model that incorporates both word embeddings and their corresponding part-of-speech (POS) tag embeddings. This enhancement allows the model to capture syntactic information more effectively during the fine-tuning process for coherence evaluation.<br/>
  
  **BERTSyn2**: an approach that measure coherence evaluation by using two separate BERT models. One model is fine-tuned on the word-level input, while the other is fine-tuned on the POS tag-level input. The outputs of both models are then concatenated to create a comprehensive representation that captures both semantic and syntactic information for coherence assessment.

## Dataset
The dataset can be downloaded from the link: https://github.com/aylai/GCDC-corpus



