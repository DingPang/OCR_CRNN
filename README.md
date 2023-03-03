# OCR_CRNN
This is a personal project by Ding Pang, and it is an implmentation of the OCR CRNN model proposed in [An End-to-End Trainable Neural Network for Image-based Sequence
Recognition and Its Application to Scene Text Recognition](https://arxiv.org/pdf/1507.05717.pdf).

## Instruction
All codes reside in the "project.ipynb" notebook, and the model was trained on Google Collab.

Running the code would require many path changes.

The training data set is too large to be uploaded, but similar data sets can be generated using [trdg](https://github.com/Belval/TextRecognitionDataGenerator), with command "trdg -c 40000 -w 5 -f 64".

The exploration hand-written data set can be found [here](https://www.kaggle.com/datasets/nabeel965/handwritten-words-dataset). However, the folder structure and file names need to be changed for the script to run.

## Trained model
The saved model is "my.ckpt", and it can be loaded for testing.
