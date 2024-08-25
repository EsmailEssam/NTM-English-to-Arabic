# English-to-Arabic Neural Machine Translation

This project implements Neural Machine Translation (NMT) models for translating English to Arabic using a sequence-to-sequence (seq2seq) architecture. Two variations of the model are provided:

1. **Seq2Seq without Attention**: A basic seq2seq model using an encoder-decoder architecture without the attention mechanism.
2. **Seq2Seq with Attention**: An enhanced seq2seq model incorporating the attention mechanism to improve translation quality.

## Project Overview

### 1. Seq2Seq without Attention
- **Model Architecture**: Encoder-Decoder
- **Training Time**: Faster compared to the attention-based model
- **Performance**: Baseline translation quality

### 2. Seq2Seq with Attention
- **Model Architecture**: Encoder-Decoder with Attention
- **Training Time**: Slower compared to the non-attention model
- **Performance**: Achieves approximately 3x better translation quality compared to the non-attention model

## Datasets
The models are trained using a parallel corpus of English and Arabic sentences. Please refer to the notebooks for details on data preprocessing

## Usage
### 1. Navigate to the desired notebook:
- Seq2Seq_without_attention.ipynb
- Seq2Seq_with_attention.ipynb
### 2. Follow the instructions in the notebook to train and evaluate the models.

## Results
- Seq2Seq without Attention: Provides a basic translation model with faster training times.
- Seq2Seq with Attention: Offers significantly improved translation quality at the cost of longer training times.
- Some of the results between the two models:
  
| English sentences | Attention Model | NoN-Attention Model |
| --- | --- | --- |
| Hi | مرحبا | مرحبا |
| run | اركض | اركض |
| I love you | انا احبك | انا يحدث |
| He loves music | يحب الموسيقي | ساسافر باني |
| I ate the meat |  اكلت اللحم | الان تمزح|


## Future Work
- Explore additional attention mechanisms or transformer-based models for further improvements.
- Experiment with different hyperparameters and datasets.
