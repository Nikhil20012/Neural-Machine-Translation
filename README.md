# Neural-Machine Translation

The folders are structured as follows:
1. Models we used: LSTM, Encoder-Decoder using Attention mechanism
2. Phase-1 PPT and the final(Phase-2) report
3. Datasets: The original datasets(IITB.en-hi.en & IITB.en-hi.hi) and the merged dataset (dataset_tdl)


Link to dataset: https://www.cfilt.iitb.ac.in/iitb_parallel

Install all the required packages given in the code before training the model.
Use the datasets(IITB.en-hi.en & IITB.en-hi.hi) for training and testing LSTM model.
Use the dataset(dataset_tdl) for training and testing Encoder-Decoder model.

LSTM CODE:-
The code is recommended to run on TPU for faster training time.  Code should run with Tensorflow version 2.6.0 and keras version 2.6 only.
The following variables have to be updated :-
Dataset_root (root folder containing dataset)
In all with open() (where dataset is present)
In os.path.exists (where preprocessed data exists)
Filepath in tf.keras.callback.ModelCheckpoint (for saving the model)
In tf.keras.models.load_model() as show in all images (for loading the saved model).

S2S
The code can be executed by just running each tabs in google colab , only dataset path have to be changed.


Phase 1 report:
The literature survey along with all the relevant analysis.

Link to phase 1 report: https://docs.google.com/presentation/d/1eopr7z0qu47RYPsfj7rkOClvEfkK-u5Q4zysMAZhwzo/edit#slide=id.p1

Phase 2 report:
The elaborate methodology to implement our solution approach has been mentioned in this report. 

Link to phase 2 report: https://docs.google.com/document/d/1di14s9TgRm7QH_5h08DjCjB69KOLVkgJ/edit
