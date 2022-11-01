# nlp-questions-generation-from-relations
An NLP project: Questions generation from relations
By: Gil Levy and Liad Levi-Raz

# 1. How to run the code
The code is provided as 3 Colab notebooks, Preprocessing NB, Simple Model NB and Enhanced Model NB.
Basically you just open them in Colab and 'Run all' after obtaining the datasets.
A GPU is needed for the Model notebooks

# 2. Preprocessing NB
link: https://colab.research.google.com/drive/1xcy9zDnt28H4RVQpAU_73rPNCGjUKuBc?usp=sharing

There is no need to run this NB, as the preprocessed datasets links were provided for each NB
(If you do wish to run it from scratch - it is possible but please contact us first as it requires 
to regiser to Google Cloud APIs for getting access to the Google Knowledge Graph API)


# 3. Simple Question Generation NB
dataset: https://drive.google.com/drive/folders/10M0YgJ9-OOUsaC41JvxreJGs-JFqUM3n?usp=sharing
link: https://colab.research.google.com/drive/1jSTHZSi58LfHC8eUpKPZ7PLIepsoH27y?usp=sharing

Download the dataset files, and upload them to Colab. The dataset files are expected to be under: 
/content/data/train_14k_df.csv
/content/data/val_14k_df.csv
/content/data/test_14k_df.csv

Run the notebook - this will run a full training (if you wish to use our pretrained model please contact us)

# 4. Enhanced Question Geneeration NB
dataset:https://drive.google.com/drive/folders/1og5PyaisweVKtx1UwVqURpsVs9yQLXPr?usp=sharing
link: https://colab.research.google.com/drive/1QhCOJCHOlTRi6ncrY-orqYE1Qg4r-TG9?usp=sharing

Download the dataset files, and upload them to Colab. The dataset files are expected to be under: 
data/p2/p2_train_seq2seq_df.csv
data/p2/p2_val_seq2seq_df.csv
data/p2/p2_test_seq2seq_df.csv

Run the notebook - this will run a full training (if you wish to use our pretrained model please contact us)
