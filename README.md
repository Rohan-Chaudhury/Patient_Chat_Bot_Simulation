# Patient_Chat_Bot_Simulation
The .ipynb notebook provides a simulation of a patient whose name is Pastor Zimmerman.
Colab link: https://colab.research.google.com/drive/12zLUj7G0Sx9VYXUw75mi0Ai2WnAsfmB4?usp=sharing

Progress: Made a bigger dataset with 71 intents and responses, 60 lines of context for personality of Pastor Zimmerman, 70 manual responses
Wrote a python script for the final bot, models used: deepset/roberta-base-squad2 and sentence-transformers/paraphrase-xlm-r-multilingual-v1
Model uses both context recognition and intent-based matching

In order to retrain the model:

  type \<fine-tune-new\>and follow the steps as mentioned in the output

In order to fine-tune the model:

  type \<fine-tune-old\> and follow the steps as mentioned in the output

For live tuning use the command \<tuning-on\>
