# analisa_sent_3label
3-label sentiment analysis with IndoNLU dataset + Pretrained indoBERT and run in google Colab runtime GPU type

Training and testing results:
eval_loss': 0.464749276638031
'eval_accuracy': 0.9412698412698413
'eval_f1': 0.9409519203714527
'eval_runtime': 2.3799
'eval_samples_per_second': 529.441
'eval_steps_per_second': 33.195
'epoch': 10.0
Accuracy on test data: 92.20%

# Code preparation
1. Run in google colab and don't forget to prepare the dataset locally/drive (in case not meet)
2. Prepare Python version 3.2 and GPU type runtime
3. Create a wandb.ai account if you haven't, prepare a personal API from there. Wandb.ai is useful for monitoring the training process and results
4. Please change the parameters yourself according to your needs
5. If there are other words you want to remove from the wordcloud, add them to the stopword

# Development Status
1. Still under development because it has only completed the stage of recognizing 3 labels, negative, neutral and positive
2. The next plan is to develop multi-label emotions for the model and recognize sentiment through emoticons
3. Implementation of the model stored in the LLM based Multi-Agent as one of the Agents that controls the LLM response and recognizes the user's emotional response.
